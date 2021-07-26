title:: Blog/Note Taking Apps
public:: true

# A thoughrough review of note taking applications evaluated with spefici criteria
## First, a disclamer:
	- Trying note taking apps is a huge waste of time and a great way to procrastonate instead of doing actual work and just taking the damn notes. A system may not be perfect but you should spend your time **using** a good system rather than spending that time **finding** the best system
	- So, in the hope of saving others from this pointless time-wasting excersize. here we have it. All the notes applications compared by someone who doesn't really like taking notes but thinks the perfect tool can fix that.
	- **It has.**
## Criteria
	- One of my personal complaints with most reviews of applications, is that the criteria they are reviewed by is often omitted, or ignored. This would seem to be possibly the most important part of a review.
	- ### My criteria are as follows
		-
		  1. Note storage
			- Where the hell are my notes anyway?
			- Are they stuck on the cloud and only accessible when i have an internet connection?
			  todo:: 1626940525381
			- Am i relying on some other company to make backups and not just magically loose all my notes? That's simply unacceptable to me.
			- The gold standard is local storage in a an open and common format like [[Markup/Markdown]]
		-
		  2. Note syncronization(which is related to note storage)
			- Are my notes automatically syncronised between devices through the app?
			  todo:: 1626940309766
			- Is their another easy option for synchronization (local files with google drive for example)
		-
		  3. Note display
			- Is the experience of editing and interacting with my notes both beautiful and functional? For me this is a major point. If i am trying to visually parse information for hours at a time it had better look good. If it doesn't look good, I'm not going to want to read it, and I'm not going to want to create it.
		-
		  4. Note compatibility (again related to storage)
			- If this program goes under, can I take my notes elsewhere? 
			  todo:: 1626940609804
		-
		  5. Additonal features
			- Does it do some other handy things that are not notes that should be considered. eg remnote has a [[Pomorodo]] timer
		-
		  6. Implimentation fo core featuers:
			- To even be considered the application must have some ability to link between notes. I think any application without this feature is not even worth using for any serious research when alternatives that do have it exist. (sorry onenote and evernote)
			- [[Links]] visualization
				- The ease of navigation between interlinked pages and ability to see where a page links to and from
					- A [[Backlinks]] list is a common eample of this
					- Unlinked instance list is another.
					- Graphs are popular But i have yet to find an example where they are very useful, however i think that is certainly personal
			- {{embed [[Hierarchical Pages]]}}
			  id:: 60f93018-4dd2-49f4-a2dd-1128ffb09783
	-
	  7. Ease of setup and use:
		- Emacs for example is a great note taking tool and ranks high in most criteria but for many people it would take a week or more just to install and setup.
			- This would require instaling linux, installing emacs, installing a plugin manager(doom emacs/spacemacs), configuring org-mode, installing org-roam, learning some elisp etc
			- TODO put a link to that great guide on how to do all this
##  General split
	- It is important to mention that these applications kind of fall in to one of two camps.
	  Whilst these styles are differn't in reality you can do outline style using a doc focused editor and viseversa, its just a leaning.
	- #Outline Focused
		- These applications display notes as dot point outlines
		- I think they encourage a kind of dot-point, abbreviated thinking style that lends itself well to many interlinked notes
		- Nesting ideas visually is a very good way to reduce distraction and provide structre to what ideas fit inside others and alsow show you what is more or less importtant.
		- IT allows you to quickly take a block and say " this should be its own page" then take it an all its children to a new page
	- #Doc focused
		- Providing a more traditional one long document style.
		- Maybe better at creating long form work, certainly more natural to write a whole assignment in.
		- more easy to export into something that makes sense to others
- Tags
	- ComplexComtent
		- ability to render LaTeX math, have tables, insert images, etc
	- Citations
		- Features to manage citations and references within the program, handy if you plan to write papers or some portion of a paper using that same tool
	- Markup/Markdown vs Files/Markdown
		- One refers to the use of markdown syntax in the editor, the other refers to storing the information in markdown files that is relevant for ((95f5a1b8-9df5-4bd2-8672-d9f4ecb39a35))
- Tools:
	- Vscode based
		- {{embed [[Vscode/Dendron]]}}
		  todo:: 1626943997431
	- {{embed [[Remnote]]}}
	- {{embed [[Roam Research]]}}
	- {{embed [[Obsidian]]}}
	- {{embed [[Logseq]] }}
	- {{embed [[Athens Research]]}}
	- {{embed [[Notion]]}}
	- Octo md
		- like obsidian but avialble via the browser.
		- support syncing for free but doesn't have any of obsidian's amazing plugins so i can't really recommend it.
	- zettlr #Doc #Offline #Citations #Free #Markup/Markdown #Files/Markdown
		- geared towards research people and journalists with inbuilt bibliography and citation tools.
		- Honestly, i haven't tried this enough in the domain it is made for (research and scientific papers) to properly comment.
		- Obsidian has similar plugins for BibTeX referencing so i would be interested to compare the two.
		-
		-
		-
	- Mac only
		- Bear and nota.md
			- #Files/Markdown #Markup/Markdown #Free #Paid #Offline #Autosync
			- I haven't actually tried either but ive done a fair amount of reading and can easily say that nota.md and bear both have some of the best amrkdown editing expeices available
			- nota has better support for links backlinks and syncing.
			- I think nota has in built [[git]] syncing
			- Mac people. It's your prerogative to try them or not, i think nota is probably the more interesting of the two.
	- Linx only
		- {{embed [[Emacs]]}}
	- ### Excluded
		- one note
			- if you want to hand write on your notes. nothing in the rest of this list will work like one note. the multimedia king.
		- evernote
			- Never really tried it. Seemed like one-note but with worse drawing abilities.
		- Neither of these support back-links or interlinked notes so they are excluded from this comparison.
	- ### Combinations:
	  id:: 95f5a1b8-9df5-4bd2-8672-d9f4ecb39a35
		- Some of these tools can be combined to create wonderful synergies (Insert ugiho fusion card here)
		- [[Files/Markdown]] + [[Files/Markdown]]
			- Any two apps with this tag will work together in som capacity and at the very least  are able to view each others notes
		- [[logseq]]+[[emacs]]
			- Logseq supports [[Markup/Org-mode]] and so inter-op between the two is very easy.
## Final Opinions:
	- Overall:
		- [[Logseq]] - Gets all the key parts right, and has extras on top.
			- Pros
				- It just gets so much right. Using plain markdown files so i can be confident about my notes being safe, backed up, and compatible with other tools
				- Supports advanced features like [[spaced repetition]] and [[transclusion]]
				- Allows me access from anywhere on any device via the web page
				- I prefer the outlier style, i think it integrates much more naturally with concepts like interlinking and referencing.
			- Cons:
				- Setting up synchronization if you want fully offline access to your notes has to be done manually see [[Setup logseq]]
	- Outliner
		- [[Remnote]] - The [[notion]] of outliers that ❤️ [[spaced repetition]]
			- If you want an outliner and you don't care about the data storage and interoperability related advantages of [[logseq]], but you do want the multi device access part, and don't know what [[git]] is:
			  Just use remnote.
			- Doesn't support some features without a paid plan(aliases and transclusion for one)
	- Doc Style
		- [[Obsidian]] - [[Logseq]] 's document based cousin with a plugin for anything.
			- Obsidian's plugins really are its main feature, there are so many and its a constantly growling list that allows it to integrate with many things and add so many fetures.
			- Has all the same syncronisation trouble as [[logseq]](you have to do it yourself) but you can pay a monthly subscription to have obsidian deal with it.
			- All the same file storage and inter-op advantages of [[logseq]] as well
		- [[Notion]] - No-nonsense no setup, no offline
			- if you just want a super easy experince thats nice to collaborate with others in and supports syncing just use notion.
			- Uses a proprietary database, has no offline support but it really is super easy, and you can still use links and back links
			-
## Other important considerations
	- ### Friction:
		- Friction is not as applicable to university as certain other domains -you have to take notes no matter what- but I think it it's still relevant here.
		- Friction is the ease or difficulty with which you interface with your notes
		- Friction can be created by a wide range of factors and for some - me personally- lower friction results in significantly better and more comprehensive notes.
		- Some small friction factors include
		  collapsed:: true
			- How your notes look when you are reading them
			- The ease with which you can express the ideas and structure you desire.
			  collapsed:: true
				- Pencil and paper wins by far in this regard for visual media. sketch,diagram etc
				- For some people being able to use markdown makes them much more productive and by creating more opportunity for structure will result in more structure
				- The outline format of software like roam, logseq and athens almost forces taking notes in a form that is nested and heirachical, for many it can be the "Pit of success"
			- The ease of accessing the program
				- if my notes application takes even 10 seconds to start i am vastly less likely to use it for taking a tiny note than if it is near-instantiations.
			- The ease of use during the program
				- Some programs are slow enough that they can tend to break flow. Even slight delays when doing common operations, can compound to make what should be effortless, be painful.
		- The largest and most important factor for most of us is parsing notes after they are written. The act of writing notes holds great value in and of itself (cite: Kevan -banana expert- Jones ), however making retrieval of information effortless changes how you look at notes completely.
			- Some features that allow this effortless retrieval
				- [[Links]] and [[Backlinks]]
				- Full text search.
				- [[Hierarchical Pages]] {{embed ((60f93018-4dd2-49f4-a2dd-1128ffb09783)) }}
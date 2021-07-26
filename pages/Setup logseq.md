- Installing:
	- You can install the logseq desktop application but it is not strictly necissary, if you just want to try it out, go to https://logseq.com and click demo. It gives you access to the full application from your web browser.
- Syncing notes
	- [[google drive]](lose ability to access your notes from any device via logseq.com)
	  collapsed:: true
		- Just stick the log-seq notes folder in your google/one drive folder and let that deal with syncing it.
		- You won't be able to access your notes from anywhere any time via logseq.com
	- [[git]]for those who know what git is and how to use it( supports accessing notes via logseq.com)
	  collapsed:: true
		- To make logseq sync your notes via [[git]] you need to have them stored on github.
			- Create a github account. Create a github repository (make it private if you don't want anyone in the world perusing your notes)
			- Go to logseq and sign in with your github account
			- Copy the url of your github repository(go to it on github then copy it from the address bar, it should look something like this : https://github.com/Eli/Notes)
			- Go to logseq, click the upper right hand corner, click add new graph, paste the link where it says to, type master into the branch name.
			- Click add and install
			- Now whenever you sign in on whatever device, you'll have access to your notes.
			- If that little green dot up in the top right corner turns yellow you are not in sync and you need may need to push or pull changes you have made..
			- You can download logseq onto your device as an application but that does not have automatic git synchronization built in
				- if you are on windows there is a program called sparkleshare which syncs git repositories. 
				  If you are on linux you can use that same program or this [script](https://github.com/simonthum/git-sync) with cron or a systmed timer or whatever, as explained in this [blog post](https://worthe-it.co.za/blog/2016-08-13-automated-syncing-with-git.html).
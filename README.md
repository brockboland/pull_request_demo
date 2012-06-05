Intro
=====
This is a simple repository to demonstrate how pull requests work in Github.

I will be posting a video demonstrating how this works.

See the video here: https://vimeo.com/41045197

FAQ
===
Wait, what?
-----------
Relax, it'll make more sense once the video is up.

I watched the video and I still don't understand.
-------------------------------------------------
Pull requests are a great way for your team to do code review before merging new features or bug fixes back into the primary branch (typically master, often times develop). For any new change, create a new branch from master and commit your changes there, then open a pull request

What if there's already  an open issue to which I'd like to attach code?
------------------------------------------------------------------------
As far as I can tell, this can't be accomplished through the interface. There's a button to create a pull request for a new branch, but no button to attach a new branch to an existing issue.

This is best accomplished, then, using [hub](https://github.com/defunkt/hub), which adds some extra features to git for use with Github.
Intro
=====
This is a simple repository to demonstrate how pull requests work in Github.

I will be posting a video demonstrating how this works.

See the video here: https://vimeo.com/41045197

Please note that this video was created in April 2012, and GitHub has been redesigned a bit since then. Things still work the same and links are still in roughly the same place, though, so you'll be fine.

FAQ
===
Wait, what?
-----------
Relax, it'll make more sense once the video is up.

I watched the video and I still don't understand.
-------------------------------------------------
Pull requests are a great way for your team to do code review before merging new features or bug fixes back into the primary branch (typically master, often times develop). For any new change, create a new branch from master and commit your changes there, then open a pull request

What if there's already an open issue to which I'd like to attach code?
------------------------------------------------------------------------
This cannot be accomplished through the interface. As of June 2014, this is still possible through the GitHub API, though they have indicated that this will be deprecated. Until that happens, though, you can convert an issue to a pull request using an older version of [hub](https://github.com/defunkt/hub). This was removed sometime after version 1.10.6.

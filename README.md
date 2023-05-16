Slackwise's WoW Addons
======================
I got sick of using various addon managers and realized I could just use git submodules to grab the addons myself and update with a `git pull` instead of needing CurseForge or some other crap, *so here we are*.

Please feel free to steal and spread this idea!


Downsides?
----------
This is perfectly fine if you don't mind:

- Digging through documentation to find a git repo with the addon in it
- Manually resolving any `RequiredDeps` in the TOC, and adding those as well, *recursively*.

Definitely don't recommend this for a non-developer.


Setup
-----
You need to run `git submodule update --init --recursive` after initial install.


Updating
--------
You should be able to use `git pull --recurse-submodules` to update all repos and submodules to the latest commits.
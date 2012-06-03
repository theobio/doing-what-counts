doing-what-counts
=================

Our process for making the world a better place.

Currently this project is in stage 1, genesis -- it is more than just an idea, it is in the process of being born.

Key concepts and vision
-----------------------

  1. iterative improvement.
    1.1 supporting revolution as well as evolution
  2. complexity management
    2.1. hierarchy (minimize in-context simultantous concerns)
      2.1.1. rule of 7, or rather 5
    2.2. linear sequence or narrative (local focus, expected route, distant blur)
    2.3. sops
    2.4. explicit metrics
    2.5. analogy
    2.6. convention and defaults
    2.7. TODO: Reduce!
  3. the process of managing projects applies recursively to itself.
    3.1. process improvement is part of every project, including this process.
    3.2. processes should be living.
      3.2.1. self-sustaning
      3.2.2. self-correcting
      3.2.3. self-replicating
    3.3. Processes should have both abstract descriptions (interfaces) and concrete descriptions (implementations)
  4. Long term visions and goals are the real projects.
    4.1. Decompose into mutliple short term projects.
    4.2. short term projects must succeed before long-term projects can.
    4.3. the process is not the long term goal.

Stages
------

1. **Genesis/Birth**         - What is the idea? Why do anything? What are the apparent benefits, and why do they outway
obvious costs? Is it more than just an idea, worth the effort to flesh out? What is the vision and how does this project
advance long term goals, especially over other things that could be done instead.
2. **Initiation/Infancy**    - What are the initial steps? What is the minimal self-sustaining system?
3. **Growth/Adolesence**     - How do we get to where we want to be? What is the base or architecture on which to build
4. **Maintenance/Adulthood** - How do we know we are done and ready to let this go. How do we enhance the contrinution this project can make.
How do we leverage this project to advance long term goals. Do we need radical change.
If so we should reproduce (fork) to allow separation of concerns.
5. **Deprecation/Senesence** - When is it not worth putting significant effort into this project. Is there something else we shoud recommend instead.
Is anyone using us in a way that advances the goals we care about.

Contributing
------------

Contributing is done done by everyone, owners, core developers, experts, and diletants.

### OWNER ###

As the initiator of a project, I either start the project here and then clone it to my system to work on,
or start the project on my system and then push it here. Ignoring everything else, I need to know how to
do at least one of these. The simplest is to start with git, and then clone, as that is described clearly
here. The abstract question is "how to collaborate on projects jointly." The concrete question applies
just to this project. For this first iteration, lets just describe one way that works for this project...
(TODO: general abstract problem.)

 * Assume git set up on the local system, https://help.github.com/articles/set-up-git.
 * Assume you have an organization account as well as an individual account on github
(TODO: links to info on how to create users. TODO: alternate approach that does not use org accounts).
 * Assume you will create on  Github, then clone to local system to work on
(TODO: reverse method should be documented as the *primary* way to do this, but this way is easier for now).
 * Assume you don't care about other aspects of sharing at this point, just want to get this done.

####Getting the project local the first time####

 1. Follow GitHubs instruction on how to create a repo, https://help.github.com/articles/create-a-repo
 2. Github's instructions on how to fork another repo [https://help.github.com/articles/fork-a-repo]
*does not apply to your own repo as an individual*, as you can not "fork" it. However, we assume
you are working as an organization where the organization "owns" the repo. The owner of the organization
has a separate account and CAN clone organization repos to my personal accounts, like everyone else,
so that is what we will do. TODO: simplified workflow for user account to work on their own prjects is needed.
 3. You need a place on your system to put git projects. We suggest having a directory for projects hosted at
github. (TODO discussion of various local layouts for how to organize development, personal accounts and fored repos.)
 4. Once you follow these instructions, you have a local copy of your public copy of the original repo.
(If you have problems, additional information on configuring remotes is at [help.github.com/remotes/])

Summary:
 1. Create a repo as your ORG account
 2. On that repository page in GitHub, under your org, click fork, select your user account.
 3. On your home system, change to target location directory
   'cd /D/Dev/GitHubHosted/Forked'
 4. Clone your forked repo <jefferys is replaced by your account name>
  `git clone git@github.com:jefferys/doing-what-counts.git`
 5. Clone the repo <theobio is the correct *original* owners name, the org.>
  `cd doing-what-counts.git`
  `git remote add upstream git://github.com/theobio/doing-what-counts.git`
 6. Check that this works by fetching upstream content
  `git fetch upstream`
 7. Redy to contribute.

### WORKFLOW ###
See http://scottchacon.com/2011/08/31/github-flow.html


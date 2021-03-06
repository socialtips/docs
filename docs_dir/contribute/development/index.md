# Development

Thanks for being interested in contributing code to this project!

## Setting up development environment
## Development cycles
## Versioning

## Git Methodology

The Coral Project practices master as tip git style.  At any given time, there should only be two active branches:

* _master_: the tip, which includes all completed and reviewed code
* _release_: the most recent release

Along side these branches, there may be any number of working branches and/or forks.  These are merged directly back into master in the manner described below. Once working branches are merged, they will be deleted.

Fixes for bugs that have made it into the _release_ branch must be applied to both the _release_ branch and _master_.

Previous releases can be accessed via tags.

## Checklists

Follow these steps when contributing to the project:

### Pre coding

Before writing any code with the intention of merging into master, ensure the work you're doing has an issue and try in good faith to engage the community in conversation in the issue feed.

* If an issue exists for the work you are beginning and,
  * no one seems to be working on it, comment that you are starting work and skip to the _coding_ checklist below.
  * If some one is already working on the issue consider collaborating
* If the issue doesn't exist, write one

Note: If the subject matter in an issue does not lend itself to a back and forth conversation (aka, a json schema), consider creating and referencing a wiki page.

### Coding

* Fork or create a branched named "Issue #xxx"
* Make an initial commit (create a file, add comments in file)
* Open a pull request that references issue in the comment and briefly describes your approach to fixing
* Recruit _code reviewer_ (send them link to the pull request and say, "hey, I'm working on **this**, could you review for me?")
* Coding will take you through any number of iterations of this:
* ... contributor works and commits updates
* ... reviewer incrementally reviews as often as possible
* Both agree the code is done
* Code reviewer merges pull request,
	* if merge conflicts arise, contributor should resolve (possibly pairing with the author of the conflicting code.)
* Once the merge is complete, the branch can be deleted

### Exceptions

* Updates to documentation may be merged directly into master
* Small bugs or tweaks caught by the contributor post merge
  * These commits should include the issue number in the commit message for reference


## How to run sprints

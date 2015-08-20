# trntbl4000

## Overview ##
> TRNTBL3000 is an app to play music. Liven up a party with this simple DIY DJ-app.
  TRNTBL4000 incorporates this need but adds video functionality and the ability to search the Youtube API to add the songs you want to sing or listen to and use a crossfader in between songs.

## Dependencies ##
> Assert

> Bootstrap

> Express.js

> Node.js

> Mongoose

> Youtube API v3

## Tests ##
> Unit Testing: Mocha, Chai

> Integration Testing: Sinon, Supertest

## Getting Started

### Installation
Install dependencies `npm install `
### Running Tests

backend testing:
`npm test`

frontend testing:
`spec/index.html`

## Developer Info ##
> Limited spec tests due to evolving architecture of application

## Roadmap ##
> Possible future updates may include the ability to:
  -search the libraries from soundcloud's API and build your own playlists
  -have multiple DJ-ing sound clips and special FX
  display lyrics for karaoke usage

## Notes on the Procfile ##
> This tells Heroku the location of the server. Other environmental variables can be set here.

## Credits ##

Version 2 Development Team:

Product Owner: [Cristian Avalos](https://github.com/cavalos0086/)

Scrum Master: [Kent Ou](https://github.com/kent10ou/)

[Kim Merino](https://github.com/dafabulousteach/)

[Christopher Salam](https://github.com/ChristopherSalam/)

Version 1 Development Team:

[Claire Bendersky](https://github.com/cdersky/)

[Vy Cu](https://github.com/veeweeherman/)

[Glenn Gonda](https://github.com/alohaglenn/)

[Marc Cristophe](https://github.com/fusupo/)

## How to Contribute ##
Contributing
General Workflow

Fork the repo
Cut a namespaced feature branch from master
bug/...
feat/...
test/...
doc/...
refactor/...
Make commits to your feature branch. Prefix each commit like so:
(feat) Added a new feature
(fix) Fixed inconsistent tests [Fixes #0]
(refactor) ...
(cleanup) ...
(test) ...
(doc) ...
When you've finished with your fix or feature, Rebase upstream changes into your branch. submit a [pull request][] directly to master. Include a description of your changes.
Your pull request will be reviewed by another maintainer. The point of code reviews is to help keep the codebase clean and of high quality and, equally as important, to help you grow as a programmer. If your code reviewer requests you make a change you don't understand, ask them why.
Fix any issues raised by your code reviwer, and push your fixes as a single new commit.
Once the pull request has been reviewed, it will be merged by another member of the team. Do not merge your own commits.
Detailed Workflow

Fork the repo

Use github’s interface to make a fork of the repo, then add that repo as an upstream remote:

git remote add upstream https://github.com/[[ SCHOOL_NAME ]]-labs/<NAME_OF_REPO>.git
Cut a namespaced feature branch from master

Your branch should follow this naming convention:

bug/...
feat/...
test/...
doc/...
refactor/...
These commands will help you do this:

# Creates your branch and brings you there
git checkout -b `your-branch-name`
Make commits to your feature branch.

Prefix each commit like so

(feat) Added a new feature
(fix) Fixed inconsistent tests [Fixes #0]
(refactor) ...
(cleanup) ...
(test) ...
(doc) ...
Make changes and commits on your branch, and make sure that you only make changes that are relevant to this branch. If you find yourself making unrelated changes, make a new branch for those changes.

Commit Message Guidelines

Commit messages should be written in the present tense; e.g. "Fix continuous integration script".
The first line of your commit message should be a brief summary of what the commit changes. Aim for about 70 characters max. Remember: This is a summary, not a detailed description of everything that changed.
If you want to explain the commit in more depth, following the first line should be a blank line and then a more detailed description of the commit. This can be as detailed as you want, so dig into details here and keep the first line short.
Rebase upstream changes into your branch

Once you are done making changes, you can begin the process of getting your code merged into the main repo. Step 1 is to rebase upstream changes to the master branch into yours by running this command from your branch:

git pull --rebase upstream master
This will start the rebase process. You must commit all of your changes before doing this. If there are no conflicts, this should just roll all of your changes back on top of the changes from upstream, leading to a nice, clean, linear commit history.

If there are conflicting changes, git will start yelling at you part way through the rebasing process. Git will pause rebasing to allow you to sort out the conflicts. You do this the same way you solve merge conflicts, by checking all of the files git says have been changed in both histories and picking the versions you want. Be aware that these changes will show up in your pull request, so try and incorporate upstream changes as much as possible.

You pick a file by git adding it - you do not make commits during a rebase.

Once you are done fixing conflicts for a specific commit, run:

git rebase --continue
This will continue the rebasing process. Once you are done fixing all conflicts you should run the existing tests to make sure you didn’t break anything, then run your new tests (there are new tests, right?) and make sure they work also.

If rebasing broke anything, fix it, then repeat the above process until you get here again and nothing is broken and all the tests pass.

Make a pull request

Make a clear pull request from your fork and branch to the upstream master branch, detailing exactly what changes you made and what feature this should add. The clearer your pull request is the faster you can get your changes incorporated into this repo.

At least one other person MUST give your changes a code review, and once they are satisfied they will merge your changes into upstream. Alternatively, they may have some requested changes. You should make more commits to your branch to fix these, then follow this process again from rebasing onwards.

Once you get back here, make a comment requesting further review and someone will look at your code again. If they like it, it will get merged, else, just repeat again.

Thanks for contributing!

Guidelines

Uphold the current code standard:
Keep your code DRY
Follow STYLE-GUIDE.md
Run the tests before submitting a pull request.
Tests are very, very important. Submit tests if your pull request contains new, testable behavior.
Your pull request is comprised of a single squashed commit.

## References ##

> https://backbonejs.org/

> https://expressjs.com/

> https://nodejs.org/

> https://www.npmjs.com/package/gridfs-stream

> https://www.npmjs.com/package/assert

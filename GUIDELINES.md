# Guidelines

When maintaing a Rails sub-project, please try to follow these suggested guidelines:

- Make sure the Readme contains all of the following:
  - Clearly describes the project and how to include in a Rails project
  - Has builds running on Travis CI, and the (hopefully) green badge is at the top of the Readme underneath the project name
  - Clear contributing instructions including environment setup either in the Readme or in a dedicated `CONTRIBUTING.md` file (see sample CONTRIBUTING.md)
  - Create a `CHANGELOG.md` file and make sure all changes are listed, to make upgrading and keeping track of changes easier. (see sample CHANGELOg.md)
- When releasing a new version, please try and complete all of the following:
  - Make sure the latest master Travis CI build is green and all tests are passing, before releasing a new version of the gem.
  - Update the `CHANGELOG.md` file to denote what changes are in the released version.
  - Run `rake release`, and make sure the new gem is on rubygems.org, and the Git branch and tag are both on Github.

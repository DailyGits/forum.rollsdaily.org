# Forum:  forum.rollsdaily.org
============================

This is the repo for the Forum.BackdropCMS.org Forum.

Development
-----------

The forum site uses [Lando] for local development. Here
is how to get started:

* If you don't have Lando, download it: [Get Lando]
* Fork this repository into your own GitHub account
* Download with git:
  * `git clone git@github.com:[YOUR_USERNAME]/
* Move into the project root:
  * `cd forum.backdropcms.org`
* Start Lando
  * `lando start`
* Download and import the DB
  * `lando pull-db`
* Download and import the files
  * `lando pull-files`

The database and files come from. This site is
protected by a username and password. You can request the credentials via
[Zulip]

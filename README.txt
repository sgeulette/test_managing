test_managing
=============

repo test to test github interface

Testing difference between https and git urls
- https needs to enter user/pwd when pushing. "git config --global credential.helper cache" can cache the credentials in memory for a time
- adding in .git/config, under the '[remote "origin"]' section, a "pushURL = git@github.com:..." will use the ssh key when pushing

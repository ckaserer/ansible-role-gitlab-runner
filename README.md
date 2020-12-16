[![](https://img.shields.io/travis/com/ckaserer/ansible-role-gitlab-runner/master?style=flat-square)](https://travis-ci.com/ckaserer/ansible-role-gitlab-runner)
![gplv3](https://img.shields.io/badge/license-GPL%20v3.0-brightgreen.svg?style=flat-square)
![Maintenance](https://img.shields.io/maintenance/yes/2021?style=flat-square)

# ckaserer.gitlab_runner

:warning: This role needs to be run as root.

This is due to the fact, that we will use become_user in the role to switch to a newly created user "gitlab-runner" and only root can switch to a new user by default.

----

Manual steps:

* run gitlab-runner register
* install, enable and start docker if needed
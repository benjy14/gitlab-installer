gitlab-installer
================

### Installer for GitLab/GitLabHQ on CentOS 6 ###

- Fully unattended
- MySQL or SQLite database (defaulting to MySQL)
- Localhost mail relay

### Install on EL6 ###

    curl https://raw.github.com/benjy14/gitlab-installer/master/gitlab-install-el6.sh | bash

### Check status (diagnostic) ###

    su - git -c "cd gitlab;bundle exec rake gitlab:check RAILS_ENV=production"


### Original Fork ###
Flattr [my profile](https://flattr.com/profile/mattiasohlsson "Mattias Ohlsson on Flattr") to support this!

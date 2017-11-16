## [![Nabla](https://debops.org/images/debops-small.png)](https://github.com/AlbanAndrieu) roles/chrome

This file was generated by Ansigenome. Do not edit this file directly but instead have a look at the files in the ./meta/ directory. 

[![License](http://img.shields.io/:license-apache-blue.svg?style=flat-square)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Travis CI](https://img.shields.io/travis/AlbanAndrieu/ansible-roles/chrome.svg?style=flat)](https://travis-ci.org/AlbanAndrieu/ansible-roles/chrome)
[![Branch](http://img.shields.io/github/tag/AlbanAndrieu/ansible-roles/chrome.svg?style=flat-square)](https://github.com/AlbanAndrieu/ansible-roles/chrome/tree/master)
[![Donate](https://img.shields.io/gratipay/AlbanAndrieu.svg?style=flat)](https://www.gratipay.com/~AlbanAndrieu)


Install chrome on Ubuntu....

### Requirements

python-pycurl and python-software-properties installed.

### Installation

This role requires at least Ansible. To install it, run:

Using `ansible-galaxy`:
```shell
$ ansible-galaxy install devbox.roles/chrome
```

Using `arm` ([Ansible Role Manager](https://github.com/mirskytech/ansible-role-manager/)):
```shell
$ arm install devbox.roles/chrome
```

Using `git`:
```shell
$ git clone https://github.com/AlbanAndrieu/ansible-roles/chrome.git
```

### Documentation

More information about `devbox.roles/chrome` can be found in the
TODO [official devbox.roles/chrome documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-roles/chrome/docs/).


### Role variables

List of default variables available in the inventory:

```YAML
---
google_chrome_stable_enabled: yes                       # Enable module
google_talkplugin_enabled: no                       # Disbale module
# Package states: present or installed or latest
google_agent_pkg_state: present
# Repository states: present or absent
google_agent_repository_state: present
google_repo_files :
  - "google-chrome.list"
  - "dl_google_com_linux_chrome_deb.list"
  - "dl_google_com_linux_talkplugin_deb.list"

docker_files_generated_directory         : "roles/chrome"
docker_volume_directory                  : ""
docker_working_directory                 : "/home/vagrant"
docker_image_name                        : "nabla/ansible-chrome"
```


### Detailed usage guide

Taken from
------------------

https://github.com/psgrove/ansibledevubuntu


### Contributor

- Alex Lourie, djay.il@gmail.com
- Alban Andrieu, alban.andrieu@free.com### Testing
```shell
$ ansible-galaxy install devbox.roles/chrome
$ vagrant up
```

### Contributing

The [issue tracker](https://github.com/AlbanAndrieu/ansible-roles/chrome/issues) is the preferred channel for bug reports, features requests and submitting pull requests.

For pull requests, editor preferences are available in the [editor config](.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>.

In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests and examples for any new or changed functionality.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

### Authors and license

`roles/chrome` role was written by:

- Alex Lourie | [e-mail](mailto:djay.il@gmail.com) | [Twitter](https://twitter.com/alourie) | [GitHub](https://github.com/ alourie)
- [Alban Andrieu](fr.linkedin.com/in/nabla/) | [e-mail](mailto:alban.andrieu@free.com) | [Twitter](https://twitter.com/AlbanAndrieu) | [GitHub](https://github.com/AlbanAndrieu)

License
-------

- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-roles/chrome/issues)!

***

This role is part of the [Nabla](https://github.com/AlbanAndrieu) project.
README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).

***

Alban Andrieu

[linkedin](fr.linkedin.com/in/nabla/)
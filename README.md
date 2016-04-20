# Ansible Role Python

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-python.svg)](https://travis-ci.org/hadenlabs/ansible-role-python)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-python.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-python)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-python.svg)](https://github.com/hadenlabs/ansible-role-python/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [python][link-python] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

```yaml
    ---
    # defaults file for python
```


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

```yaml
    - hosts: servers
      roles:
        - hadenlabs.python
```


To install a specific version:

```yaml
  - hosts: servers
    roles:
      - { role: hadenlabs.python }
```


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-python]: https://www.python.org
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors

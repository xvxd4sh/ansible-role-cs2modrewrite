# ansible-role-cs2modrewrite #

[![GitHub Build Status](https://github.com/xvxd4sh/ansible-role-cs2modrewrite/workflows/build/badge.svg)](https://github.com/xvxd4sh/ansible-role-cs2modrewrite/actions)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/xvxd4sh/ansible-role-cs2modrewrite.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/xvxd4sh/ansible-role-cs2modrewrite/alerts/)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/xvxd4sh/ansible-role-cs2modrewrite.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/xvxd4sh/ansible-role-cs2modrewrite/context:python)

This Ansible role for downloading [cs2modrewrite](https://github.com/threatexpress/cs2modrewrite/blob/master/cs2modrewrite.py).

## Requirements ##

None.

## Role Variables ##

None.

<!--
| Variable | Description | Default | Required |
|----------|-------------|---------|----------|
| optional_variable | Describe its purpose. | `default_value` | No |
| required_variable | Describe its purpose. | n/a | Yes |
-->

## Dependencies ##

None.

## Example Playbook ##

Here's how to use it in a playbook:

```yaml
- hosts: all
  become: yes
  become_method: sudo
  roles:
    - cs2modrewrite
```

## Contributing ##

We welcome contributions!  Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for
details.

## License ##

This project is in the worldwide [public domain](LICENSE).

This project is in the public domain within the United States, and
copyright and related rights in the work worldwide are waived through
the [CC0 1.0 Universal public domain
dedication](https://creativecommons.org/publicdomain/zero/1.0/).

All contributions to this project will be released under the CC0
dedication. By submitting a pull request, you are agreeing to comply
with this waiver of copyright interest.

## Author Information ##

Heather Fetty - <heather.fetty@cisa.dhs.gov>

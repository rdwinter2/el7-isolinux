Enterpise Linux 7 (EL7) kickstart ISO creator  [![Build Status](https://travis-ci.org/rdwinter2/el7-isolinux.png?branch=master)](https://travis-ci.org/rdwinter2/el7-isolinux)
=============================================

This Ansible role creates a self-contained ISO image for an unattended of an Enterprise Linux 7 server.

The role follows the hardening best pratices outlined in [RedHatGov/ssg-el7-kickstart](https://github.com/RedHatGov/ssg-el7-kickstart).

Some files from the above repo, [commit 9a5ecc8 on Jan 15, 2019](https://github.com/RedHatGov/ssg-el7-kickstart/commit/9a5ecc8bbc8a4ecf7bcdb6f54d4a3ad1736b4f31) are duplicated in their entirety in this repo. See [ssg-el7-kickstart](https://github.com/RedHatGov/ssg-el7-kickstart/blob/9a5ecc8bbc8a4ecf7bcdb6f54d4a3ad1736b4f31/LICENSE) for LICENSE.

The included files include:
* ssg-suplemental.sh
* ipa-pam-configuration.sh

## Documentation

## Requirements

## Dependencies

None

## Setup

## Testing

## Role Variables

| Name | Default Value | Description |
|------|---------------|-------------|
|

## Example Playbook

```{.yml}
- name: Exercise the role el7-isolinux
  hosts: all
  become: true
  become_method: 'sudo'
  roles:
    - { role: el7-isolinux }
```

## Configuration

## Road Map

### Planned Additions

### Current Issues

### Changelog

## Discussion

## Transcluded Content

## License

MIT


## Author Information

| Author                | E-mail                        |
|-----------------------|-------------------------------|
| Robert D. Winter, 2nd |  rdwinter2@gmail.com          |

## References

*

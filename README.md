# Ansible role `personal`

Build Status (master): [![Travis BuildStatus](https://travis-ci.org/vonpupp/ansible-role-vonpupp.svg?branch=master)](https://travis-ci.org/vonpupp/ansible-role-vonpupp)

An Ansible role for PURPOSE. Specifically, the responsibilities of this role are to:

-

## Requirements

No specific requirements

## Role Variables


| Variable   | Required | Default | Comments (type)  |
| :---       | :---     | :---    | :---             |
| `role_var` | no       | -       | (scalar) PURPOSE |

## Dependencies

No dependencies.

## Example Playbook

See the [test playbook](tests/test.yml)

## Testing

The `tests` directory contains tests for this role in the form of a Vagrant environment. The directory `tests/roles/personal` is a symbolic link that should point to the root of this project in order to work. To create it, do

```ShellSession
$ cd tests/
$ mkdir roles
$ ln -frs ../../PROJECT_DIR roles/personal
```

You may want to change the base box into one that you like. The current one is based on Box-Cutter's [CentOS Packer template](https://github.com/boxcutter/centos).

The playbook [`test.yml`](tests/test.yml) applies the role to a VM, setting role variables.

## Contributing

Issues, feature requests, ideas are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Preferably, create a topic branch and when submitting, squash your commits into one (with a descriptive message).

## License

BSD

## Author Information

[vonpupp]

Based on the Ansible [skeleton] and the [script] from: Bert Van Vreckem (bert.vanvreckem@gmail.com)

[vonpupp]: https://github.com/vonpupp
[skeleton]: https://github.com/bertvv/ansible-role-skeleton
[script]: https://github.com/bertvv/scripts/blob/master/src/role-skel.sh

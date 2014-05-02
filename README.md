ansible-ark-nodejs
=======================

Playbook for a NodeJS Ark

Support open source!

## The Dockerfile

The Dockerfile represents an example output of using the ansible ark playbook.
It has been served up to docker.io for demonstration purposes.

## How to use

See this integration test [playbook](https://github.com/AnsibleShipyard/ansible-ark-nodejs/blob/master/tests/playbook.yml)
on how to use this role.

Also, see the [ansible-ghost](https://github.com/AnsibleShipyard/ansible-ghost) playbook (very
similar to the above test playbook).

There is lots of room for improvement, such as using the archive module, etc...
Expect to see those soon.

Send a Pull Request if you have changes and would like to contribute!

## Notes

You will see that in this role, I keep the Dockerfile within `tests/`. The reason
is the Dockerfile created is _purely_ for testing. Otherwise a `docker/` dir
should be created.

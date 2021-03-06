# telemetry-framework

Automation for telemetry framework using Ansible playbooks layered on top of
OpenShift Ansible

## Prerequisites

The `bootstrap.sh` script assumes you already have `git` installed on your
system and that you have access to `github.com`. No checks are performed to
validate this for you.

## Usage

Run `bootstrap.sh` which will clone the OpenShift Ansible repository and setup
the _telemetry framework_ components inside the repository.

The script is intended to be run from the root of the repository.

```
./scripts/bootstrap.sh
```

## Installation

Installation of the telemetry framework is currently being developed. Documentation is available in the [documentation](docs/README.md) folder.

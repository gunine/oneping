# Oneping Application

## What is Oneping Application?
Sample application that permits only one ICMP ping per minute for a unique src/dst MAC pair per switch.

## How to run?
Clone the oneping application source to apps directory under onos root path.

```bash
$ cd onos/apps
$ git clone https://github.com/gunine/oneping.git
```

Add oneping app module to modules.defs and modules.bzl under ONOS_APPS section.
```
"//apps/oneping:onos-apps-oneping-oar",
```

Compile the entire project using following command.
```bash
$ bazel build onos
```

Run ONOS locally.
```bash
$ ok clean
```

Access ONOS through CLI.
```bash
$ onos localhost
```

Activate oneping application.
```bash
onos> app activate oneping
```

# Configuration management
- Intro to Configuration Management
- Puppet resource type: file (check “Resource types” for all - - - manifest types in the left menu)
- Puppet’s Declarative Language: Modeling Instead of Scripting
- Puppet lint
- Puppet emacs mode

## Technologies
* Scripts written in Bash 4.3.11(1)
* Tested on Ubuntu 14.04 LTS
* Puppet 3.8

## Files

| Filename | Description |
| -------- | ----------- |
| `0-create_a_file.pp` | Create a file in `/tmp` |
| `1-install_a_package.pp` | Install `puppet-lint` |
| `2-execute_a_command.pp` | Create a manifest that kills a process named `killmenow` |
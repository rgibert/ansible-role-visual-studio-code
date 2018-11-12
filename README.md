# Visual Studio Code

Ansible role to install Visual Studio Code

[![Build Status](https://travis-ci.org/rgibert/ansible-role-visual-studio-code.svg?branch=master)](https://travis-ci.org/rgibert/ansible-role-visual-studio-code)
[![GitHub issues](https://img.shields.io/github/issues/rgibert/ansible-role-visual-studio-code.svg)](https://github.com/rgibert/ansible-role-visual-studio-code/issues)
[![GitHub forks](https://img.shields.io/github/forks/rgibert/ansible-role-visual-studio-code.svg)](https://github.com/rgibert/ansible-role-visual-studio-code/network)
[![GitHub stars](https://img.shields.io/github/stars/rgibert/ansible-role-visual-studio-code.svg)](https://github.com/rgibert/ansible-role-visual-studio-code/stargazers)
[![GitHub license](https://img.shields.io/github/license/rgibert/ansible-role-visual-studio-code.svg)](https://github.com/rgibert/ansible-role-visual-studio-code/blob/master/LICENSE)

## Requirements

- none

## Role Variables

| Variable | Default | Description |
|----------|---------|-------------|
| visual_studio_code_arch | | Architecture of the binaries to install |
| visual_studio_code_repo_root | https://vscode-update.azurewebsites.net/latest | Root URI for downloads |

## Dependencies

- none

## Example Playbook

```yaml
- hosts:
    - servers
  roles:
    - rgibert.visual_studio_code
```

## License

GPLv3

## Author Information

Richard Gibert
[richard@gibert.ca](mailto:richard@gibert.ca)
[https://richard.gibert.ca](https://richard.gibert.ca/)

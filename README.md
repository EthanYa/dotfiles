# dotfiles
My macOS dotfiles

## Install

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/EthanYa/dotfiles/master/install.sh)"
```

## Manually steps
### Login / Unlock Bitwarden
Login to Bitwarden
```shell
bw login $BITWARDEN_EMAIL
```
Unlock Bitwarden vault
```shell
bw unlock
```
### Sync Brave Browser
- [How do I set up Sync](https://support.brave.com/hc/en-us/articles/360021218111-How-do-I-set-up-Sync-)
> Disable sync `Open Tabs` , `Passwords`, `Addresses and more`


### Generate SSH key for GitHub
- [Generate a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [Add a new SSH key via terraform](https://github.com/EthanYa/github-infrastructure/blob/528289a125dafa0f3988a66327f356d1a42d92f6/terraform.tfvars#L1)


### Generate GPG key for GitHub
- [Generating a new GPG](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-)
- [Add GPG key via terraform](https://github.com/EthanYa/github-infrastructure/blob/528289a125dafa0f3988a66327f356d1a42d92f6/terraform.tfvars#L5)

### Use Raycast as launcher
- [Disable Spotlight](https://manual.raycast.com/hotkey)
- import setting

### Sync Jetbrains IDEs setting
- [WebStorm](https://www.jetbrains.com/help/webstorm/sharing-your-ide-settings.html#IDE_settings_sync)
- [DataGriip](https://www.jetbrains.com/help/datagrip/sharing-your-ide-settings.html#IDE_settings_sync)

## TODO
- [X] ~/.aws
- [ ] ~/.kube
- [ ] ~/.ssh
- [ ] ~/.vim
- [ ] gh setting
- asdf
  - [ ] add plugins (nodejs, terraform, golang, rust)
  - [ ] set default global version
- mac configuration
    - [X] time format use 24-Hour time
    - [X] keyboard > Key Repeat > Fast
    - [X] keyboard > Delay Until Repeat > Short
    - [X] Dock & Menu Bar > Automatically hide and show the Dock > enabled

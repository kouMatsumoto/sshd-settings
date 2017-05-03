# sshd-settings
A checklist of creating linux user for sshd

# Chack List

## SSH Key

1. permission of `~/.ssh/` is 0700
1. permission of `~/.ssh/authorized_keys` is 0600

## sshd_config

1. RSAAuthentication yes
1. PubkeyAuthentication yes


## Recommended

1. PermitRootLogin no
1. PasswordAuthentication no
1. Port `not 22`

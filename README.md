# macops
Shell scripts for macOS tasks

## .ssh profile switching

In order to switch between SSH profiles on your Mac you will need
to create your `USERN` profiles in an `ssh` directory (_not_
`.ssh`). `macops ssh $USER` will symlink `~/.ssh` to the directory
`ssh/$USER`:

```
$  mkdir ssh/{USER1,USER2,USER3,...}
$  macops ssh ${USERN}
```

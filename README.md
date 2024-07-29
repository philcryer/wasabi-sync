# wasabi-sync

![](img/sync-or-backup-files-to-wasabi.png)
*Sync or backup files to Wasabi*

README.md WIP

## Summary

## Requirments

```shell
apt get install rsync rclone
```

## Steps

### Install

* wasabi-sync and wasabi-local

```shell
git clone 
cd wasabi-sync
mkdir -p ~/bin
cp wasabi-sync wasabi-sync-local ~/bin
chmod 0755 ~/bin/wasabi-sync*
```

* setup systemd automation task

```shell
mkdir -p ~/.config/systemd/user/
cp wasabi-sync.service wasabi-sync.timer ~/.config/systemd/user/
```

### Configure

### Enable

### Test

## License

[MIT License](LICENSE)

### Thanks

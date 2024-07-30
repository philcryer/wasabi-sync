# wasabi-sync

<figure>
<div align="center" />
    <img src="img/sync-or-backup-files-to-wasabi.png" alt="Sync or backup files to Wasabi" /><br />
    <figcaption>Sync or backup files to Wasabi</figcaption>
</div>
</figure>

## Summary

## Requirments

* Debian/Ubuntu or other Debian variant 

```shell
apt install rsync rclone
```

* Fedora/Silverblue or other Red Hat variant

```shell
dnf install rsync rclone
```

* Homebrew (MacOS / Linux)

```shell
brew install rsync rclone
```

## Steps

### Install

* wasabi-sync and wasabi-local

```shell
git clone git@github.com:philcryer/wasabi-sync.git
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

https://rclone.org/s3/#wasabi

```shell
rclone config

n/s> n
name> wasabi




### Enable

### Test

## License

[MIT License](LICENSE)

### Thanks

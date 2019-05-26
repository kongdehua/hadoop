# some tips

## 开机不进入图形界面

### ubuntu 16

```
	sudo systemctl lightdm.service disable
```

### ubuntu 14

```
	vim /etc/default grub
```

Find this line:

```
	GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"
```

Change it to:

```
	GRUB_CMDLINE_LINUX_DEFAULT="text"
```

Update GRUD:

```
	sudo update-grub
```



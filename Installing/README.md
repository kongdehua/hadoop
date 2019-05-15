# Installing on a headless server

## Install a java jdk, xvfb

```
	sudo apt-get install xvfb
```

## Runing

```
	$ Xvfb :1 -screen 0 1024x768x24 &
	$ DISPLAY=:1 ./eclipse/eclimd -b
```


# dockerwm
Docker Container with a Window-Manager
 
## Building
```bash
$ docker build -t csicar/dockerwm .
```

### Running
- install Xephyr
- `$ docker run -it -e DISPLAY=:1 --device /dev/snd -v /tmp/.X11-unix:/tmp/.X11-unix csicar/dockerwm /usr/bin/mate-session`

# pwm

## How to use

```bash
docker run --name pwm \
           -p 8443:8443 \
           -v /etc/localtime:/etc/localtime \
           -v ./config:/config \
           -d ebrainte/docker-pwm
```

## Special Volumes

|  Volume  | Info |
|:------:|:-------:|
| /config  | All config files used by PWM|
| /etc/localtime  | To set container clock as the host clock |

## LIBS Version

These are the version of the package used by the container.

|  NAME  | Info | 
|:------:|:-------:|
|   VERSION  | 2.0.5 |
|   VERSION_N |  2_0_5 | 

## References

This project contains part of code taken or similar from [fjudith container Dockerfile](https://hub.docker.com/r/fjudith/pwm/dockerfile).

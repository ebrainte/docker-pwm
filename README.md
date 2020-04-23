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
|   PWM Version  | pwm-onejar-2.0.0-SNAPSHOT.jar |
|   RELEASE_DATE |  2020-03-19T20_16_30Z | 

## References

This project contains part of code taken or similar from [fjudith container Dockerfile](https://hub.docker.com/r/fjudith/pwm/dockerfile).

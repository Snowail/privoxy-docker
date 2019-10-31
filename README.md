# privoxy-docker
A privoxy docker image based on Alpine Linux.


## Usage

```
docker run -dt --name privoxy \
--restart unless-stopped \
-p 8118:8118 \
-v ~/privoxy.conf:/etc/privoxy/config \
snowail/privoxy-docker
```

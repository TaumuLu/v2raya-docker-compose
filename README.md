# v2raya-docker-compose

## docker run
```
docker run -d \
        --restart=always \
        --privileged \
        --network=host \
        --name v2raya \
        -v /etc/resolv.conf:/etc/resolv.conf \
        -v /etc/v2raya:/etc/v2raya \
        mzz2017/v2raya
```

# odat-docker
A Dockerized version of Oracle Database Attacking Tool (https://github.com/quentinhardy/odat)

# How build
```bash
docker build -t="hktalent/odat" .
```

# How use
```bash
docker run -i -t hktalent/odat /bin/bash
cd /root/odat
python3 ./odat.py -h
python3 ./odat.py all -p 1521 -s 192.168.1.254
```

# more
https://hub.docker.com/u/hktalent

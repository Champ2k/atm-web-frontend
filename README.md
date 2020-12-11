# atm-web-frontend
Writing a dockerfile to running an atm web app

## Installation

```
git clone https://github.com/Champ2k/atm-web-frontend.git
cd atm-web-frontend
docker build -t atm-docker .
docker run -d -p 9000:8090 atm-docker
```


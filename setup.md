# Running TOR SOCKS5 PROXY

## Run

docker compose up -d

## Test

curl --socks5-hostname 127.0.0.1:9150 https://check.torproject.org/api/ip

{"IsTor":true,"IP":"178.20.55.16"}

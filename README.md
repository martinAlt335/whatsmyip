# whatsmyip
Golang API running as a [Vercel Serverless Function](https://vercel.com/docs/serverless-functions) which returns your public IP address

![tests](https://github.com/wafer-bw/whatsmyip/workflows/tests/badge.svg)

## Links
* [Homepage](https://whatsmyip.wafer-bw.vercel.app)
* [API](https://whatsmyip.wafer-bw.vercel.app/api/ip) which supports the following `accept` headers:
    * `application/json`
    * `application/protobuf`

## Usage
```bash
git clone git@github.com:wafer-bw/whatsmyip.git
cd whatsmyip
make test
```

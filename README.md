# Personal Quartz 

## Build and preview

`npx quartz build --serve`

## Run with docker

`docker run --restart=always -d -itp 1111:8080 -v $(pwd)/content:/usr/src/app/content $(docker build -q .)`

## Quartz 4 documentation

Read the documentation and get started: https://quartz.jzhao.xyz/


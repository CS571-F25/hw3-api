build
```bash
docker build . -t ctnelson1997/cs571-f25-hw3-api
docker push ctnelson1997/cs571-f25-hw3-api
```

run
```bash
docker pull ctnelson1997/cs571-f25-hw3-api
docker run --name=cs571_f25_hw3_api -d --restart=always -p 48103:48103 -v /cs571/f25/hw3:/cs571 ctnelson1997/cs571-f25-hw3-api
```
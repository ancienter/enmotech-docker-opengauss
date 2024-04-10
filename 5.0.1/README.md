```bash
docker buildx build . -t registry.cn-chengdu.aliyuncs.com/hlzt/opengauss:5.0.1 --build-arg TARGETARCH="amd64"
```

```bash
docker push registry.cn-chengdu.aliyuncs.com/hlzt/opengauss:5.0.1
```

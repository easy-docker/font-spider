# docker-font-spider
字蛛
# 使用方法
参考: http://font-spider.org/#use

font-spider命令前增加
`docker run -it --rm -v $PWD:/data ghostry/font-spider `
,并注意路径的映射关系

例如:
```
docker pull ghostry/font-spider
docker run -it --rm \
    -v $PWD:/data \
    ghostry/font-spider \
    font-spider /data/*.html
```

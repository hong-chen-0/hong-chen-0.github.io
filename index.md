## Docker

获取镜像

```markdown
docker pull nginx
```

列出镜像

```markdown
docker image ls
```

列出容器

```markdown
docker ps -a
```

查看容器状态

```markdown
docker stats
```

运行镜像（80端口映射）

```markdown
docker run -d -p 80:80 nginx:cc
```

重命名容器

```markdown
docker rename vv cc
```

删除镜像

```markdown
docker rmi nginx:cc
```

导出镜像

```markdown
docker save nginx:cc > d:/cc.tar
```

导入镜像

```markdown
docker load < d:/cc.tar
```

进入容器（linux操作）

```markdown
docker exec -it nginx:cc bash
```

容器打包为镜像

```markdown
docker commit cc nginx:cc
```

重命名镜像（标记镜像）

```markdown
docker tag nginx:cc qgctempler/nginx:cc
```

镜像上传在线仓库（必须标记镜像后才能上传）

```markdown
docker push qgctempler/nginx:cc
```









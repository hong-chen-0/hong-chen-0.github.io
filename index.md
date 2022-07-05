## Docker

获取镜像

```markdown
docker pull nginx
```

列出镜像

```markdown
docker image ls
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
docker rmi ad080923604a
```

导出镜像

```markdown
docker save 1f7070945b34 > d:/cc.tar
```

导入镜像

```markdown
docker load < d:/cc.tar
```

重命名镜像

```markdown
docker tag 1f7070945b34 nginx:cc
```

进入镜像（linux操作）

```markdown
docker run -it nginx:cc bash
```

容器打包为镜像

```markdown
docker commit vv nginx:vv
```

镜像改名

```markdown
docker tag nginx:cc qgctempler/nginx:cc
```

镜像上传在线仓库

```markdown
docker push qgctempler/nginx:cc
```









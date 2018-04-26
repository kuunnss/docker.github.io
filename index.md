## Linux Docker Demo

You can use the [editor on GitHub](https://github.com/kuunnss/docker.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### 1.安装docker
···
sudo apt install docker.io
···

### 2.查看docker版本
```
sudo docker -v
```

### 3.配置 Docker 加速器
···
curl -sSL https://get.daocloud.io/daotools/set_mirror.sh | sh -s http://91221545.m.daocloud.io
···

### 4.输出Hello World
```
sudo docker run Hello-World
```



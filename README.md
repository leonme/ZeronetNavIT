# WebStack-Hugo 导航站点

本项目是基于 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 静态响应式网址导航主题，打造的的**个人定制版本**。

### 安装部署

下载更新，更新子模块。

```
$ git clone https://github.com/shenweiyan/NavBioIT.git
$ cd NavBioIT
$ git submodule update --init --recursive
$ cd themes/WebStack-Hugo
$ git pull https://github.com/leonme/WebStack-Hugo.git
```

### 发布站点

通过 GitHub Actions - [HugoAction.yml](https://github.com/leonme/ZeronetNavIT/blob/main/.github/workflows/HugoAction.yml)，本源码执行自动构建，并发布到以下仓库。


1. 发布至 GitHub 的 **[NavBioIT](https://github.com/leonme/ZeronetNavIT)** 可通过以下自定义域名访问；

   - **[https://www.zeronet.ltd](https://www.zeronet.ltd)**

2. 发布至 GitHub 的 **[WebStackBioIT](https://github.com/leonme/WebStackBioIT)**，该仓库 master 分支与 Cloudflare 的 **[biox.pages.dev](https://biox.pages.dev/)** 进行绑定；

### 站点地址

- **[https://www.zeronet.ltd](https://www.zeronet.ltd)**

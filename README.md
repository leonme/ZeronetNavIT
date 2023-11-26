
# Zeronet 导航页面

## 基本信息

本项目是基于 [WebStack-Hugo](https://github.com/leonme/WebStack-Hugo) 静态响应式网址导航主题，打造的的个人定制版本。

### Github源代码

* [leonme/WebStack-Hugo](https://github.com/leonme/WebStack-Hugo)： 本项目是基于纯静态的网址导航网站 webstack.cc 制作的 Hugo 主题，是一个基于 Hugo 的静态响应式网址导航主题。
* [leonme/ZeronetNavIT](https://github.com/leonme/ZeronetNavIT)： 本项目是基于 WebStack-Hugo 静态响应式网址导航主题，打造的的个人定制版本。

## 如何更新导航页面

下载更新，更新子模块。
```shell
$ git clone https://github.com/leonme/ZeronetNavIT.git
$ cd NavBioIT
$ git submodule update --init --recursive
$ cd themes/WebStack-Hugo
$ git pull https://github.com/leonme/WebStack-Hugo.git
```

直接修改 /content 下的内容

WebStack-Hugo 在ZeronetNavIT的theams下作为一个submodule

icon存在 [leonme/WebStack-Hugo](https://github.com/leonme/WebStack-Hugo) /static/assets/images/logos

在Intellij中直接修改ZeronetNavIT或者WebStack-Hugo，Commit Push的时候一起提交


## Github Action Automation

本项目已实现Github Automation自动部署到`www.zeronet.ltd`自定义域名下的Github Pages

Refer to: https://github.com/leonme/ZeronetNavIT/blob/main/.github/workflows/HugoAction.yml

当有新的Commit到main branch后，Action自动运行并发布部署

## 站点地址

- **[https://www.zeronet.ltd](https://www.zeronet.ltd)**

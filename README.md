# DaoCloud助力中国开发者提升Docker使用体验

昨天在DaoCloud主办的Docker两周年庆生会上，我们在Docker的朋友分享了一个惊天消息，今天这个消息已经在云计算的朋友圈里刷屏：《Docker完成9500万美元的融资》。

Docker这个本世纪以来发展最快，最受关注的开源爆款单品，已经在逆天的道路上前无古人，一骑绝尘，迈进独角兽俱乐部。

从14年底开始，DaoCloud作为中国最早的容器技术创业团队，我们一直致力于构建基于Docker的云计算技术。在此过程中，不仅作为最早落地的Docker产品，推出了Docker容器管理平台及Docker 云平台两个产品，还积极回馈社区与Docker公司联手促进国内Docker的生态建设，相信国内第一批Docker用户都或多或少从中受益。

玩Docker很难吧？这是早期用户都会问的第一个问题。虽然Docker将容器技术的门槛大大拉低，但是我们发现对初次接触的开发者来说，的确涉及到不大不小的一点学习曲线，尤其是和它第一次亲密接触时被其复杂的安装过程吓退，这难免有点因噎废食的可惜。

昨天下午在庆生会上我们收集了大家的痛点相似之处：安装，配置，和速度。于是乎，在大家的共同努力和Geek精神感召下，24小时后的此时此刻，我们烫手端出DaoCloud一站式Docker服务功能。空谈误国，实干兴邦，这也算我们给Docker项目2岁生日献上一份贺礼，也为国内的Docker用户解决燃眉之急。

我们的一站式Docker服务位于 http://get.daocloud.io 上，包含以下三个功能，内部代号“Docker吉祥三宝”。

## 第一宝：Docker官方安装包 - Docker Installation Mirror

我们提供了Linux下Docker安装包的镜像，每三小时会与国外源同步一次，配合七牛存储网络和CDN加速，使Docker的安装可以在瞬间完成。

```curl -sSL https://get.daocloud.io/docker | sh```

## 第二宝：Boot2Docker高速下载 - Boot2Docker Mirror

我们镜像了Boot2Docker的Windows和Mac的所有历史版本，一分钟内完成下载，瞬间开启Docker之旅。

https://get.daocloud.io/boot2docker/windows-installer/

https://get.daocloud.io/boot2docker/osx-installer/

## 第三宝：Docker Hub加速器 - Docker Hub Mirror

DaoCloud的Docker Hub Mirror服务，采用官方Mirror机制，结合国内云主机、对象存储和CDN加速网络，硬生生把国内docker pull的速度从几十KB，提升到了1M以上。从此Build、Ship、Run无需等候，全程无尿点，高速docker run！

https://dashboard.daocloud.io/mirror

## 服务承诺
以上服务由DaoCloud专业团队运维，实时更新，并承诺永久免费。如果你喜欢我们的服务，请不吝给我们点个赞。https://github.com/DaoCloud/docker-mirror

Calm Down and Docker Run!

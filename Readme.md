### Tensorflow的常用部署方式

我们在用tensorflow训练完模型之后可以得到 **.pb**  或者 ckpt 文件, 如果我们想要部署到不同的环境中,需要选择哪种格式的文件呢? 本项目主要用 mnist 分类的实例来介绍 tensorflow的几种常用的部署方式, 供大家参考, 相信大家看了demo 之后可以很容易地应用到自己的项目中.

目前项目包含以下几种部署方式:

**tensorflow-serving 部署 (cpu)**

**tensorflow-serving 部署(gpu)**

**java 部署tensorlfow 模型(.pb 格式)**

**flask 部署tensorflow 模型**



tensorflow的部署方式多样，欢迎大家贡献其它的部署方式。
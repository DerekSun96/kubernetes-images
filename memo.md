# Kubernetes核心组件镜像创建

用于拉取到Kubernetes官方镜像（正常Kubernetes官方镜像是被墙掉的）

Kubernetes核心组件的镜像都是在谷歌官方的镜像仓库中保存的，这样对于国内的工程师来说要想取得官方镜像是非常困难的。

采用DockerHub与GitHub联合创建docker镜像的方式可以通过DockerHub服务器从Kubernetes官方镜像库拉取过来并在DockerHub上创建镜像，这样就间接解决了国内不能访问国外镜像库的问题了。

因此这里在我的GitHub账户下创建一个保存Dockerfile的git仓库，然后将Kubernetes的Dockerfile上传到GitHub仓库，用来取得Kubernetes核心组件镜像。

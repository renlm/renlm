# 个人笔记

## SpringCloudKubernetes
<a href="/doc/rancher/install/v2.6.9/Ubuntu.html" target="_blank">Rancher v2.6.9 安装（Ubuntu 22.04）</a>  
<a href="/doc/KubeConfig.html" target="_blank">KubeConfig</a>  

### MyGraph
	$ helm upgrade --install renlm mygraph \
        --repo https://renlm.gitee.io/helm/repo \
        --namespace renlm --create-namespace \
        --version 0.1.0

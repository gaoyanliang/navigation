# hexo-theme-webstack

https://blog.coolchong.cn/navigation/#

参考：https://blog.coolchong.cn/2021/07/16/navigation/


## 部署方式

- 在本地执行 hexo clean & hexo g
- hexo s // 本地预览是否正常

当本地预览没有任何问题后，我们打开navigation下的public文件夹，这个文件夹存储的是生成的html文件，我们将public文件夹下的所有文件复制

然后我们打开自己的博客站点文件夹，我这里是myblog（名字可能不同），然后在博客站点文件夹下进入source文件夹并创建一个新的文件夹navigation

然后进入这个navigation文件夹将刚刚复制的文件拷贝过来即可。

> 然后我们再打开博客站点文件夹下的_config.yml文件，在如下地方加入- "navigation/**"。意思是hexo博客渲染生成页面时这个文件夹下的内容跳过渲染显示
# 《这本书能让你连接互联网 Ⅱ》

《这本书能让你连接互联网》-> 《这本书能让你连接互联网 Ⅱ》的更新要点：

* 增加速成科学上网篇章
* 增加相关上网方式以及软件配置操作
* crx_header_invalid 解决方案的说明
* VPN连接上服务器却无法访问任何网页及其他网络的解决办法
* Windows 无法设置系统代理的问题
* 项目内置 probot 机器人，method 新增 战略家模式

* <details><summary>其他更新 click me! </summary>

    * 增加对虚拟电话注册方案的说明
    * 谷歌新账户注册方式
    * 网页时光机以及查找相似站点
    * 利用个人博客作为连接互联网的中转

    </details>

### 在线部署

1. fork 《这本书》 到你的 repo
2. 修改 docs/index.html 将`window.$docsify = {}` 的`repo` 修改成你的 repo
3. 在 settings 找到 GitHub Pages 并选择 `master brach/docs folder` 
4. 访问 `https://你的GitHub用户名.github.io/fq-book` 即可看到效果

```
# 代理设置
git config --global http.proxy 'socks5://127.0.0.1:1080'
git config --global https.proxy 'socks5://127.0.0.1:1080'
# 取消代理
git config --global --unset https.proxy 'socks5://127.0.0.1:1080'
git config --global --unset http.proxy 'socks5://127.0.0.1:1080'
```
# mydocsify# mydocsify


```bash
# 安装node, npm
curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt install -y nodejs

node -v
npm -v
# 安装docsify
sudo npm i docsify-cli -g
```

```bash
# 初始化和运行docsify
docsify init ./docs
docsify serve docs --port 8000
```

github网址过程
文件夹docs
setting, pages即可
https://jerrychen94.github.io/mydocsify/


www.jerrychen.top过程
- 阿里云购买域名，需要实名认证才能购买
- 域名DNS解析到非80端口(https://blog.csdn.net/weixin_42452567/article/details/108340072)
 - 中途会遇到问题，需要备案www.jerrychen.top，身份证和签名书
 - test.jerrychen.top
 - www.jerrychen.top: http://test.jerrychen.top:8000
- docsify
 
# clash

## 给bash设置代理

&emsp;&emsp;查询代理：

```bash
netstat
```

看到有端口号为7890与Clash for Windows的端口号相同（Clash全局设置为直连，规则设置为美国）。

```bash
# 设置代理端口
git config --global http.proxy 'http://127.0.0.1:7890'
git config --global https.proxy 'https://127.0.0.1:7890'
```

完毕。

# 配置文件

&emsp;&emsp;有时候在网上下载配置文件失败。把配置文件导入到系统即可。常规-配置文件主目录-打开目录。profiles下xxx.yml即为你的配置文件，记住同时要复制list.yml文件。
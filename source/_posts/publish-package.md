---
layout: _post
title: 从零开始发布自己的NPM包
date: 2022-12-05 15:48:56
keywords: npm npmjs NPM 从零开始发布自己的NPM包
description: 从零开始发布自己的NPM包 NPM的全称是Node Package Manager，是一个NodeJS包管理和分发工具，已经成为了非官方的发布Node模块（包）的标准。
top_img: https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/3d1a51e4-3a0c-4d21-8043-2d35c1fbc64e.jpg
cover: https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/3d1a51e4-3a0c-4d21-8043-2d35c1fbc64e.jpg
---

{% note 'fa-brands fa-npm' modern %}
NPM的全称是Node Package Manager，是一个NodeJS包管理和分发工具，已经成为了非官方的发布Node模块（包）的标准。2020年3月17日，Github宣布收购npm，GitHub现在已经保证npm将永远免费。
{% endnote %}

注册NPM账户
======

{% note orange warning modern %}
如果还没有 NPM 帐户，可以创建一个帐户以便在 NPM 上共享和下载 Javascript 包。
{% endnote %}

1. 前往 [NPM](https://www.npmjs.com/signup) 注册页面。
2. 在注册页面表单中，填写用户名、邮箱、密码。
![](https://docs.npmjs.com/getting-started/setting-up-your-npm-user-account/signup-form.png)
3. 阅读最终用户许可协议和隐私政策，并表明您同意它们。
![](https://docs.npmjs.com/getting-started/setting-up-your-npm-user-account/privacy-policy.png)
4. 点击创建帐户。
![](https://docs.npmjs.com/getting-started/setting-up-your-npm-user-account/create-account-button.png)

---

添加NPM账户
======

{% note orange warning modern %}
在指定的注册表中创建一个新用户，并将凭据保存到.npmrc文件中。如果没有指定注册表，将使用默认注册表
{% endnote %}

1. npm adduser

```
npm adduser
```

2. 输入账号
3. 输入密码
4. 输入邮箱
5. 输入邮箱验证码

![](https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/b35bd90a-6c63-4fb8-b402-0558325ee641.png)

---

配置本地环境
======

{% note orange warning modern %}
要向 NPM 发布和安装包，必须使用 Node 版本管理器或 Node 安装程序安装 Node.js 和 npm 命令行界面。
{% endnote %}

1. 前往 [Node.js](https://nodejs.org/en/download/) 下载页面，下载并安装Node.js。

![](https://www.npmjs.cn/images/win-installing-node-lts.png)

2. 检查 NPM 和 Node.js 版本

```
node -v
npm -v
```

---

创建一个 package.json 文件
======

{% note orange warning modern %}
要发布一个 npm 包，需要创建一个 package.json 文件，用来描述包信息及依赖包。
{% endnote %}

1. 首先在本地新建一个文件夹，例如 mkdir hello-world

```
mkdir hello-world
```

2. 执行命令进入 hello-world 目录，cd hello-world

```
cd hello-world
```

3. 执行命令 npm init 进行初始化依赖，自动生成 package.json 文件

```
npm init
```

![](https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/57a58852-8672-40d5-9f97-fc2d6b81e4d3.png)

---

package.json 重点字段说明
======

{% note orange warning modern %}
其他相关字段说明参考[官方文档](https://docs.npmjs.com/cli/v8/configuring-npm/package-json)
{% endnote %}

|字段|说明|
|-|-|
|name|`npm项目包名，发布到npm时就是取这个name名，自己取个语义化的名字，和已有的npm库不能重复。`|
|version|`版本号，更新npm包时必须修改一个更高的版本号才能成功发布到npm，版本号最好遵循npm版本管理规范。`|
|description|`包的描述，发布到npm后你搜索该npm包时，在搜索联想列表里会显示在包名的下方，作为描述说明。`|
|main|`入口文件路径，在你通过import或require引用该npm包时就是引入的该路径的文件。`|

---

发布
======

1. npm publish --access public

```
npm publish --access public
```

![](https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/b61f948a-d104-4f34-8d54-9314f538f37d.png)

2. 前往 [NPM](https://www.npmjs.com/search?q=%40chen-af) 查看发布的包

![](https://mp-d7930f7b-df5c-4ab2-9b66-d51c38b2bf6c.cdn.bspapp.com/cloudstorage/346bd9e5-8b01-42f0-ac5f-48bd1f1c90b6.png)

---

{% flink %}
- class_name: 相关链接
  link_list:
    - name: NPM
      link: https://www.npmjs.com
      avatar: https://www.npmjs.cn/images/npm-lg.jpg
      descr: Node Package Manager
{% endflink %}

---
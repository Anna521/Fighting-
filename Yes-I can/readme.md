# 下载git后的一些基本操作

**提示**：*以下只是作为小白的我整理出来的初学git的一些微薄知识点，写出来只是为了让自己谨记，以后还可能会慢慢增加一些自己新学的内容*

下载好git后，需要做一些配置，以下我会整理一些配置要求与方法
---------
- 用户信息的设置

1. 设置用户名称

命令：$ git config --global user.name"Your username"

![图片详解](https://i.loli.net/2019/01/17/5c3f5565e0def.png)

2. 设置邮件地址

(1). 命令：$ git config --global user.email Your email

![图片详解](https://i.loli.net/2019/01/17/5c3f55be9e3e6.png)

- 密钥的创建

命令：$ ssh -keygen -t rsa -C "Youremail@example.com"

![图片详解](https://i.loli.net/2019/01/17/5c3f55e85cde4.jpg)

$ ls

$ cd ~ /.ssh

![图片详解](https://i.loli.net/2019/01/17/5c3f5618ebf9b.png)

$ cat id_rsa.pub

![图片详解](https://i.loli.net/2019/01/17/5c3f5618edb43.png)

**注**：*复制里面的内容*

(2).选择github中右上角*setting*那个选项

![图片详解](https://i.loli.net/2019/01/17/5c3f5618efac5.png)

(3).选择setting中*SSH and GPG keys*那个选项

![图片详解](https://i.loli.net/2019/01/17/5c3f56190f359.png)

(4).在key里粘贴开始所复制的内容

(5)为了检查成功与否，还需在git bash里跑一下

命令:ssh -T git@github.com

![图片详解](https://i.loli.net/2019/01/17/5c3f56191a07f.png)

**注**:*出现图片里的内容就代表可以了*

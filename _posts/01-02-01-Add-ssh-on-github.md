---
isChild: true
title:   在 github 上添加 SSH key 的步骤
anchor:  Add-ssh-on-github
---

## 在 github 上添加 SSH key 的步骤 {#Add-ssh-on-github_title}

首先需要检查你本地是否已经有 SSH key
 
{% highlight console %}
> la -al ~/.ssh
{% endhighlight %}

创建一个 SSH key

{% highlight console %}
> ssh-keygen -t rsa -C "your_email@example.com"
{% endhighlight %}


自动生成的文件

{% highlight console %}
> id_rsa  id_rsa.pub  known_hos
{% endhighlight %}

进入  id_rsa.pub  目录粘贴密匙到 github 账户的 点击菜单栏的 SSH key 进入页面添加 Add SSH Key 中 

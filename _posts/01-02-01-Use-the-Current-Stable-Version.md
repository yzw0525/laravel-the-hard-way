---
isChild: true
title:   在 github 上添加 SSH key 的步骤
anchor:  use_the_current_stable_version
---

## 在 github 上添加 SSH key 的步骤 {#use_the_current_stable_version_title}

首先需要检查你本地是否已经有 SSH key
 
{% highlight console %}
> la -al ~/.ssh
{% endhighlight %}

创建一个 SSH key

{% highlight console %}
> ssh-keygen -t rsa -C "your_email@example.com"
{% endhighlight %}


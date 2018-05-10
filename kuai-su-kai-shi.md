# 快速开始

## 快速开始

首先我们clone avg.engine和avg.render部分

{% code-tabs %}
{% code-tabs-item title="Bash" %}
```bash
$ git clone https://github.com/AngryPowman/avg.engine.git
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="Bash" %}
```bash
$ git clone https://github.com/AngryPowman/avg.renderer.git
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="info" %}
确保你已经安装了[nodejs](https://nodejs.org/en/)，[git](https://git-scm.com/)等依赖环境
{% endhint %}

在 avg.engine目录下

```bash
npm link
```

在 avg.render目录下

{% code-tabs %}
{% code-tabs-item title="Bash" %}
```bash
npm install
npm link "avg-engine"
npm run electron:dev
```
{% endcode-tabs-item %}
{% endcode-tabs %}




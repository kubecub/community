<h1 align="center" style="border-bottom: none">
    <b>
        <a href="https://docker.nsddd.top">KubeCub</a><br>
    </b>
</h1>
<h3 align="center" style="border-bottom: none">
      ⭐️  Open source automation community construction based on k8s  ⭐️ <br>
<h3>

<p align=center>
<a href="https://goreportcard.com/report/github.com/kubecub/go-project-layout"><img src="https://goreportcard.com/badge/github.com/kubecub/go-project-layout" alt="A+"></a>
<a href="https://github.com/issues?q=org%kubecub+is%3Aissue+label%3A%22good+first+issue%22+no%3Aassignee"><img src="https://img.shields.io/github/issues/kubecub/go-project-layout/good%20first%20issue?logo=%22github%22" alt="good first"></a>
<a href="https://github.com/kubecub/go-project-layout"><img src="https://img.shields.io/github/stars/kubecub/go-project-layout.svg?style=flat&logo=github&colorB=deeppink&label=stars"></a>
<a href="https://join.slack.com/t/kubecub/shared_invite/zt-1se0k2bae-lkYzz0_T~BYh3rjkvlcUqQ"><img src="https://img.shields.io/badge/Slack-100%2B-blueviolet?logo=slack&amp;logoColor=white"></a>
<a href="https://github.com/kubecub/go-project-layout/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-green"></a>
<a href="https://golang.org/"><img src="https://img.shields.io/badge/Language-Go-blue.svg"></a>
</p>

</p>

<p align="center">
    <a href="./README-zh-CN.md"><b>简体中文</b></a> •
    <a href="./README-zh-TW.md"><b>繁體中文</b></a> •
    <a href="./README-hi.md"><b>हिन्दी</b></a> •
    <a href="./README-ar.md"><b>العربية</b></a> •
    <a href="./README-fr.md"><b>Français</b></a> •
    <a href="./README.md"><b>English</b></a>
</p>

</p>

* * *

# 什么是 kubecub？

Kubecub是一个基于Kubernetes的开源生态项目，提供链上能力，将所有开源生态整合成一个可参考、可复制的系统和规范。它不仅包括基于Kubernetes的分布式应用，还包括开源工具的开发和组织，以及基于Kubecub的所有开源项目的管理和规范设计。

Kubecub是云原生领域的开源社区，其主要目标是帮助建立可复制的开源规范，并提供完整的运营体系，使社区能够健康发展。如今，该领域的项目很多，但在规格和操作方面往往缺乏统一的标准。 Kubecub的愿景是统一标准，提高开源项目质量，打造全球认可的云原生领域开源社区。

Kubecub主要使用Golang编程语言开发，但未来不仅限于此。印象最深刻的是Kubecub的社区运营采用了先进高效的运营体系，这让我深刻认识到当前开源社区存在的问题。在这种运营模式下，Kubecub管理员分配需求，为开源社区提供服务，及时获得反馈，并提供象征性奖励。通过这些手段，Kubecub参与者可以获得良好的开发体验，更有可能坚持下去，从而使开源社区更健康、更好的发展。

Kubecub目前正在设计一些工具，比如标签同步器、机器人、自动化、AI、客服等，这些工具的主要目的是辅助开源社区的管理，提高运营效率。他们也希望从事二次开发的开发者能够使用和改进他们的工具并遵守他们规定的开源规范。此外，Kubecub还在底层开发基于Kubernetes构建的分布式环境，用于运维整个社区。因此，Kubecub是一个非常有前途的开源社区管理工具。

综上所述，Kubecub的愿景是打造一个具有全球影响力的云原生领域开源社区，不仅要提高开源项目的质量和规范，还要让开源项目更加健康、成熟。同时，Kubecub提供了高效的运营体系来吸引和留住参与者，从而促进云原生社区的发展。对于热衷于云原生领域的开发者来说，Kubecub将是一个宝贵的机会，参与到标准化、可操作的开源社区，为云原生领域的进步做出贡献。

## 为什么要创建 Kubecub？

与其他开源社区不同，Kubecub 不仅仅是 Kubecub 的产品或存储库。它的功能远不止于此。让我解释...

**为什么叫库贝库布？**

> 🔥 kubecub 提供了 k8s 链的能力。

我认为Kubecub为Kubernetes提供了链的能力。连锁能力是什么？

在 Kubernetes 快速发展的同时，在 CNCF 基金会的引导下，整个云原生领域蓬勃发展，整个云原生领域的工具数不胜数，带动了整个开源社区的发展和繁荣。 Kubecub应运而生。

Kubecub就像一个区块链，将所有区块记录在一个超级账本中。 Kubecub将所有开源生态系统链接在一起，形成可参考、可复制的系统和规范。

包括但不仅限于：

-   基于Kubernetes的分布式应用，集成现有的Kubernetes解决方案。
-   Development and organization of open-source tools.
-   基于Kubecub的所有开源项目的管理和规范设计。

## 当前开源社区存在的问题

我们知道，任何顶级的开源项目都离不开顶级的运营模式，Kubernetes也不例外。对于 Kubernetes 来说，管理、运营和开发并不是相互排斥的，这也是为什么 Kubernetes 社区仍然是整个开源社区的领导者。

然而，并不是所有的项目都有成本和精力去运营和自动化管理，导致很多社区缺乏或很少有成熟的自动化和CICD以及社区规范。

Kubecub 混合了各种 DevOps 手段，使用机器人和动作来集成管理自动化和部分社区运营工作的手段。

## 谁可以参加 Kubecub？

Kubecub没有门槛！

Kubecub不需要钱！

Kubecub 没有任何限制！

您可以自己提出并实现一个想法，您可以根据项目中现有的提案来实现它，您还可以参与任何存储库来提出或解决功能、错误等。

甚至，你什么也做不了~随便输入一个项目的pull requests，看看哪个代码段不爽，评论一下~

## 从哪儿开始

我们有一个[HTTPS://GitHub.com/苦B ECU B/community](https://github.com/kubecub/community)存储库，定义社区规范和各种模板。

![yangzi](http://sm.nsddd.top/sm202306012140301.png)

**[0000-template.md](http://0000-template.md/)**是一个模板。我们可以使用这个模板，写一个markdown格式的提案到PRC目录下作为PR。这被认为是一个完整的 PR。项目开始前的规划工作就完成了。

阅读我们的[贡献者指南](https://github.com/kubecub/community/blob/main/CONTRIBUTING.md)，您可以在其中学习向开源项目贡献代码的最佳标准和实践。

## 未来方向

一个人的力量是有限的，后期的开源氛围势必会更加繁荣。越来越多想要加入开源的合作伙伴或团队都渴望拥有一个现成的解决方案。

我们将坚持Kubecub的运营，促进开源爱好者的成长和交流。

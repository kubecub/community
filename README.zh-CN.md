<h1 align="center" style="border-bottom: none">
    <b>
        <a href="https://docker.nsddd.top">KubeCub</a><br>
    </b>
</h1>
<h3 align="center" style="border-bottom: none">
      ⭐️  Open source automation community construction based on k8s cloud out of the box.  ⭐️ <br>
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

Kubecub 是一个基于 Kubernetes 的开源生态项目，提供链式能力，将所有开源生态整合成一个可引用、可复制的系统和规范。它不仅包括基于Kubernetes的分布式应用，还包括开源工具的开发和组织，以及所有基于Kubecub的开源项目的管理和规范设计。

Kubecub是云原生领域的一个开源社区，其主要目标是帮助建立一个可复制的开源规范，并提供一个完整的操作系统，使社区能够健康发展。如今，这一领域的项目很多，但在规范和操作上往往缺乏统一的标准。 Kubecub的愿景是统一标准，提升开源项目质量，打造云原生领域全球认可的开源社区。

Kubecub主要是使用Golang编程语言开发的，但以后不局限于此。印象最深的是Kubecub的社区运营采用了先进高效的运营体系，这让我深刻认识到了当前开源社区存在的问题。在这种运行模式下，Kubecub 管理员分配需求，为开源社区提供服务，及时得到反馈，并提供象征性的奖励。通过这些方式，Kubecub 的参与者可以获得良好的开发体验，也更容易坚持下去，从而使开源社区更健康、更好地发展。

Kubecub目前正在设计一些工具，比如标签同步器、机器人、自动化、AI、客服等，这些工具的主要目的是辅助开源社区的管理，提高运营效率。他们也希望从事二次开发的开发者能够使用和改进他们的工具，并遵守他们规定的开源规范。此外，Kubecub还在底层开发基于Kubernetes构建的分布式环境，用于运维整个社区。因此，Kubecub 是一个非常有前途的开源社区管理工具。

综上所述，Kubecub的愿景是在云原生领域打造一个具有全球影响力的开源社区，不仅要提升开源项目的质量和规范，还要让开源项目更健康、更成熟。同时，Kubecub 提供高效的运营体系来吸引和留住参与者，从而促进云原生社区的发展。对于热衷于云原生领域的开发者来说，Kubecub 将是一个参与到标准化、可操作的开源社区，为云原生领域的进步贡献力量的宝贵机会。

## 为什么要创建 Kubecub？

与其他开源社区不同，Kubecub 不仅仅是 Kubecub 的产品或存储库。它的功能远不止于此。让我解释...

**为什么叫 Kubecub？**

> 🔥 kubecub 提供了 k8s 链的能力。

我认为 Kubecub 为 Kubernetes 提供了上链的能力。什么是连锁能力？

在Kubernetes飞速发展的同时，在CNCF基金会的引领下，整个云原生领域蓬勃发展，整个云原生领域的工具更是数不胜数，带动了整个开源社区的发展与繁荣。 Kubecub 应运而生。

Kubecub 就像一个区块链，将所有区块记录在一个超级账本中。 Kubecub 将所有开源生态系统链接在一起，形成一个可参考和可复制的系统和规范。

包括但不仅限于：

-   基于 Kubernetes 的分布式应用，集成现有的 Kubernetes 解决方案。
-   开源工具的开发和组织。
-   基于Kubecub的所有开源项目的管理和规范设计。

## 当前开源社区存在的问题

我们知道任何顶级的开源项目都离不开顶级的运行模式，包括Kubernetes。对于 Kubernetes 来说，管理、运维和开发并不是相互排斥的，这也是为什么 Kubernetes 社区仍然是整个开源社区中的佼佼者。

然而，并不是所有的项目都有成本和精力来运营和自动化管理，导致很多社区缺乏或很少有成熟的自动化和CICD和社区规范。

Kubecub 混合了各种 DevOps 手段，使用机器人和动作来整合手段来管理自动化和社区的部分运营工作。

## 谁可以参与 Kubecub？

Kubecub 没有门槛！

Kubecub 不需要钱！

Kubecub 没有任何限制！

你可以自己提出并实施一个想法，你可以根据项目中现有的提案实施它，你也可以参与任何存储库来提出或解决功能、错误等。

甚至，你什么也做不了~随便输入一个项目的pull requests，看看哪个代码段不舒服，提点意见~

## 从哪儿开始

我们有一个<https://github.com/kubecub/community>存储库，它定义了社区规范和各种模板。

![yangzi](http://sm.nsddd.top/sm202306012140301.png)

**[0000-template.面对](http://0000-template.md/)**是一个模板。我们可以使用这个模板，写一个 markdown 格式的提案作为 PR 到 PRC 目录。这被认为是一个完整的 PR。并在开始项目之前完成计划工作。

阅读我们的[贡献者指南](https://github.com/kubecub/community/blob/main/CONTRIBUTING.md)，您可以在其中了解为开源项目贡献代码的最佳标准和实践。

## 未来方向

一个人的力量是有限的，后期的开源氛围势必会更加兴盛。越来越多想要加入开源的合作伙伴或团队渴望有一个现成的解决方案。

我们将坚持Kubecub的运营，促进开源爱好者的成长与交流。

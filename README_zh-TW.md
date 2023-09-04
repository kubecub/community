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

# What is kubecub?

Kubecub是一個基於Kubernetes的開源生態項目，提供鏈上能力，將所有開源生態整合成一個可參考、可複制的系統和規範。它不僅包括基於Kubernetes的分佈式應用，還包括開源工具的開發和組織，以及基於Kubecub的所有開源項目的管理和規範設計。

Kubecub是雲原生領域的開源社區，其主要目標是幫助建立可複制的開源規範，並提供完整的運營體系，使社區能夠健康發展。如今，該領域的項目很多，但在規格和操作方面往往缺乏統一的標準。 Kubecub的願景是統一標準，提高開源項目質量，打造全球認可的雲原生領域開源社區。

Kubecub主要使用Golang編程語言開發，但未來不僅限於此。印象最深刻的是Kubecub的社區運營採用了先進高效的運營體系，這讓我深刻認識到當前開源社區存在的問題。在這種運營模式下，Kubecub管理員分配需求，為開源社區提供服務，及時獲得反饋，並提供象徵性獎勵。通過這些手段，Kubecub參與者可以獲得良好的開發體驗，更有可能堅持下去，從而使開源社區更健康、更好的發展。

Kubecub目前正在設計一些工具，比如標籤同步器、機器人、自動化、AI、客服等，這些工具的主要目的是輔助開源社區的管理，提高運營效率。他們也希望從事二次開發的開發者能夠使用和改進他們的工具並遵守他們規定的開源規範。此外，Kubecub還在底層開發基於Kubernetes構建的分佈式環境，用於運維整個社區。因此，Kubecub是一個非常有前途的開源社區管理工具。

綜上所述，Kubecub的願景是打造一個具有全球影響力的雲原生領域開源社區，不僅要提高開源項目的質量和規範，還要讓開源項目更加健康、更加成熟。同時，Kubecub提供高效的運營體係來吸引和留住參與者，從而促進云原生社區的發展。對於熱衷於雲原生領域的開發者來說，Kubecub將是一個寶貴的機會，參與到標準化、可操作的開源社區，為雲原生領域的進步做出貢獻。

## 為什麼要創建 Kubecub？

與其他開源社區不同，Kubecub 不僅僅是 Kubecub 的產品或存儲庫。它的功能遠不止於此。讓我解釋...

**為什麼叫庫貝庫布？**

> 🔥 kubecub 提供了 k8s 鏈的能力。

我認為Kubecub為Kubernetes提供了鏈的能力。連鎖能力是什麼？

在 Kubernetes 快速發展的同時，在 CNCF 基金會的引導下，整個雲原生領域蓬勃發展，整個雲原生領域的工具數不勝數，帶動了整個開源社區的發展和繁榮。 Kubecub應運而生。

Kubecub就像一個區塊鏈，將所有區塊記錄在一個超級賬本中。 Kubecub將所有開源生態系統鏈接在一起，形成可參考、可複制的系統和規範。

包括但不僅限於：

-   基於Kubernetes的分佈式應用，集成現有的Kubernetes解決方案。
-   開源工具的開發和組織。
-   基於Kubecub的所有開源項目的管理和規範設計。

## 當前開源社區存在的問題

我們知道任何頂級的開源項目都離不開頂級的運營模式，Kubernetes也不例外。對於 Kubernetes 來說，管理、運營和開發並不是相互排斥的，這也是為什麼 Kubernetes 社區仍然是整個開源社區的領導者。

然而，並不是所有的項目都有成本和精力去運營和自動化管理，導致很多社區缺乏或很少有成熟的自動化和CICD以及社區規範。

Kubecub 混合了各種 DevOps 手段，使用機器人和動作來集成管理自動化和部分社區運營工作的手段。

## 誰可以參加 Kubecub？

Kubecub沒有門檻！

Kubecub不需要錢！

Kubecub 沒有任何限制！

您可以自己提出並實現一個想法，您可以根據項目中現有的提案來實現它，您還可以參與任何存儲庫來提出或解決功能、錯誤等。

甚至，你什麼也做不了~隨便輸入一個項目的pull requests，看看哪個代碼段不舒服，評論一下~

## 從哪兒開始

我們有一個<https://github.com/kubecub/community>存儲庫，定義社區規範和各種模板。

![yangzi](http://sm.nsddd.top/sm202306012140301.png)

**[0000-template.md](http://0000-template.md/)**是一個模板。我們可以使用這個模板，寫一個markdown格式的提案到PRC目錄下作為PR。這被認為是一個完整的 PR。項目開始前的規劃工作就完成了。

閱讀我們的[貢獻者指南](https://github.com/kubecub/community/blob/main/CONTRIBUTING.md)，您可以在其中學習向開源項目貢獻代碼的最佳標準和實踐。

## 未來方向

一個人的力量是有限的，後期的開源氛圍勢必會更加繁榮。越來越多想要加入開源的合作夥伴或團隊都渴望擁有一個現成的解決方案。

我們將堅持Kubecub的運營，促進開源愛好者的成長和交流。

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

# 什麼是 kubecub？

Kubecub是一個基於Kubernetes的開源生態項目，提供鏈上能力，將所有開源生態整合成一個可參考、可複製的系統和規格。它不僅包括基於Kubernetes的分散式應用，還包括開源工具的開發和組織，以及基於Kubecub的所有開源專案的管理和規格設計。

Kubecub是雲端原生領域的開源社區，其主要目標是協助建立可複製的開源規範，並提供完整的營運體系，使社區能夠健康發展。如今，該領域的項目很多，但在規格和操作方面往往缺乏統一的標準。 Kubecub的願景是統一標準，提升開源專案質量，打造全球認可的雲端原生領域開源社群。

Kubecub主要使用Golang程式語言開發，但未來不僅限於此。印象最深刻的是Kubecub的社群運作採用了先進且有效率的營運體系，這讓我深刻體會到目前開源社群存在的問題。在這種營運模式下，Kubecub管理員分配需求，為開源社群提供服務，及時獲得回饋，並提供象徵性獎勵。透過這些手段，Kubecub參與者可以獲得良好的開發體驗，更有可能堅持下去，從而使開源社群更健康、更好的發展。

Kubecub目前正在設計一些工具，例如標籤同步器、機器人、自動化、AI、客服等，這些工具的主要目的是輔助開源社群的管理，提高營運效率。他們也希望從事二次開發的開發者能夠使用和改進他們的工具，並遵守他們規定的開源規範。此外，Kubecub還在底層開發基於Kubernetes建構的分散式環境，用於維運整個社區。因此，Kubecub是一個非常有前景的開源社群管理工具。

綜上所述，Kubecub的願景是打造一個具有全球影響力的雲端原生領域開源社區，不僅要提高開源專案的品質和規範，還要讓開源專案更加健康、成熟。同時，Kubecub提供高效率的營運體系來吸引和留住參與者，從而促進雲端原生社群的發展。對於熱衷於雲端原生領域的開發者來說，Kubecub將是一個寶貴的機會，參與到標準化、可操作的開源社區，為雲端原生領域的進步做出貢獻。

## 為什麼要創建 Kubecub？

與其他開源社群不同，Kubecub 不僅僅是 Kubecub 的產品或儲存庫。它的功能遠不止於此。讓我解釋...

**為什麼叫庫貝庫布？**

> 🔥 kubecub 提供了 k8s 鏈的能力。

我認為Kubecub為Kubernetes提供了鏈的能力。連鎖能力是什麼？

在 Kubernetes 快速發展的同時，在 CNCF 基金會的引導下，整個雲原生領域蓬勃發展，整個雲原生領域的工具數不勝數，帶動了整個開源社群的發展和繁榮。 Kubecub應運而生。

Kubecub is like a blockchain that records all blocks in a super ledger. Kubecub chains all open-source ecosystems together to form a referenceable and reproducible system and specification.

包括但不僅限於：

-   基於Kubernetes的分散式應用，整合現有的Kubernetes解決方案。
-   開源工具的開發與組織。
-   基於Kubecub的所有開源專案的管理和規範設計。

## 目前開源社群存在的問題

我們知道，任何頂級的開源專案都離不開頂級的營運模式，Kubernetes也不例外。對 Kubernetes 來說，管理、營運和開發並不是相互排斥的，這也是為什麼 Kubernetes 社群仍然是整個開源社群的領導者。

然而，並不是所有的專案都有成本和精力去營運和自動化管理，導致許多社區缺乏或很少有成熟的自動化和CICD以及社區規範。

Kubecub 混合了各種 DevOps 手段，使用機器人和動作來整合管理自動化和部分社區運作工作的手段。

## 誰可以參加 Kubecub？

There is no threshold for Kubecub!

Kubecub不需要錢！

Kubecub 沒有任何限制！

您可以自己提出並實現一個想法，您可以根據專案中現有的提案來實現它，您還可以參與任何儲存庫來提出或解決功能、錯誤等。

甚至，你什麼也做不了~隨便輸入一個項目的pull requests，看看哪個代碼段不爽，評論一下~

## Where to start

我們有一個<https://github.com/kubecub/community>儲存庫，定義社群規範和各種範本。

![yangzi](http://sm.nsddd.top/sm202306012140301.png)

**[0000-template.md](http://0000-template.md/)**是一個模板。我們可以使用這個模板，寫一個markdown格式的提案到PRC目錄下當PR。這被認為是一個完整的 PR。專案開始前的規劃工作就完成了。

閱讀我們的[Contributor's Guide](https://github.com/kubecub/community/blob/main/CONTRIBUTING.md)，您可以在其中學習向開源專案貢獻程式碼的最佳標準和實踐。

## 未來方向

The power of one person is limited, and the open-source atmosphere in the later period is bound to become more prosperous. More and more partners or teams who want to join open-source are eager to have an existing solution.

我們將堅持Kubecub的運營，促進開源愛好者的成長和交流。

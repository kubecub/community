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

# ما هو kubecub؟

Kubecub هو مشروع نظام بيئي مفتوح المصدر يعتمد على Kubernetes يوفر إمكانات سلسلة لدمج جميع النظم الإيكولوجية مفتوحة المصدر في نظام ومواصفات قابلة للإحالة والتكرار. لا يشمل فقط التطبيقات الموزعة القائمة على Kubernetes ، ولكن أيضًا تطوير وتنظيم أدوات مفتوحة المصدر ، بالإضافة إلى تصميم الإدارة والمواصفات لجميع المشاريع مفتوحة المصدر القائمة على Kubecub.

Kubecub is an open-source community in the cloud-native field whose main goal is to help establish a reproducible open-source specification and provide a complete operational system to enable the community to have healthy development. Today, there are many projects in this field, but often there is a lack of uniform standards in terms of specifications and operations. Kubecub's vision is to unify standards, improve the quality of open-source projects, and create a globally recognized open-source community in the cloud-native field.

تم تطوير Kubecub بشكل أساسي باستخدام لغة برمجة Golang ، ولكنه لا يقتصر على هذا في المستقبل. الأمر الأكثر إثارة للإعجاب هو أن عمليات مجتمع Kubecub تستخدم نظامًا تشغيليًا متقدمًا وفعالًا ، مما جعلني على دراية عميقة بالمشكلات الموجودة في مجتمع المصادر المفتوحة الحالي. في هذا الوضع التشغيلي ، يخصص مسؤولو Kubecub الطلبات ، ويقدمون الخدمات لمجتمع المصادر المفتوحة ، ويحصلون على التعليقات في الوقت المناسب ، ويقدمون مكافآت رمزية. من خلال هذه الوسائل ، يمكن للمشاركين في Kubecub الحصول على تجربة تطوير جيدة ومن المرجح أن يستمروا ، مما يجعل مجتمع المصدر المفتوح أكثر صحة وتطورًا.

Kubecub is currently designing some tools, such as label synchronizers, robots, automation, AI, customer service, etc. The main purpose of these tools is to assist in the management of open-source communities and improve operational efficiency. They also hope that developers who engage in secondary development can use and improve their tools and comply with their prescribed open-source specifications. In addition, Kubecub is also developing a distributed environment built on Kubernetes at the bottom to operate and maintain the entire community. Therefore, Kubecub is a very promising open-source community management tool.

باختصار ، تتمثل رؤية Kubecub في إنشاء مجتمع مفتوح المصدر مؤثر عالميًا في مجال السحابة الأصلية ، ليس فقط لتحسين جودة ومواصفات المشاريع مفتوحة المصدر ولكن أيضًا لجعل المشاريع مفتوحة المصدر أكثر صحة ونضجًا. في الوقت نفسه ، يوفر Kubecub نظامًا تشغيليًا فعالًا لجذب المشاركين والاحتفاظ بهم ، وبالتالي تعزيز تطوير مجتمع السحابة الأصلي. بالنسبة للمطورين الذين لديهم شغف بمجال السحابة الأصلية ، ستكون Kubecub فرصة لا تقدر بثمن للمشاركة في مجتمع المصادر المفتوحة المعياري والتشغيلي والمساهمة في تقدم مجال السحابة الأصلية.

## لماذا تنشئ Kubecub؟

Unlike other open-source communities, Kubecub is not just a product or repository of Kubecub. Its functions are far more than that. Let me explain...

**لماذا سميت Kubecub؟**

> يوفر kubecub قدرة سلاسل k8s.

أعتقد أن Kubecub يوفر لـ Kubernetes القدرة على الربط. ما هي القدرة على السلسلة؟

بينما تتطور Kubernetes بسرعة ، بتوجيه من مؤسسة CNCF ، يزدهر حقل السحابة الأصلي بأكمله ، والأدوات الموجودة في مجال السحابة الأصلية بالكامل لا تعد ولا تحصى ، مما يؤدي إلى تطوير وازدهار مجتمع المصادر المفتوحة بالكامل. Kubecub إلى الوجود.

Kubecub يشبه blockchain يسجل جميع الكتل في دفتر الأستاذ الفائق. يربط Kubecub جميع الأنظمة البيئية مفتوحة المصدر معًا لتشكيل نظام ومواصفات قابلة للإحالة والتكرار.

بما في ذلك على سبيل المثال لا الحصر:

-   التطبيقات الموزعة على أساس Kubernetes ، ودمج حلول Kubernetes الحالية.
-   تطوير وتنظيم أدوات مفتوحة المصدر.
-   تصميم الإدارة والمواصفات لجميع المشاريع مفتوحة المصدر على أساس Kubecub.

## مشاكل في مجتمع المصادر المفتوحة الحالي

نحن نعلم أن أي مشروع مفتوح المصدر عالي المستوى لا يمكنه الاستغناء عن وضع التشغيل عالي المستوى ، بما في ذلك Kubernetes. بالنسبة إلى Kubernetes ، فإن الإدارة والعمليات والتطوير ليست حصرية بشكل متبادل ، وهذا هو السبب في أن مجتمع Kubernetes لا يزال الرائد في مجتمع المصادر المفتوحة بالكامل.

However, not all projects have the cost and energy to operate and automate management, resulting in a lack of or very few mature automated and CICD and community specifications in many communities.

يمزج Kubecub بين وسائل DevOps المختلفة ، باستخدام الروبوتات والإجراءات لدمج وسائل إدارة الأتمتة وجزءًا من العمل التشغيلي للمجتمع.

## من يمكنه المشاركة في Kubecub؟

لا توجد عتبة ل Kubecub!

لا يتطلب Kubecub المال!

Kubecub ليس لديه أي قيود!

يمكنك اقتراح فكرة وتنفيذها بنفسك ، ويمكنك تنفيذها بناءً على المقترحات الموجودة في المشاريع ، كما يمكنك المشاركة في أي مستودع لاقتراح أو حل الميزات والأخطاء وما إلى ذلك.

حتى ، لا يمكنك فعل أي شيء ~ أدخل طلبات السحب للمشروع بشكل عرضي ، واطلع على مقطع الكود غير المريح ، وأدخل بعض التعليقات ~

## من أين أبدا

لدينا[هتبص://جذب.كوم/كبكب/كومنت](https://github.com/kubecub/community)المستودع ، الذي يحدد مواصفات المجتمع والقوالب المختلفة.

![yangzi](http://sm.nsddd.top/sm202306012140301.png)

**[٠٠٠٠-تيمبلاتي.مد](http://0000-template.md/)**هو نموذج. يمكننا استخدام هذا القالب وكتابة اقتراح تنسيق تخفيض السعر إلى دليل جمهورية الصين الشعبية باعتباره العلاقات العامة. هذا يعتبر علاقات عامة كاملة. ويتم التخطيط للعمل قبل البدء في المشروع.

اقرأ[دليل المساهم](https://github.com/kubecub/community/blob/main/CONTRIBUTING.md)، حيث يمكنك معرفة أفضل المعايير والممارسات للمساهمة في التعليمات البرمجية في مشروع مفتوح المصدر.

## الاتجاه المستقبلي

قوة شخص واحد محدودة ، ومن المؤكد أن الجو المفتوح المصدر في الفترة اللاحقة سيصبح أكثر ازدهارًا. المزيد والمزيد من الشركاء أو الفرق الذين يرغبون في الانضمام إلى المصادر المفتوحة حريصون على الحصول على حل موجود.

سنصر على تشغيل Kubecub ونعزز نمو وتواصل عشاق المصادر المفتوحة.

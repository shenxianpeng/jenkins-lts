---
description: 按"你从哪个版本升"来写的 Jenkins LTS 中文升级指南，附 38 个 LTS 版本的实测结果。
---

# Jenkins LTS 升级指南

每出一个 Jenkins LTS 版本，这里写一份升级指南：这个版本里跟升级有关的变化，以及**从你现在的版本升过来会怎样**。

官方升级指南讲的是"这个版本改了什么"，但同一个版本，从某些版本升只是换个 war 包，从另一些版本升却要分三步走。每份指南开头都有一张表，告诉你从你的版本升过来会怎样，数据来自对 38 个 LTS 版本的实测。

为什么要有中文版：Jenkins 官方中文站（jenkins.io/zh）从 2020 年起就没再更新，安装页还写着 Java 8 就行。

| LTS | 发布日期 | 指南 | 要点 |
| --- | --- | --- | --- |
| 2.580.x | 2026-09-30 / 2026-10-28 | [2.580](2-580.md) | 必须 Java 21 或 25；从 2.355 及更早直接升可能起不来；2.580.2 修了 15 个漏洞 |

## 这些指南怎么写的 {#how}

- 依据官方升级指南、更新日志和安全公告，AI 起草，再和原文逐条核对。
- 和官方说法不一致的地方，会单独标出来并写明依据。
- 实测数据来自 [jenkins-upgrade-check](https://github.com/keelinfra/jenkins-upgrade-check) 的[升级矩阵](https://github.com/keelinfra/jenkins-upgrade-check/tree/matrix)，每周自动跑一次。
- 发现错误，或者升级时踩了这里没写的坑，欢迎[提 issue](https://github.com/shenxianpeng/jenkins-lts/issues)。

文字内容使用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.zh-hans) 许可，和 jenkins.io 一致。

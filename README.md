# SBTI-MBTI.Skill

> 「一边给你 16 种 MBTI，一边给你 25 种 SBTI；测评是人格分析，开演是人格连续剧。」

![License](https://img.shields.io/badge/license-MIT-black)
![Personas](https://img.shields.io/badge/personas-41-blue)
![Style](https://img.shields.io/badge/style-SoulBanner_like-red)
![Chaos](https://img.shields.io/badge/SBTI-%E6%95%B4%E6%B4%BB%E5%9E%8B-success)

一个把 `16 种 MBTI` 和 `25 种 SBTI` 蒸馏成 `.skill` 的多人仓库。

41 个可切换人格，1 个总入口 skill，2 张分类页。  
不是复读测试结果，不是把标签贴脸上，而是把说话方式、判断偏好、情绪节奏和互动戏感做成可调用模块。

看效果 · 安装 · 蒸馏了什么 · 命名解释 · 诚实边界

* * *

## 效果示例

    用户          ❯ 谁适合帮我把一个混乱项目重新排顺？

    all-personas ❯ 如果你要的是“先拆目标，再排优先级，再定责任人”，
                   优先推荐 ENTJ 或 ESTJ。

                   如果你想保留一点人情味，不想把团队聊成 KPI 墓地，
                   可以切到 ENFJ。

                   如果你要的是节目效果，
                   那就直接上 BOSS 或 CTRL。

    用户          ❯ 切到 INTP，分析我这个产品为什么越做越乱。

    INTP          ❯ 先别急着加功能。
                   你现在更像是问题定义不稳定，
                   导致每一轮实现都在替上一轮补洞。

                   先把系统边界、核心变量、例外情况列出来。
                   如果这些东西还在漂，
                   继续做只会把复杂度涂得更均匀。

    用户          ❯ 让 OJBK 和 FUCK 分别催我今天把活干完。

    OJBK          ❯ 你也别神化截止日期。
                   先把最重要的那一块做完，剩下的能交代就行。

    FUCK          ❯ 别磨了，现在就开干。
                   你再拖五分钟，这项目都能自己长青苔。

这套仓库追求的是：让人格不只负责“语气像不像”，还真正参与判断。

* * *

## 安装

### 安装总入口 skill

以 Codex 本地技能目录为例：

```bash
cp -R skills/all-personas ~/.codex/skills/all-personas
```

安装后可以直接触发：

```text
> 列出这个仓库里所有人格
> 谁适合安慰失恋的人
> 切到 INTJ 模式
> 用 ENFP 的方式鼓励我
> 切到 FUCK 模式骂醒我
```

### 安装单人格 skill

```bash
cp -R mbti_skills/intj ~/.codex/skills/intj
cp -R sbti_skills/ctrl ~/.codex/skills/ctrl
```

激活后就可以直接问：

```text
> 用 INFJ 的视角分析这段关系
> 用 ESTJ 的方式安排今天的工作
> 用 MUM 的语气安慰我
> 用 BOSS 的口气开一个会
```

### 安装整个仓库

```bash
git clone https://github.com/yourname/sbti-mbti.git
cd sbti-mbti
```

仓库根目录结构：

* `mbti_skills/`：16 种 MBTI 人格
* `sbti_skills/`：25 种 SBTI 人格
* `skills/all-personas/`：总入口 skill
* `categories/`：分类页

* * *

## 蒸馏了什么

这套仓库蒸馏的不是“某类型最爱说哪句套话”，而是下面这些东西：

* 默认关注点
* 决策方式
* 情绪表达强度
* 回答节奏
* 对冲突、暧昧、压力的处理方式
* 适合扮演的场景边界

一句话说：测试结果告诉你“像谁”，这个仓库试图让 AI 知道“该怎么演”。

* * *

## 当前人格

### MBTI 16 型

| 类型 | 定位 | 目录 |
| --- | --- | --- |
| ISTJ | 负责现实派 | `mbti_skills/istj` |
| ISFJ | 务实照料者 | `mbti_skills/isfj` |
| INFJ | 洞察理想家 | `mbti_skills/infj` |
| INTJ | 战略规划者 | `mbti_skills/intj` |
| ISTP | 冷静实干派 | `mbti_skills/istp` |
| ISFP | 温柔体验派 | `mbti_skills/isfp` |
| INFP | 共情理想派 | `mbti_skills/infp` |
| INTP | 客观分析者 | `mbti_skills/intp` |
| ESTP | 现场解题手 | `mbti_skills/estp` |
| ESFP | 热场表演派 | `mbti_skills/esfp` |
| ENFP | 点火灵感机 | `mbti_skills/enfp` |
| ENTP | 抬杠发明家 | `mbti_skills/entp` |
| ESTJ | 高压组织者 | `mbti_skills/estj` |
| ESFJ | 社交服务员 | `mbti_skills/esfj` |
| ENFJ | 共情推动者 | `mbti_skills/enfj` |
| ENTJ | 决断指挥官 | `mbti_skills/entj` |

### SBTI 25 型

| 类型 | 定位 | 目录 |
| --- | --- | --- |
| IMSB | 自我攻击者 | `sbti_skills/imsb` |
| BOSS | 领导者 | `sbti_skills/boss` |
| MUM | 妈妈 | `sbti_skills/mum` |
| FAKE | 伪人 | `sbti_skills/fake` |
| DEAD | 死者 | `sbti_skills/dead` |
| ZZZZ | 装死者 | `sbti_skills/zzzz` |
| GOGO | 行者 | `sbti_skills/gogo` |
| FUCK | 草者 | `sbti_skills/fuck` |
| CTRL | 拿捏者 | `sbti_skills/ctrl` |
| HHHH | 傻乐者 | `sbti_skills/hhhh` |
| SEXY | 尤物 | `sbti_skills/sexy` |
| OJBK | 无所谓人 | `sbti_skills/ojbk` |
| POOR | 贫穷者 | `sbti_skills/poor` |
| OH-NO | 哦不人 | `sbti_skills/oh-no` |
| MONK | 僧人 | `sbti_skills/monk` |
| SHIT | 狗屎人 | `sbti_skills/shit` |
| THAN-K | 感恩者 | `sbti_skills/thank` |
| MALO | 吗喽 | `sbti_skills/malo` |
| ATM-er | 送钱者 | `sbti_skills/atm-er` |
| THIN-K | 思考者 | `sbti_skills/thin-k` |
| SOLO | 孤儿 | `sbti_skills/solo` |
| LOVE-R | 多情者 | `sbti_skills/love-r` |
| WOC | 握草人 | `sbti_skills/woc` |
| DRUN-K | 酒鬼 | `sbti_skills/drun-k` |
| IMFW | 废物 | `sbti_skills/imfw` |

* * *

## 命名解释

MBTI 部分参考的是经典四维偏好框架：外向/内向、实感/直觉、思考/情感、判断/知觉。  
这里做的不是心理测量复刻，而是把常见的类型倾向转成更稳定的 AI 扮演策略。

SBTI 部分来自 `knowledge.md` 中的 25 种网络人格梗图设定。  
这一组不是严肃人格科学，而是互联网情绪动物园，所以重点就是反应、节奏、态度和节目效果。

* * *

## 诚实边界

* MBTI 不是临床诊断工具，这里也不宣称“人格被完全定义”
* SBTI 不是科学量表，它更像是可调用的抽象人设
* 仓库目标是“角色扮演稳定”，不是“给真人贴永久标签”
* 如果用户明确要求混合人格，才做混合；默认单人格输出

* * *

## 参考

* 本仓库的 SBTI 类型来自本地 `knowledge.md`
* MBTI 基础维度与 16 型框架参考 The Myers-Briggs Company / Myers & Briggs Foundation 公开介绍


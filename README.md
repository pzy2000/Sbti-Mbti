# SBTI-MBTI.Skill

> 「MBTI 已经死了，现在是 SBTI 的时代；16 型负责分析你，25 型负责演死你。」

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

先上 SBTI。  
毕竟 MBTI 负责人格归类，SBTI 负责精神开片。

    用户          ❯ 我今天不想上班，谁来骂醒我？

    FUCK          ❯ 你再躺十分钟，工位都要继承你遗产了。
                   现在，立刻，给我把那个文件打开。
                   别等灵感，打工人最大的灵感叫“月底要发工资”。

    用户          ❯ 那谁来安慰我一下？

    MUM           ❯ 先别急，班可以上，命别拿去硬顶。
                   你先喝口水，坐稳一点，今天的事一件一件做。
                   真撑不住就先做最小那块，别把自己吓成连续剧女主。

    用户          ❯ 我刚给前任发了“在吗”，现在想撤回人生。

    OH-NO         ❯ 完了，真的完了。
                   他还没回，你们孩子跟谁姓我都替你脑补完了。
                   但先别慌，说不定他只是也在和人生搏斗。

    用户          ❯ 让 BOSS 和 MALO 分别点评我这个周报。

    BOSS          ❯ 这不叫周报，这叫一封对结果毫无贡献的散文。
                   重写。保留结论、数据、风险，别让我在废话里考古。

    MALO          ❯ 老板要的是周报，我交上去的像临终自述。
                   但没事，吗喽的尊严本来就是选填项，我这就再改。

再上 MBTI。  
SBTI 负责整活，MBTI 负责把活讲明白。

    用户          ❯ 切到 INTP，分析我这个产品为什么越做越乱。

    INTP          ❯ 先别急着加功能。
                   你现在更像是问题定义不稳定，
                   导致每一轮实现都在替上一轮补洞。

                   先把系统边界、核心变量、例外情况列出来。
                   如果这些东西还在漂，
                   继续做只会把复杂度涂得更均匀。

    用户          ❯ 谁适合帮我把一个混乱项目重新排顺？

    all-personas ❯ 如果你要的是“先拆目标，再排优先级，再定责任人”，
                   优先推荐 ENTJ 或 ESTJ。

                   如果你想保留一点人情味，不想把团队聊成 KPI 墓地，
                   可以切到 ENFJ。

                   如果你要的是节目效果，
                   那就直接上 BOSS 或 CTRL。

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

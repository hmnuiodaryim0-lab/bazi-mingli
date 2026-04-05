# bazi-mingli 八字命理技能包

基于中国古典典籍的 OpenClaw 八字分析系统。连书籍带技能一起分发，开箱即用。

## 包含内容

```
bazi-mingli/
├── skills/
│   └── bazi-mingli/
│       ├── SKILL.md              # 技能入口
│       └── references/
│           ├── book-index.md     # 典籍章节索引
│           ├── principles.md     # 干支五行十神基础
│           └── analysis-guide.md # 实战分析流程
└── books/                        # 原书籍（4本）
    ├── 渊海子平/                  # 216章
    ├── 三命通会/                 # 227章
    ├── 滴天髓/                    # 64章
    ├── 穷通宝鉴/                  # 11章
    └── 四书合用指南.md
```

## 安装

### 方式一：直接安装（推荐）

```bash
# 克隆仓库
git clone https://github.com/你的用户名/bazi-mingli.git

# 安装 skill
openclaw skills install ./bazi-mingli/skills/bazi-mingli
```

### 方式二：打包安装

```bash
openclaw skills install /path/to/bazi-mingli.skill
```

## 依赖

安装前需要先装好以下 skills：

```bash
openclaw skills install lunar-calendar   # 农历/干支计算
openclaw skills install proactive-agent   # 主动代理（可选）
```

## 使用方法

安装完成后，对我说：

- "分析一下我的八字"
- "查查八字格局"
- "大运怎么走"
- "滴天髓里怎么说的"
- "我的命局用神是什么"

我会自动调用典籍内容进行专业分析。

## 内容来源

| 典籍 | 作者/年代 | 篇幅 | 核心价值 |
|------|----------|------|---------|
| 渊海子平 | 徐子平（宋） | 216章 | 四柱体系奠基 |
| 三命通会 | 万民英（明） | 227章 | 命理方法论最全 |
| 滴天髓 | 子平（托名） | 64章 | 高层次理论 |
| 穷通宝鉴 | 调候专论 | 11章 | 用神调候核心 |

## 免责声明

本技能包仅供学习和研究使用。命理分析属于传统文化范畴，分析结果仅供参考，不代表任何确定的命运预测。命运由多因素综合决定，八字只是其中一环。

## License

MIT

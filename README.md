# AI Interview Coach - Cursor Skill

一个专为求职者设计的AI面试教练，帮助你高效准备面试。

## 功能特性

- **简历分析**: 自动读取PDF、Word、Markdown格式的简历文件
- **职位定制**: 根据指定职位生成针对性面试题
- **智能出题**: 基于简历内容或职位要求生成10道高质量面试题
- **参考答案**: 每道题附带详细参考答案和答题建议
- **练习友好**: 每道题后预留3行空白供你手写答案

## 适用场景

- 准备技术岗位面试（前端、后端、算法等）
- 准备产品/运营/管理类面试
- 自我能力评估和查漏补缺
- 模拟面试练习

## 安装使用

### 方法一：一键安装（推荐）

使用 Cursor 的 skills 安装命令：

```bash
npx skills add username/ai-interview-coach
```

### 方法二：手动安装

1. 克隆或下载本项目
2. 将整个文件夹复制到你的 Cursor skills 目录：
   ```
   # Windows
   %USERPROFILE%\.cursor\skills\ai-interview-coach\
   
   # macOS/Linux
   ~/.cursor/skills/ai-interview-coach/
   ```
3. 重启 Cursor 或刷新 skills 缓存

### 方法三：直接复制内容

直接复制 `SKILL.md` 中的内容到 Cursor 中使用。

## 使用方法

### 方式1：基于简历生成

```
请帮我准备面试，我的简历文件是：path/to/your/resume.pdf
```

### 方式2：基于职位生成

```
我想面试前端工程师职位，请帮我生成10道面试练习题
```

### 方式3：直接描述背景

```
我有3年Java开发经验，熟悉Spring Boot和MySQL，帮我生成面试题
```

## 输出示例

AI Interview Coach 会生成格式统一的 Markdown 文档：

```markdown
# 面试练习题 - Java后端工程师

> Generated on: 2026-04-14
> Source: resume.pdf

---

## 面试题目

### 第1题
请解释Spring Boot的自动配置原理，以及它是如何简化Spring应用开发的？

---

（请在此作答）



---

### 第2题
...

## 参考答案

### 第1题答案

**考察点**: Spring框架理解、自动配置机制

**参考答案**:
...

**答题建议**:
- 从@SpringBootApplication注解说起
- 解释@EnableAutoConfiguration的作用
- 说明条件化配置的原理
```

## 支持的简历格式

| 格式 | 扩展名 | 支持状态 |
|------|--------|----------|
| PDF | .pdf | 支持 |
| Word | .docx | 支持 |
| Markdown | .md, .markdown | 支持 |
| 纯文本 | .txt | 支持 |

## 面试题类型

生成的10道题目涵盖以下维度：

1. **技术知识** (2-3题): 考察核心技术栈深度
2. **项目经验** (2-3题): 基于简历项目或职位要求
3. **问题解决** (2题): 场景分析和方案设计
4. **行为面试** (2-3题): 团队合作、沟通能力等

## 项目结构

```
ai-interview-coach/
├── SKILL.md          # 核心技能定义
├── examples.md       # 使用示例
└── README.md         # 项目说明
```

## 贡献指南

欢迎提交 Issue 和 PR！

- 发现了问题？提交 [Issue](../../issues)
- 想改进功能？提交 [Pull Request](../../pulls)

## 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

---

**祝你面试顺利！**

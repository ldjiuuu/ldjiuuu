# GitHub 学习路线（求职向 · 计算机专业）

> 适合：计算机专业在读生，希望在求职时用 GitHub 展示学习过程与项目。
>
> 原则：**每完成一个阶段，就有一个"看得见"的产出**。建议每天 30–60 分钟，边学边做，不要只看不练。

## 总览

| 阶段 | 主题 | 预计时间 | 产出 |
| --- | --- | --- | --- |
| 0 | 注册与认识 GitHub | 1–2 天 | 完善的主页 + 学生包 |
| 1 | Git 版本控制 | 约 1 周 | 本地仓库 + 规范提交 |
| 2 | GitHub 核心操作 | 约 1 周 | 完成第一个 PR |
| 3 | 项目管理与协作 | 3–5 天 | 用 Issues/Projects 管理的项目 |
| 4 | GitHub Actions 自动化 | 约 1 周 | CI 自动测试 / 自动部署 |
| 5 | GitHub Pages 个人网站 | 3–5 天 | 在线简历站 / 博客 |
| 6 | 开源贡献 | 1–3 个月 | 被合并的 PR |

---

## 阶段 0：注册与认识 GitHub（1–2 天）

**任务**

- 注册账号，设置头像、个人简介，用学校邮箱（`.edu.cn`）验证身份
- 申请 **GitHub Student Developer Pack**（学生包）：免费 Copilot、云资源、域名等
- 认识核心概念：Repository（仓库）/ Star / Fork / Issue / Pull Request（PR）/ Release

**资源**

- GitHub 官方 Hello World 教程：https://docs.github.com/zh/get-started/quickstart/hello-world
- GitHub Student Developer Pack：https://education.github.com/pack

---

## 阶段 1：Git 版本控制（约 1 周）

**任务**

- 安装 Git，配置 `user.name` / `user.email`
- 掌握常用命令：`clone` / `add` / `commit` / `push` / `pull` / `status` / `log` / `diff`
- 掌握分支：`branch` / `checkout` / `merge` / `rebase`（先理解，不必精通）
- 学会写 `.gitignore` 和规范的提交信息（推荐 Conventional Commits）

**资源**

- Pro Git 中文版（免费电子书）：https://git-scm.com/book/zh/v2
- git-flight-rules（Git 出错急救手册）：https://github.com/github/git-flight-rules
- 提交信息规范：https://www.conventionalcommits.org/zh-hans/

---

## 阶段 2：GitHub 核心操作（约 1 周）

**任务**

- 配置 SSH Key，实现免密推送
- 创建仓库时写好 README、License、`.gitignore`
- 完整走一遍 PR 流程：本地建分支 → 提交 → push → GitHub 提 PR → 合并
- Watch 一个你正在用的框架或工具，每天花 5 分钟看它的 Issues 和 Release

**资源**

- first-contributions（5 分钟体验人生第一个 PR）：https://github.com/firstcontributions/first-contributions
- GitHub 官方入门文档：https://docs.github.com/zh/get-started

---

## 阶段 3：项目管理与协作（3–5 天）

**任务**

- 用 Issues 管理任务，配置 Issue 模板（Bug 报告 / 功能建议）
- 用 Projects 看板规划项目进度
- 用 Release 发布版本，写清更新日志
- 给别人的项目提一个 Issue（提问或建议），体验真实协作

**资源**

- GitHub 官方 Issues 文档：https://docs.github.com/zh/issues
- HelloGitHub（中文项目推荐，按语言分类）：https://github.com/521xueweihan/HelloGitHub

---

## 阶段 4：GitHub Actions 自动化（约 1 周）

**任务**

- 理解 workflow / job / step / 触发事件 这几个概念
- 实践 1：推送代码后自动跑测试（CI）
- 实践 2：自动部署 GitHub Pages
- 实践 3：生成主页里的贡献小蛇（本仓库已带 `.github/workflows/snake.yml`）
- 进阶：给自己的项目加一个自动发布包的工作流

**资源**

- GitHub Actions 官方文档：https://docs.github.com/zh/actions
- awesome-actions（精选 Action 清单）：https://github.com/sdras/awesome-actions

---

## 阶段 5：GitHub Pages 个人网站（3–5 天）

**任务**

- 用 Jekyll / Hugo / VuePress 搭一个简历站或博客
- 放上：个人介绍、项目、简历、联系方式
- 绑定自定义域名（学生包有免费域名额度）

**资源**

- GitHub Pages 官方文档：https://docs.github.com/zh/pages
- jekyll-now（最快上手的个人站模板）：https://github.com/barryclark/jekyll-now

---

## 阶段 6：开源贡献（长期，1–3 个月出成果）

**任务**

- 从小处入手：修文档、补注释、修拼写错误的 PR（同样算真实贡献）
- 再进阶：复现 Bug → 写测试 → 修复简单 Issue
- 在下方"优质仓库"里挑 1 个与求职方向相关的项目深入阅读源码
- 参加官方活动：开源之夏（中科院软件所）、Google Summer of Code

**资源**

- 开源之夏：https://summer-ospp.ac.cn
- Google Summer of Code：https://summerofcode.withgoogle.com

---

## 求职展示自查清单

- [ ] 主页 README 完整：有介绍、技术栈、项目、联系方式
- [ ] 置顶 2–3 个高质量项目，README 讲清"是什么 / 怎么做 / 亮点"
- [ ] 简历上放 GitHub 链接，主页内容与简历一致
- [ ] 保持每周 3 次以上提交（笔记、练习、项目都可以）
- [ ] 有至少 1 个被合并的开源 PR（文档类也算）
- [ ] 写技术博客并同步到仓库（面试加分项）

---

## 值得收藏的优质仓库

| 方向 | 仓库 | 一句话说明 |
| --- | --- | --- |
| 面试算法 | [jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university) | 系统化面试准备路线 |
| 计算机基础 | [CyC2018/CS-Notes](https://github.com/CyC2018/CS-Notes) | 中文面试知识整理 |
| 数据结构与算法 | [krahets/hello-algo](https://github.com/krahets/hello-algo) | 图解算法，入门友好 |
| 手写项目 | [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | 从零实现数据库、编译器、操作系统等 |
| 项目实战 | [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) | 按语言分类的练手项目教程 |
| 国内课程 | [ConteGrand/awesome-cs-courses](https://github.com/ConteGrand/awesome-cs-courses) | 国内高校计算机课程资源 |
| 免费书籍 | [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 免费编程书籍合集 |
| Git 急救 | [github/git-flight-rules](https://github.com/github/git-flight-rules) | Git 出错对照表 |
| 开源推荐 | [521xueweihan/HelloGitHub](https://github.com/521xueweihan/HelloGitHub) | 每月推荐有趣开源项目 |
| 刷题 | [doocs/leetcode](https://github.com/doocs/leetcode) | LeetCode 中文题解 |

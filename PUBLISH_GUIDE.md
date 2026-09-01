# 发布指南：把主页上线

## 第 1 步：创建同名仓库

1. 登录 [GitHub](https://github.com)
2. 点右上角 **+** → **New repository**
3. **Repository name** 填你的用户名（必须和用户名完全一致，例如用户名是 `zhangsan`，仓库名就是 `zhangsan`）
4. 选择 **Public**，勾选 **Add a README file**
5. 点击 **Create repository**

## 第 2 步：上传文件

把本文件夹里的内容全部放进这个仓库：

- `README.md`（主页核心内容）
- `assets/banner.svg`（顶部横幅）
- `.github/workflows/snake.yml`（贡献小蛇自动生成）
- `LEARNING_ROADMAP.md`（学习路线）
- `PUBLISH_GUIDE.md`（本指南，可留可删）

网页端最简单：仓库首页 → **Add file** → **Upload files**，把文件拖进去后 **Commit changes**。

## 第 3 步：替换占位符

全局搜索并替换：

| 占位符 | 替换为 |
| --- | --- |
| ~~`YOUR_USERNAME`~~ | 已替换为 `ldjiuuu`，无需操作 |
| `你的名字` / `Your Name` | 你的真实姓名或英文名 |
| `your-email@example.com` | 你的常用邮箱 |
| `your-blog.example.com` | 你的博客地址（没有就删掉） |
| `space.bilibili.com/你的ID` | 你的 B 站链接（没有就删掉） |
| 项目表格中的 TODO 行 | 你的真实项目 |

## 第 4 步：激活贡献小蛇

1. 仓库 → **Actions** 页面
2. 找到 `generate-snake` → 点 **Run workflow** 手动运行一次
3. 运行成功后，刷新你的个人主页即可看到小蛇
4. 之后每天会自动更新（无需手动操作）

## 第 5 步：置顶项目 & 完善简历

- 回到个人主页，在 **Pinned** 区域置顶 2–3 个最能展示能力的项目
- 简历上加上 GitHub 链接，确保主页内容和简历一致

> 💡 统计卡（Stars/语言/连击）由第三方服务生成，首次显示可能有几分钟缓存延迟，属正常现象。

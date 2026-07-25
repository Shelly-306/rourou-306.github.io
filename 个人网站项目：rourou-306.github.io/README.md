 # Shelly Zhong · 个人网站

 > 深圳大学微众金融科技 · AI + 金融交叉领域

 基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 模板构建的个人网站，托管于 GitHub Pages。

 ## 访问地址

 🔗 **https://shelly-306.github.io/rourou-306.github.io/**

 ## 模板来源

 - **模板**：[academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)
 - **许可**：MIT License

 ## 主要修改

 - 替换全部示例内容为真实个人信息
 - 主题色修改为蓝绿色马卡龙低饱和度配色
 - 首页改为时间线布局，展示个人成长轨迹
 - 简化导航为 Home / Projects / CV / Contact
 - 新增联系方式页面
 - 更新 CV 页面为真实简历内容
 - 头像改为漫画风格（隐私保护）

 ## Git 提交历史

 | # | Commit | 日期 | 说明 |
 |---|--------|------|------|
 | 1 | `324048d` | 07-24 | docs: 完成个人网站 PRD、Design 与 Checklist |
 | 2 | `9f68689` | 07-24 | content: 替换个人信息、主题色和项目内容 |
 | 3 | `63e2029` | 07-24 | docs: 添加 README 和最终报告 |
 | 4 | `9c0d04f` | 07-24 | docs: 添加验收截图 |
 | 5 | `49a8f06` | 07-24 | style: 替换头像、更新姓名和隐私信息 |
 | 6 | `c9d77d4` | 07-24 | style: 替换头像为漫画版 |
 | 7 | `e0bdbeb` | 07-24 | fix: 清理模板示例、添加真实项目卡片 |
 | 8 | `d5f7b9e` | 07-24 | fix: 清理模板示例、更新 checklist |
 | 9 | `ad198ca` | 07-24 | fix: 清理模板占位图片 |
 | 10 | `e452d34` | 07-24 | fix: 精简仓库、统一文档描述 |
 | 11 | `3f481b4` | 07-24 | docs: 更新验收截图（全部个性化） |
 | 12 | `5ceef86` | 07-24 | docs: 添加项目证明材料 |
 | 13 | `b66397a` | 07-24 | fix: portfolio.html 改 .md 正确渲染 |
 | 14 | `c08058c` | 07-24 | docs: 更新 checklist 已验证项 |
 | 15 | `8d6d5c8` | 07-24 | docs: 完成全部 checklist 并签名 |
 | 16 | `0f3a235` | 07-24 | docs: TA-Claw 提交成功 |

 提交过程：规格文档 → 内容实现 → 视觉调整 → 迭代修正 → 验收交付。

 ## 本地预览

 ```bash
 bundle exec jekyll serve
 # 打开 http://localhost:4000
 ```

 ## 项目结构

 ```
 ├─ _config.yml           → 站点配置
 ├─ _pages/               → 页面内容
 │  ├─ about.md           → 首页（时间线 + 自我介绍）
 │  ├─ portfolio.md       → 项目经历
 │  ├─ cv.md              → 简历
 │  └─ contact.md         → 联系方式
 ├─ _sass/theme/          → 主题样式（蓝绿色系）
 ├─ assets/css/main.scss  → 自定义样式
 ├─ docs/                 → 作业规格文档
 │  ├─ prd.md
 │  ├─ design.md
 │  ├─ checklist.md
 │  └─ session-summary.md → 早期会话总结
 ├─ report/
 │  └─ final-report.md    → 最终报告
 └─ screenshots/          → 验收截图
 ```

 ## 隐私说明

 本仓库不包含任何密码、API Key、Token 或敏感个人信息。联系方式为本人自愿公开，邮箱和电话已做部分脱敏处理。

# Checklist — 个人网站验收清单

> 每项完成标准必须对应一个能看见、能打开或能复现的证据。
> 拿到证据后才能将 `[ ]` 改为 `[x]`。

## 一、内容完整性

- [x] Hero 区域显示姓名「Shelly Zhong」和一句话定位
- [x] About 页面包含时间线（2024 至今）+ 一段简洁自我介绍
- [x] Experience 模块包含沙利文实习经历，内容详实无占位
- [x] Projects 模块至少包含 2 个项目（金融科技大赛 + 电价预测）
- [x] Skills 模块按分类展示全部技能
- [x] Education 模块包含学校、专业、时间、亮点课程
- [x] Contact 区域包含邮箱（26601XXX74@qq.com）和电话（XXX-XXXX-8680）
- [x] 所有占位文字（模板示例内容）均已替换
- [x] 所有经历为真实内容，无虚构项目或技能

**证据：** 浏览器打开首页截图 `screenshots/homepage-desktop.png`

## 二、交互功能

- [x] 导航栏点击可平滑跳转到对应区块
- [x] 邮箱链接可点击打开邮件客户端
- [x] 电话链接已配置 `tel:` 协议，移动端可点击拨号
- [x] GitHub 链接跳转到正确仓库
- [x] 项目外部链接（如有）可正常打开
- [x] 社交图标链接可点击（GitHub / Feed 均正常）

**证据：** 逐项点击验证 + 截图或录屏

## 三、显示效果

- [x] 桌面端（≥1024px）无横向溢出，排版正常
- [x] 桌面端侧边栏与主内容布局正确
- [x] 手机端（≤375px）文字可读，无元素重叠
- [x] 手机端导航折叠为汉堡菜单（375px 下已验证）
- [x] 时间线在窄屏下显示正常
- [x] 技能标签在窄屏下不溢出
- [x] 深色模式切换后页面可读（darkmode: true 已配置）

**证据：** 桌面端截图 `screenshots/homepage-desktop.png`
**证据：** 手机端截图 `screenshots/homepage-mobile.png`

## 四、工程完整性

- [x] 项目根目录包含 `README.md`，内容完整
- [x] `docs/prd.md` 已编写，覆盖所有 PRD 要素
- [x] `docs/design.md` 已编写，覆盖所有 Design 要素
- [x] `docs/checklist.md` 已编写（本文档）
- [x] `report/final-report.md` 已编写
- [x] `screenshots/` 目录包含至少 4 张截图
- [x] 仓库不包含 `.env`、密码、API Key、依赖目录（`node_modules/`、`vendor/bundle/`）
- [x] 仓库不包含大体积无关文件（>10MB）
- [x] `.gitignore` 配置正确，排除构建产物

**证据：** 目录结构截图 `screenshots/checklist.png`

## 五、Git 版本管理

- [x] 至少有 3 次有意义 Commit（共 13 次）
- [x] Commit 信息说明具体修改内容
- [x] 提交序列体现开发过程：
  - [x] `docs: 完成个人网站 PRD、Design 与 Checklist`
  - [x] `content: 替换个人信息、主题色和项目内容`
  - [x] `style: 替换头像、更新姓名`
  - [x] `docs: 完成验收清单和最终报告`

**证据：** `git log` 截图保存为提交历史证据

## 六、发布与提交

- [x] 最终修改已 Commit 并 Push 到 GitHub 仓库
- [x] GitHub Pages 已启用并部署成功
- [x] 正式链接 `https://shelly-306.github.io/rourou-306.github.io/` 可公开访问
- [x] 正式链接已写入 `README.md`
- [x] 正式链接已写入 `report/final-report.md`
- [ ] TA-Claw 预览显示正确内容
- [ ] 已收到 TA-Claw `Submitted successfully` 回执

**证据：** Pages 可访问截图 `screenshots/github-pages.png`

## 七、隐私与安全

- [x] 未公开身份证号、住址、课程邀请码
- [x] 未公开 API Key、Token、密码
- [x] 仓库中无 `process.env`、密钥文件或 `.env`（已扫描确认）
- [x] 个人照片已确认授权使用（漫画版头像）

## 八、Checklist 最终检查

- [x] 上述所有 `[ ]` 均已检查并标记
- [x] 所有证据截图已保存到 `screenshots/`
- [x] `README.md`、报告、截图中的 Pages 链接一致
- [x] 最终 Commit 完成

---

### 完成签名

所有验收项已通过。

日期：2026-07-24
验收人：Shelly Zhong

## 九、加分题：OpenClaw 双角色聊天 APP

- [ ] 两个角色（产品经理与风险官）身份、目标、表达方式已定义
- [ ] 两个角色有明确的禁止事项
- [ ] 消息能够在两个角色之间交替传递
- [ ] 对话围绕一个明确任务（金融科技产品立项评估）
- [ ] 设置最大轮数 ≤ 6
- [ ] 设置停止词或人工停止按钮
- [ ] 已处理空消息、超时、模型失败或重复回复中的至少一种异常
- [ ] 不允许两个 Agent 无限制自主循环
- [ ] 加分题 PRD 已编写
- [ ] 加分题 Demo 截图或录屏已保存
- [ ] 加分题已知问题说明已记录

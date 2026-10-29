# 发布步骤（GitHub Desktop，约 5 分钟）

仓库已经准备好了，路径：`D:\AI data\2026-10-26-23-35-13\qihe-repo`
已经 `git init` 并提交过（commit 872a6f3），**你只需要在 GitHub Desktop 里点几下**。

---

## 第 1 步：添加本地仓库

打开 **GitHub Desktop** →

- 菜单 `File` → `Add local repository…`
- 路径选：`D:\AI data\2026-10-26-23-35-13\qihe-repo`
- 点 `Add repository`

如果它提示「这个目录不是 git 仓库」——说明选错了层级，确认选的是 `qihe-repo` 文件夹本身。

---

## 第 2 步：发布到 GitHub

顶部会出现 `Publish repository` 按钮，点它。

填写：

| 字段 | 建议值 |
|---|---|
| Name | `qihe-match` |
| Description | 相亲资料加密成码，双向达标才交换联系方式。无服务器、无账号、离线可用。 |
| Keep this code private | **不勾选**（必须是公开仓库，Pages 才能免费开） |

点 `Publish repository`。

> 如果这一步报网络错误（`CONNECT tunnel failed` 之类），说明代理有问题。
> 试试：GitHub Desktop 菜单 `File → Options → Network`，或用浏览器登录 github.com 确认能打开。

---

## 第 3 步：开启 GitHub Pages

发布成功后，浏览器打开：

```
https://github.com/michaelmay0079/qihe-match/settings/pages
```

设置：

- **Source**：`Deploy from a branch`
- **Branch**：选 `main`，目录选 `/ (root)`
- 点 `Save`

等 1–2 分钟，页面顶部会出现地址：

```
https://michaelmay0079.github.io/qihe-match/
```

**这就是你要的体验链接。** 打开确认能正常显示首页。

---

## 第 4 步：把地址填回去

拿到地址后告诉我，或者自己改这两个地方：

1. **README.md 第 5 行**：
   ```
   🔗 **在线体验**：https://michaelmay0079.github.io/qihe-match/
   ```
   改完在 GitHub Desktop 里 commit + push。

2. **SHARE.md** 里所有 `[链接]` 替换成实际地址。

---

## 第 5 步：截图（投稿要用，1–3 张）

建议截这三屏：

| # | 截什么 | 为什么 |
|---|---|---|
| 1 | **首页「四种用法」** | 一眼看懂产品是干嘛的，这是最大特点 |
| 2 | **现实校准的分数牌**（第 5 步） | 那个「5.1 / 100 人」最有冲击力 |
| 3 | **载体图**（第 6 步，带照片水印那张） | 视觉上最直观 |

截图注意：**不要出现真实姓名、真实联系方式**（填 `anonymous@example.com` 这类假数据）。

---

## 第 6 步：投稿

投稿入口（活动页面给的）：

```
https://www.workbuddy.link/p/8QYARuAmZ9RgQty3FSzNUs
```

需要填：

- ✅ 应用界面截图 1–3 张
- ✅ 体验链接（第 3 步拿到的地址）
- ⬜ 社媒分享链接（选填，但**这是宣传的关键，强烈建议填**）

---

## 关于宣传（你说这才是重点）

活动墙上会有作品列表，但真正带来流量的是**社媒那一步**。`SHARE.md` 里写了三个版本的文案：

- **版本 A**：从「公园相亲角照片背面写着我的收入」切入，适合小红书 / 朋友圈
- **版本 B**：从技术实现切入（三段式协议、踩过的四个坑），适合知乎 / V2EX / 掘金
- **版本 C**：一句话版，适合发群里

建议发 **版本 A**——相亲这个话题在小红书和朋友圈的传播力远高于技术细节。版本 B 可以作为第二篇（知乎），覆盖另一拨人。

发的时候记得：
- 带 `#WorkBuddy #1024程序员节`
- 配 2–3 张图（首页四种用法 + 分数牌）
- **别写「算命」「预测」「缘分」这类词**（活动明令禁止，会被判违规）

---

## 时间提醒

截止：**2026-11-01 23:59**，还有约 2 天。

建议顺序：发布 → 拿链接 → 截图 → 投稿（先占住） → 发社媒 → 有余力再补二维码功能。

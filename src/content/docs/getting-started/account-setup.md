---
title: 账号配置
description: 了解如何添加和管理平台账号
order: 2
category: getting-started
---

## 账号类型

SendFox 支持两种类型的账号配置：

- **爬取账号**：用于从源社区采集内容
- **发布账号**：用于向目标社区发布内容

## 添加狐友账号

### 方式一：手机号验证码登录（推荐）

1. 进入「账号管理」页面
2. 点击「添加账号」→ 选择「狐友」平台
3. 选择「手机号登录」方式
4. 输入手机号，获取并填入验证码
5. 验证成功后账号自动绑定

<!-- 配图：手机号登录流程截图 -->
<div class="doc-image-placeholder">
  <img src="/images/docs/phone-login-placeholder.png" alt="手机号登录流程截图" />
</div>

### 方式二：Token 抓包

1. 在浏览器中登录狐友平台
2. 使用开发者工具获取 AccessToken 和 RefreshToken
3. 在 SendFox 中填入 Token 信息
4. 点击「验证」确认 Token 有效

<!-- 配图：Token 抓包操作截图 -->
<div class="doc-image-placeholder">
  <img src="/images/docs/token-capture-placeholder.png" alt="Token 抓包操作截图" />
</div>

## 账号状态说明

| 状态 | 说明 |
|------|------|
| 有效 | 账号正常，可以正常使用 |
| 已过期 | Token 已失效，需要重新绑定 |
| 无效 | 账号异常，建议检查或更换 |

## 账号安全

- Token 信息加密存储，不会明文展示
- 定期验证 Token 有效性，及时提醒续期
- 支持批量管理账号，一键检查所有账号状态

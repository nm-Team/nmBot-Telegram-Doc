---
title: nmTeam 支持
description: 在此获取 nmTeam 旗下产品的支持。
hide_docs_list: true
hide:
  - navigation
---

<div class="headerBackground">
    <div class="image"></div>
    <h1>nmTeam 支持</h1>
    <p>在此获取 nmTeam 旗下产品的支持。</p>
</div>

<center>

## 产品和服务

</center>
<div class="productsTable">
    <a class="product" href="nmbot-telegram">
        <img src="https://websiteres.nmteam.xyz/producticon/nmBot/logo@128.png" alt="nmBot logo" />
        <h3>nmBot</h3>
    </a>
    <a class="product" href="nmteam-account">
        <img src="https://websiteres.nmteam.xyz/producticon/nmTeam/logo@128.png" alt="nmTeam account logo" />
        <h3>nmTeam 账号</h3>
    </a>
    <a class="product" href="contact-us">
        <img src="https://websiteres.nmteam.xyz/producticon/nmTeam-Support/logo@512.png" alt="contact logo" />
        <h3>联系方式</h3>
    </a>
</div>

<center>

## 关于帮助文档

nmTeam 帮助文档为您提供 nmTeam 旗下产品的使用指南和支持信息。您还可以找到联系 nmTeam 支持的方式。

您可以[在此](./about.md)了解关于 nmTeam 帮助文档的信息。

### 参与改进 nmTeam 帮助文档

nmTeam 帮助文档由 nmTeam 成员和社区志愿者共同编辑。您可以在 [GitHub](https://github.com/nm-Team/Support) 上参与贡献此文档。

## nmTeam 官方网站

访问 [nmTeam 官网](https://nmteam.xyz)了解 nmTeam 的最新动态和产品信息。

</center>

<style>
    .headerBackground {
        position: relative;
        width: 120%;
        height: 300px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin: -50px -10% 20px -10%;
    }
    .headerBackground .image {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: var(--md-default-bg-color);
        background-image: url(../img/nmteam-support-background.jpg);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        z-index: -1;
    }
    body[data-md-color-media="(prefers-color-scheme: dark)"] .headerBackground .image {
        filter: brightness(0.7);
    }
    .headerBackground h1,
    .headerBackground p {
        position: relative;
        z-index: 1;
        text-align: center;
        text-shadow: 0 0 5px rgba(0, 0, 0, 0.7);
        font-weight: bold !important;
        color: #fff !important;
    }
    .productsTable {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
    }
    .product {
        width: 200px;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 1rem;
        border-radius: 0.2rem;
        color: var(--md-default-fg-color) !important;
    }
    .product:hover,
    .product:focus-visible {
        background-color: var(--md-default-fg-color--lightest);
    }
    .product img {
        width: 64px;
        height: 64px;
        border-radius: 8px;
    }
    .product h3 {
        margin-top: 1rem;
        margin-bottom: 0;
    }
</style>

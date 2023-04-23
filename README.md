<div align="center">

<img src="https://s.electerious.com/images/ackee/icon.png" title="Ackee" alt="Ackee logo" width="128">

# Ackee

![Build](https://github.com/electerious/Ackee/workflows/Build/badge.svg) [![Coverage Status](https://coveralls.io/repos/github/electerious/Ackee/badge.svg?branch=master)](https://coveralls.io/github/electerious/Ackee?branch=master) [![Mentioned in Awesome Selfhosted](https://awesome.re/mentioned-badge.svg)](https://github.com/awesome-selfhosted/awesome-selfhosted) [![Donate via PayPal](https://img.shields.io/badge/paypal-donate-009cde.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CYKBESW577YWE)

面向重视隐私的用户的自托管 Node.js 分析工具。阿基运行在您自己的服务器上,分析您网站的流量并在极简接口中提供有用的统计数据。

[🌍 Website](https://ackee.electerious.com) | [🔮 Live Demo](https://demo.ackee.electerious.com) | [🧸 GraphQL Playground](https://demo.ackee.electerious.com/api)

<br/>

![Ackee in a browser](https://s.electerious.com/images/ackee/readme.png)

</div>

## 👋 介绍

Ackee 是一款自托管的分析工具,它注重用户隐私。 我们认为您无需跟踪访客的各个方面。 Ackee 将跟踪的数据匿名化存储以避免用户可以识别出来,同时仍然提供有用的见解。 它是所有不需要像 Google Analytics 或Matomo这样全功能的营销分析平台的合适工具。

- **自托管** : Ackee 运行在您自己的服务器上并且是100% 开源
- **现代技术** : 轻量级的Node.js 和MongoDB 架构
- **美观** : 最小化和专注的界面
- **无cookies** : 没有唯一用户跟踪,因此无需cookie 信息
- **事件** : 跟踪按钮点击、资讯订阅等
- **GraphQL API** : 完全文档化的GraphQL API,可用于在Ackee 之上构建新工具

## 🚀 Get started

Get Ackee up and running…

- […with Docker Compose](docs/Get%20started.md#with-docker-compose)
- […with Docker](docs/Get%20started.md#with-docker)
- […with Helm](docs/Get%20started.md#with-helm)
- […without Docker](docs/Get%20started.md#without-docker)
- […with Netlify](docs/Get%20started.md#with-netlify)
- […with Vercel](docs/Get%20started.md#with-vercel)
- […with Heroku](docs/Get%20started.md#with-heroku)
- […with Qovery](docs/Get%20started.md#with-qovery)
- […with Render](docs/Get%20started.md#with-render)
- […with Railway](docs/Get%20started.md#with-railway)
- […with Koyeb](docs/Get%20started.md#with-koyeb)

And configure Ackee and your server correctly…

- […with environment variables](docs/Options.md)
- […with SSL and HTTPS enabled](docs/SSL%20and%20HTTPS.md)
- […with CORS headers](docs/CORS%20headers.md)

Take a look at the [FAQ](docs/FAQ.md) if you have any questions left.

## 📚 文档

文档和指南位于 [the /docs folder](docs/) 文件夹中。如果您还有任何疑问,请检查常见问题解答。

### API

Ackee features a [GraphQL API](docs/API.md) that allows you to build custom tools upon Ackee. Everything you see in the UI is made from data delivered by the API.

### Options

Ackee uses environment variables and supports [`.env` files](https://www.npmjs.com/package/dotenv) in the root of the project if you want to store all variables in one file. [Options &#187;](docs/Options.md)

## Miscellaneous

### Donate

I am working hard on continuously developing and maintaining Ackee. Please consider making a donation to keep the project going strong and me motivated.

- [Become a GitHub sponsor](https://github.com/sponsors/electerious)
- [Donate via PayPal](https://paypal.me/electerious)
- [Buy me a coffee](https://www.buymeacoffee.com/electerious)

### Articles

- [Quit Google Analytics, Self-hosted Gatsby Statistics with Ackee](https://dev.to/aleccool213/quit-google-analytics-self-hosted-gatsby-statistics-with-ackee-4011)
- [Getting Ackee up and running with Heroku 🇪🇸](https://rubenr.dev/blog/ackee-analitica-web-sencilla/)
- [Why I Self-Host My Website Analytics](https://mbuffett.com/posts/why-i-self-host-my-analytics/)

### Related

- [ackee-tracker](https://github.com/electerious/ackee-tracker) - Transfer data to Ackee
- [ackee-bitbar](https://github.com/electerious/ackee-bitbar) - Ackee stats in your macOS menu bar
- [ackee-lighthouse](https://github.com/electerious/ackee-lighthouse) - Send Lighthouse reports to Ackee
- [ackee-report](https://github.com/BetaHuhn/ackee-report) - CLI tool to generate performance reports
- [gatsby-plugin-ackee-tracker](https://github.com/Burnsy/gatsby-plugin-ackee-tracker) - Gatsby plugin for Ackee
- [Soapberry](https://wordpress.org/plugins/soapberry/) - WordPress plugin for Ackee
- [Ackee-PHP](https://github.com/BrookeDot/ackee-php) - A PHP Class for Ackee
- [use-ackee](https://github.com/electerious/use-ackee) - Use Ackee in React
- [nuxt-ackee](https://github.com/bdrtsky/nuxt-ackee) - Nuxt.js module for Ackee
- [ngx-ackee-wrapper](https://github.com/oakify/ngx-ackee-wrapper) - Angular wrapper for Ackee
- [django-ackee-middleware](https://github.com/suda/django-ackee-middleware) - Django middleware for Ackee
- [gridsome-plugin-ackee](https://github.com/DenzoNL/gridsome-plugin-ackee) - Gridsome plugin for Ackee
- [vuepress-plugin-ackee](https://github.com/spekulatius/vuepress-plugin-ackee) - VuePress plugin for Ackee
- [svelte-ackee](https://github.com/gaia-green-tech/svelte-ackee) - Svelte module for Ackee
- [ackee_dart](https://github.com/marchellodev/ackee_dart) - Ackee plugin for Dart/Flutter ([pub.dev](https://pub.dev/packages/ackee_dart))
- [ackee-tracker-consent](https://www.npmjs.com/package/ackee-tracker-consent) - A consent banner to activate detailed tracking on Ackee

### Links

- [Follow Ackee on Twitter](https://twitter.com/getackee)
- [Vote for Ackee on ProductHunt](https://www.producthunt.com/posts/ackee)

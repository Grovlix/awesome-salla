# Awesome Salla [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources, tools, libraries and learning material for building on [Salla](https://salla.dev/), the e-commerce platform for merchants in Saudi Arabia and the Gulf.

قائمة منتقاة من الموارد والأدوات والمكتبات والمحتوى التعليمي للتطوير على منصة سلة.

Maintained by [Grovlix](https://grovlix.com), a Saudi company that builds apps and themes for Salla and Zid. This list is not affiliated with or endorsed by Salla. Salla's official GitHub organization is at [SallaApp](https://github.com/SallaApp).

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Contents | المحتويات

- [Official Resources | الموارد الرسمية](#official-resources--الموارد-الرسمية)
- [SDKs & Libraries | المكتبات وأدوات التطوير](#sdks--libraries--المكتبات-وأدوات-التطوير)
- [Themes & Theme Development | القوالب وتطوير القوالب](#themes--theme-development--القوالب-وتطوير-القوالب)
- [CLI & Tooling | سطر الأوامر والأدوات](#cli--tooling--سطر-الأوامر-والأدوات)
- [Webhooks | الويب هوك](#webhooks--الويب-هوك)
- [Starter Templates & Example Apps | قوالب البداية والتطبيقات التجريبية](#starter-templates--example-apps--قوالب-البداية-والتطبيقات-التجريبية)
- [Payment & Shipping Integrations | تكامل الدفع والشحن](#payment--shipping-integrations--تكامل-الدفع-والشحن)
- [AI & Automation | الذكاء الاصطناعي والأتمتة](#ai--automation--الذكاء-الاصطناعي-والأتمتة)
- [Learning | التعلم](#learning--التعلم)
- [Community | المجتمع](#community--المجتمع)

## Official Resources | الموارد الرسمية

- [Authorization (OAuth 2.0)](https://docs.salla.dev/authorization) - Official guide to the OAuth 2.0 flows used by Salla apps.
- [Merchant API Changelog](https://docs.salla.dev/changelog) - Release notes for the Salla Merchant API.
- [Rate Limiting](https://docs.salla.dev/rate-limiting) - Official explanation of Merchant API request limits.
- [Salla Developer Docs](https://docs.salla.dev/) - Official documentation for the Merchant API, Twilight themes, App Functions, Embedded SDK and CLI.
- [Salla Developers Blog](https://salla.dev/blog/) - Announcements and technical articles from the Salla developer team.
- [Salla Developers Site](https://salla.dev/) - Home of Salla's developer program with news, blog and tutorials.
- [Salla Help Center](https://help.salla.sa/) - Merchant-facing help articles, useful for understanding store features.
- [Salla on GitHub](https://github.com/SallaApp) - Official GitHub organization with the CLI, starter kits, themes and libraries.
- [Salla Partners Portal](https://partners.salla.com/) - Portal for creating, managing and publishing apps and themes for Salla merchants.
- [Salla Status](https://status.salla.com/) - Real-time and historical status of Salla services.
- [Support and Developer Contact](https://docs.salla.dev/support) - Official support channels for app and theme developers.

## SDKs & Libraries | المكتبات وأدوات التطوير

- [App Functions](https://docs.salla.dev/app-functions/welcome) - Run TypeScript handlers inside Salla in response to store events, without hosting a server.
- [Embedded App SDK](https://docs.salla.dev/embedded-sdk/overview) - Official SDK for embedding your app inside the Salla merchant dashboard.
- [oauth2-merchant](https://github.com/SallaApp/oauth2-merchant) - Official PHP OAuth 2.0 client for authorizing apps against Salla merchant stores.
- [passport-strategy](https://github.com/SallaApp/passport-strategy) - Official Passport.js strategy for Salla OAuth 2.0 authentication.
- [Twilight JS SDK](https://docs.salla.dev/twilight-sdk/overview) - Official JavaScript SDK for cart, auth, products and events in Salla storefronts.
- [Twilight Web Components](https://docs.salla.dev/twilight-js-components/overview) - Official library of storefront web components such as product cards, sliders and modals.
- [ZATCA](https://github.com/SallaApp/ZATCA) - PHP package maintained by Salla for generating ZATCA (Fatoora) e-invoice QR codes.

## Themes & Theme Development | القوالب وتطوير القوالب

- [Create a Salla Theme](https://docs.salla.dev/twilight-engine/create-theme) - Official getting-started guide for building a theme on the Twilight engine.
- [Salla-Vite-Watcher](https://github.com/MAHMOUDGAD123/Salla-Vite-Watcher) - Vite plugin that replaces the Webpack workflow with hot reload and Twig syncing for Salla themes.
- [theme-raed](https://github.com/SallaApp/theme-raed) - Raed, Salla's official base theme and a reference for Twilight and Twig themes.
- [theme-raed-react](https://github.com/SallaApp/theme-raed-react) - Official React version of the Raed storefront theme.
- [Twilight Engine Changelog](https://docs.salla.dev/twilight-engine/changelog) - Release notes for the Twilight theme engine.
- [Twilight VS Code Extension](https://github.com/SallaApp/twilight-vscode-extension) - Official VS Code tooling for working with the Twilight theme engine.
- [twilight.json Reference](https://docs.salla.dev/twilight-engine/twilight-json) - Documentation of the theme manifest that defines settings, components and features.

## CLI & Tooling | سطر الأوامر والأدوات

- [Arabic SEO Toolkit](https://github.com/Grovlix/arabic-seo-toolkit) - Arabic-first SEO audit web app and CLI for Salla and Zid merchants, maintained by Grovlix.
- [Salla CLI](https://github.com/SallaApp/Salla-CLI) - Official command line tool for managing, previewing and publishing Salla apps and themes.
- [Salla CLI Documentation](https://docs.salla.dev/salla-cli/welcome) - Command reference for apps, themes and theme component bundles.

## Webhooks | الويب هوك

- [Conditional Webhooks](https://docs.salla.dev/conditional-webhooks) - Official guide to filtering webhook payloads with rules.
- [Salla Webhooks Guide](https://docs.salla.dev/webhooks) - Official guide to registering, securing and verifying webhooks with signature or token strategies.
- [Webhook Reference (Salla & Zid)](https://github.com/Grovlix/salla-webhook-reference) - Bilingual (English and Arabic) reference for Salla and Zid webhook events, maintained by Grovlix (work in progress).
- [webhook-actions-js](https://github.com/SallaApp/webhook-actions-js) - Official Node.js and Express.js listener for events sent by Salla webhooks.

## Starter Templates & Example Apps | قوالب البداية والتطبيقات التجريبية

- [app-functions-starterkit](https://github.com/SallaApp/app-functions-starterkit) - Official TypeScript starter for building and deploying Salla App Functions.
- [express-starter-kit](https://github.com/SallaApp/express-starter-kit) - Official Express.js starter for Salla apps with OAuth and webhooks.
- [laravel-starter-kit](https://github.com/SallaApp/laravel-starter-kit) - Official Laravel starter template for Salla apps.
- [store-events-tracker-starter-kit](https://github.com/SallaApp/store-events-tracker-starter-kit) - Official TypeScript starter for tracking storefront e-commerce events.

## Payment & Shipping Integrations | تكامل الدفع والشحن

- [AWB and Shipping Routes](https://docs.salla.dev/awb/getting-started) - Official guide to air waybill and shipping route integration.
- [Payments API](https://docs.salla.dev/payments) - Official reference for payment methods and bank details.
- [Recurring Payments](https://docs.salla.dev/recurring-payments/overview) - Official guide to building recurring billing for Salla subscriptions.
- [Shipping API](https://docs.salla.dev/ship-fulfillment-apis/getting-started) - Official guide to building shipping apps that manage and track Salla shipments.

## AI & Automation | الذكاء الاصطناعي والأتمتة

- [n8n-nodes-salla](https://github.com/aolamer/n8n-nodes-salla) - Community n8n node for Salla with OAuth 2.0 credentials.
- [n8n-nodes-sallaflow](https://github.com/MoMorgan1/n8n-nodes-sallaflow) - Community n8n node with Merchant API actions and real-time store event triggers.
- [Salla MCP Server (adshaa)](https://github.com/adshaa/salla-mcp-server) - Community MCP server for managing Salla stores, products and orders from AI assistants.
- [Salla MCP Server (theYahia)](https://github.com/theYahia/salla-mcp) - Community MCP server exposing Salla products and orders to AI agents.
- [Salla Partners Agent Kit](https://github.com/SallaApp/salla-partners-agent-kit) - Official skills that teach coding agents how to build and publish Salla apps.

## Learning | التعلم

- [Create Your First App](https://docs.salla.dev/create-app) - Official step-by-step tutorial for your first Salla app.
- [Embedded SDK Getting Started](https://docs.salla.dev/embedded-sdk/getting-started) - Official tutorial for embedding an app in the merchant dashboard.
- [Get Started](https://docs.salla.dev/get-started) - Official overview of the Salla platform for new developers.
- [Salla Developer on YouTube](https://www.youtube.com/@SallaDeveloper) - Official channel with tutorials for Salla app and theme developers.
- [Salla Developers Tutorials](https://salla.dev/tutorials/) - Official tutorials from the Salla developer site.

## Community | المجتمع

- [Salla Community](https://community.salla.sa/) - Arabic community forum where merchants share experience and ask questions.
- [Salla Developers on Telegram](https://t.me/salladev) - Official developer community on Telegram, linked from the Salla docs.
- [Salla Partners on X](https://x.com/sallapartners) - Official Salla Partners account for developer news.

## License | الرخصة

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.

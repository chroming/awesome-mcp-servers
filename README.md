# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![ไทย](https://img.shields.io/badge/Thai-Click-blue)](README-th.md)
[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點擊查看-orange)](README-zh_TW.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-青)](README-ja.md)
[![한국어](https://img.shields.io/badge/한국어-클릭-yellow)](README-ko.md)
[![Português Brasileiro](https://img.shields.io/badge/Português_Brasileiro-Clique-green)](README-pt_BR.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

A curated list of awesome Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Clients](#clients)
* [Tutorials](#tutorials)
* [Community](#community)
* [Legend](#legend)
* [Server Implementations](#server-implementations)
* [Frameworks](#frameworks)
* [Tips & Tricks](#tips-and-tricks)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

## Clients

Checkout [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/) and [glama.ai/mcp/clients](https://glama.ai/mcp/clients).

> [!TIP]
> [Glama Chat](https://glama.ai/chat) is a multi-modal AI client with MCP support & [AI gateway](https://glama.ai/gateway).

## Tutorials

* [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legend

* 🎖️ – official implementation
* programming language
  * 🐍 – Python codebase
  * 📇 – TypeScript (or JavaScript) codebase
  * 🏎️ – Go codebase
  * 🦀 – Rust codebase
  * #️⃣ - C# Codebase
  * ☕ - Java codebase
  * 🌊 – C/C++ codebase
  * 💎 - Ruby codebase

* scope
  * ☁️ - Cloud Service
  * 🏠 - Local Service
  * 📟 - Embedded Systems
* operating system
  * 🍎 – For macOS
  * 🪟 – For Windows
  * 🐧 - For Linux

> [!NOTE]
> Confused about Local 🏠 vs Cloud ☁️?
> * Use local when MCP server is talking to a locally installed software, e.g. taking control over Chrome browser.
> * Use network when MCP server is talking to remote APIs, e.g. weather API.

## Server Implementations

> [!NOTE]
> We now have a [web-based directory](https://glama.ai/mcp/servers) that is synced with the repository.

* 🔗 - [Aggregators](#aggregators)
* 🎨 - [Art & Culture](#art-and-culture)
* 📂 - [Browser Automation](#browser-automation)
* 🧬 - [Biology Medicine and Bioinformatics](#bio)
* ☁️ - [Cloud Platforms](#cloud-platforms)
* 👨‍💻 - [Code Execution](#code-execution)
* 🤖 - [Coding Agents](#coding-agents)
* 🖥️ - [Command Line](#command-line)
* 💬 - [Communication](#communication)
* 👤 - [Customer Data Platforms](#customer-data-platforms)
* 🗄️ - [Databases](#databases)
* 📊 - [Data Platforms](#data-platforms)
* 🚚 - [Delivery](#delivery)
* 🛠️ - [Developer Tools](#developer-tools)
* 🧮 - [Data Science Tools](#data-science-tools)
* 📟 - [Embedded system](#embedded-system)
* 📂 - [File Systems](#file-systems)
* 💰 - [Finance & Fintech](#finance--fintech)
* 🎮 - [Gaming](#gaming)
* 🧠 - [Knowledge & Memory](#knowledge--memory)
* 🗺️ - [Location Services](#location-services)
* 🎯 - [Marketing](#marketing)
* 📊 - [Monitoring](#monitoring)
* 🎥 - [Multimedia Process](#multimedia-process)
* 🔎 - [Search & Data Extraction](#search)
* 🔒 - [Security](#security)
* 🌐 - [Social Media](#social-media)
* 🏃 - [Sports](#sports)
* 🎧 - [Support & Service Management](#support-and-service-management)
* 🌎 - [Translation Services](#translation-services)
* 🎧 - [Text-to-Speech](#text-to-speech)
* 🚆 - [Travel & Transportation](#travel-and-transportation)
* 🔄 - [Version Control](#version-control)
* 🏢 - [Workplace & Productivity](#workplace-and-productivity)
* 🛠️ - [Other Tools and Integrations](#other-tools-and-integrations)


### 🔗 <a name="aggregators"></a>Aggregators

Servers for accessing many apps and tools through a single MCP server.

- [1mcp/agent](https://github.com/1mcp-app/agent (⭐ 44, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 🍎 🪟 🐧 - A unified Model Context Protocol server implementation that aggregates multiple MCP servers into one.
- [duaraghav8/MCPJungle](https://github.com/duaraghav8/MCPJungle (⭐ 147, ⏰ 2025-07-20)​‌‍) 🏎️ 🏠 - Self-hosted MCP Server registry for enterprise AI Agents
- [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server (⭐ 9, ⏰ 2025-07-14)​‌‍) ☁️ 📇 🍎 🪟 🐧 - A list of MCP servers so you can ask your client which servers you can use to improve your daily workflow.
- [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp (⭐ 34, ⏰ 2025-07-17)​‌‍) 📇 🏠 🪟 🍎 🐧 - A powerful image generation tool using Google's Imagen 3.0 API through MCP. Generate high-quality images from text prompts with advanced photography, artistic, and photorealistic controls.
- [julien040/anyquery](https://github.com/julien040/anyquery (⭐ 1075, ⏰ 2025-07-20)​‌‍) 🏎️ 🏠 ☁️ - Query more than 40 apps with one binary using SQL. It can also connect to your PostgreSQL, MySQL, or SQLite compatible database. Local-first and private by design.
- [metatool-ai/metatool-app](https://github.com/metatool-ai/metatool-app (⭐ 764, ⏰ 2025-07-20)​‌‍) 📇 ☁️ 🏠 🍎 🪟 🐧 - MetaMCP is the one unified middleware MCP server that manages your MCP connections with GUI.
- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb (⭐ 34637, ⏰ 2025-07-20)​‌‍) - Connect and unify data across various platforms and databases with [MindsDB as a single MCP server](https://docs.mindsdb.com/mcp/overview).
- [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol) ☁️ 🏠 - Connect with 2,500 APIs with 8,000+ prebuilt tools, and manage servers for your users, in your own app.
- [sitbon/magg](https://github.com/sitbon/magg (⭐ 24, ⏰ 2025-07-19)​‌‍) 🍎 🪟 🐧 ☁️ 🏠 🐍 - Magg: A meta-MCP server that acts as a universal hub, allowing LLMs to autonomously discover, install, and orchestrate multiple MCP servers - essentially giving AI assistants the power to extend their own capabilities on-demand.
- [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp (⭐ 50, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - OpenAI GPT image generation/editing MCP server.
- [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point (⭐ 82, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 🍎 🪟 🐧 - Turn a web service into an MCP server in one click without making any code changes.
- [TheLunarCompany/lunar#mcpx](https://github.com/TheLunarCompany/lunar/tree/main/mcpx) 📇 🏠  ☁️ 🍎 🪟 🐧 - MCPX is a production-ready, open-source gateway to manage MCP servers at scale—centralize tool discovery, access controls, call prioritization, and usage tracking to simplify agent workflows.
- [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity (⭐ 63, ⏰ 2025-07-19)​‌‍) 📇 🏠 - A proxy tool for composing multiple MCP servers into one unified endpoint. Scale your AI tools by load balancing requests across multiple MCP servers, similar to how Nginx works for web servers.
- [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy (⭐ 63, ⏰ 2025-07-19)​‌‍)  📇 🏠 - A comprehensive proxy server that combines multiple MCP servers into a single interface with extensive visibility features. It provides discovery and management of tools, prompts, resources, and templates across servers, plus a playground for debugging when building MCP servers.
- [WayStation-ai/mcp](https://github.com/waystation-ai/mcp (⭐ 24, ⏰ 2025-07-18)​‌‍) ☁️ 🍎 🪟 - Seamlessly and securely connect Claude Desktop and other MCP hosts to your favorite apps (Notion, Slack, Monday, Airtable, etc.). Takes less than 90 secs.
- [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp (⭐ 218, ⏰ 2025-07-19)​‌‍) 📇 🏠 🍎 🪟 🐧 - Turn a web API into an MCP server in 10 seconds and add it to the open source registry: https://open-mcp.org

### 🎨 <a name="art-and-culture"></a>Art & Culture

Access and explore art collections, cultural heritage, and museum databases. Enables AI models to search and analyze artistic and cultural content.

- [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library (⭐ 18, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - A MCP server for the Open Library API that enables AI assistants to search for book information.
- [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server (⭐ 427, ⏰ 2025-07-19)​‌‍) 🐍 🏠 🪟 🐧 - A local MCP server that generates animations using Manim.
- [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp (⭐ 12497, ⏰ 2025-07-20)​‌‍) 🐍 - MCP server for working with Blender
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp (⭐ 179, ⏰ 2025-07-17)​‌‍) 🐍 - Add, Analyze, Search, and Generate Video Edits from your Video Jungle Collection
- [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp (⭐ 116, ⏰ 2025-07-19)​‌‍) 📇 🏠 ☁️ 🍎 🪟 - Provides comprehensive and accurate Bazi (Chinese Astrology) charting and analysis
- [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server (⭐ 32, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - MCP server to interact with the Discogs API
- [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp (⭐ 66, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - MCP server using the Aseprite API to create pixel art
- [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server (⭐ 44, ⏰ 2025-07-08)​‌‍) 📇 ☁️ MCP server to interact with Quran.com corpus via the official REST API v4.
- [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp (⭐ 7, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - Metropolitan Museum of Art Collection API integration to search and display artworks in the collection.
- [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp (⭐ 2, ⏰ 2025-07-12)​‌‍) #️⃣ ☁️ - A 3D printer MCP server that allows for getting live printer state, webcam snapshots, and printer control.
- [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp (⭐ 68, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - A MCP Server and an extension enables natural language control of NVIDIA Isaac Sim, Lab, OpenUSD and etc.
- [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP (⭐ 15, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - MCP server for Autodesk Maya
- [r-huijts/oorlogsbronnen-mcp](https://github.com/r-huijts/oorlogsbronnen-mcp (⭐ 10, ⏰ 2025-07-15)​‌‍) 📇 ☁️ - Oorlogsbronnen (War Sources) API integration for accessing historical WWII records, photographs, and documents from the Netherlands (1940-1945)
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp (⭐ 53, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - Rijksmuseum API integration for artwork search, details, and collections
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp (⭐ 253, ⏰ 2025-07-17)​‌‍) 🐍 - MCP server integration for DaVinci Resolve providing powerful tools for video editing, color grading, media management, and project control
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp (⭐ 43, ⏰ 2025-07-05)​‌‍) 📇 ☁️ - A MCP server integrating AniList API for anime and manga information

### <a name="bio"></a>Biology, Medicine and Bioinformatics

- [genomoncology/biomcp](https://github.com/genomoncology/biomcp (⭐ 214, ⏰ 2025-07-20)​‌‍) 🐍 ☁️ - Biomedical research MCP server providing access to PubMed, ClinicalTrials.gov, and MyVariant.info.
- [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp (⭐ 16, ⏰ 2025-07-17)​‌‍) 🐍 🏠 ☁️ - MCP server to interact with the BioThings API, including genes, genetic variants, drugs, and taxonomic information.
- [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp (⭐ 4, ⏰ 2025-07-09)​‌‍) 🐍 🏠 ☁️ - MCP server providing a powerful bioinformatics toolkit for genomics queries and analysis, wrapping the popular `gget` library.
- [longevity-genie/opengenes-mcp](https://github.com/longevity-genie/opengenes-mcp (⭐ 6, ⏰ 2025-07-14)​‌‍) 🎖️ 🐍 🏠 ☁️ - MCP server for a queryable database for aging and longevity research from the OpenGenes project.
- [longevity-genie/synergy-age-mcp](https://github.com/longevity-genie/synergy-age-mcp (⭐ 4, ⏰ 2025-06-19)​‌‍) 🎖️ 🐍 🏠 ☁️ - MCP server for the SynergyAge database of synergistic and antagonistic genetic interactions in longevity.

### 📂 <a name="browser-automation"></a>Browser Automation

Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

- [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js (⭐ 108, ⏰ 2025-07-17)​‌‍) 📇 🏠 - A MCP server that supports searching for Bilibili content. Provides LangChain integration examples and test scripts.
- [agent-infra/mcp-server-browser](https://github.com/bytedance/UI-TARS-desktop/tree/main/packages/agent-infra/mcp-servers/browser) 📇 🏠 - Browser automation capabilities using Puppeteer, both support local and remote browser connection.
- [automatalabs/mcp-server-playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright (⭐ 226, ⏰ 2025-07-18)​‌‍) 🐍 - An MCP server for browser automation using Playwright
- [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp (⭐ 135, ⏰ 2025-07-19)​‌‍) 🐍 - An MCP python server using Playwright for browser automation,more suitable for llm
- [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase (⭐ 2264, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 - Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more)
- [browsermcp/mcp](https://github.com/browsermcp/mcp (⭐ 3181, ⏰ 2025-07-20)​‌‍) 📇 🏠 - Automate your local Chrome browser
- [co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server (⭐ 642, ⏰ 2025-07-20)​‌‍) 🐍 - browser-use packaged as an MCP server with SSE transport. includes a dockerfile to run chromium in docker + a vnc server.
- [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu (⭐ 176, ⏰ 2025-07-18)​‌‍) 🏎️ 🏠 🍎 🐧 🪟 - A fully functional MCP server and CLI for YouTube to automate YouTube operation
- [executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright (⭐ 4363, ⏰ 2025-07-20)​‌‍) 📇 - An MCP server using Playwright for browser automation and webscrapping
- [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp (⭐ 81, ⏰ 2025-07-19)​‌‍) 📇 🏠 - An MCP server paired with a browser extension that enables LLM clients to control the user's browser (Firefox).
- [fradser/mcp-server-apple-reminders](https://github.com/FradSer/mcp-server-apple-reminders (⭐ 93, ⏰ 2025-07-18)​‌‍) 📇 🏠 🍎 - An MCP server for interacting with Apple Reminders on macOS
- [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp (⭐ 32, ⏰ 2025-07-13)​‌‍) 📇 🏠 - Extract structured data from any website. Just prompt and get JSON.
- [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript (⭐ 267, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Fetch YouTube subtitles and transcripts for AI analysis
- [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing (⭐ 25, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - A `minimal` server/client MCP implementation using Azure OpenAI and Playwright.
- [lightpanda-io/gomcp](https://github.com/lightpanda-io/gomcp (⭐ 17, ⏰ 2025-07-04)​‌‍) 🏎 🏠/☁️ 🐧/🍎 - An MCP server in Go for Lightpanda, the ultra fast headless browser designed for web automation
- [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp (⭐ 14997, ⏰ 2025-07-20)​‌‍) - Official Microsoft Playwright MCP server, enabling LLMs to interact with web pages through structured accessibility snapshots
- [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) 📇 🏠 - Browser automation for web scraping and interaction
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit (⭐ 22, ⏰ 2025-07-12)​‌‍) 📇 🏠 - An MCP Server for interacting with manifest v2 compatible browsers.
- [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit (⭐ 22, ⏰ 2025-07-12)​‌‍) 📇 🏠 - An MCP Server that enables AI assistants to interact with your local browsers.
- [operative_sh/web-eval-agent](https://github.com/Operative-Sh/web-eval-agent (⭐ 1111, ⏰ 2025-07-19)​‌‍) 🐍 🏠 🍎 - An MCP Server that autonomously debugs web applications with browser-use browser agents
- [pskill9/web-search](https://github.com/pskill9/web-search (⭐ 231, ⏰ 2025-07-19)​‌‍) 📇 🏠 - An MCP server that enables free web searching using Google search results, with no API keys required.
- [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts (⭐ 210, ⏰ 2025-07-19)​‌‍) 📇 🏠 🍎 - An MCP Server Integration with Apple Shortcuts
- [xspadex/bilibili-mcp](https://github.com/xspadex/bilibili-mcp.git) 📇 🏠 - A FastMCP-based tool that fetches Bilibili's trending videos and exposes them via a standard MCP interface.
- [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent (⭐ 17, ⏰ 2025-07-19)​‌‍) 📇 🏠 - A Model Context Protocol (MCP) integration that provides Claude Desktop with autonomous browser automation capabilities.

### ☁️ <a name="cloud-platforms"></a>Cloud Platforms

Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

- [4everland/4everland-hosting-mcp](https://github.com/4everland/4everland-hosting-mcp (⭐ 0, ⏰ 2025-06-19)​‌‍) 🎖️ 📇 🏠 🍎 🐧 - An MCP server implementation for 4EVERLAND Hosting enabling instant deployment of AI-generated code to decentralized storage networks like Greenfield, IPFS, and Arweave.
- [aashari/mcp-server-aws-sso](https://github.com/aashari/mcp-server-aws-sso (⭐ 2, ⏰ 2025-07-04)​‌‍) 📇 ☁️ 🏠 - AWS Single Sign-On (SSO) integration enabling AI systems to securely interact with AWS resources by initiating SSO login, listing accounts/roles, and executing AWS CLI commands using temporary credentials.
- [alexbakers/mcp-ipfs](https://github.com/alexbakers/mcp-ipfs (⭐ 9, ⏰ 2025-06-09)​‌‍) 📇 ☁️ - upload and manipulation of IPFS storage
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server (⭐ 147, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - A lightweight but powerful server that enables AI assistants to execute AWS CLI commands, use Unix pipes, and apply prompt templates for common AWS tasks in a safe Docker environment with multi-architecture support
- [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server (⭐ 156, ⏰ 2025-07-19)​‌‍) 🐍 - A lightweight yet robust server that empowers AI assistants to securely execute Kubernetes CLI commands (`kubectl`, `helm`, `istioctl`, and `argocd`) using Unix pipes in a safe Docker environment with multi-architecture support.
- [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server (⭐ 62, ⏰ 2025-07-17)​‌‍) 🎖️ 🐍 ☁️ - A MCP server that enables AI assistants to operation resources on Alibaba Cloud, supporting ECS, Cloud Monitor, OOS and widely used cloud products.
- [awslabs/mcp](https://github.com/awslabs/mcp (⭐ 4822, ⏰ 2025-07-20)​‌‍) 🎖️ ☁️ - AWS MCP servers for seamless integration with AWS services and resources.
- [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server (⭐ 29, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - A VMware ESXi/vCenter management server based on MCP (Model Control Protocol), providing simple REST API interfaces for virtual machine management.
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare (⭐ 2741, ⏰ 2025-07-20)​‌‍) 🎖️ 📇 ☁️ - Integration with Cloudflare services including Workers, KV, R2, and D1
- [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops (⭐ 28, ⏰ 2025-07-13)​‌‍) 🎖️ 🏎️ ☁️ - An MCP server that allows AI agents to manage Kubernetes resources through Cyclops abstraction
- [elementfm/mcp](https://gitlab.com/elementfm/mcp) 🎖️ 🐍 📇 🏠 ☁️ - Open source podcast hosting platform
- [erikhoward/adls-mcp-server](https://github.com/erikhoward/adls-mcp-server (⭐ 4, ⏰ 2025-06-05)​‌‍) 🐍 ☁️/🏠 - MCP Server for Azure Data Lake Storage. It can perform manage containers, read/write/upload/download operations on container files and manage file metadata.
- [flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes (⭐ 890, ⏰ 2025-07-19)​‌‍) 📇 ☁️/🏠 - Typescript implementation of Kubernetes cluster operations for pods, deployments, services.
- [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server (⭐ 10, ⏰ 2025-06-22)​‌‍) 📇 ☁️/🏠 - A Model Context Protocol server for querying and analyzing Azure resources at scale using Azure Resource Graph, enabling AI assistants to explore and monitor Azure infrastructure.
- [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp (⭐ 73, ⏰ 2025-07-09)​‌‍) - A wrapper around the Azure CLI command line that allows you to talk directly to Azure
- [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp (⭐ 2, ⏰ 2025-05-07)​‌‍) 🔒 ☁️ - An MCP to give access to all Netskope Private Access components within a Netskope Private Access environments including detailed setup information and LLM examples on usage.
- [liveblocks/liveblocks-mcp-server](https://github.com/liveblocks/liveblocks-mcp-server (⭐ 9, ⏰ 2025-07-13)​‌‍) 🎖️ 📇 ☁️ - Create, modify, and delete different aspects of [Liveblocks](https://liveblocks.io) such as rooms, threads, comments, notifications, and more. Additionally, it has read access to Storage and Yjs.
- [manusa/Kubernetes MCP Server](https://github.com/manusa/kubernetes-mcp-server (⭐ 385, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 A - powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for **any** Kubernetes resource, this server provides specialized tools to interact with your cluster.
- [Nebula-Block-Data/nebulablock-mcp-server](https://github.com/Nebula-Block-Data/nebulablock-mcp-server (⭐ 0, ⏰ 2025-06-27)​‌‍) 📇 🏠 - integrates with the fastmcp library to expose the full range of NebulaBlock API functionalities as accessible tools
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp (⭐ 324, ⏰ 2025-07-19)​‌‍) - 🦀 🏠 - A Terraform MCP server allowing AI assistants to manage and operate Terraform environments, enabling reading configurations, analyzing plans, applying configurations, and managing Terraform state.
- [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp (⭐ 46, ⏰ 2025-07-20)​‌‍) 🏎️ ☁️/🏠 - A powerful MCP server that enables AI assistants to seamlessly interact with Portainer instances, providing natural language access to container management, deployment operations, and infrastructure monitoring capabilities.
- [pulumi/mcp-server](https://github.com/pulumi/mcp-server (⭐ 53, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 🏠 - MCP server for interacting with Pulumi using the Pulumi Automation API and Pulumi Cloud API. Enables MCP clients to perform Pulumi operations like retrieving package information, previewing changes, deploying updates, and retrieving stack outputs programmatically.
- [pythonanywhere/pythonanywhere-mcp-server](https://github.com/pythonanywhere/pythonanywhere-mcp-server (⭐ 5, ⏰ 2025-07-13)​‌‍) 🐍 🏠 - MCP server implementation for PythonAnywhere cloud platform.
- [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server (⭐ 21, ⏰ 2025-07-07)​‌‍) 🐍 ☁️ - A MCP built on Qiniu Cloud products, supporting access to Qiniu Cloud Storage, media processing services, etc.
- [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis (⭐ 157, ⏰ 2025-07-20)​‌‍-cloud) 📇 ☁️ - Manage your Redis Cloud resources effortlessly using natural language. Create databases, monitor subscriptions, and configure cloud deployments with simple commands.
- [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server (⭐ 47, ⏰ 2025-07-19)​‌‍) 🏎️ ☁️/🏠 - A Kubernetes Model Context Protocol (MCP) server that provides tools for interacting with Kubernetes clusters through a standardized interface, including API resource discovery, resource management, pod logs, metrics, and events.
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server (⭐ 654, ⏰ 2025-07-18)​‌‍) 🐍 ☁️/🏠 - A Model Context Protocol (MCP) server for Kubernetes that enables AI assistants like Claude, Cursor, and others to interact with Kubernetes clusters through natural language.
- [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s (⭐ 109, ⏰ 2025-07-20)​‌‍) 🏎️ ☁️/🏠 - MCP-K8S is an AI-driven Kubernetes resource management tool that allows users to operate any resources in Kubernetes clusters through natural language interaction, including native resources (like Deployment, Service) and custom resources (CRD). No need to memorize complex commands - just describe your needs, and AI will accurately execute the corresponding cluster operations, greatly enhancing the usability of Kubernetes.
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp (⭐ 42, ⏰ 2025-07-18)​‌‍) 🏎️ ☁️ - MKP is a Model Context Protocol (MCP) server for Kubernetes that allows LLM-powered applications to interact with Kubernetes clusters. It provides tools for listing and applying Kubernetes resources through the MCP protocol.
- [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp (⭐ 42, ⏰ 2025-07-18)​‌‍) 🏎️ ☁️/🏠 - Model Kontext Protocol Server for Kubernetes that allows LLM-powered applications to interact with Kubernetes clusters through native Go implementation with direct API integration and comprehensive resource management
- [StacklokLabs/ocireg-mcp](https://github.com/StacklokLabs/ocireg-mcp (⭐ 9, ⏰ 2025-07-15)​‌‍) 🏎️ ☁️ - An SSE-based MCP server that allows LLM-powered applications to interact with OCI registries. It provides tools for retrieving information about container images, listing tags, and more.
- [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go (⭐ 321, ⏰ 2025-07-16)​‌‍) 🏎️ ☁️/🏠 - Kubernetes cluster operations through MCP
- [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix (⭐ 9, ⏰ 2025-06-17)​‌‍) 🏎️ 🏠/☁️ - Go-based MCP Server for interfacing with Nutanix Prism Central resources.
- [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp (⭐ 11, ⏰ 2025-07-17)​‌‍) 🏎️ ☁️/🏠 - Get up-to-date EC2 pricing information with one call. Fast. Powered by a pre-parsed AWS pricing catalogue.
- [VmLia/books-mcp-server](https://github.com/VmLia/books-mcp-server (⭐ 4, ⏰ 2025-07-02)​‌‍) 📇 ☁️ - This is an MCP server used for querying books, and it can be applied in common MCP clients, such as Cherry Studio.
- [weibaohui/k8m](https://github.com/weibaohui/k8m (⭐ 577, ⏰ 2025-07-20)​‌‍) 🏎️ ☁️/🏠 - Provides MCP multi-cluster Kubernetes management and operations, featuring a management interface, logging, and nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
- [weibaohui/kom](https://github.com/weibaohui/kom (⭐ 120, ⏰ 2025-07-19)​‌‍) 🏎️ ☁️/🏠 - Provides MCP multi-cluster Kubernetes management and operations. It can be integrated as an SDK into your own project and includes nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye (⭐ 22, ⏰ 2025-07-19)​‌‍) 🏎️ ☁️/🏠 - MCP Server for kubernetes management, and analyze your cluster, application health

### 👨‍💻 <a name="code-execution"></a>Code Execution

Code execution servers. Allow LLMs to execute code in a secure environment, e.g. for coding agents.

- [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp (⭐ 80, ⏰ 2025-07-19)​‌‍) 📇 🏠 – A Node.js MCP server that spins up isolated Docker-based sandboxes for executing JavaScript snippets with on-the-fly npm dependency installation and clean teardown
- [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp (⭐ 111, ⏰ 2025-07-19)​‌‍) 🏎️ ☁️ - OpenAPI-MCP: Dockerized MCP Server to allow your AI agent to access any API with existing api docs.
- [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp (⭐ 10, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Give your AI assistant its own AI assistants. For example: "Could you ask openai to generate an image of a dog?"
- [hileamlakB/PRIMS](https://github.com/hileamlakB/PRIMS (⭐ 9, ⏰ 2025-07-10)​‌‍) 🐍 🏠 – A Python Runtime Interpreter MCP Server that executes user-submitted code in an isolated environment.
- [ouvreboite/openapi-to-mcp](https://github.com/ouvreboite/openapi-to-mcp (⭐ 10, ⏰ 2025-07-15)​‌‍) #️⃣ ☁️ - Lightweight MCP server to access any API using their OpenAPI specification. Supports OAuth2 and full JSON schema parameters and request body.
- [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai/tree/main/mcp-run-python) 🐍 🏠 - Run Python code in a secure sandbox via MCP tool calls
- [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js (⭐ 14, ⏰ 2025-07-07)​‌‍) 🦀 🏠 🐧 🍎 - A Javascript code execution sandbox that uses v8 to isolate code to run AI generated javascript locally without fear. Supports heap snapshotting for persistent sessions.
- [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js (⭐ 25, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 ☁️ - Execute any LLM-generated code in a secure and scalable sandbox environment and create your own MCP tools using JavaScript or Python, with full support for NPM and PyPI packages

### 🤖 <a name="coding-agents"></a>Coding Agents

Full coding agents that enable LLMs to read, edit, and execute code and solve general programming tasks completely autonomously.

- [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode (⭐ 17, ⏰ 2025-07-15)​‌‍) 📇 ☁️ - An MCP server that enables AI models to search, retrieve, and solve LeetCode problems. Supports metadata filtering, user profiles, submissions, and contest data access.
- [ezyang/codemcp](https://github.com/ezyang/codemcp (⭐ 1493, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - Coding agent with basic read, write and command line tools.
- [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent (⭐ 3, ⏰ 2025-07-03)​‌‍) 🦀 🏠 - A high-performance Rust reimplementation of WCGW for code agents, providing shell execution and advanced file management capabilities for LLMs via MCP.
- [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server (⭐ 38, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - MCP server enabling automated access to **LeetCode**'s programming problems, solutions, submissions and public data with optional authentication for user-specific features (e.g., notes), supporting both `leetcode.com` (global) and `leetcode.cn` (China) sites.
- [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server (⭐ 161, ⏰ 2025-07-18)​‌‍) 📇 🏠 - A MCP Server that allows AI such as Claude to read from the directory structure in a VS Code workspace, see problems picked up by linter(s) and the language server, read code files, and make edits.
- [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree (⭐ 25, ⏰ 2025-07-19)​‌‍) 🌊 🏠 📟 🐧 🪟 🍎 - A single-binary MCP server that converts source code into AST, regardless of language.
- [oraios/serena](https://github.com/oraios/serena (⭐ 4037, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - A fully-featured coding agent that relies on symbolic code operations by using language servers.
- [pdavis68/RepoMapper](https://github.com.mcas.ms/pdavis68/RepoMapper) 🐧 🪟 🍎 - An MCP server (and command-line tool) to provide a dynamic map of chat-related files from the repository with their function prototypes and related files in order of relevance. Based on the "Repo Map" functionality in Aider.chat
- [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP (⭐ 700, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - A framework for creating multi-agent systems using MCP for coordinated AI collaboration, featuring task management, shared context, and RAG capabilities.
- [stippi/code-assistant](https://github.com/stippi/code-assistant (⭐ 80, ⏰ 2025-07-19)​‌‍) 🦀 🏠 - Coding agent with basic list, read, replace_in_file, write, execute_command and web search tools. Supports multiple projects concurrently.
- [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server (⭐ 61, ⏰ 2025-07-18)​‌‍) 🐍 🏠 🎵 🎥 - A coding agent for Max (Max/MSP/Jitter), which is a visual programming language for music and multimedia.
- [VertexStudio/developer](https://github.com/VertexStudio/developer (⭐ 11, ⏰ 2025-07-17)​‌‍) 🦀 🏠 🍎 🪟 🐧 - Comprehensive developer tools for file editing, shell command execution, and screen capture capabilities

### 🖥️ <a name="command-line"></a>Command Line

Run commands, capture output and otherwise interact with shells and command line tools.

- [automateyournetwork/pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP (⭐ 28, ⏰ 2025-07-03)​‌‍) - Cisco pyATS server enabling structured, model-driven interaction with network devices.
- [aymericzip/intlayer](https://github.com/aymericzip/intlayer (⭐ 199, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 - A MCP Server that enhance your IDE with AI-powered assistance for Intlayer i18n / CMS tool: smart CLI access, access to the docs.
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp (⭐ 393, ⏰ 2025-07-18)​‌‍) 🖥️ 🛠️ 💬 - A Model Context Protocol server that provides access to iTerm. You can run commands and ask questions about what you see in the iTerm terminal.
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands (⭐ 172, ⏰ 2025-07-19)​‌‍) 📇 🏠 - Run any command with `run_command` and `run_script` tools.
- [maxim-saplin/mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor (⭐ 28, ⏰ 2025-07-17)​‌‍) - Safe Python interpreter based on HF Smolagents `LocalPythonExecutor`
- [misiektoja/kill-process-mcp](https://github.com/misiektoja/kill-process-mcp (⭐ 5, ⏰ 2025-07-07)​‌‍) 🐍 🏠 🍎 🪟 🐧 - List and terminate OS processes via natural language queries
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server (⭐ 130, ⏰ 2025-07-17)​‌‍) 🐍 🏠 - Command line interface with secure execution and customizable security policies
- [OthmaneBlial/term_mcp_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek (⭐ 11, ⏰ 2025-07-09)​‌‍) 🐍 🏠 - A DeepSeek MCP-like Server for Terminal
- [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell (⭐ 9, ⏰ 2025-07-09)​‌‍) - 🏎️ 🏠 🍎 🪟 🐧 Give hands to AI. MCP server to run shell commands securely, auditably, and on demand on isolated environments like docker.
- [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp (⭐ 39, ⏰ 2025-07-20)​‌‍) 📇 🏠 🐧 🪟 - MCP server exposing SSH control for Linux and Windows servers via Model Context Protocol. Securely execute remote shell commands with password or SSH key authentication.
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server (⭐ 113, ⏰ 2025-07-17)​‌‍) - A secure shell command execution server implementing the Model Context Protocol (MCP)
- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP (⭐ 3928, ⏰ 2025-07-20)​‌‍) 📇 🏠 🍎 🪟 🐧 - A swiss-army-knife that can manage/execute programs and read/write/search/edit code and text files.

### 💬 <a name="communication"></a>Communication

Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp (⭐ 33, ⏰ 2025-07-07)​‌‍) ☁️ - A Nostr MCP server that allows to interact with Nostr, enabling posting notes, and more.
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit (⭐ 188, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Interact with Twitter search and timeline
- [agentmail-toolkit/mcp](https://github.com/agentmail-to/agentmail-toolkit/tree/main/mcp) 🐍 💬 - An MCP server to create inboxes on the fly to send, receive, and take actions on email. We aren't AI agents for email, but email for AI Agents.
- [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp (⭐ 83, ⏰ 2025-07-19)​‌‍) - TSgram: Telegram + Claude with local workspace access on your phone in typescript. Read, write, and vibe code on the go!
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks (⭐ 15, ⏰ 2025-07-12)​‌‍) 📇 ☁️ - An MCP server to interface with the Google Tasks API
- [Cactusinhand/mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify (⭐ 28, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - A MCP server that send desktop notifications with sound effect when agent tasks are completed.
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp (⭐ 142, ⏰ 2025-07-19)​‌‍) 🏠 🍎 🚀 - An MCP server that securely interfaces with your iMessage database via the Model Context Protocol (MCP), allowing LLMs to query and analyze iMessage conversations. It includes robust phone number validation, attachment processing, contact management, group chat handling, and full support for sending and receiving messages.
- [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp (⭐ 138, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 - Telegram API integration for accessing user data, managing dialogs (chats, channels, groups), retrieving messages, and handling read status
- [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp (⭐ 239, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - Telegram API integration for accessing user data, managing dialogs (chats, channels, groups), retrieving messages, sending messages and handling read status.
- [Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp (⭐ 4, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - MCP server for Calcom. Manage event types, create bookings, and access Cal.com scheduling data through LLMs.
- [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) 🐍 ☁️ - An MCP server for Inbox Zero. Adds functionality on top of Gmail like finding out which emails you need to reply to or need to follow up on.
- [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp (⭐ 28, ⏰ 2025-07-13)​‌‍) 📇 ☁️ 🏠 - An ntfy MCP server for sending/fetching ntfy notifications to your self-hosted ntfy server from AI Agents 📤 (supports secure token auth & more - use with npx or docker!)
- [gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git) 🚀 ☁️ - An MCP server application that sends various types of messages to the WeCom group robot.
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server (⭐ 60, ⏰ 2025-07-19)​‌‍) 🐍 🏠 🍎 - An MCP server that provides safe access to your iMessage database through Model Context Protocol (MCP), enabling LLMs to query and analyze iMessage conversations with proper phone number validation and attachment handling
- [i-am-bee/acp-mcp](https://github.com/i-am-bee/acp-mcp (⭐ 24, ⏰ 2025-07-04)​‌‍) 🐍 💬 - An MCP server acting as an adapter into the [ACP](https://agentcommunicationprotocol.dev) ecosystem. Seamlessly exposes ACP agents to MCP clients, bridging the communication gap between the two protocols.
- [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server (⭐ 279, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server that integrates Microsoft Teams messaging (read, post, mention, list members and threads)
- [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host (⭐ 22, ⏰ 2025-07-13)​‌‍) 🐍 🏠 - A MCP server along with MCP host that provides access to Mattermost teams, channels and messages. MCP host is integrated as a bot in Mattermost with access to MCP servers that can be configured.
- [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server (⭐ 27, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - MCP server for Product Hunt. Interact with trending posts, comments, collections, users, and more.
- [keturiosakys/bluesky-context-server](https://github.com/keturiosakys/bluesky-context-server (⭐ 24, ⏰ 2025-06-21)​‌‍) 📇 ☁️ - Bluesky instance integration for querying and interaction
- [khan2a/telephony-mcp-server](https://github.com/khan2a/telephony-mcp-server (⭐ 2, ⏰ 2025-07-19)​‌‍) 🐍 💬 - MCP Telephony server for automating voice calls with Speech-to-Text and Speech Recognition to summarize call conversations. Send and receive SMS, detect voicemail, and integrate with Vonage APIs for advanced telephony workflows.
- [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server (⭐ 321, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - The most powerful MCP server for Slack Workspaces.
- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp (⭐ 4505, ⏰ 2025-07-20)​‌‍) 🐍 🏎️ - An MCP server for searching your personal WhatsApp messages, contacts and sending messages to individuals or groups
- [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server (⭐ 434, ⏰ 2025-07-20)​‌‍) 🎖 📇 ☁️ - MCP Server for Integrating LINE Official Account
- [OverQuotaAI/chatterboxio-mcp-server](https://github.com/OverQuotaAI/chatterboxio-mcp-server (⭐ 4, ⏰ 2025-07-16)​‌‍) 📇 ☁️ - MCP server implementation for ChatterBox.io, enabling AI agents to send bots to online meetings (Zoom, Google Meet) and obtain transcripts and recordings.
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp (⭐ 39, ⏰ 2025-07-15)​‌‍) - 📇 🏠 This is an MCP server for interacting with the VRChat API. You can retrieve information about friends, worlds, avatars, and more in VRChat.
- [softeria/ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server (⭐ 163, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - MCP server that connects to Microsoft Office and the whole Microsoft 365 suite using Graph API (including Outlook, mail, files, Excel, calendar)
- [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp (⭐ 30, ⏰ 2025-07-05)​‌‍) - The MCP server that keeps you informed by sending the notification on phone using ntfy
- [userad/didlogic_mcp](https://github.com/UserAd/didlogic_mcp (⭐ 1, ⏰ 2025-03-29)​‌‍) 🐍 ☁️ - An MCP server for [DIDLogic](https://didlogic.com). Adds functionality to manage SIP endpoints, numbers and destinations.
- [YCloud-Developers/ycloud-whatsapp-mcp-server](https://github.com/YCloud-Developers/ycloud-whatsapp-mcp-server (⭐ 6, ⏰ 2025-06-26)​‌‍) 📇 🏠 - MCP server for WhatsApp Business Platform by YCloud.
- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp (⭐ 70, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - An MCP server to Manage Google Tasks
- [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server (⭐ 51, ⏰ 2025-07-20)​‌‍) 📇 ☁️ 🏠 - A Model Context Protocol (MCP) server with built-in Feishu OAuth authentication, supporting remote connections and providing comprehensive Feishu document management tools including block creation, content updates, and advanced features.


### 👤 <a name="customer-data-platforms"></a>Customer Data Platforms

Provides access to customer profiles inside of customer data platforms

- [antv/mcp-server-chart](https://github.com/antvis/mcp-server-chart (⭐ 2022, ⏰ 2025-07-20)​‌‍) 🎖️ 📇 ☁️ - A Model Context Protocol server for generating visual charts using [AntV](https://github.com/antvis).
- [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid (⭐ 58, ⏰ 2025-07-19)​‌‍) 📇 🏠 - Generate [mermaid](https://mermaid.js.org/) diagram and chart with AI MCP dynamically.
- [iaptic/mcp-server-iaptic](https://github.com/iaptic/mcp-server-iaptic (⭐ 4, ⏰ 2025-05-09)​‌‍) 🎖️ 📇 ☁️ - Connect with [iaptic](https://www.iaptic.com) to ask about your Customer Purchases, Transaction data and App Revenue statistics.
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP (⭐ 126, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Connect any Open Data to any LLM with Model Context Protocol.
- [sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server (⭐ 6, ⏰ 2025-07-02)​‌‍) 📇 ☁️ - An MCP server to access and updates profiles on an Apache Unomi CDP server.
- [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird (⭐ 69, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - An MCP server to interact with a Tinybird Workspace from any MCP client.

### 🗄️ <a name="databases"></a>Databases

Secure database access with schema inspection capabilities. Enables querying and analyzing data with configurable security controls including read-only access.

- [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven (⭐ 7, ⏰ 2025-06-09)​‌‍) - 🐍 ☁️ 🎖️ -  Navigate your [Aiven projects](https://go.aiven.io/mcp-server) and interact with the PostgreSQL®, Apache Kafka®, ClickHouse® and OpenSearch® services
- [alexanderzuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server (⭐ 767, ⏰ 2025-07-19)​‌‍) - Supabase MCP Server with support for SQL query execution and database exploration tools
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server (⭐ 140, ⏰ 2025-07-19)​‌‍) ☕ 🐍 ☁️ - MCP service for Tablestore, features include adding documents, semantic search for documents based on vectors and scalars, RAG-friendly, and serverless.
- [benborla29/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql (⭐ 646, ⏰ 2025-07-19)​‌‍) ☁️ 🏠 - MySQL database integration in NodeJS with configurable access controls and schema inspection
- [bytebase/dbhub](https://github.com/bytebase/dbhub (⭐ 949, ⏰ 2025-07-19)​‌‍) 📇 🏠 – Universal database MCP server supporting mainstream databases.
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb (⭐ 20, ⏰ 2025-05-10)​‌‍) 🐍 ☁️ - TiDB database integration with schema inspection and query capabilities
- [Canner/wren-engine](https://github.com/Canner/wren-engine (⭐ 380, ⏰ 2025-07-18)​‌‍) 🐍 🦀 🏠 - The Semantic Engine for Model Context Protocol(MCP) Clients and AI Agents
- [centralmind/gateway](https://github.com/centralmind/gateway (⭐ 428, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 🍎 🪟 - MCP and MCP SSE Server that automatically generate API based on database schema and data. Supports PostgreSQL, Clickhouse, MySQL, Snowflake, BigQuery, Supabase
- [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp (⭐ 54, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ 🏠 - DICOM integration to query, read, and move medical images and reports from PACS and other DICOM compliant systems.
- [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp (⭐ 236, ⏰ 2025-07-19)​‌‍) 🎖️ 🐍 ☁️ 🏠 - Chroma MCP server to access local and cloud Chroma instances for retrieval capabilities
- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse (⭐ 453, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - ClickHouse database integration with schema inspection and query capabilities
- [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent (⭐ 82, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ - Confluent integration to interact with Confluent Kafka and Confluent Cloud REST APIs.
- [Couchbase-Ecosystem/mcp-server-couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase (⭐ 14, ⏰ 2025-07-18)​‌‍) 🎖️ 🐍 ☁️ 🏠 - Couchbase MCP server provides unfied access to both Capella cloud and self-managed clusters for document operations, SQL++ queries and natural language data analysis.
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server (⭐ 175, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - MCP Server implementation that provides Elasticsearch interaction
- [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp (⭐ 708, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - All-in-one MCP server for Postgres development and operations, with tools for performance analysis, tuning, and health checks
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino (⭐ 16, ⏰ 2025-07-04)​‌‍) 🐍 ☁️ - Trino MCP Server to query and access data from Trino Clusters.
- [davewind/mysql-mcp-server](https://github.com/dave-wind/mysql-mcp-server (⭐ 8, ⏰ 2025-07-13)​‌‍) 🏎️ 🏠 A – user-friendly read-only mysql mcp server for cursor and n8n...
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server (⭐ 704, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - MySQL database integration with configurable access controls, schema inspection, and comprehensive security guidelines
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server (⭐ 213, ⏰ 2025-07-19)​‌‍) 📇 🏠 - Airtable database integration with schema inspection, read and write capabilities
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server (⭐ 32, ⏰ 2025-07-15)​‌‍) 📇 ☁️ - Nocodb database integration, read and write capabilities
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server (⭐ 103, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server (⭐ 92, ⏰ 2025-07-19)​‌‍) 📇 🏠 - Node.js-based MySQL database integration that provides secure MySQL database operations
- [ferrants/memvid-mcp-server](https://github.com/ferrants/memvid-mcp-server (⭐ 2, ⏰ 2025-06-28)​‌‍) 🐍 🏠 - Python Streamable HTTP Server you can run locally to interact with [memvid](https://github.com/Olow304/memvid (⭐ 8209, ⏰ 2025-07-19)​‌‍) storage and semantic search.
- [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server (⭐ 19, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Fireproof ledger database with multi-user sync
- [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets (⭐ 13, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - MCP server for Google Sheets API integration with comprehensive reading, writing, formatting, and sheet management capabilities.
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server (⭐ 244, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 – A high-performance multi-database MCP server built with Golang, supporting MySQL & PostgreSQL (NoSQL coming soon). Includes built-in tools for query execution, transaction management, schema exploration, query building, and performance analysis, with seamless Cursor integration for enhanced database workflows.
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens (⭐ 175, ⏰ 2025-07-14)​‌‍) 📇 🏠 - MongoDB Lens: Full Featured MCP Server for MongoDB Databases
- [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp (⭐ 184, ⏰ 2025-07-19)​‌‍) 🔥 ⛅️ - Firebase services including Auth, Firestore and Storage.
- [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) 📇 ☁️ - Convex database integration to introspect tables, functions, and run oneoff queries ([Source](https://github.com/get-convex/convex-backend/blob/main/npm-packages/convex/src/cli/mcp.ts))
- [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox (⭐ 7280, ⏰ 2025-07-20)​‌‍) 🏎️ ☁️ - Open source MCP server specializing in easy, fast, and secure tools for Databases.
- [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server (⭐ 20, ⏰ 2025-06-27)​‌‍) 🐍 🏠 - MCP Server for querying GreptimeDB.
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server (⭐ 77, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - An MCP server that provides safe, read-only access to SQLite databases through Model Context Protocol (MCP). This server is built with the FastMCP framework, which enables LLMs to explore and query SQLite databases with built-in safety features and query validation.
- [hydrolix/mcp-hydrolix](https://github.com/hydrolix/mcp-hydrolix (⭐ 3, ⏰ 2025-06-30)​‌‍) 🎖️ 🐍 ☁️ - Hydrolix time-series datalake integration providing schema exploration and query capabilities to LLM-based workflows.
- [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server (⭐ 17, ⏰ 2025-07-14)​‌‍) 📇 ☁️ 🏠 - Run queries against InfluxDB OSS API v2.
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server (⭐ 132, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - Snowflake integration implementing read and (optional) write operations as well as insight tracking
- [yannbrrd/simple_snowflake_mcp](https://github.com/YannBrrd/simple_snowflake_mcp (⭐ 4, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ - Simple Snowflake MCP server that works behind a corporate proxy. Read and write (optional) operations
- [joshuarileydev/supabase-mcp-server](https://github.com/joshuarileydev/supabase (⭐ 42, ⏰ 2025-06-25)​‌‍) - Supabase MCP Server for managing and creating projects and organisations in Supabase
- [jovezhong/mcp-timeplus](https://github.com/jovezhong/mcp-timeplus (⭐ 9, ⏰ 2025-06-09)​‌‍) 🐍 ☁️ - MCP server for Apache Kafka and Timeplus. Able to list Kafka topics, poll Kafka messages, save Kafka data locally and query streaming data with SQL via Timeplus
- [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite (⭐ 23, ⏰ 2025-07-15)​‌‍) 📇 🏠 - Model Context Protocol (MCP) server that provides comprehensive SQLite database interaction capabilities.
- [KashiwaByte/vikingdb-mcp-server](https://github.com/KashiwaByte/vikingdb-mcp-server (⭐ 3, ⏰ 2025-06-01)​‌‍) 🐍 ☁️ - VikingDB integration with collection and index introduction, vector store and search capabilities.
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server (⭐ 253, ⏰ 2025-07-18)​‌‍) 📇 🏠 - A Model Context Protocol Server for MongoDB
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb (⭐ 139, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - DuckDB database integration with schema inspection and query capabilities
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery (⭐ 111, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - BigQuery database integration with schema inspection and query capabilities
- [memgraph/mcp-memgraph](https://github.com/memgraph/ai-toolkit/tree/main/integrations/mcp-memgraph) 🐍 🏠 - Memgraph MCP Server - includes a tool to run a query against Memgraph and a schema resource.
- [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) 📇 🏠 - PostgreSQL database integration with schema inspection and query capabilities
- [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) 🐍 🏠 - SQLite database operations with built-in analysis features
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j (⭐ 543, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - Model Context Protocol with Neo4j (Run queries, Knowledge Graph Memory, Manaage Neo4j Aura Instances)
- [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon (⭐ 371, ⏰ 2025-07-20)​‌‍) 📇 ☁️ — An MCP Server for creating and managing Postgres databases using Neon Serverless Postgres
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server (⭐ 16, ⏰ 2025-07-16)​‌‍) MCP server for Nile's Postgres platform - Manage and query Postgres databases, tenants, users, auth using LLMs
- [openlink/mcp-server-jdbc](https://github.com/OpenLinkSoftware/mcp-jdbc-server (⭐ 3, ⏰ 2025-06-27)​‌‍) 🐍 🏠 - An MCP server for generic Database Management System (DBMS) Connectivity via the Java Database Connectivity (JDBC) protocol
- [openlink/mcp-server-odbc](https://github.com/OpenLinkSoftware/mcp-odbc-server (⭐ 7, ⏰ 2025-07-11)​‌‍) 🐍 🏠 - An MCP server for generic Database Management System (DBMS) Connectivity via the Open Database Connectivity (ODBC) protocol
- [openlink/mcp-server-sqlalchemy](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server (⭐ 14, ⏰ 2025-06-09)​‌‍) 🐍 🏠 - An MCP server for generic Database Management System (DBMS) Connectivity via SQLAlchemy using Python ODBC (pyodbc)
- [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server (⭐ 44, ⏰ 2025-07-13)​‌‍) 🐍 ☁️ - Query and analyze Azure Data Explorer databases
- [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server (⭐ 156, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ -  Query and analyze Prometheus, open-source monitoring system.
- [prisma/mcp](https://github.com/prisma/mcp (⭐ 19, ⏰ 2025-07-16)​‌‍) 📇 ☁️ 🏠 - Gives LLMs the ability to manage Prisma Postgres databases (e.g. spin up new databases and run migrations or queries).
- [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant (⭐ 777, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - A Qdrant MCP server
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp (⭐ 156, ⏰ 2025-07-10)​‌‍) 📇 🏠 - MongoDB integration that enables LLMs to interact directly with databases.
- [quarkiverse/mcp-server-jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) ☕ 🏠 - Connect to any JDBC-compatible database and query, insert, update, delete, and more.
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp (⭐ 24, ⏰ 2025-07-15)​‌‍) 🐍 ☁️ - Connect AI tools directly to Airtable. Query, create, update, and delete records using natural language. Features include base management, table operations, schema manipulation, record filtering, and data migration through a standardized MCP interface.
- [redis/mcp-redis](https://github.com/redis/mcp-redis (⭐ 157, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - The Redis official MCP Server offers an interface to manage and search data in Redis.
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy (⭐ 267, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - Universal SQLAlchemy-based database integration supporting PostgreSQL, MySQL, MariaDB, SQLite, Oracle, MS SQL Server and many more databases. Features schema and relationship inspection, and large dataset analysis capabilities.
- [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript (⭐ 8, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 ☁️ - Official MCP server for the S2.dev serverless stream platform.
- [schemacrawler/SchemaCrawler-MCP-Server-Usage](https://github.com/schemacrawler/SchemaCrawler-MCP-Server-Usage (⭐ 2, ⏰ 2025-07-16)​‌‍) 🎖️ ☕ – Connect to any relational database, and be able to get valid SQL, and ask questions like what does a certain column prefix mean.
- [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone (⭐ 136, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ - Pinecone integration with vector search capabilities
- [skysqlinc/skysql-mcp](https://github.com/skysqlinc/skysql-mcp (⭐ 1, ⏰ 2025-05-15)​‌‍) 🎖️ ☁️ - Serverless MariaDB Cloud DB MCP server. Tools to launch, delete, execute SQL and work with DB level AI agents for accurate text-2-sql and conversations.
- [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp (⭐ 1808, ⏰ 2025-07-20)​‌‍) 🎖️ 📇 ☁️ - Official Supabase MCP server to connect AI assistants directly with your Supabase project and allows them to perform tasks like managing tables, fetching config, and querying data.
- [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp (⭐ 49, ⏰ 2025-07-18)​‌‍) 🐍 🏠 Universal database MCP server supporting multiple database types including PostgreSQL, Redshift, CockroachDB, MySQL, RDS MySQL, Microsoft SQL Server, BigQuery, Oracle DB, and SQLite.
- [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server (⭐ 4, ⏰ 2025-07-13)​‌‍) 🐍 ☁️ - TDolphinDB database integration with schema inspection and query capabilities
- [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino (⭐ 42, ⏰ 2025-07-17)​‌‍) 🏎️ ☁️ - A Go implementation of a Model Context Protocol (MCP) server for Trino
- [VictoriaMetrics-Community/mcp-victorialogs](https://github.com/VictoriaMetrics-Community/mcp-victorialogs (⭐ 14, ⏰ 2025-07-16)​‌‍) 🎖️ 🏎️ 🏠 - Provides comprehensive integration with your [VictoriaLogs instance APIs](https://docs.victoriametrics.com/victorialogs/querying/#http-api) and [documentation](https://docs.victoriametrics.com/victorialogs/) for working with logs, investigating and debugging tasks related to your VictoriaLogs instances.
- [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate (⭐ 136, ⏰ 2025-07-19)​‌‍) 🐍 📇 ☁️ - An MCP Server to connect to your Weaviate collections as a knowledge base as well as using Weaviate as a chat memory store.
- [wenb1n-dev/mysql_mcp_server_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro (⭐ 226, ⏰ 2025-07-18)​‌‍)  🐍 🏠 - Supports SSE, STDIO; not only limited to MySQL's CRUD functionality; also includes database exception analysis capabilities; controls database permissions based on roles; and makes it easy for developers to extend tools with customization
- [xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql (⭐ 12, ⏰ 2025-07-08)​‌‍) 📇 🏠 ☁️ - Production-ready MCP server for libSQL databases with comprehensive security and management tools.
- [XGenerationLab/xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server (⭐ 184, ⏰ 2025-07-17)​‌‍) 📇 ☁️ — An MCP server that supports fetching data from a database using natural language queries, powered by XiyanSQL as the text-to-SQL LLM.
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets (⭐ 282, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - A Model Context Protocol server for interacting with Google Sheets. This server provides tools to create, read, update, and manage spreadsheets through the Google Sheets API.
- [ydb/ydb-mcp](https://github.com/ydb-platform/ydb-mcp (⭐ 21, ⏰ 2025-07-04)​‌‍) 🎖️ 🐍 ☁️ - MCP server for interacting with [YDB](https://ydb.tech) databases
- [yincongcyincong/VictoriaMetrics-mcp-server](https://github.com/yincongcyincong/VictoriaMetrics-mcp-server (⭐ 6, ⏰ 2025-07-04)​‌‍) 🐍 🏠 - An MCP server for interacting with VictoriaMetrics database.
- [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql (⭐ 38, ⏰ 2025-07-18)​‌‍) 🏎️ 🏠 – Easy to use, zero dependency MySQL MCP server built with Golang with configurable readonly mode and schema inspection.
- [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus (⭐ 158, ⏰ 2025-07-14)​‌‍) 🐍 🏠 ☁️ - MCP Server for Milvus / Zilliz, making it possible to interact with your database.

### 📊 <a name="data-platforms"></a>Data Platforms

Data Platforms for data integration, transformation and pipeline orchestration.

- [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp (⭐ 17, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ 🏠 🍎 🪟 🐧 - Comprehensive Kafka Schema Registry MCP server with 48 tools for multi-registry management, schema migration, and enterprise features.
- [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp (⭐ 311, ⏰ 2025-07-19)​‌‍) 🎖️ 🐍 🏠 ☁️ - Official MCP server for [dbt (data build tool)](https://www.getdbt.com/product/what-is-dbt) providing integration with dbt Core/Cloud CLI, project metadata discovery, model information, and semantic layer querying capabilities.
- [flowcore/mcp-flowcore-platform](https://github.com/flowcore-io/mcp-flowcore-platform (⭐ 5, ⏰ 2025-07-07)​‌‍) 🎖️ 📇 ☁️ 🏠 - Interact with Flowcore to perform actions, ingest data, and analyse, cross reference and utilise any data in your data cores, or in public data cores; all with human language.
- [JordiNei/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server (⭐ 36, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - Connect to Databricks API, allowing LLMs to run SQL queries, list jobs, and get job status.
- [jwaxman19/qlik-mcp](https://github.com/jwaxman19/qlik-mcp (⭐ 4, ⏰ 2025-07-08)​‌‍) 📇 ☁️ - MCP Server for Qlik Cloud API that enables querying applications, sheets, and extracting data from visualizations with comprehensive authentication and rate limiting support.
- [keboola/keboola-mcp-server](https://github.com/keboola/keboola-mcp-server (⭐ 67, ⏰ 2025-07-18)​‌‍) 🐍 - interact with Keboola Connection Data Platform. This server provides tools for listing and accessing data from Keboola Storage API.
- [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp (⭐ 12, ⏰ 2025-07-17)​‌‍) 🐍 🏠 - MCP server for dbt-core (OSS) users as the official dbt MCP only supports dbt Cloud. Supports project metadata, model and column-level lineage and dbt documentation.
- [yashshingvi/databricks-genie-MCP](https://github.com/yashshingvi/databricks-genie-MCP (⭐ 7, ⏰ 2025-07-04)​‌‍) 🐍 ☁️ - A server that connects to the Databricks Genie API, allowing LLMs to ask natural language questions, run SQL queries, and interact with Databricks conversational agents.


### 💻 <a name="developer-tools"></a>Developer Tools

Tools and integrations that enhance the development workflow and environment management.

- [21st-dev/Magic-MCP](https://github.com/21st-dev/magic-mcp (⭐ 3019, ⏰ 2025-07-20)​‌‍) - Create crafted UI components inspired by the best 21st.dev design engineers.
- [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket (⭐ 49, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Atlassian Bitbucket Cloud integration. Enables AI systems to interact with repositories, pull requests, workspaces, and code in real time.
- [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence (⭐ 23, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - Atlassian Confluence Cloud integration. Enables AI systems to interact with Confluence spaces, pages, and content with automatic ADF to Markdown conversion.
- [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira (⭐ 15, ⏰ 2025-07-15)​‌‍) 📇 ☁️ - Atlassian Jira Cloud integration. Enables AI systems to interact with Jira projects, issues, comments, and related development information in real time.
- [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP (⭐ 192, ⏰ 2025-07-19)​‌‍) 🐍 📇 🦀 - Analyzes your codebase identifying important files based on dependency relationships. Generates diagrams and importance scores, helping AI assistants understand the codebase.
- [akramIOT/MCP_AI_SOC_Sher](https://github.com/akramIOT/MCP_AI_SOC_Sher (⭐ 0, ⏰ 2025-04-30)​‌‍)  🐍 ☁️ 📇 - MCP Server to do dynamic AI SOC Security Threat analysis for a  Text2SQL  AI Agent.
- [alimo7amed93/webhook-tester-mcp](https://github.com/alimo7amed93/webhook-tester-mcp (⭐ 2, ⏰ 2025-07-16)​‌‍)  🐍 ☁️ – A FastMCP-based server for interacting with webhook-test.com. Enables users to create, retrieve, and delete webhooks locally using Claude.
- [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp (⭐ 9, ⏰ 2025-07-04)​‌‍) 📇 🏠 🍎 A MCP server implementation for iOS Simulator control.
- [api7/apisix-mcp](https://github.com/api7/apisix-mcp (⭐ 25, ⏰ 2025-06-20)​‌‍) 🎖️ 📇 🏠 MCP Server that support for querying and managing all resource in [Apache APISIX](https://github.com/apache/apisix (⭐ 15378, ⏰ 2025-07-20)​‌‍).
- [ArchAI-Labs/fastmcp-sonarqube-metrics](https://github.com/ArchAI-Labs/fastmcp-sonarqube-metrics (⭐ 8, ⏰ 2025-07-03)​‌‍) 🐍 🏠 🪟 🐧 🍎 -  A Model Context Protocol (MCP) server that provides a set of tools for retrieving information about SonarQube projects like metrics (actual and historical), issues, health status.
- [artmann/package-registry-mcp](https://github.com/artmann/package-registry-mcp (⭐ 10, ⏰ 2025-07-19)​‌‍) 🏠 📇 🍎 🪟 🐧 - MCP server for searching and getting up-to-date information about NPM, Cargo, PyPi, and NuGet packages.
- [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link (⭐ 493, ⏰ 2025-07-18)​‌‍) 🏎️ 🏠 - Seamlessly Integrate Any API with AI Agents (with OpenAPI Schema)
- [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner (⭐ 10, ⏰ 2025-07-09)​‌‍) 📇 🏠 - An MCP server for running code locally via Docker and supporting multiple programming languages.
- [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp (⭐ 38, ⏰ 2025-07-14)​‌‍) 📇 🏠 - Analyze React code locally, generate docs / llm.txt for whole project at once
- [bucketco/bucket-javascript-sdk#cli](https://github.com/bucketco/bucket-javascript-sdk/tree/main/packages/cli#model-context-protocol) 🎖️ 📇 ☁️ - Flag features directly from chat in your IDE with [Bucket](https://bucket.co).
- [Chunkydotdev/bldbl-mcp](https://github.com/chunkydotdev/bldbl-mcp (⭐ 1, ⏰ 2025-07-03)​‌‍) 📇 ☁️ 🍎 🪟 🐧 - Official MCP server for Buildable AI-powered development platform [bldbl.dev](https://bldbl.dev). Enables AI assistants to manage tasks, track progress, get project context, and collaborate with humans on software projects.
- [CircleCI/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci (⭐ 58, ⏰ 2025-07-18)​‌‍) 📇 ☁️ Enable AI Agents to fix build failures from CircleCI.
- [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager (⭐ 1337, ⏰ 2025-07-20)​‌‍) 📇 ☁️ 🏠 – A programming-focused task management system that boosts coding agents like Cursor AI with advanced task memory, self-reflection, and dependency management. [ShrimpTaskManager](https://cjo4m06.github.io/mcp-shrimp-task-manager)
- [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp (⭐ 38, ⏰ 2025-07-19)​‌‍) 🏎️ ☁️ 📟 🪟 🐧 🍎 - A zero-configuration Go library to automatically expose existing Gin web framework APIs as MCP tools.
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker (⭐ 540, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - Integrate with Docker to manage containers, images, volumes, and networks.
- [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server (⭐ 20, ⏰ 2025-07-18)​‌‍) 🎖️ 🐍 ☁️ 🍎 🪟 🐧 - Official MCP server for CodeLogic, providing access to code dependency analytics, architectural risk analysis, and impact assessment tools.
- [Comet-ML/Opik-MCP](https://github.com/comet-ml/opik-mcp (⭐ 136, ⏰ 2025-07-17)​‌‍) 🎖️ 📇 ☁️ 🏠 - Use natural language to explore LLM observability, traces, and monitoring data captured by Opik.
- [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server (⭐ 13, ⏰ 2025-07-17)​‌‍) ☕ - Helping Your AI Agent Identify Hotspots for Refactoring; Help AI Understand How to 'Make Code Better'
- [currents-dev/currents-mcp](https://github.com/currents-dev/currents-mcp (⭐ 6, ⏰ 2025-07-15)​‌‍) 🎖️ 📇 ☁️ Enable AI Agents to fix Playwright test failures reported to [Currents](https://currents.dev).
- [davidlin2k/pox-mcp-server](https://github.com/davidlin2k/pox-mcp-server (⭐ 1, ⏰ 2025-03-24)​‌‍) 🐍 🏠 - MCP server for the POX SDN controller to provides network control and management capabilities.
- [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server (⭐ 114, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Interact with [Postman API](https://www.postman.com/postman/postman-public-workspace/)
- [docker/hub-mcp](https://github.com/docker/hub-mcp (⭐ 23, ⏰ 2025-07-17)​‌‍) 🎖️ 📇 ☁️ 🏠 - Official MCP server to interact with Docker Hub, providing access to repositories, hub search and Docker Hardened Images
- [flipt-io/mcp-server-flipt](https://github.com/flipt-io/mcp-server-flipt (⭐ 2, ⏰ 2025-06-05)​‌‍) 📇 🏠 - Enable AI assistants to interact with your feature flags in [Flipt](https://flipt.io).
- [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor (⭐ 11, ⏰ 2025-07-20)​‌‍) 📇 🏠 - Extracts component information from Storybook design systems. Provides HTML, styles, props, dependencies, theme tokens and component metadata for AI-powered design system analysis.
- [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli (⭐ 244, ⏰ 2025-07-19)​‌‍) 🎖️ 🏎️ 🏠 ☁️ 🍎 🪟 🐧 - A CLI for interacting with GitKraken APIs. Includes an MCP server via `gk mcp` that not only wraps GitKraken APIs, but also Jira, GitHub, GitLab, and more. Works with local tools and remote services.
- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP (⭐ 9248, ⏰ 2025-07-20)​‌‍) 📇 🏠 - Provide coding agents direct access to Figma data to help them one-shot design implementation.
- [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp (⭐ 9, ⏰ 2025-07-03)​‌‍) 🎖️ 📇 ☁️ - Integrates, discovers, manages, and codifies cloud resources with [Firefly](https://firefly.ai).
- [gorosun/unified-diff-mcp](https://github.com/gorosun/unified-diff-mcp (⭐ 3, ⏰ 2025-06-26)​‌‍) 📇 🏠 - Generate and visualize unified diff comparisons with beautiful HTML/PNG output, supporting side-by-side and line-by-line views for filesystem dry-run integration
- [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server (⭐ 140, ⏰ 2025-07-19)​‌‍) 🦀 🏠 - Provides up-to-date documentation context for a specific Rust crate to LLMs via an MCP tool, using semantic search (embeddings) and LLM summarization.
- [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server (⭐ 1680, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - An Excel manipulation server providing workbook creation, data operations, formatting, and advanced features (charts, pivot tables, formulae).
- [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server (⭐ 19, ⏰ 2025-06-24)​‌‍) 🐍 🏠 - MCP server that provides comprehensive tools for managing [Higress](https://github.com/alibaba/higress (⭐ 5927, ⏰ 2025-07-19)​‌‍) gateway configurations and operations.
- [hijaz/postmancer](https://github.com/hijaz/postmancer (⭐ 19, ⏰ 2025-07-13)​‌‍) 📇 🏠 - A MCP server for replacing Rest Clients like Postman/Insomnia, by allowing your LLM to maintain and use api collections.
- [hloiseaufcms/mcp-gopls](https://github.com/hloiseaufcms/mcp-gopls (⭐ 34, ⏰ 2025-07-18)​‌‍) 🏎️ 🏠 - A MCP server for interacting with [Go's Language Server Protocol (gopls)](https://github.com/golang/tools/tree/master/gopls) and benefit from advanced Go code analysis features.
- [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp (⭐ 24, ⏰ 2025-07-17)​‌‍) 📇 🏠 - A MCP server for interacting with [Bruno API Client](https://www.usebruno.com/).
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind (⭐ 192, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - Control Android devices with AI through MCP, enabling device control, debugging, system analysis, and UI automation with a comprehensive security framework.
- [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp (⭐ 13, ⏰ 2025-06-21)​‌‍) 🎖️ 📇 ☁️ - Integration with [QA Sphere](https://qasphere.com/) test management system, enabling LLMs to discover, summarize, and interact with test cases directly from AI-powered IDEs
- [idosal/git-mcp](https://github.com/idosal/git-mcp (⭐ 3491, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - [gitmcp.io](https://gitmcp.io/) is a generic remote MCP server to connect to ANY [GitHub](https://www.github.com) repository or project for documentation
- [IlyaGulya/gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server (⭐ 26, ⏰ 2025-07-18)​‌‍) 🏠 - Gradle integration using the Gradle Tooling API to inspect projects, execute tasks, and run tests with per-test result reporting
- [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb (⭐ 207, ⏰ 2025-07-17)​‌‍) 📇 🏠 🍎 - A Model Context Protocol (MCP) server that enables LLMs to interact with iOS simulators (iPhone, iPad, etc.) through natural language commands.
- [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression (⭐ 22, ⏰ 2025-06-30)​‌‍) 🐍 🏠 - MCP server for local compression of various image formats.
- [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp (⭐ 763, ⏰ 2025-07-20)​‌‍) 📇 🏠 🍎 - A Model Context Protocol (MCP) server for interacting with iOS simulators. This server allows you to interact with iOS simulators by getting information about them, controlling UI interactions, and inspecting UI elements.
- [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server (⭐ 696, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 - MCP Language Server helps MCP enabled clients navigate codebases more easily by giving them access to semantic tools like get definition, references, rename, and diagnostics.
- [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp (⭐ 22, ⏰ 2025-07-08)​‌‍) 📇 🏠 - A Model Context Protocol (MCP) server that provides AI-powered search and querying capabilities for the Vercel AI SDK documentation.
- [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer (⭐ 22, ⏰ 2025-07-18)​‌‍) 🐍 - MCP server that provides SQL analysis, linting, and dialect conversion using [SQLGlot](https://github.com/tobymao/sqlglot (⭐ 8015, ⏰ 2025-07-19)​‌‍)
- [janreges/ai-distiller-mcp](https://github.com/janreges/ai-distiller (⭐ 52, ⏰ 2025-07-18)​‌‍) 🏎️ 🏠 - Extracts essential code structure from large codebases into AI-digestible format, helping AI agents write code that correctly uses existing APIs on the first attempt.
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you (⭐ 383, ⏰ 2025-07-19)​‌‍) 📇 🏠 - An MCP Server and VS Code Extension which enables (language agnostic) automatic debugging via breakpoints and expression evaluation.
- [jetbrains/mcpProxy](https://github.com/JetBrains/mcpProxy (⭐ 859, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 🏠 - Connect to JetBrains IDE
- [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI (⭐ 18, ⏰ 2025-07-19)​‌‍) 📇 🏠 🍎 - A personal MCP (Model Context Protocol) server for securely storing and accessing API keys across projects using the macOS Keychain.
- [jordandalton/restcsv-mcp-server](https://github.com/JordanDalton/RestCsvMcpServer (⭐ 6, ⏰ 2025-05-27)​‌‍) 📇 ☁️ - An MCP server for CSV files.
- [joshuarileydev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server (⭐ 79, ⏰ 2025-07-19)​‌‍) 📇 🏠 - An MCP server to communicate with the App Store Connect API for iOS Developers
- [joshuarileydev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server (⭐ 46, ⏰ 2025-07-14)​‌‍) 📇 🏠 - An MCP server to control iOS Simulators
- [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server (⭐ 287, ⏰ 2025-07-20)​‌‍) 📇 🏠 - MCP server that gives AI assistants seamless access to shadcn/ui v4 components, blocks, demos, and metadata.
- [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server (⭐ 12, ⏰ 2025-07-17)​‌‍) 🎖️ 📇 ☁️ - The Globalping MCP server provides users and LLMs access to run network tools like ping, traceroute, mtr, HTTP and DNS resolve from thousands of locations around the world.
- [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer (⭐ 26, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 - Token-efficient access to OpenAPI/Swagger specs via MCP Resources.
- [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse (⭐ 67, ⏰ 2025-07-18)​‌‍) 📇 🏠 🛠️ - A middleware server that enables multiple isolated instances of the same MCP servers to coexist independently with unique namespaces and configurations.
- [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse (⭐ 112, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - MCP server to access and manage LLM application prompts created with [Langfuse]([https://langfuse.com/](https://langfuse.com/docs/prompts/get-started)) Prompt Management.
- [lpigeon/ros-mcp-server](https://github.com/lpigeon/ros-mcp-server (⭐ 139, ⏰ 2025-07-19)​‌‍) 🐍 🏠 🍎 🪟 🐧 - The ROS MCP Server supports robot control by converting user-issued natural language commands into ROS or ROS2 control commands.
- [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server (⭐ 34, ⏰ 2025-07-18)​‌‍) 🐍 🏠 🐧 - The Unitree Go2 MCP Server is a server built on the MCP that enables users to control the Unitree Go2 robot using natural language commands interpreted by a LLM.
- [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp (⭐ 1430, ⏰ 2025-07-20)​‌‍) 📇 🏠 🐧 🍎 - MCP Server for Android/iOS application and device automation, development and app scraping. Simulator/Emulator/Physical devices like iPhone, Google Pixel, Samsung supported.
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp (⭐ 39, ⏰ 2025-07-15)​‌‍) 🐍 🏠 - Simple MCP Server to enable a human-in-the-loop workflow in tools like Cline and Cursor.
- [narumiruna/gitingest-mcp](https://github.com/narumiruna/gitingest-mcp (⭐ 3, ⏰ 2025-07-11)​‌‍) 🐍 🏠 - A MCP server that uses [gitingest](https://github.com/cyclotruc/gitingest (⭐ 11030, ⏰ 2025-07-20)​‌‍) to convert any Git repository into a simple text digest of its codebase.
- [neilberkman/editorconfig_mcp](https://github.com/neilberkman/editorconfig_mcp (⭐ 0, ⏰ 2025-06-08)​‌‍) 📇 🏠 - Formats files using `.editorconfig` rules, acting as a proactive formatting gatekeeper to ensure AI-generated code adheres to project-specific formatting standards from the start.
- [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp (⭐ 18, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - lets your preferred AI agent create & run fully managed [Octomind](https://www.octomind.dev/) end-to-end tests from your codebase or other data sources like Jira, Slack or TestRail.
- [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp (⭐ 107, ⏰ 2025-07-20)​‌‍) ☁️ 📇 🍎 🪟 🐧 - AI-powered developer assistant that enables advanced research, analysis and discovery across GitHub and NPM realms in realtime.
- [opslevel/opslevel-mcp](https://github.com/opslevel/opslevel-mcp (⭐ 5, ⏰ 2025-07-19)​‌‍) 🎖️ 🏎️ ☁️ 🪟 🍎 🐧 - Official MCP Server for [OpsLevel](https://www.opslevel.com)
- [picahq/mcp](https://github.com/picahq/mcp (⭐ 5, ⏰ 2025-07-09)​‌‍) 🎖️ 🦀 📇 ☁️ - One MCP for all your integrations — powered by [Pica](https://www.picaos.com), the infrastructure for intelligent, collaborative agents.
- [posthog/mcp](https://github.com/posthog/mcp (⭐ 73, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 ☁️ - An MCP server for interacting with PostHog analytics, feature flags, error tracking and more.
- [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp (⭐ 12, ⏰ 2025-07-18)​‌‍) 🐍 🏠 🍎 - Identifies resource-intensive processes on macOS and provides performance improvement suggestions.
- [pskill9/website-downloader](https://github.com/pskill9/website-downloader (⭐ 115, ⏰ 2025-07-18)​‌‍) 🗄️ 🚀 - This MCP server provides a tool to download entire websites using wget. It preserves the website structure and converts links to work locally.
- [qainsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server (⭐ 36, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - JMeter MCP Server for performance testing
- [qainsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server (⭐ 9, ⏰ 2025-07-13)​‌‍) 🐍 🏠 - Grafana k6 MCP Server for performance testing
- [qainsights/locust-mcp-server](https://github.com/QAInsights/locust-mcp-server (⭐ 5, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - Locust MCP Server for performance testing
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp (⭐ 341, ⏰ 2025-07-18)​‌‍) 🏎️ 🏠 - Docker container management and operations through MCP
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server (⭐ 288, ⏰ 2025-07-18)​‌‍) 📇 🏠 🍎 - Xcode integration for project management, file operations, and build automation
- [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi (⭐ 53, ⏰ 2025-07-18)​‌‍) 📇 🏠 - MCP server that lets LLMs know everything about your OpenAPI specifications to discover, explain and generate code/mock data
- [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server (⭐ 28, ⏰ 2025-07-16)​‌‍) 🎖️ 🐍 ☁️ 🍎 - MCP server for the incident management platform [Rootly](https://rootly.com/).
- [ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp (⭐ 10, ⏰ 2025-07-09)​‌‍) 📇 ☁️ 🪟 🐧 🍎 - GitHub Repo MCP allow your AI assistants browse GitHub repositories, explore directories, and view file contents.
- [sammcj/mcp-package-version](https://github.com/sammcj/mcp-package-version (⭐ 107, ⏰ 2025-07-19)​‌‍) 📇 🏠 - An MCP Server to help LLMs suggest the latest stable package versions when writing code.
- [sapientpants/sonarqube-mcp-server](https://github.com/sapientpants/sonarqube-mcp-server (⭐ 70, ⏰ 2025-07-18)​‌‍) 🦀 ☁️ 🏠 - A Model Context Protocol (MCP) server that integrates with SonarQube to provide AI assistants with access to code quality metrics, issues, and quality gate statuses
- [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code (⭐ 224, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - An implementation of Claude Code capabilities using MCP, enabling AI code understanding, modification, and project analysis with comprehensive tool support.
- [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server (⭐ 739, ⏰ 2025-07-20)​‌‍) 🏎️ 🏠 - Connect any HTTP/REST API server using an Open API spec (v3)
- [spacecode-ai/SpaceBridge-MCP](https://github.com/spacecode-ai/SpaceBridge-MCP (⭐ 4, ⏰ 2025-07-09)​‌‍) 🐍 🏠 🍎 🐧 - Bring structure and preserve context in vibe coding by automatically tracking issues.
- [stass/lldb-mcp](https://github.com/stass/lldb-mcp (⭐ 50, ⏰ 2025-07-13)​‌‍) 🐍 🏠 🐧 🍎 - A MCP server for LLDB enabling AI binary and core file analysis, debugging, disassembling.
- [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp (⭐ 220, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - An MCP service for deploying HTML content to EdgeOne Pages and obtaining a publicly accessible URL.
- [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp (⭐ 14, ⏰ 2025-07-12)​‌‍) 📇 ☁️ - An MCP server for interacting with [Bugsnag](https://www.bugsnag.com/)
- [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp (⭐ 6, ⏰ 2025-06-16)​‌‍) 📇 🏠 - Your Ionic coding buddy enabled via MCP – build awesome mobile apps using React/Angular/Vue or even Vanilla JS!
- [tipdotmd/tip-md-x402-mcp-server](https://github.com/tipdotmd/tip-md-x402-mcp-server (⭐ 1, ⏰ 2025-07-10)​‌‍) 📇 ☁️ - MCP server for cryptocurrency tipping through AI interfaces using x402 payment protocol and CDP Wallet.
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor (⭐ 133, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - A line-oriented text file editor. Optimized for LLM tools with efficient partial file access to minimize token usage.
- [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos (⭐ 192, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - MCP server providing accurate information about NixOS packages, system options, Home Manager configurations, and nix-darwin macOS settings to prevent AI hallucinations.
- [vivekvells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc (⭐ 325, ⏰ 2025-07-19)​‌‍) 🗄️ 🚀 - MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, PDF, DOCX (.docx), csv and more.
- [VSCode Devtools](https://github.com/biegehydra/BifrostMCP (⭐ 148, ⏰ 2025-07-17)​‌‍) 📇 - Connect to VSCode ide and use semantic tools like `find_usages`
- [Wooonster/hocr_mcp_server](https://github.com/Wooonster/hocr_mcp_server (⭐ 0, ⏰ 2025-04-30)​‌‍) 🐍 🏠 – A fastAPI-based FastMCP server with a Vue frontend that sends uploaded images to VLM via the MCP to quickly extract handwritten mathematical formulas as clean LaTeX code.
- [xcodebuild](https://github.com/ShenghaiWang/xcodebuild (⭐ 69, ⏰ 2025-07-13)​‌‍) 🍎 Build iOS Xcode workspace/project and feed back errors to llm.
- [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server (⭐ 17, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - Control HarmonyOS-next devices with AI through MCP. Support device control and UI automation.
- [xzq.xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server (⭐ 62, ⏰ 2025-07-14)​‌‍) 📇 🏠  - An implementation project of a JVM-based MCP (Model Context Protocol) server.
- [yangkyeongmo@/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow (⭐ 66, ⏰ 2025-07-10)​‌‍) 🐍 🏠 - MCP server that connects to [Apache Airflow](https://airflow.apache.org/) using official client.
- [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server (⭐ 19, ⏰ 2025-07-17)​‌‍) 🏎️ ☁️ 🪟 🐧 🍎 - Query Go package information on pkg.go.dev
- [yiwenlu66/PiloTY](https://github.com/yiwenlu66/PiloTY (⭐ 6, ⏰ 2025-07-07)​‌‍) 🐍 🏠 - AI pilot for PTY operations enabling agents to control interactive terminals with stateful sessions, SSH connections, and background process management
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server (⭐ 151, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - A Model Context Protocol (MCP) server for generating a beautiful interactive mindmap.
- [YuChenSSR/multi-ai-advisor](https://github.com/YuChenSSR/multi-ai-advisor-mcp (⭐ 54, ⏰ 2025-07-19)​‌‍) 📇 🏠 - A Model Context Protocol (MCP) server that queries multiple Ollama models and combines their responses, providing diverse AI perspectives on a single question.
- [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe (⭐ 31, ⏰ 2025-07-19)​‌‍) 📇 🏠 - MCP server that provides Typescript API information efficiently to the agent to enable it to work with untrained APIs
- [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server (⭐ 5, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 - A Model Context Protocol (MCP) server that converts OpenAPI/Swagger specifications to MCP format, enabling AI assistants to interact with REST APIs through standardized protocol.
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp (⭐ 496, ⏰ 2025-07-19)​‌‍) 📇 🏠 - An MCP server to flexibly fetch JSON, text, and HTML data
- [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml (⭐ 22, ⏰ 2025-07-14)​‌‍) 🐍 🏠 ☁️ - An MCP server to connect with your [ZenML](https://www.zenml.io) MLOps and LLMOps pipelines
- [zillow/auto-mobile](https://github.com/zillow/auto-mobile (⭐ 37, ⏰ 2025-07-17)​‌‍) 📇 🏠 🐧  - Tool suite built around an MCP server for Android automation for developer workflow and testing

### 🔒 <a name="delivery"></a>Delivery

- [https://github.com/jordandalton/doordash-mcp-server (⭐ 9, ⏰ 2025-07-02)​‌‍](https://github.com/JordanDalton/DoorDash-MCP-Server (⭐ 9, ⏰ 2025-07-02)​‌‍) 🐍 – DoorDash Delivery (Unofficial)

### 🧮 <a name="data-science-tools"></a>Data Science Tools

Integrations and tools designed to simplify data exploration, analysis and enhance data science workflows.

- [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp (⭐ 19, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Connects to Kaggle, ability to download and analyze datasets.
- [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp (⭐ 84, ⏰ 2025-07-13)​‌‍) 🐍 ☁️ - Predict anything with Chronulus AI forecasting and prediction agents.
- [DataEval/dingo](https://github.com/DataEval/dingo (⭐ 298, ⏰ 2025-07-19)​‌‍) 🎖️ 🐍 🏠 🍎 🪟 🐧 - MCP server for the Dingo: a comprehensive data quality evaluation tool. Server Enables interaction with Dingo's rule-based and LLM-based evaluation capabilities and rules&prompts listing.
- [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server (⭐ 513, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - Model Context Protocol (MCP) Server for Jupyter.
- [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp (⭐ 10, ⏰ 2025-07-14)​‌‍) 🎖️ 📇 🏠 🪟 🐧 🍎 — Tools for creating and interacting with GrowthBook feature flags and experiments.
- [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server (⭐ 13, ⏰ 2025-07-18)​‌‍) 🎖️ 🐍 ☁️ 🪟 🐧 🍎 - Create, manage, and automate Label Studio projects, tasks, and predictions for data labeling workflows.
- [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp (⭐ 85, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - connects Jupyter Notebook to Claude AI, allowing Claude to directly interact with and control Jupyter Notebooks.
- [kdqed/zaturn](https://github.com/kdqed/zaturn (⭐ 50, ⏰ 2025-07-17)​‌‍) 🐍 🏠 🪟 🐧 🍎 - Link multiple data sources (SQL, CSV, Parquet, etc.) and ask AI to analyze the data for insights and visualizations.
- [mckinsey/vizro-mcp](https://github.com/mckinsey/vizro/tree/main/vizro-mcp) 🎖️ 🐍 🏠 - Tools and templates to create validated and maintainable data charts and dashboards.
- [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp (⭐ 37, ⏰ 2025-07-17)​‌‍) 🎖️ 🐍 🏠 🐧 🍎 - Official MCP server enabling seamless orchestration of hyperparameter search and other optimization tasks with [Optuna](https://optuna.org/).
- [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration (⭐ 433, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Enables autonomous data exploration on .csv-based datasets, providing intelligent insights with minimal effort.
- [subelsky/bundler_mcp](https://github.com/subelsky/bundler_mcp (⭐ 14, ⏰ 2025-07-14)​‌‍) 💎 🏠 - Enables agents to query local information about dependencies in a Ruby project's `Gemfile`.
- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp (⭐ 1918, ⏰ 2025-07-20)​‌‍) 📇 🏠 - An MCP server to convert almost any file or web content into Markdown

### 📟 <a name="embedded-system"></a>Embedded System

Provides access to documentation and shortcuts for working on embedded devices.

- [horw/esp-mcp](https://github.com/horw/esp-mcp (⭐ 85, ⏰ 2025-07-19)​‌‍) 📟 - Workflow for fixing build issues in ESP32 series chips using ESP-IDF.
- [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp (⭐ 13, ⏰ 2025-07-13)​‌‍) 🐍 📟 - An MCP server that standardizes and contextualizes industrial Modbus data.
- [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp (⭐ 12, ⏰ 2025-07-01)​‌‍) 🐍 📟 - An MCP server that connects to OPC UA-enabled industrial systems.
- [stack-chan/stack-chan](https://github.com/stack-chan/stack-chan (⭐ 934, ⏰ 2025-07-17)​‌‍) 📇 📟 - A JavaScript-driven M5Stack-embedded super-kawaii robot with MCP server functionality for AI-controlled interactions and emotions.
- [yoelbassin/gnuradioMCP](https://github.com/yoelbassin/gnuradioMCP (⭐ 8, ⏰ 2025-07-18)​‌‍) 🐍 📟 🏠 - An MCP server for GNU Radio that enables LLMs to autonomously create and modify RF `.grc` flowcharts.

### 📂 <a name="file-systems"></a>File Systems

Provides direct access to local file systems with configurable permissions. Enables AI models to read, write, and manage files within specified directories.

- [8b-is/smart-tree](https://github.com/8b-is/smart-tree (⭐ 73, ⏰ 2025-07-18)​‌‍) 🦀 🏠 🍎 🪟 🐧 - AI-native directory visualization with semantic analysis, ultra-compressed formats for AI consumption, and 10x token reduction. Supports quantum-semantic mode with intelligent file categorization.
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py (⭐ 247, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - Share code context with LLMs via MCP or clipboard
- [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger (⭐ 15, ⏰ 2025-06-11)​‌‍) 🏎️ 🏠 - File merger tool, suitable for AI chat length limits.
- [filesystem@quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/filesystem) ☕ 🏠 - A filesystem allowing for browsing and editing files implemented in Java using Quarkus. Available as jar or native image.
- [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server (⭐ 7, ⏰ 2025-07-06)​‌‍) 📇 ☁️ - Box integration for listing, reading and searching files
- [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive (⭐ 147, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Model Context Protocol (MCP) Server for reading from Google Drive and editing Google Sheets.
- [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp (⭐ 8, ⏰ 2025-07-09)​‌‍) 🐍 🏠 🍎 - Control your macOS Homebrew setup using natural language via this MCP server. Simply manage your packages, or ask for suggestions, troubleshoot brew issues etc.
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search (⭐ 217, ⏰ 2025-07-18)​‌‍) 🐍 🏠 🪟 - Fast Windows file search using Everything SDK
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server (⭐ 455, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 - Golang implementation for local file system access.
- [mickaelkerjean/filestash](https://github.com/mickael-kerjean/filestash/tree/master/server/plugin/plg_handler_mcp) 🏎️ ☁️ - Remote Storage Access: SFTP, S3, FTP, SMB, NFS, WebDAV, GIT, FTPS, gcloud, azure blob, sharepoint, etc.
- [microsoft/markitdown](https://github.com/microsoft/markitdown/tree/main/packages/markitdown-mcp) 🎖️ 🐍 🏠 - MCP tool access to MarkItDown -- a library that converts many file formats (local or remote) to Markdown for LLM consumption.
- [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) 📇 🏠 - Direct local file system access.
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal (⭐ 31, ⏰ 2025-06-28)​‌‍) 🐍 🏠 ☁️ - Access any storage with Apache OpenDAL™

### 💰 <a name="finance--fintech"></a>Finance & Fintech

Financial data access and analysis tools. Enables AI models to work with market data, trading platforms, and financial information.

- [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp (⭐ 116, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Deep Research for crypto - free & fully local
- [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp (⭐ 5, ⏰ 2025-07-10)​‌‍) 🎖️ 🐍 ☁️ - Risk score / asset holdings of EVM blockchain address (EOA, CA, ENS) and even domain names.
- [getAlby/mcp](https://github.com/getAlby/mcp (⭐ 17, ⏰ 2025-07-18)​‌‍) 🎖️ 📇 ☁️ 🏠 - Connect any bitcoin lightning wallet to your agent to send and receive instant payments globally.
- [alchemy/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server (⭐ 54, ⏰ 2025-07-08)​‌‍) 🎖️ 📇 ☁️ - Allow AI agents to interact with Alchemy's blockchain APIs.
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server (⭐ 36, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - Coinmarket API integration to fetch cryptocurrency listings and quotes
- [araa47/jupiter-mcp](https://github.com/araa47/jupiter-mcp (⭐ 0, ⏰ 2025-07-08)​‌‍) 🐍 ☁️ - Jupiter API Access (allow AI to Trade Tokens on Solana + Access Balances + Search Tokens + Create Limit Orders )
- [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server (⭐ 75, ⏰ 2025-07-17)​‌‍) 🐍 🏠 🪟 - Enable AI LLMs to execute trades using MetaTrader 5 platform
- [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp (⭐ 176, ⏰ 2025-07-20)​‌‍) 🐍 ☁️ - MCP to interface with multiple blockchains, staking, DeFi, swap, bridging, wallet management, DCA, Limit Orders, Coin Lookup, Tracking and more.
- [bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp/) 📇 ☁️ - Bankless Onchain API to interact with smart contracts, query transaction and token information
- [base/base-mcp](https://github.com/base/base-mcp (⭐ 262, ⏰ 2025-07-18)​‌‍) 🎖️ 📇 ☁️ - Base Network integration for onchain tools, allowing interaction with Base Network and Coinbase API for wallet management, fund transfers, smart contracts, and DeFi operations
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp (⭐ 54, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ - Alpha Vantage API integration to fetch both stock and crypto information
- [bitteprotocol/mcp](https://github.com/BitteProtocol/mcp (⭐ 10, ⏰ 2025-07-07)​‌‍) 📇 - Bitte Protocol integration to run AI Agents on several blockchains.
- [carsol/monarch-mcp-server](https://github.com/carsol/monarch-mcp-server (⭐ 0, ⏰ 2025-06-08)​‌‍) 🐍 ☁️ - MCP server providing read-only access to Monarch Money financial data, enabling AI assistants to analyze transactions, budgets, accounts, and cashflow data with MFA support.
- [chargebee/mcp](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol) 🎖️ 📇 ☁️ - MCP Server that connects AI agents to [Chargebee platform](https://www.chargebee.com/).
- [codex-data/codex-mcp](https://github.com/Codex-Data/codex-mcp (⭐ 12, ⏰ 2025-07-14)​‌‍) 🎖️ 📇 ☁️ - [Codex API](https://www.codex.io) integration for real-time enriched blockchain and market data on 60+ networks
- [coinpaprika/dexpaprika-mcp](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol) 🎖️ 📇 ☁️ 🍎 🪟 🐧 - Coinpaprika's DexPaprika MCP server exposes high-performance [DexPaprika API](https://docs.dexpaprika.com) covering 20+ chains and 5M+ tokens with real time pricing, liquidity pool data & historical OHLCV data, providing AI agents standardized access to comprehensive market data through Model Context Protocol.
- [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt (⭐ 89, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - An MCP server for accessing real-time crypto market data and trading via 20+ exchanges using the CCXT library. Supports spot, futures, OHLCV, balances, orders, and more.
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent (⭐ 216, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - Yahoo Finance integration to fetch stock market data including options recommendations
- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent (⭐ 32, ⏰ 2025-07-12)​‌‍) 🐍 ☁️ - Tastyworks API integration to handle trading activities on Tastytrade
- [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp (⭐ 11, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Reddit integration to analyze content on WallStreetBets community
- [getalby/nwc-mcp-server](https://github.com/getalby/nwc-mcp-server (⭐ 13, ⏰ 2025-07-18)​‌‍) 📇 🏠 - Bitcoin Lightning wallet integration powered by Nostr Wallet Connect
- [glaksmono/finbud-data-mcp](https://github.com/glaksmono/finbud-data-mcp/tree/main/packages/mcp-server) 📇 ☁️ 🏠 - Access comprehensive, real-time financial data (stocks, options, crypto, forex) via developer-friendly, AI-native APIs offering unbeatable value.
- [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server (⭐ 53, ⏰ 2025-07-19)​‌‍) 🎖️ ⛅️ 🏠 🐍 - Access specialized web3 AI agents for blockchain analysis, smart contract security auditing, token metrics evaluation, and on-chain interactions through the Heurist Mesh network. Provides comprehensive tools for DeFi analysis, NFT valuation, and transaction monitoring across multiple blockchains
- [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server (⭐ 27, ⏰ 2025-07-15)​‌‍) 🐍 ☁️ - MCP server based on baostock, providing access and analysis capabilities for Chinese stock market data.
- [intentos-labs/beeper-mcp](https://github.com/intentos-labs/beeper-mcp (⭐ 3, ⏰ 2025-07-02)​‌‍) 🐍 - Beeper provides transactions on BSC, including balance/token transfers, token swaps in Pancakeswap and beeper reward claims.
- [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener (⭐ 9, ⏰ 2025-07-02)​‌‍) 📇 ☁️ - Real-time on-chain market prices using open and free Dexscreener API
- [kukapay/binance-alpha-mcp](https://github.com/kukapay/binance-alpha-mcp (⭐ 3, ⏰ 2025-06-26)​‌‍) 🐍 ☁️ - An MCP server for tracking Binance Alpha trades, helping AI agents optimize alpha point accumulation.
- [kukapay/blockbeats-mcp](https://github.com/kukapay/blockbeats-mcp (⭐ 5, ⏰ 2025-06-26)​‌‍) 🐍 ☁️ -  An MCP server that delivers blockchain news and in-depth articles from BlockBeats for AI agents.
- [kukapay/blocknative-mcp](https://github.com/kukapay/blocknative-mcp (⭐ 2, ⏰ 2025-05-15)​‌‍) 🐍 ☁️ -  Providing real-time gas price predictions across multiple blockchains, powered by Blocknative.
- [kukapay/bridge-rates-mcp](https://github.com/kukapay/bridge-rates-mcp (⭐ 4, ⏰ 2025-07-10)​‌‍) 📇 ☁️ - Delivering real-time cross-chain bridge rates and optimal transfer routes to onchain AI agents.
- [kukapay/chainlink-feeds-mcp](https://github.com/kukapay/chainlink-feeds-mcp (⭐ 4, ⏰ 2025-07-17)​‌‍) 📇 ☁️ -  Providing real-time access to Chainlink's decentralized on-chain price feeds.
- [kukapay/chainlist-mcp](https://github.com/kukapay/chainlist-mcp (⭐ 2, ⏰ 2025-06-13)​‌‍) 📇 ☁️ -  An MCP server that gives AI agents fast access to verified EVM chain information, including RPC URLs, chain IDs, explorers, and native tokens.
- [kukapay/cointelegraph-mcp](https://github.com/kukapay/cointelegraph-mcp (⭐ 2, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ -  Providing real-time access to the latest news from Cointelegraph.
- [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp (⭐ 33, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ -  Providing real-time and historical Crypto Fear & Greed Index data.
- [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp (⭐ 57, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - An MCP server providing a range of cryptocurrency technical analysis indicators and strategie.
- [kukapay/crypto-liquidations-mcp](https://github.com/kukapay/crypto-liquidations-mcp (⭐ 3, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - Streams real-time cryptocurrency liquidation events from Binance.
- [kukapay/crypto-news-mcp](https://github.com/kukapay/crypto-news-mcp (⭐ 5, ⏰ 2025-06-24)​‌‍) 🐍 ☁️ - An MCP server that provides real-time cryptocurrency news sourced from NewsData for AI agents.
- [kukapay/crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp (⭐ 4, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - Analyzing order book depth and imbalance across major crypto exchanges.
- [kukapay/crypto-pegmon-mcp](https://github.com/kukapay/crypto-pegmon-mcp (⭐ 2, ⏰ 2025-05-19)​‌‍) 🐍 ☁️ -  Tracking stablecoin peg integrity across multiple blockchains.
- [kukapay/crypto-portfolio-mcp](https://github.com/kukapay/crypto-portfolio-mcp (⭐ 7, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - An MCP server for tracking and managing cryptocurrency portfolio allocations.
- [kukapay/crypto-projects-mcp](https://github.com/kukapay/crypto-projects-mcp (⭐ 0, ⏰ 2025-05-11)​‌‍) 🐍 ☁️ - Providing cryptocurrency project data from Mobula.io to AI agents.
- [kukapay/crypto-rss-mcp](https://github.com/kukapay/crypto-rss-mcp (⭐ 3, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - An MCP server that aggregates real-time cryptocurrency news from multiple RSS feeds.
- [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp (⭐ 26, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - An MCP server that delivers cryptocurrency sentiment analysis to AI agents.
- [kukapay/crypto-trending-mcp](https://github.com/kukapay/crypto-trending-mcp (⭐ 3, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - Tracking the latest trending tokens on CoinGecko.
- [kukapay/crypto-whitepapers-mcp](https://github.com/kukapay/crypto-whitepapers-mcp (⭐ 2, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - Serving as a structured knowledge base of crypto whitepapers.
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server (⭐ 47, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Providing latest cryptocurrency news to AI agents, powered by CryptoPanic.
- [kukapay/defi-yields-mcp](https://github.com/kukapay/defi-yields-mcp (⭐ 5, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - An MCP server for AI agents to explore DeFi yield opportunities.
- [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp (⭐ 22, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ -  A mcp server that bridges Dune Analytics data to AI agents.
- [kukapay/etf-flow-mcp](https://github.com/kukapay/etf-flow-mcp (⭐ 3, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ -  Delivering crypto ETF flow data to power AI agents' decision-making.
- [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp (⭐ 59, ⏰ 2025-07-13)​‌‍) 🐍 ☁️ - An MCP server that integrates with the Freqtrade cryptocurrency trading bot.
- [kukapay/funding-rates-mcp](https://github.com/kukapay/funding-rates-mcp (⭐ 3, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - Providing real-time funding rate data across major crypto exchanges.
- [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp (⭐ 10, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - An MCP server that provides real-time data and insights from the Hyperliquid perp DEX for use in bots, dashboards, and analytics.
- [kukapay/hyperliquid-whalealert-mcp](https://github.com/kukapay/hyperliquid-whalealert-mcp (⭐ 3, ⏰ 2025-07-06)​‌‍) 🐍 ☁️ - An MCP server that provides real-time whale alerts on Hyperliquid, flagging positions with a notional value exceeding $1 million.
- [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp (⭐ 18, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - An MCP server for executing token swaps on the Solana blockchain using Jupiter's new Ultra API.
- [kukapay/pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp (⭐ 5, ⏰ 2025-07-02)​‌‍) 🐍 ☁️ -  An MCP server that tracks newly created pools on Pancake Swap.
- [kukapay/pumpswap-mcp](https://github.com/kukapay/pumpswap-mcp (⭐ 3, ⏰ 2025-07-03)​‌‍) 🐍 ☁️ - Enabling AI agents to interact with PumpSwap for real-time token swaps and automated on-chain trading.
- [kukapay/raydium-launchlab-mcp](https://github.com/kukapay/raydium-launchlab-mcp (⭐ 2, ⏰ 2025-07-14)​‌‍) 🐍 ☁️ - An MCP server that enables AI agents to launch, buy, and sell tokens on the Raydium Launchpad(aka LaunchLab).
- [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp (⭐ 10, ⏰ 2025-07-02)​‌‍) 🐍 ☁️ - An MCP server that detects potential risks in Solana meme tokens.
- [kukapay/sui-trader-mcp](https://github.com/kukapay/sui-trader-mcp (⭐ 4, ⏰ 2025-07-10)​‌‍) 📇 ☁️ - An MCP server designed for AI agents to perform optimal token swaps on the Sui blockchain.
- [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp (⭐ 5, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ -  An MCP server that powers AI agents with indexed blockchain data from The Graph.
- [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp (⭐ 15, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ -  An MCP server providing tools for AI agents to mint ERC-20 tokens across multiple blockchains.
- [kukapay/token-revoke-mcp](https://github.com/kukapay/token-revoke-mcp (⭐ 2, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - An MCP server for checking and revoking ERC-20 token allowances across multiple blockchains.
- [kukapay/twitter-username-changes-mcp](https://github.com/kukapay/twitter-username-changes-mcp (⭐ 2, ⏰ 2025-05-21)​‌‍) 🐍 ☁️ - An MCP server that tracks the historical changes of Twitter usernames.
- [kukapay/uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp (⭐ 5, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ -  An MCP server that tracks newly created liquidity pools on Uniswap across multiple blockchains.
- [kukapay/uniswap-price-mcp](https://github.com/kukapay/uniswap-price-mcp (⭐ 2, ⏰ 2025-07-17)​‌‍) 📇 ☁️ -  An MCP server that tracks newly created liquidity pools on Uniswap across multiple blockchains.
- [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp (⭐ 24, ⏰ 2025-07-11)​‌‍) 🐍 ☁️ -  An MCP server that delivers real-time token prices from Uniswap V3 across multiple chains.
- [kukapay/wallet-inspector-mcp](https://github.com/kukapay/wallet-inspector-mcp (⭐ 4, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ -  An MCP server that empowers AI agents to inspect any wallet’s balance and onchain activity across major EVM chains and Solana chain.
- [kukapay/web3-jobs-mcp](https://github.com/kukapay/web3-jobs-mcp (⭐ 2, ⏰ 2025-07-02)​‌‍) 🐍 ☁️ -  An MCP server that provides AI agents with real-time access to curated Web3 jobs.
- [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp (⭐ 29, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ -  A mcp server for tracking cryptocurrency whale transactions.
- [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp (⭐ 20, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - An MCP Server for the Alpaca trading API to manage stock and crypto portfolios, place trades, and access market data.
- [logotype/fixparser](https://gitlab.com/logotype/fixparser) 🎖 📇 ☁️ 🏠 📟  - FIX Protocol (send orders, market data, etc.) written in TypeScript.
- [longportapp/openapi](https://github.com/longportapp/openapi/tree/main/mcp) - 🐍 ☁️ - LongPort OpenAPI provides real-time stock market data, provides AI access analysis and trading capabilities through MCP.
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server (⭐ 297, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Comprehensive blockchain services for 30+ EVM networks, supporting native tokens, ERC20, NFTs, smart contracts, transactions, and ENS resolution.
- [mcpdotdirect/starknet-mcp-server](https://github.com/mcpdotdirect/starknet-mcp-server (⭐ 4, ⏰ 2025-05-23)​‌‍) 📇 ☁️ - Comprehensive Starknet blockchain integration with support for native tokens (ETH, STRK), smart contracts, StarknetID resolution, and token transfers.
- [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger (⭐ 23, ⏰ 2025-07-18)​‌‍) 🐍 🏠 -  A ledger-cli integration for managing financial transactions and generating reports.
- [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp (⭐ 35, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - An MCP server that uses yfinance to obtain information from Yahoo Finance.
- [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server (⭐ 54, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Octagon AI Agents to integrate private and public market data
- [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx (⭐ 10, ⏰ 2025-07-17)​‌‍) ☁️ 🏠 -  A core banking integration for managing clients, loans, savings, shares, financial transactions and generating financial reports.
- [polygon-io/mcp_polygon)](https://github.com/polygon-io/mcp_polygon (⭐ 30, ⏰ 2025-07-19)​‌‍)) 🐍 ☁️ -  An MCP server that provides access to [Polygon.io](https://polygon.io/) financial market data APIs for stocks, indices, forex, options, and more.
- [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server (⭐ 22, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ -  Bitget API to fetch cryptocurrency price.
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp (⭐ 79, ⏰ 2025-07-08)​‌‍) 📇 ☁️ - Real-time cryptocurrency market data integration using CoinCap's public API, providing access to crypto prices and market information without API keys
- [QuentinCody/braintree-mcp-server](https://github.com/QuentinCody/braintree-mcp-server (⭐ 1, ⏰ 2025-07-02)​‌‍) 🐍 - Unofficial PayPal Braintree payment gateway MCP Server for AI agents to process payments, manage customers, and handle transactions securely.
- [RomThpt/xrpl-mcp-server](https://github.com/RomThpt/mcp-xrpl (⭐ 4, ⏰ 2025-05-19)​‌‍) 📇 ☁️ - MCP server for the XRP Ledger that provides access to account information, transaction history, and network data. Allows querying ledger objects, submitting transactions, and monitoring the XRPL network.
- [SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop.git) 🐍 ☁️ - An MCP tool that provides cryptocurrency market data using the CoinGecko API.
- [SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop.git) 🐍 ☁️ - An MCP tool that provides stock market data and analysis using the Yahoo Finance API.
- [shareseer/shareseer-mcp-server](https://github.com/shareseer/shareseer-mcp-server (⭐ 2, ⏰ 2025-07-02)​‌‍) 🏎️ ☁️ - MCP to Access SEC filings, financials & insider trading data in real time using [ShareSeer](https://shareseer.com)
- [ThomasMarches/substrate-mcp-rs](https://github.com/ThomasMarches/substrate-mcp-rs (⭐ 7, ⏰ 2025-07-11)​‌‍) 🦀 🏠 - An MCP server implementation to interact with Substrate-based blockchains. Built with Rust and interfacing the [subxt](https://github.com/paritytech/subxt (⭐ 462, ⏰ 2025-07-18)​‌‍) crate.
- [tooyipjee/yahoofinance-mcp](https://github.com/tooyipjee/yahoofinance-mcp.git) 📇 ☁️ - TS version of yahoo finance mcp.
- [Trade-Agent/trade-agent-mcp](https://github.com/Trade-Agent/trade-agent-mcp.git) 🎖️ ☁️ - Trade stocks and crypto on common brokerages (Robinhood, E*Trade, Coinbase, Kraken) via Trade Agent's MCP server.
- [twelvedata/mcp](https://github.com/twelvedata/mcp (⭐ 13, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - Interact with [Twelve Data](https://twelvedata.com) APIs to access real-time and historical financial market data for your AI agents.
- [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp (⭐ 23, ⏰ 2025-07-11)​‌‍) 🦀 🏠 - An MCP tool for querying Solana transactions using natural language with Solscan API.
- [Wuye-AI/mcp-server-wuye-ai](https://github.com/wuye-ai/mcp-server-wuye-ai (⭐ 1, ⏰ 2025-07-14)​‌‍) 🎖️ 📇 ☁️ - An MCP server that interact with capabilities of the CRIC Wuye AI platform, an intelligent assistant specifically for the property management industry.
- [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server (⭐ 104, ⏰ 2025-07-19)​‌‍) 📇 ☁️ – An MCP server that integrates with Xero's API, allowing for standardized access to Xero's accounting and business features.
- [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server (⭐ 38, ⏰ 2025-07-14)​‌‍) 🐍 ☁️ - An MCP server for accessing professional financial data, supporting multiple data providers such as Tushare.
- [zolo-ryan/MarketAuxMcpServer](https://github.com/Zolo-Ryan/MarketAuxMcpServer (⭐ 0, ⏰ 2025-06-30)​‌‍) 📇 ☁️ - MCP server for comprehensive market and financial news search with advanced filtering by symbols, industries, countries, and date ranges.

### 🎮 <a name="gaming"></a>Gaming

Integration with gaming related data, game engines, and services

- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity (⭐ 788, ⏰ 2025-07-19)​‌‍) #️⃣ 🏠 - MCP Server for Unity3d Game Engine integration for game development
- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp (⭐ 630, ⏰ 2025-07-20)​‌‍) 📇 🏠 - A MCP server for interacting with the Godot game engine, providing tools for editing, running, debugging, and managing scenes in Godot projects.
- [ddsky/gamebrain-api-clients](https://github.com/ddsky/gamebrain-api-clients (⭐ 0, ⏰ 2025-07-04)​‌‍) ☁️ - Search and discover hundreds of thousands of video games on any platform through the [GameBrain API](https://gamebrain.co/api).
- [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP (⭐ 284, ⏰ 2025-07-19)​‌‍) #️⃣ 🏠 🍎 🪟 🐧 - MCP Server for Unity Editor and for a game made with Unity
- [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess (⭐ 12, ⏰ 2025-07-15)​‌‍) 🐍 🏠 - A MCP server playing chess against LLMs.
- [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp (⭐ 9, ⏰ 2025-07-18)​‌‍) 🏎️ ☁️ - An MCP server that enables interaction with board game related data via the BoardGameGeek API (XML API2).
- [opgginc/opgg-mcp](https://github.com/opgginc/opgg-mcp (⭐ 23, ⏰ 2025-07-16)​‌‍) 📇 ☁️ - Access real-time gaming data across popular titles like League of Legends, TFT, and Valorant, offering champion analytics, esports schedules, meta compositions, and character statistics.
- [pab1ito/chess-mcp](https://github.com/pab1it0/chess-mcp (⭐ 43, ⏰ 2025-07-09)​‌‍) 🐍 ☁️ - Access Chess.com player data, game records, and other public information through standardized MCP interfaces, allowing AI assistants to search and analyze chess information.
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp/) 🐍 ☁️ - An MCP server for real-time Fantasy Premier League data and analysis tools.
- [sonirico/mpc-stockfish](https://github.com/sonirico/mcp-stockfish (⭐ 1, ⏰ 2025-06-29)​‌‍) - 🏎️ 🏠 🍎 🪟 🐧️ MCP server connecting AI systems to Stockfish chess engine.
- [stefan-xyz/mcp-server-runescape](https://github.com/stefan-xyz/mcp-server-runescape (⭐ 3, ⏰ 2025-06-09)​‌‍) 📇 - An MCP server with tools for interacting with RuneScape (RS) and Old School RuneScape (OSRS) data, including item prices, player hiscores, and more.
- [tomholford/mcp-tic-tac-toe](https://github.com/tomholford/mcp-tic-tac-toe (⭐ 0, ⏰ 2025-07-11)​‌‍) 🏎️ 🏠 - Play Tic Tac Toe against an AI opponent using this MCP server.

### 🧠 <a name="knowledge--memory"></a>Knowledge & Memory

Persistent memory storage using knowledge graph structures. Enables AI models to maintain and query structured information across sessions.

- [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer (⭐ 99, ⏰ 2025-07-18)​‌‍) 📕 ☁️ - AI Summarization MCP Server, Support for multiple content types: Plain text, Web pages, PDF documents, EPUB books, HTML content
- [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG (⭐ 40, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ 🏠 - Production-ready RAG platform combining Graph RAG, vector search, and full-text search. Best choice for building your own Knowledge Graph and for Context Engineering
- [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum (⭐ 1003, ⏰ 2025-07-18)​‌‍) - Query and summarize your chat messages with AI prompts.
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh (⭐ 277, ⏰ 2025-07-19)​‌‍) 📇 🏠 - Enhanced graph-based memory with a focus on AI role-play and story generation
- [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp (⭐ 65, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - A Model Context Protocol (MCP) server that implements the Zettelkasten knowledge management methodology, allowing you to create, link, and search atomic notes through Claude and other MCP-compatible clients.
- [GistPad-MCP](https://github.com/lostintangent/gistpad-mcp (⭐ 136, ⏰ 2025-07-17)​‌‍) 📇 🏠 - Use GitHub Gists to manage and access your personal knowledge, daily notes, and reusable prompts. This acts as a companion to https://gistpad.dev and the [GistPad VS Code extension](https://aka.ms/gistpad).
- [graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server (⭐ 334, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Ingest anything from Slack, Discord, websites, Google Drive, Linear or GitHub into a Graphlit project - and then search and retrieve relevant knowledge within an MCP client like Cursor, Windsurf or Cline.
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs (⭐ 209, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - An MCP server implementation that provides tools for retrieving and processing documentation through vector search, enabling AI assistants to augment their responses with relevant documentation context
- [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server (⭐ 73, ⏰ 2025-07-18)​‌‍) 📇 🏠 - An MCP server built on [markmap](https://github.com/markmap/markmap (⭐ 11496, ⏰ 2025-07-20)​‌‍) that converts **Markdown** to interactive **mind maps**. Supports multi-format exports (PNG/JPG/SVG), live browser preview, one-click Markdown copy, and dynamic visualization features.
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero (⭐ 123, ⏰ 2025-07-16)​‌‍) 📇 ☁️ - A connector for LLMs to work with collections and sources on your Zotero Cloud
- [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp (⭐ 400, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - A Model Context Protocol server for Mem0 that helps manage coding preferences and patterns, providing tools for storing, retrieving and semantically handling code implementations, best practices and technical documentation in IDEs like Cursor and Windsurf
- [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) 📇 🏠 - Knowledge graph-based persistent memory system for maintaining context
- [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp (⭐ 28, ⏰ 2025-07-18)​‌‍) 🎖️ 🦀 ☁️ - Connects to your Pinecone Assistant and gives the agent context from its knowledge engine.
- [ragieai/mcp-server](https://github.com/ragieai/ragie-mcp-server (⭐ 55, ⏰ 2025-07-16)​‌‍) 📇 ☁️ - Retrieve context from your [Ragie](https://www.ragie.ai) (RAG) knowledge base connected to integrations like Google Drive, Notion, JIRA and more.
- [TechDocsStudio/biel-mcp](https://github.com/TechDocsStudio/biel-mcp (⭐ 2, ⏰ 2025-07-07)​‌‍) 📇 ☁️ - Let AI tools like Cursor, VS Code, or Claude Desktop answer questions using your product docs. Biel.ai provides the RAG system and MCP server.
- [topoteretes/cognee](https://github.com/topoteretes/cognee/tree/dev/cognee-mcp) 📇 🏠 - Memory manager for AI apps and Agents using various graph and vector stores and allowing ingestion from 30+ data sources
- [unibaseio/membase-mcp](https://github.com/unibaseio/membase-mcp (⭐ 7, ⏰ 2025-07-05)​‌‍) 📇 ☁️ - Save and query your agent memory in distributed way by Membase
- [upstash/context7](https://github.com/upstash/context7 (⭐ 20953, ⏰ 2025-07-20)​‌‍) 📇 ☁️ - Up-to-date code documentation for LLMs and AI code editors.

### 🗺️ <a name="location-services"></a>Location Services

Location-based services and mapping tools. Enables AI models to work with geographic data, weather information, and location-based analytics.

- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo (⭐ 26, ⏰ 2025-07-08)​‌‍) 🐍 ☁️  - IP address geolocation and network information using IPInfo API
- [devilcoder01/weather-mcp-server](https://github.com/devilcoder01/weather-mcp-server (⭐ 9, ⏰ 2025-07-20)​‌‍) 🐍 ☁️ - Access real-time weather data for any location using the WeatherAPI.com API, providing detailed forecasts and current conditions.
- [ip2location/mcp-ip2location-io](https://github.com/ip2location/mcp-ip2location-io (⭐ 4, ⏰ 2025-07-16)​‌‍) 🐍 ☁️  - Official IP2Location.io MCP server to obtain the geolocation, proxy and network information of an IP address utilizing IP2Location.io API.
- [ipfind/ipfind-mcp-server](https://github.com/ipfind/ipfind-mcp-server (⭐ 0, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - IP Address location service using the [IP Find](https://ipfind.com) API
- [ipfred/aiwen-mcp-server-geoip](https://github.com/ipfred/aiwen-mcp-server-geoip (⭐ 3, ⏰ 2025-07-16)​‌‍) 🐍 📇 ☁️ – MCP Server for the Aiwen IP Location, Get user network IP location, get IP details (country, province, city, lat, lon, ISP, owner, etc.)
- [iplocate/mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate (⭐ 1, ⏰ 2025-06-30)​‌‍) 🎖️ 📇 🏠  - Look up IP address geolocation, network information, detect proxies and VPNs, and find abuse contact details using IPLocate.io
- [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp (⭐ 81, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - An OpenStreetMap MCP server with location-based services and geospatial data.
- [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp (⭐ 12, ⏰ 2025-07-03)​‌‍) 🐍 ☁️ - An MCP server for nearby place searches with IP-based location detection.
- [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp (⭐ 31, ⏰ 2025-07-19)​‌‍) 🏠 – A Model Context Protocol (MCP) server implementation that connects LLMs to the GeoServer REST API, enabling AI assistants to interact with geospatial data and services.
- [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp (⭐ 25, ⏰ 2025-07-18)​‌‍) 🏠 – A Model Context Protocol (MCP) server implementation that connects Large Language Models (LLMs) to GIS operations using GIS libraries, enabling AI assistants to perform accurate geospatial operations and transformations.
- [modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/google-maps) 📇 ☁️ - Google Maps integration for location services, routing, and place details
- [QGIS MCP](https://github.com/jjsantos01/qgis_mcp (⭐ 566, ⏰ 2025-07-17)​‌‍) - connects QGIS Desktop to Claude AI through the MCP. This integration enables prompt-assisted project creation, layer loading, code execution, and more.
- [rossshannon/Weekly-Weather-mcp](https://github.com/rossshannon/weekly-weather-mcp.git) 🐍 ☁️ - Weekly Weather MCP server which returns 7 full days of detailed weather forecasts anywhere in the world.
- [SaintDoresh/Weather-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Weather-MCP-ClaudeDesktop.git) 🐍 ☁️ - An MCP tool that provides real-time weather data, forecasts, and historical weather information using the OpenWeatherMap API.
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver (⭐ 38, ⏰ 2025-07-06)​‌‍) 🐍 🏠 - Access the time in any timezone and get the current local time
- [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather (⭐ 11, ⏰ 2025-07-17)​‌‍) 📇 ☁️  - Accurate weather forecasts via the AccuWeather API (free tier available).
- [trackmage/trackmage-mcp-server](https://github.com/trackmage/trackmage-mcp-server (⭐ 1, ⏰ 2025-06-09)​‌‍) 📇 - Shipment tracking api and logistics management capabilities through the [TrackMage API] (https://trackmage.com/)
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo (⭐ 22, ⏰ 2025-07-16)​‌‍) 🐍 🏠 - Geocoding MCP server for nominatim, ArcGIS, Bing

### 🎯 <a name="marketing"></a>Marketing

Tools for creating and editing marketing content, working with web meta data, product positioning, and editing guides.

- [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server (⭐ 95, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server acting as an interface to the Facebook Ads, enabling programmatic access to Facebook Ads data and management features.
- [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server (⭐ 25, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server acting as an interface to the Google Ads, enabling programmatic access to Google Ads data and management features.
- [marketplaceadpros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server (⭐ 5, ⏰ 2025-07-20)​‌‍) 📇 ☁️  - Enables tools to interact with Amazon Advertising, analyzing campaign metrics and configurations.
- [open-strategy-partners/osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools (⭐ 201, ⏰ 2025-07-17)​‌‍) 🐍 🏠 - A suite of marketing tools from Open Strategy Partners including writing style, editing codes, and product marketing value map creation.
- [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp (⭐ 169, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ 🏠 - Enables AI agents to monitor and optimize Meta ad performance, analyze campaign metrics, adjust audience targeting, manage creative assets, and make data-driven recommendations for ad spend and campaign settings through seamless Graph API integration.
- [stape-io/stape-mcp-server](https://github.com/stape-io/stape-mcp-server (⭐ 1, ⏰ 2025-07-07)​‌‍) 📇 ☁️ – This project implements an MCP (Model Context Protocol) server for the Stape platform. It allows interaction with the Stape API using AI assistants like Claude or AI-powered IDEs like Cursor.
- [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server (⭐ 23, ⏰ 2025-07-18)​‌‍) 📇 ☁️ – This server supports remote MCP connections, includes built-in Google OAuth, and provide an interface to the Google Tag Manager API.


### 📊 <a name="monitoring"></a>Monitoring

Access and analyze application monitoring data. Enables AI models to review error reports and performance metrics.

- [edgedelta/edgedelta-mcp-server](https://github.com/edgedelta/edgedelta-mcp-server (⭐ 4, ⏰ 2025-07-10)​‌‍) 🎖️ 🏎️ ☁️ – Interact with Edge Delta anomalies, query logs / patterns / events, and pinpoint root causes and optimize your pipelines.
- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana (⭐ 1217, ⏰ 2025-07-20)​‌‍) 🎖️ 🐍 🏠 ☁️ - Search dashboards, investigate incidents and query datasources in your Grafana instance
- [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp (⭐ 54, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - Enhance AI-generated code quality through intelligent, prompt-based analysis across 10 critical dimensions from complexity to security vulnerabilities
- [inventer-dev/mcp-internet-speed-test](https://github.com/inventer-dev/mcp-internet-speed-test (⭐ 7, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - Internet speed testing with network performance metrics including download/upload speed, latency, jitter analysis, and CDN server detection with geographic mapping
- [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server (⭐ 40, ⏰ 2025-07-17)​‌‍) - Seamlessly bring real-time production context—logs, metrics, and traces—into your local environment to auto-fix code faster
- [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server (⭐ 43, ⏰ 2025-07-18)​‌‍) 🎖️ 🏎️ ☁️ - Query and interact with kubernetes environments monitored by Metoro
- [MindscapeHQ/server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun (⭐ 15, ⏰ 2025-07-16)​‌‍) 📇 ☁️ - Raygun API V3 integration for crash reporting and real user monitoring
- [modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) 🐍 ☁️ - Sentry.io integration for error tracking and performance monitoring
- [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server (⭐ 30, ⏰ 2025-07-14)​‌‍) 🐍 ☁️ 🐧 🪟 🍎 - Zabbix integration for hosts, items, triggers, templates, problems, data and more.
- [netdata/netdata#Netdata](https://github.com/netdata/netdata/blob/master/src/web/mcp/README.md) 🎖️ 🏠 ☁️ 📟 🍎 🪟 🐧 - Discovery, exploration, reporting and root cause analysis using all observability data, including metrics, logs, systems, containers, processes, and network connections
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp (⭐ 89, ⏰ 2025-07-16)​‌‍) 🎖️ 🐍 ☁️ - Provides access to OpenTelemetry traces and metrics through Logfire
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor (⭐ 50, ⏰ 2025-07-17)​‌‍) 🏎️ 🏠 - A system monitoring tool that exposes system metrics via the Model Context Protocol (MCP). This tool allows LLMs to retrieve real-time system information through an MCP-compatible interface.（support CPU、Memory、Disk、Network、Host、Process）
- [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp (⭐ 11, ⏰ 2025-07-09)​‌‍) 🐍 🏠 - An MCP server that allows querying Loki logs through the Grafana API.
- [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics (⭐ 53, ⏰ 2025-07-18)​‌‍) 🎖️ 🏎️ 🏠 - Provides comprehensive integration with your [VictoriaMetrics instance APIs](https://docs.victoriametrics.com/victoriametrics/url-examples/) and [documentation](https://docs.victoriametrics.com/) for monitoring, observability, and debugging tasks related to your VictoriaMetrics instances
- [imprvhub/mcp-status-observer](https://github.com/imprvhub/mcp-status-observer (⭐ 5, ⏰ 2025-07-03)​‌‍) 📇 ☁️ -  Model Context Protocol server for monitoring Operational Status of major digital platforms in Claude Desktop.
- [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server (⭐ 10, ⏰ 2025-07-18)​‌‍) 🏎️ ☁️ 🏠 🐧 🪟 🍎 - Debug your Container and Kubernetes workloads with an AI interface powered by eBPF.

### 🎥 <a name="multimedia-process"></a>Multimedia Process

Provides the ability to handle multimedia, such as audio and video editing, playback, format conversion, also includes video filters, enhancements, and so on

- [ananddtyagi/gif-creator-mcp](https://github.com/ananddtyagi/gif-creator-mcp/tree/main) 📇 🏠 - A MCP server for creating GIFs from your videos.
- [bogdan01m/zapcap-mcp-server](https://github.com/bogdan01m/zapcap-mcp-server (⭐ 0, ⏰ 2025-07-13)​‌‍) 🐍 ☁️ - MCP server for ZapCap API providing video caption and B-roll generation via natural language
- [stass/exif-mcp](https://github.com/stass/exif-mcp (⭐ 14, ⏰ 2025-07-17)​‌‍) 📇 🏠 🐧 🍎 🪟 - A MCP server that allows one to examine image metadata like EXIF, XMP, JFIF and GPS.  This provides foundation for LLM-powered search and analysis of photo librares and image collections.
- [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp (⭐ 62, ⏰ 2025-07-20)​‌‍) 🐍 🏠 🐧 🍎 🪟 - ComputerVision-based 🪄 sorcery of image recognition and editing tools for AI assistants.
- [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp.git) 🎥 🔊 - Using ffmpeg command line to achieve an mcp server, can be very convenient, through the dialogue to achieve the local video search, tailoring, stitching, playback and other functions

### 🔎 <a name="RAG"></a>end to end RAG platforms

- [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp (⭐ 13, ⏰ 2025-07-15)​‌‍) 🐍 🏠 ☁️ - An MCP server for accessing Vectara's trusted RAG-as-a-service platform.

### 🔎 <a name="search"></a>Search & Data Extraction

- [0xdaef0f/job-searchoor](https://github.com/0xDAEF0F/job-searchoor (⭐ 29, ⏰ 2025-07-09)​‌‍) 📇 🏠 - An MCP server for searching job listings with filters for date, keywords, remote work options, and more.
- [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch (⭐ 162, ⏰ 2025-07-19)​‌‍) 🐍 📇 ☁️ - Web search using free multi-engine search (NO API KEYS REQUIRED) — Supports Bing, Baidu, DuckDuckGo, Brave, Exa, and CSDN.
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi (⭐ 35, ⏰ 2025-07-06)​‌‍) 📇 ☁️ - Kagi search API integration
- [adawalli/nexus](https://github.com/adawalli/nexus (⭐ 6, ⏰ 2025-07-06)​‌‍) 📇 ☁️ - AI-powered web search server using Perplexity Sonar models with source citations. Zero-install setup via NPX.
- [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp (⭐ 24, ⏰ 2025-07-15)​‌‍) 📇 🏠 - A MCP server for taking screenshots of webpages to use as feedback during UI developement.
- [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv (⭐ 123, ⏰ 2025-07-16)​‌‍) - 🐍 ☁️  MCP for LLM to search and read papers from arXiv
- [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed (⭐ 109, ⏰ 2025-07-19)​‌‍) - 🐍 ☁️  MCP to search and read medical / life sciences papers from PubMed.
- [angheljf/nyt](https://github.com/angheljf/nyt (⭐ 12, ⏰ 2025-06-30)​‌‍) 📇 ☁️ - Search articles using the NYTimes API
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser (⭐ 171, ⏰ 2025-07-20)​‌‍) 📇 ☁️ - An MCP server for Apify's open-source RAG Web Browser Actor to perform web searches, scrape URLs, and return content in Markdown.
- [Bigsy/Clojars-MCP-Server](https://github.com/Bigsy/Clojars-MCP-Server (⭐ 5, ⏰ 2025-06-25)​‌‍) 📇 ☁️ - Clojars MCP Server for upto date dependency information of Clojure libraries
- [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server (⭐ 1443, ⏰ 2025-07-20)​‌‍) ☁️ 🐍 - Search ArXiv research papers
- [chanmeng/google-news-mcp-server](https://github.com/ChanMeng666/server-google-news (⭐ 67, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Google News integration with automatic topic categorization, multi-language support, and comprehensive search capabilities including headlines, stories, and related topics through [SerpAPI](https://serpapi.com/).
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp/) 🐍 🏠 ☁️ - This is a Python-based MCP server that provides OpenAI `web_search` build-in tool.
- [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp (⭐ 24, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ - Enable fast, free real-time web search and access premium data from trusted media brands—news, financial markets, sports, entertainment, weather, and more. Build powerful AI agents with Dappier.
- [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition (⭐ 85, ⏰ 2025-07-15)​‌‍) 📇 🏠 - Local MCP server for searching 300,000+ foods, nutrition facts, and barcodes from the OpenNutrition database.
- [dealx/mcp-server](https://github.com/DealExpress/mcp-server (⭐ 0, ⏰ 2025-04-01)​‌‍) ☁️ - MCP Server for DealX platform
- [devflowinc/trieve](https://github.com/devflowinc/trieve/tree/main/clients/mcp-server) 🎖️ 📇 ☁️ 🏠 - Crawl, embed, chunk, search, and retrieve information from datasets through [Trieve](https://trieve.ai)
- [Dumpling-AI/mcp-server-dumplingai](https://github.com/Dumpling-AI/mcp-server-dumplingai (⭐ 21, ⏰ 2025-07-13)​‌‍) 🎖️ 📇 ☁️ - Access data, web scraping, and document conversion APIs by [Dumpling AI](https://www.dumplingai.com/)
- [emicklei/melrose-mcp](https://github.com/emicklei/melrose-mcp (⭐ 5, ⏰ 2025-07-02)​‌‍) 🏎️ 🏠 - Plays [Melrōse](https://melrōse.org) music expressions as MIDI
- [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn (⭐ 48, ⏰ 2025-07-16)​‌‍) 🐍 ☁️ - An MCP server to search Hacker News, get top stories, and more.
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server (⭐ 1868, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 ☁️ – A Model Context Protocol (MCP) server lets AI assistants like Claude use the Exa AI Search API for web searches. This setup allows AI models to get real-time web information in a safe and controlled way.
- [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp (⭐ 143, ⏰ 2025-07-08)​‌‍) 📇 ☁️ - Search via search1api (requires paid API key)
- [format37/youtube_mcp](https://github.com/format37/youtube_mcp (⭐ 12, ⏰ 2025-07-07)​‌‍) 🐍 ☁️ – MCP server that transcribes YouTube videos to text. Uses yt-dlp to download audio and OpenAI's Whisper-1 for more precise transcription than youtube captions. Provide a YouTube URL and get back the full transcript splitted by chunks for long videos.
- [genomoncology/biomcp](https://github.com/genomoncology/biomcp (⭐ 214, ⏰ 2025-07-20)​‌‍) 🐍 ☁️ - Biomedical research server providing access to PubMed, ClinicalTrials.gov, and MyVariant.info.
- [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode (⭐ 11, ⏰ 2025-07-15)​‌‍) - 🐍 ☁️ MCP to search through PapersWithCode API
- [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server (⭐ 144, ⏰ 2025-07-10)​‌‍)) 🐍 ☁️ - A MCP server for Unsplash image search.
- [Himalayas-App/himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp (⭐ 2, ⏰ 2025-07-01)​‌‍) 📇 ☁️ - Access tens of thousands of remote job listings and company information. This public MCP server provides real-time access to Himalayas' remote jobs database.
- [Ihor-Sokoliuk/MCP-SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng (⭐ 146, ⏰ 2025-07-19)​‌‍) 📇 🏠/☁️ - A Model Context Protocol Server for [SearXNG](https://docs.searxng.org)
- [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp (⭐ 28, ⏰ 2025-07-14)​‌‍) 📇 ☁️ - MCP server for Naver Search API integration, supporting blog, news, shopping search and DataLab analytics features.
- [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp (⭐ 773, ⏰ 2025-07-19)​‌‍) 📇 🏠 - MCP server for fetching web page content using Playwright headless browser, supporting Javascript rendering and intelligent content extraction, and outputting Markdown or HTML format.
- [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp (⭐ 176, ⏰ 2025-07-18)​‌‍) 📇 🏠 - A powerful MCP server for Google search that enables parallel searching with multiple keywords simultaneously.
- [joelio/stocky](https://github.com/joelio/stocky (⭐ 4, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ 🏠 - An MCP server for searching and downloading royalty-free stock photography from Pexels and Unsplash. Features multi-provider search, rich metadata, pagination support, and async performance for AI assistants to find and access high-quality images.
- [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast (⭐ 9, ⏰ 2025-07-15)​‌‍) 📇 🏠 - Fast, token-efficient web content extraction for AI agents - converts websites to clean Markdown while preserving links. Features Mozilla Readability, smart caching, polite crawling with robots.txt support, and concurrent fetching.
- [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast (⭐ 4, ⏰ 2025-07-13)​‌‍) 📇 🏠 - Fast screenshot capture tool optimized for Claude Vision API. Automatically tiles full pages into 1072x1072 chunks for optimal AI processing with configurable viewports and wait strategies for dynamic content.
- [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp (⭐ 132, ⏰ 2025-07-18)​‌‍) ☁️ 📇 – Official Kagi Search MCP Server
- [kshern/mcp-tavily](https://github.com/kshern/mcp-tavily.git) ☁️ 📇 – Tavily AI search API
- [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp (⭐ 53, ⏰ 2025-07-02)​‌‍) 📇 ☁️ - Web search capabilities using Microsoft Bing Search API
- [lfnovo/content-core](https://github.com/lfnovo/content-core (⭐ 28, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - Extract content from URLs, documents, videos, and audio files using intelligent auto-engine selection. Supports web pages, PDFs, Word docs, YouTube transcripts, and more with structured JSON responses.
- [luminati-io/brightdata-mcp](https://github.com/luminati-io/brightdata-mcp (⭐ 958, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Discover, extract, and interact with the web - one interface powering automated access across the public internet.
- [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp (⭐ 41, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Web, Image, News, Video, and Local Point of Interest search capabilities using Brave's Search API
- [modelcontextprotocol/server-brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) 📇 ☁️ - Web search capabilities using Brave's Search API
- [modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) 🐍 🏠 ☁️ - Efficient web content fetching and processing for AI consumption
- [mzxrai/mcp-webresearch](https://github.com/mzxrai/mcp-webresearch (⭐ 269, ⏰ 2025-07-17)​‌‍) 🔍 📚 - Search Google and do deep web research on any topic
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server (⭐ 314, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Web search using DuckDuckGo
- [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag (⭐ 60, ⏰ 2025-07-17)​‌‍) 🏠 🐍 - "primitive" RAG-like web search model context protocol (MCP) server that runs locally. No APIs needed.
- [nyxn-ai/NyxDocs](https://github.com/nyxn-ai/NyxDocs (⭐ 3, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ 🏠 - Specialized MCP server for cryptocurrency project documentation management with multi-blockchain support (Ethereum, BSC, Polygon, Solana).
- [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp (⭐ 31, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 ☁️ 🏠 - Lightning-Fast, High-Accuracy Deep Research Agent
- [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl (⭐ 14, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - Advanced search and retrieval for web crawler data. Supports WARC, wget, Katana, SiteOne, and InterroBot crawlers.
- [QuentinCody/catalysishub-mcp-server](https://github.com/QuentinCody/catalysishub-mcp-server (⭐ 1, ⏰ 2025-05-20)​‌‍) 🐍 - Unofficial MCP server for searching and retrieving scientific data from the Catalysis Hub database, providing access to computational catalysis research and surface reaction data.
- [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp (⭐ 13, ⏰ 2025-06-19)​‌‍) 📇 ☁️ - Access Dutch Parliament (Tweede Kamer) information including documents, debates, activities, and legislative cases through structured search capabilities (based on opentk project by Bert Hubert)
- [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research (⭐ 140, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - MCP server providing OpenAI/Perplexity-like autonomous deep research, structured query elaboration, and concise reporting.
- [ricocf/mcp-wolframalpha](https://github.com/ricocf/mcp-wolframalpha (⭐ 32, ⏰ 2025-07-15)​‌‍) 🐍 🏠 ☁️ - An MCP server lets AI assistants use the Wolfram Alpha API for real-time access to computational knowledge and data.
- [sascharo/gxtract](https://github.com/sascharo/gxtract (⭐ 0, ⏰ 2025-05-20)​‌‍) 🐍 ☁️ 🪟 🐧 🍎 - GXtract is a MCP server designed to integrate with VS Code and other compatible editors (documentation: [sascharo.github.io/gxtract](https://sascharo.github.io/gxtract)). It provides a suite of tools for interacting with the GroundX platform, enabling you to leverage its powerful document understanding capabilities directly within your development environment.
- [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server (⭐ 31, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - The Scrapeless Model Context Protocol service acts as an MCP server connector to the Google SERP API, enabling web search within the MCP ecosystem without leaving it.
- [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng (⭐ 81, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - An MCP Server to connect to searXNG instances
- [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp (⭐ 31, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - Get the LaTeX source of arXiv papers to handle mathematical content and equations
- [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server (⭐ 14, ⏰ 2025-07-09)​‌‍) 🐍 ☁️ - An MCP Server that retrieves and processes news data from the GeekNews site.
- [tianqitang1/enrichr-mcp-server](https://github.com/tianqitang1/enrichr-mcp-server (⭐ 2, ⏰ 2025-07-14)​‌‍) 📇 ☁️ - A MCP server that provides gene set enrichment analysis using the Enrichr API
- [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp (⭐ 88, ⏰ 2025-07-17)​‌‍) 🎖️ 📇 ☁️ - MCP server that provides [AgentQL](https://agentql.com)'s data extraction capabilities.
- [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily (⭐ 40, ⏰ 2025-06-26)​‌‍) ☁️ 🐍 – Tavily AI search API
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) ☁️ 📇 - [Vectorize](https://vectorize.io) MCP server for advanced retrieval, Private Deep Research, Anything-to-Markdown file extraction and text chunking.
- [vitorpavinato/ncbi-mcp-server](https://github.com/vitorpavinato/ncbi-mcp-server (⭐ 1, ⏰ 2025-07-05)​‌‍) 🐍 ☁️ 🏠 - Comprehensive NCBI/PubMed literature search server with advanced analytics, caching, MeSH integration, related articles discovery, and batch processing for all life sciences and biomedical research.
- [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server (⭐ 19, ⏰ 2025-07-12)​‌‍) 🎖️ 📇 ☁️ - Interact with [WebScraping.ai](https://webscraping.ai) for web data extraction and scraping.
- [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server (⭐ 32, ⏰ 2025-07-11)​‌‍) 📇 🏠 - MCP server that searches Baseline status using Web Platform API
- [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mpc-server/) 📇 🏠 ☁️ - This is a TypeScript-based MCP server that provides DuckDuckGo search functionality.
- [zoomeye-ai/mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye (⭐ 35, ⏰ 2025-07-11)​‌‍) 📇 ☁️ - Querying network asset information by ZoomEye MCP Server
- [Pearch-ai/mcp_pearch](https://github.com/Pearch-ai/mcp_pearch (⭐ 2, ⏰ 2025-07-03)​‌‍) 🎖️ 🐍 ☁️ - Best people search engine that reduces the time spent on talent discovery
- [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability (⭐ 7, ⏰ 2025-07-07)​‌‍) 🐍 ☁️ - A Model Context Protocol (MCP) server that enables Claude Desktop to check domain availability across 50+ TLDs. Features DNS/WHOIS verification, bulk checking, and smart suggestions. Zero-clone installation via uvx.
- [imprvhub/mcp-claude-hackernews](https://github.com/imprvhub/mcp-claude-hackernews (⭐ 4, ⏰ 2025-07-16)​‌‍) 📇 🏠 ☁️ - An integration that allows Claude Desktop to interact with Hacker News using the Model Context Protocol (MCP).
- [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator (⭐ 5, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 - Model Context Protocol Server for aggregating RSS feeds in Claude Desktop.

### 🔒 <a name="security"></a>Security

- [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP (⭐ 59, ⏰ 2025-07-18)​‌‍) 🐍 ☕ 🏠 - MCP server for integrating Ghidra with AI assistants. This plugin enables binary analysis, providing tools for function inspection, decompilation, memory exploration, and import/export analysis via the Model Context Protocol.
- [AIM-Intelligence/AIM-Guard-MCP](https://github.com/AIM-Intelligence/AIM-MCP (⭐ 3, ⏰ 2025-07-01)​‌‍) 📇 🏠 🍎 🪟 🐧 - Security-focused MCP server that provides safety guidelines and content analysis for AI agents.
- [atomicchonk/roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server (⭐ 41, ⏰ 2025-06-13)​‌‍) 🐍 🪟 🏠 MCP server for analyzing ROADrecon gather results from Azure tenant enumeration
- [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist (⭐ 31, ⏰ 2025-07-19)​‌‍) 📇 🪟 ☁️ - MCP server for dnstwist, a powerful DNS fuzzing tool that helps detect typosquatting, phishing, and corporate espionage.
- [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret (⭐ 167, ⏰ 2025-07-19)​‌‍) 📇 🪟 ☁️ - MCP server for maigret, a powerful OSINT tool that collects user account information from various public sources. This server provides tools for searching usernames across social networks and analyzing URLs.
- [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan (⭐ 65, ⏰ 2025-07-19)​‌‍) 📇 🪟 ☁️ - MCP server for querying the Shodan API and Shodan CVEDB. This server provides tools for IP lookups, device searches, DNS lookups, vulnerability queries, CPE lookups, and more.
- [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal (⭐ 69, ⏰ 2025-07-19)​‌‍) 📇 🪟 ☁️ - MCP server for querying the VirusTotal API. This server provides tools for scanning URLs, analyzing file hashes, and retrieving IP address reports.
- [co-browser/attestable-mcp-server](https://github.com/co-browser/attestable-mcp-server (⭐ 14, ⏰ 2025-07-15)​‌‍) 🐍 🏠 ☁️ 🐧 - An MCP server running inside a trusted execution environment (TEE) via Gramine, showcasing remote attestation using [RA-TLS](https://gramine.readthedocs.io/en/stable/attestation.html). This allows an MCP client to verify the server before conencting.
- [dkvdm/onepassword-mcp-server](https://github.com/dkvdm/onepassword-mcp-server) - An MCP server that enables secure credential retrieval from 1Password to be used by Agentic AI.
- [firstorderai/authenticator_mcp](https://github.com/firstorderai/authenticator_mcp (⭐ 16, ⏰ 2025-07-19)​‌‍) 📇 🏠 🍎 🪟 🐧 – A secure MCP (Model Context Protocol) server that enables AI agents to interact with the Authenticator App.
- [fosdickio/binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp (⭐ 72, ⏰ 2025-07-19)​‌‍) 🐍 🏠 🍎 🪟 🐧 - A Binary Ninja plugin, MCP server, and bridge that seamlessly integrates [Binary Ninja](https://binary.ninja) with your favorite MCP client.  It enables you to automate the process of performing binary analysis and reverse engineering.
- [fr0gger/MCP_Security](https://github.com/fr0gger/MCP_Security (⭐ 41, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - MCP server for querying the ORKL API. This server provides tools for fetching threat reports, analyzing threat actors, and retrieving intelligence sources.
- [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp (⭐ 21, ⏰ 2025-07-14)​‌‍) - MCP server for Volatility 3.x, allowing you to perform memory forensics analysis with AI assistant. Experience memory forensics without barriers as plugins like pslist and netscan become accessible through clean REST APIs and LLMs.
- [gbrigandi/mcp-server-cortex](https://github.com/gbrigandi/mcp-server-cortex (⭐ 5, ⏰ 2025-07-18)​‌‍) 🦀 🏠 🚨 🍎 🪟 🐧 - A Rust-based MCP server to integrate Cortex, enabling observable analysis and automated security responses through AI.
- [gbrigandi/mcp-server-thehive](https://github.com/gbrigandi/mcp-server-thehive (⭐ 8, ⏰ 2025-07-14)​‌‍) 🦀 🏠 🚨 🍎 🪟 🐧 - A Rust-based MCP server to integrate TheHive, facilitating collaborative security incident response and case management via AI.
- [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh (⭐ 82, ⏰ 2025-07-18)​‌‍) 🦀 🏠 🚨 🍎 🪟 🐧 - A Rust-based MCP server bridging Wazuh SIEM with AI assistants, providing real-time security alerts and event data for enhanced contextual understanding.
- [hieutran/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server (⭐ 11, ⏰ 2025-07-15)​‌‍) 🐍 ☁️ - A MCP server for Microsoft Entra ID (Azure AD) directory, user, group, device, sign-in, and security operations via Microsoft Graph Python SDK.
- [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp (⭐ 15, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server to access [Intruder](https://www.intruder.io/), helping you identify, understand, and fix security vulnerabilities in your infrastructure.
- [jtang613/GhidrAssistMCP](https://github.com/jtang613/GhidrAssistMCP (⭐ 266, ⏰ 2025-07-20)​‌‍) ☕ 🏠 - A native Model Context Protocol server for Ghidra. Includes GUI configuration and logging, 31 powerful tools and no external dependencies.
- [jyjune/mcp_vms](https://github.com/jyjune/mcp_vms (⭐ 6, ⏰ 2025-07-18)​‌‍) 🐍 🏠 🪟 - A Model Context Protocol (MCP) server designed to connect to a CCTV recording program (VMS) to retrieve recorded and live video streams. It also provides tools to control the VMS software, such as showing live or playback dialogs for specific channels at specified times.
- [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP (⭐ 5415, ⏰ 2025-07-19)​‌‍) ☕ 🏠 - A Model Context Protocol server for Ghidra that enables LLMs to autonomously reverse engineer applications. Provides tools for decompiling binaries, renaming methods and data, and listing methods, classes, imports, and exports.
- [mobb-dev/mobb-vibe-shield-mcp](https://github.com/mobb-dev/bugsy (⭐ 55, ⏰ 2025-07-18)​‌‍?tab=readme-ov-file#model-context-protocol-mcp-server) 🎖️ 📇 ☁️ 🍎 🪟 🐧 - [Mobb Vibe Shield](https://vibe.mobb.ai/) identifies and remediates vulnerabilities in both human and AI-written code, ensuring your applications remain secure without slowing development.
- [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp (⭐ 2696, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - MCP server for IDA Pro, allowing you to perform binary analysis with AI assistants. This plugin implement decompilation, disassembly and allows you to generate malware analysis reports automatically.
- [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon (⭐ 13, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 - Conversational recon interface and MCP server powered by httpx and asnmap. Supports various reconnaissance levels for domain analysis, security header inspection, certificate analysis, and ASN lookup.
- [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther (⭐ 20, ⏰ 2025-07-18)​‌‍) 🎖️ 🐍 ☁️ 🍎 - MCP server that enables security professionals to interact with Panther's SIEM platform using natural language for writing detections, querying logs, and managing alerts.
- [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server (⭐ 4, ⏰ 2025-07-19)​‌‍) 🦀 🏠 🍎 🪟 🐧 - A MCP server for MobSF which can be used for static and dynamic analysis of Android and iOS application.
- [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit (⭐ 36, ⏰ 2025-07-18)​‌‍) 📇 ☁️ A powerful MCP (Model Context Protocol) Server that audits npm package dependencies for security vulnerabilities. Built with remote npm registry integration for real-time security checks.
- [rad-security/mcp-server](https://github.com/rad-security/mcp-server (⭐ 4, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - MCP server for RAD Security, providing AI-powered security insights for Kubernetes and cloud environments. This server provides tools for querying the Rad Security API and retrieving security findings, reports, runtime data and many more.
- [roadwy/cve-search_mcp](https://github.com/roadwy/cve-search_mcp (⭐ 35, ⏰ 2025-07-13)​‌‍) 🐍 🏠 - A Model Context Protocol (MCP) server for querying the CVE-Search API. This server provides comprehensive access to CVE-Search, browse vendor and product、get CVE per CVE-ID、get the last updated CVEs.
- [safedep/vet](https://github.com/safedep/vet/blob/main/docs/mcp.md) 🎖️ 🏎️ ☁️ 🍎 🪟 🐧 - vet-mcp checks open source packages—like those suggested by AI coding tools—for vulnerabilities and malicious code. It supports npm and PyPI, and runs locally via Docker or as a standalone binary for fast, automated vetting.
- [sanyambassi/ciphertrust-manager-mcp-server](https://github.com/sanyambassi/ciphertrust-manager-mcp-server (⭐ 3, ⏰ 2025-07-03)​‌‍) 🐍 ☁️ 🏠 - MCP server for Thales CipherTrust Manager integration, enabling secure key management, cryptographic operations, and compliance monitoring through AI assistants.
- [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp (⭐ 116, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - All-in-one security testing toolbox that brings together popular open source tools through a single MCP interface. Connected to an AI agent, it enables tasks like pentesting, bug bounty hunting, threat hunting, and more.
- [semgrep/mcp](https://github.com/semgrep/mcp (⭐ 224, ⏰ 2025-07-19)​‌‍) 📇 ☁️ Allow AI agents to scan code for security vulnerabilites using [Semgrep](https://semgrep.dev).
- [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server (⭐ 15, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server for interacting with the CyberChef server API which will allow an MCP client to utilise the CyberChef operations.
- [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp (⭐ 14, ⏰ 2025-07-16)​‌‍) 🏎️ ☁️ - Access the OSV (Open Source Vulnerabilities) database for vulnerability information. Query vulnerabilities by package version or commit, batch query multiple packages, and get detailed vulnerability information by ID.
- [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP (⭐ 8, ⏰ 2025-07-16)​‌‍) 📇 🏠 - MCP Server for managing & interacting with Open Source NGFW OPNSense via Natural Language
- [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server (⭐ 154, ⏰ 2025-07-18)​‌‍) 🐍 🏠 - APKTool MCP Server is a MCP server for the Apk Tool to provide automation in reverse engineering of Android APKs.
- [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp (⭐ 382, ⏰ 2025-07-20)​‌‍) ☕ 🏠 - JADX-AI-MCP is a plugin and MCP Server for the JADX decompiler that integrates directly with Model Context Protocol (MCP) to provide live reverse engineering support with LLMs like Claude.

### 🌐 <a name="social-media"></a>Social Media

Integration with social media platforms to allow posting, analytics, and interaction management. Enables AI-driven automation for social presence.

- [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp (⭐ 9, ⏰ 2025-07-15)​‌‍) 🏎️ ☁️ - AI‑powered YouTube uploader—no CLI, no YouTube Studio. Uploade videos directly from MCP clients with all AI capabilities.
- [gwbischof/bluesky-social-mcp](https://github.com/gwbischof/bluesky-social-mcp (⭐ 5, ⏰ 2025-06-09)​‌‍) 🐍 🏠 - An MCP server for interacting with Bluesky via the atproto client.
- [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server (⭐ 25, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - Integrates with Facebook Pages to enable direct management of posts, comments, and engagement metrics through the Graph API for streamlined social media management.
- [kunallunia/twitter-mcp](https://github.com/LuniaKunal/mcp-twitter (⭐ 23, ⏰ 2025-07-15)​‌‍) 🐍 🏠 - All-in-one Twitter management solution providing timeline access, user tweet retrieval, hashtag monitoring, conversation analysis, direct messaging, sentiment analysis of a post, and complete post lifecycle control - all through a streamlined API.
- [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp (⭐ 10, ⏰ 2025-07-18)​‌‍) - 🎖️ 🐍 ☁️ Access real-time X/Reddit/YouTube data directly in your LLM applications  with search phrases, users, and date filtering.


### 🏃 <a name="sports"></a>Sports

Tools for accessing sports-related data, results, and statistics.

- [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp (⭐ 14, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - MCP server that acts as a proxy to the freely available MLB API, which provides player info, stats, and game information.
- [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp (⭐ 10, ⏰ 2025-07-17)​‌‍) 📇 - MCP server that integrates balldontlie api to provide information about players, teams and games for the NBA, NFL and MLB
- [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp (⭐ 12, ⏰ 2025-07-09)​‌‍) 📇 ☁️ - Access cycling race data, results, and statistics through natural language. Features include retrieving start lists, race results, and rider information from firstcycling.com.
- [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp (⭐ 90, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - A Model Context Protocol (MCP) server that connects to Strava API, providing tools to access Strava data through LLMs
- [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1 (⭐ 12, ⏰ 2025-07-05)​‌‍) 🐍 ☁️ - MCP server that controls [MultiViewer](https://multiviewer.app), an app for watching motorsports like Formula 1, World Endurance Championship, IndyCar and others.
- [willvelida/mcp-afl-server](https://github.com/willvelida/mcp-afl-server (⭐ 6, ⏰ 2025-07-13)​‌‍) ☁️ - MCP server that integrates with the Squiggle API to provide information on Australian Football League teams, ladder standings, results, tips, and power rankings.
- [cloudbet/sports-mcp-server](https://github.com/cloudbet/sports-mcp-server (⭐ 3, ⏰ 2025-07-14)​‌‍) 🏎️ ☁️ – Access structured sports data via the Cloudbet API. Query upcoming events, live odds, stake limits, and market info across soccer, basketball, tennis, esports, and more.


### 🎧 <a name="support-and-service-management"></a>Support & Service Management

Tools for managing customer support, IT service management, and helpdesk operations.

- [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp (⭐ 13, ⏰ 2025-07-13)​‌‍) 🐍 ☁️ 🏠 - MCP Server for Yandex Tracker. Provides tools for searching and retrieving information about issues, queues, users.
- [effytech/freshdesk-mcp](https://github.com/effytech/freshdesk_mcp (⭐ 17, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server that integrates with Freshdesk, enabling AI models to interact with Freshdesk modules and perform various support operations.
- [incentivai/quickchat-ai-mcp](https://github.com/incentivai/quickchat-ai-mcp (⭐ 20, ⏰ 2025-07-02)​‌‍) 🐍 🏠 ☁️ - Launch your conversational Quickchat AI agent as an MCP to give AI apps real-time access to its Knowledge Base and conversational capabilities.
- [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp (⭐ 42, ⏰ 2025-07-16)​‌‍) 🏎️ ☁️ - A Go-based MCP connector for Jira that enables AI assistants like Claude to interact with Atlassian Jira. This tool provides a seamless interface for AI models to perform common Jira operations including issue management, sprint planning, and workflow transitions.
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian (⭐ 2490, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
- [tom28881/mcp-jira-server](https://github.com/tom28881/mcp-jira-server (⭐ 1, ⏰ 2025-07-07)​‌‍) 📇 ☁️ 🏠 - Comprehensive TypeScript MCP server for Jira with 20+ tools covering complete project management workflow: issue CRUD, sprint management, comments/history, attachments, batch operations.

### 🌎 <a name="translation-services"></a>Translation Services

Translation tools and services to enable AI assistants to translate content between different languages.

- [mmntm/weblate-mcp](https://github.com/mmntm/weblate-mcp (⭐ 1, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Comprehensive Model Context Protocol server for Weblate translation management, enabling AI assistants to perform translation tasks, project management, and content discovery with smart format transformations.
- [translated/lara-mcp](https://github.com/translated/lara-mcp (⭐ 64, ⏰ 2025-07-19)​‌‍) 🎖️ 📇 ☁️ - MCP Server for Lara Translate API, enabling powerful translation capabilities with support for language detection and context-aware translations.

### 🎧 <a name="text-to-speech"></a>Text-to-Speech

Tools for converting text-to-speech and vice-versa

- [daisys-ai/daisys-mcp](https://github.com/daisys-ai/daisys-mcp (⭐ 6, ⏰ 2025-07-15)​‌‍) 🐍 🏠 🍎 🪟 🐧 - Generate high-quality text-to-speech and text-to-voice outputs using the [DAISYS](https://www.daisys.ai/) platform and make it able to play and store audio generated.
- [mbailey/voice-mcp](https://github.com/mbailey/voice-mcp (⭐ 119, ⏰ 2025-07-20)​‌‍) 🐍 🏠 - Complete voice interaction server supporting speech-to-text, text-to-speech, and real-time voice conversations through local microphone, OpenAI-compatible APIs, and LiveKit integration
- [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp (⭐ 48, ⏰ 2025-07-13)​‌‍) 🐍 🏠 - MCP Server that uses the open weight Kokoro TTS models to convert text-to-speech. Can convert text to MP3 on a local driver or auto-upload to an S3 bucket.

### 🚆 <a name="travel-and-transportation"></a>Travel & Transportation

Access to travel and transportation information. Enables querying schedules, routes, and real-time travel data.

- [campertunity/mcp-server](https://github.com/campertunity/mcp-server (⭐ 2, ⏰ 2025-07-01)​‌‍) 🎖️ 📇 🏠 - Search campgrounds around the world on campertunity, check availability, and provide booking links
- [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp (⭐ 92, ⏰ 2025-07-09)​‌‍) 🐍 🏠 - A Model Context Protocol (MCP) server that provides access to your TeslaMate database, allowing AI assistants to query Tesla vehicle data and analytics.
- [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks (⭐ 20, ⏰ 2025-07-03)​‌‍) 📇 ☁️ - National Park Service API integration providing latest information of park details, alerts, visitor centers, campgrounds, and events for U.S. National Parks
- [lucygoodchild/mcp-national-rail](https://github.com/lucygoodchild/mcp-national-rail (⭐ 0, ⏰ 2025-06-02)​‌‍) 📇 ☁️ - An MCP server for UK National Rail trains service, providing train schedules and live travel information, intergrating the Realtime Trains API
- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb (⭐ 229, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Provides tools to search Airbnb and get listing details.
- [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp (⭐ 33, ⏰ 2025-07-18)​‌‍) 📇 🐍 - A MCP server that enables LLMs to interact with Tripadvisor API, supporting location data, reviews, and photos through standardized MCP interfaces
- [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server (⭐ 39, ⏰ 2025-06-28)​‌‍) 📇 ☁️ - Access Dutch Railways (NS) travel information, schedules, and real-time updates
- [skedgo/tripgo-mcp-server](https://github.com/skedgo/tripgo-mcp-server (⭐ 1, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Provides tools from the TripGo API for multi-modal trip planning, transport locations, and public transport departures, including real-time information.
- [srinath1510/alltrails-mcp-server](https://github.com/srinath1510/alltrails-mcp-server (⭐ 1, ⏰ 2025-07-05)​‌‍) 🐍 ☁️ - A MCP server that provides access to AllTrails data, allowing you to search for hiking trails and get detailed trail information

### 🔄 <a name="version-control"></a>Version Control

Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

- [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest (⭐ 259, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - Read and analyze GitHub repositories with your LLM
- [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp (⭐ 22, ⏰ 2025-07-18)​‌‍) 📇 ☁️ 🏠 - MCP server for GitHub Enterprise API integration
- [gitea/gitea-mcp](https://gitea.com/gitea/gitea-mcp) 🎖️ 🏎️ ☁️ 🏠 🍎 🪟 🐧 - Interactive with Gitea instances with MCP.
- [github/github-mcp-server](https://github.com/github/github-mcp-server (⭐ 18013, ⏰ 2025-07-20)​‌‍) 📇 ☁️ - Official GitHub server for integration with repository management, PRs, issues, and more.
- [kaiyuanxiaobing/atomgit-mcp-server](https://github.com/kaiyuanxiaobing/atomgit-mcp-server (⭐ 6, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - Official AtomGit server for integration with repository management, PRs, issues, branches, labels, and more.
- [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp (⭐ 48, ⏰ 2025-07-16)​‌‍) 📇 ☁️ - Interact seamlessly with issues and merge requests of your GitLab projects.
- [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) 🐍 🏠 - Direct Git repository operations including reading, searching, and analyzing local repositories
- [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) 📇 ☁️ 🏠 - GitLab platform integration for project management and CI/CD operations
- [QuentinCody/github-graphql-mcp-server](https://github.com/QuentinCody/github-graphql-mcp-server (⭐ 3, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - Unofficial GitHub MCP server that provides access to GitHub's GraphQL API, enabling more powerful and flexible queries for repository data, issues, pull requests, and other GitHub resources.
- [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops (⭐ 276, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Azure DevOps integration for repository management, work items, and pipelines.

### 🏢 <a name="workplace-and-productivity"></a>Workplace & Productivity

- [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server (⭐ 6, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ 🍎 🪟 🐧 - MCP server that seamlessly interacts with your Google Calendar, Gmail, Drive and so on.
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite (⭐ 403, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Integration with gmail and Google Calendar.
- [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp (⭐ 43, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - An MCP server to interface with the Google Calendar API. Based on TypeScript.
- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp (⭐ 305, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ 🍎 🪟 🐧 - Comprehensive Google Workspace MCP server with full support for Google Calendar, Drive, Gmail, and Docs, Forms, Chats, Slides and Sheets over stdio, Streamable HTTP and SSE transports.

### 🛠️ <a name="other-tools-and-integrations"></a>Other Tools and Integrations

- [2niuhe/plantuml_web](https://github.com/2niuhe/plantuml_web (⭐ 2, ⏰ 2025-07-19)​‌‍) 🐍 🏠 ☁️ 🍎 🪟 🐧 - A web-based PlantUML frontend with MCP server integration, enable plantuml image generation and plantuml syntax validation.
- [2niuhe/qrcode_mcp](https://github.com/2niuhe/qrcode_mcp (⭐ 3, ⏰ 2025-07-15)​‌‍) 🐍 🏠 🍎 🪟 🐧 - A QR code generation MCP server that converts any text (including Chinese characters) to QR codes with customizable colors and base64 encoding output.
- [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp (⭐ 52, ⏰ 2025-07-19)​‌‍) - ₿ A Model Context Protocol (MCP) server that enables AI models to interact with Bitcoin, allowing them to generate keys, validate addresses, decode transactions, query the blockchain, and more.
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server (⭐ 34, ⏰ 2025-07-15)​‌‍) - Allows the AI to read from your Bear Notes (macOS only)
- [allenporter/mcp-server-home-assistant](https://github.com/allenporter/mcp-server-home-assistant (⭐ 57, ⏰ 2025-07-13)​‌‍) 🐍 🏠 - Expose all Home Assistant voice intents through a Model Context Protocol Server allowing home control.
- [altinoren/utopia](https://github.com/altinoren/Utopia (⭐ 4, ⏰ 2025-07-05)​‌‍) #️⃣ 🏠 - MCP that simulates a set of smart home and lifestyle devices, allowing you to test agent's reasoning and discovery capabilities.
- [Amazon Bedrock Nova Canvas](https://github.com/zxkane/mcp-server-amazon-bedrock (⭐ 21, ⏰ 2025-05-31)​‌‍) 📇 ☁️ - Use Amazon Nova Canvas model for image generation.
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server (⭐ 36, ⏰ 2025-07-09)​‌‍) 🐍/📇 ☁️ - Send requests to OpenAI, MistralAI, Anthropic, xAI, Google AI or DeepSeek using MCP protocol via tool or predefined prompts. Vendor API key required
- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer (⭐ 1310, ⏰ 2025-07-19)​‌‍) 🐍 🏠 -  An MCP server that installs other MCP servers for you.
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube (⭐ 406, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Fetch YouTube subtitles
- [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant (⭐ 33, ⏰ 2025-07-17)​‌‍) - 🐍 ☁️  MCP to talk to OpenAI assistants (Claude can use any GPT model as his assitant)
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver (⭐ 18, ⏰ 2025-07-14)​‌‍) 🐍 🏠☁️ - An MCP server that allows checking local time on the client machine or current UTC time from an NTP server
- [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server (⭐ 270, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Use 3,000+ pre-built cloud tools, known as Actors, to extract data from websites, e-commerce, social media, search engines, maps, and more
- [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server (⭐ 52, ⏰ 2025-07-13)​‌‍) 📇 ☁️ PiAPI MCP server makes users able to generate media content with Midjourney/Flux/Kling/Hunyuan/Udio/Trellis directly from Claude or any other MCP-compatible apps.
- [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp (⭐ 37, ⏰ 2025-07-10)​‌‍) 📇 ☁️ - Provides the ability to generate images via Replicate's API.
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior (⭐ 20, ⏰ 2025-07-09)​‌‍) 🏠 📇 - An MCP server for basic local taskwarrior usage (add, update, remove tasks)
- [Azure/azure-mcp](https://github.com/Azure/azure-mcp (⭐ 967, ⏰ 2025-07-20)​‌‍) - Official Microsoft MCP server for Azure services including Storage, Cosmos DB, and Azure Monitor.
- [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp (⭐ 20, ⏰ 2025-07-09)​‌‍) 🐍 ☁️ - A Model Context Protocol (MCP) server that integrates with Notion's API to manage personal todo lists efficiently.
- [ankitmalik84/notion-mcp-server](https://github.com/ankitmalik84/Agentic_Longterm_Memory/tree/main/src/notion_mcp_server) 🐍 ☁️ - A comprehensive Model Context Protocol (MCP) server for Notion integration with enhanced functionality, robust error handling, production-ready feature.
- [bart6114/my-bear-mcp-server](https://github.com/bart6114/my-bear-mcp-server/) 📇 🏠 🍎 - Allows to read notes and tags for the Bear Note taking app, through a direct integration with Bear's sqlitedb.
- [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses (⭐ 10, ⏰ 2025-07-03)​‌‍) 🐍 ☁️ - MCP server for Claude to talk to ChatGPT and use its web search capability.
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql (⭐ 230, ⏰ 2025-07-20)​‌‍) 📇 ☁️ - Allows the AI to query GraphQL servers
- [boldsign/boldsign-mcp](https://github.com/boldsign/boldsign-mcp (⭐ 3, ⏰ 2025-07-15)​‌‍) 📇 ☁️ - Search, request, and manage e-signature contracts effortlessly with [BoldSign](https://boldsign.com/).
- [brianxiadong/ones-wiki-mcp-server](https://github.com/brianxiadong/ones-wiki-mcp-server (⭐ 0, ⏰ 2025-05-29)​‌‍) ☕ ☁️/🏠 - A Spring AI MCP-based service for retrieving ONES Waiki content and converting it to AI-friendly text format.
- [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian (⭐ 1008, ⏰ 2025-07-19)​‌‍) 📇 🏠 - This is a connector to allow Claude Desktop (or any MCP client) to read and search any directory containing Markdown notes (such as an Obsidian vault).
- [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp (⭐ 478, ⏰ 2025-07-19)​‌‍) 📇 🏠 🍎 🪟 🐧 - Wenyan MCP Server, which lets AI automatically format Markdown articles and publish them to WeChat GZH.
- [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli (⭐ 1575, ⏰ 2025-07-19)​‌‍) 🐍 🏠 - Yet another CLI tool for testing MCP servers
- [danhilse/notion_mcp](https://github.com/danhilse/notion_mcp (⭐ 192, ⏰ 2025-07-20)​‌‍) 🐍 ☁️ - Integrates with Notion's API to manage personal todo lists
- [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp (⭐ 24, ⏰ 2025-07-15)​‌‍) 🐍 - PDF download, view & manipulation utilities.
- [dotemacs/domain-lookup-mcp](https://github.com/dotemacs/domain-lookup-mcp (⭐ 3, ⏰ 2025-07-14)​‌‍) 🏎️ - Domain name lookup service, first via [RDAP](https://en.wikipedia.org/wiki/Registration_Data_Access_Protocol) and then as a fallback via [WHOIS](https://en.wikipedia.org/wiki/WHOIS)
- [ekkyarmandi/ticktick-mcp](https://github.com/ekkyarmandi/ticktick-mcp (⭐ 4, ⏰ 2025-07-15)​‌‍) 🐍 ☁️ - [TickTick](https://ticktick.com/) MCP server that integrates with TickTick's API to manage personal todo projects and the tasks.
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy (⭐ 14, ⏰ 2025-07-16)​‌‍) 🏎️ 🏠 - MCP server proxy that offers a Web UI to the full message flow
- [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures (⭐ 20, ⏰ 2025-07-17)​‌‍) 🐍 ☁️️ - Contract and template management for drafting, reviewing, and sending binding contracts via the eSignatures API.
- [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace (⭐ 332, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - Use HuggingFace Spaces directly from Claude. Use Open Source Image Generation, Chat, Vision tasks and more. Supports Image, Audio and text uploads/downloads.
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro (⭐ 66, ⏰ 2025-07-13)​‌‍) 📇 ☁️ - Access MIRO whiteboards, bulk create and read items. Requires OAUTH key for REST API.
- [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp (⭐ 21, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - Read, create, update and delete Google Keep notes.
- [fotoetienne/gqai](https://github.com/fotoetienne/gqai (⭐ 17, ⏰ 2025-07-10)​‌‍) 🏎 🏠 - Define tools using regular GraphQL queries/mutations and gqai automatically generates an MCP server for you.
- [future-audiences/wikimedia-enterprise-model-context-protocol](https://gitlab.wikimedia.org/repos/future-audiences/wikimedia-enterprise-model-context-protocol) 🐍 ☁️  - Wikipedia Article lookup API
- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator (⭐ 91, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - This server enables LLMs to use calculator for precise numerical calculations
- [gotoolkits/DifyWorkflow](https://github.com/gotoolkits/mcp-difyworkflow-server (⭐ 52, ⏰ 2025-07-16)​‌‍) - 🏎️ ☁️ Tools to the query and execute of Dify workflows
- [growilabs/growi-mcp-server](https://github.com/growilabs/growi-mcp-server (⭐ 3, ⏰ 2025-07-07)​‌‍) 🎖️ 📇 ☁️ - Official MCP Server to integrate with GROWI APIs.
- [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp (⭐ 10, ⏰ 2025-07-15)​‌‍) 🐍 🏠 - Give your AI free will tools. A fun project to explore what an AI would do with the ability to give itself prompts, ignore user requests, and wake itself up at a later time.
- [Harry-027/JotDown](https://github.com/Harry-027/JotDown (⭐ 18, ⏰ 2025-07-14)​‌‍) 🦀 🏠 - An MCP server to create/update pages in Notion app & auto generate mdBooks from structured content.
- [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server (⭐ 20, ⏰ 2025-07-14)​‌‍) - 📇 ☁️ A Model-Context-Protocol (MCP) server for integrating with Yuque API, allowing AI models to manage documents, interact with knowledge bases, search content, and access analytics data from the Yuque platform.
- [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server (⭐ 42, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - An integration that allows LLMs to interact with Raindrop.io bookmarks using the Model Context Protocol (MCP).
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server (⭐ 13, ⏰ 2025-07-13)​‌‍) - 📇 ☁️ Allows AI clients to manage records and notes in Attio CRM
- [MonadsAG/capsulecrm-mcp](https://github.com/MonadsAG/capsulecrm-mcp (⭐ 0, ⏰ 2025-07-12)​‌‍) - 📇 ☁️ Allows AI clients to manage contacts, opportunities and tasks in Capsule CRM including Claude Desktop ready DTX-file
- [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server (⭐ 119, ⏰ 2025-07-17)​‌‍) 🎖️ 📇 🏠 - Turn your [Make](https://www.make.com/) scenarios into callable tools for AI assistants.
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server (⭐ 75, ⏰ 2025-07-05)​‌‍) 🐍 🏠 - Generate visualizations from fetched data using the VegaLite format and renderer.
- [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo (⭐ 25, ⏰ 2025-07-18)​‌‍) 🐍 ☁️/🏠 - Connect AI assistants to Odoo ERP systems for business data access, record management, and workflow automation.
- [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp (⭐ 55, ⏰ 2025-07-17)​‌‍) 📇 🏠 - Update, create, delete content, content-models and assets in your Contentful Space
- [j3k0/speech.sh](https://github.com/j3k0/speech.sh/blob/main/MCP_README.md) 🏠 - Let the agent speak things out loud, notify you when he's done working with a quick summary
- [jagan-shanmugam/climatiq-mcp-server](https://github.com/jagan-shanmugam/climatiq-mcp-server (⭐ 5, ⏰ 2025-07-08)​‌‍) 🐍 🏠 - A Model Context Protocol (MCP) server for accessing the Climatiq API to calculate carbon emissions. This allows AI assistants to perform real-time carbon calculations and provide climate impact insights.
- [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp (⭐ 24, ⏰ 2025-07-07)​‌‍) 🐍 ☁️ - [TickTick](https://ticktick.com/) MCP server. Built upon the ticktick-py library, it offers significantly improved filtering capabilities.
- [jimfilippou/things-mcp](https://github.com/jimfilippou/things-mcp (⭐ 1, ⏰ 2025-07-09)​‌‍) 📇 🏠 🍎 - A Model Context Protocol (MCP) server that provides seamless integration with the [Things](https://culturedcode.com/things/) productivity app. This server enables AI assistants to create, update, and manage your todos and projects in Things using its comprehensive URL scheme.
- [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp (⭐ 50, ⏰ 2025-07-06)​‌‍) 🐍 🏠 - MCP server for Typst, a markup-based typesetting system. It provides tools for converting between LaTeX and Typst, validating Typst syntax, and generating images from Typst code.
- [joshuarileydev/mac-apps-launcher-mcp-server](https://github.com/JoshuaRileyDev/mac-apps-launcher (⭐ 13, ⏰ 2025-07-03)​‌‍) 📇 🏠 - An MCP server to list and launch applications on MacOS
- [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro (⭐ 25, ⏰ 2025-07-15)​‌‍) 📇 ☁️ - Miro MCP server, exposing all functionalities available in official Miro SDK
- [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server (⭐ 27, ⏰ 2025-07-06)​‌‍) - 🏎️ 🏠 This MCP Server will help you to manage projects and issues through [Plane's](https://plane.so) API
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq (⭐ 31, ⏰ 2025-07-16)​‌‍) 🐍 🏠 - Enable interaction (admin operation, message enqueue/dequeue) with RabbitMQ
- [kimtth/mcp-remote-call-ping-pong](https://github.com/kimtth/mcp-remote-call-ping-pong (⭐ 1, ⏰ 2025-04-09)​‌‍) 🐍 🏠 - An experimental and educational app for Ping-pong server demonstrating remote MCP (Model Context Protocol) calls
- [kiwamizamurai/mcp-kibela-server](https://github.com/kiwamizamurai/mcp-kibela-server (⭐ 6, ⏰ 2025-05-26)​‌‍) - 📇 ☁️ Powerfully interact with Kibela API.
- [kj455/mcp-kibela](https://github.com/kj455/mcp-kibela (⭐ 12, ⏰ 2025-05-01)​‌‍) - 📇 ☁️ Allows AI models to interact with [Kibela](https://kibe.la/)
- [Klavis-AI/YouTube](https://github.com/Klavis-AI/klavis/tree/main/mcp_servers/youtube) 🐍 📇 - Extract and convert YouTube video information.
- [KS-GEN-AI/confluence-mcp-server](https://github.com/KS-GEN-AI/confluence-mcp-server (⭐ 11, ⏰ 2025-06-10)​‌‍) 📇 ☁️ 🍎 🪟 - Get Confluence data via CQL and read pages.
- [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server (⭐ 24, ⏰ 2025-07-11)​‌‍) 📇 ☁️ 🍎 🪟 - Read jira data via JQL and api and execute requests to create and edit tickets.
- [kw510/strava-mcp](https://github.com/kw510/strava-mcp (⭐ 15, ⏰ 2025-07-06)​‌‍) 📇 ☁️ - An MCP server for Strava, an app for tracking physical exercise
- [louiscklaw/hko-mcp](https://github.com/louiscklaw/hko-mcp (⭐ 1, ⏰ 2025-05-01)​‌‍) 📇 🏠 - MCP server with basic demonstration of getting weather from Hong Kong Observatory
- [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy (⭐ 14, ⏰ 2025-07-12)​‌‍) 📇 ☁️ - Search and retrieve GIFs from Giphy's vast library through the Giphy API.
- [marcelmarais/Spotify](https://github.com/marcelmarais/spotify-mcp-server (⭐ 95, ⏰ 2025-07-19)​‌‍) - 📇 🏠 Control Spotify playback and manage playlists.
- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian (⭐ 1509, ⏰ 2025-07-20)​‌‍) 🐍 ☁️ 🏠 - Interacting with Obsidian via REST API
- [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe (⭐ 15306, ⏰ 2025-07-20)​‌‍) - 🎖️ 🦀 🏠 🍎 Local-first system capturing screen/audio with timestamped indexing, SQL/embedding storage, semantic search, LLM-powered history analysis, and event-triggered actions - enables building context-aware AI agents through a NextJS plugin ecosystem.
- [modelcontextprotocol/server-everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) 📇 🏠 - MCP server that exercises all the features of the MCP protocol
- [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp (⭐ 68, ⏰ 2025-07-19)​‌‍) 🏎️ 🏠 - Token-efficient Go documentation server that provides AI assistants with smart access to package docs and types without reading entire source files
- [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot (⭐ 37, ⏰ 2025-07-16)​‌‍) 🐍 🏠 - enables AI to fully control and access GUI interactions by providing tools for mouse and keyboard, ideal for general automation, education, and experimentation.
- [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai (⭐ 54, ⏰ 2025-06-30)​‌‍) 📇 ☁️ - Chat with OpenAI's smartest models
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui.git) 🏠 🍎 - MCP server that can execute commands such as keyboard input and mouse movement
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol (⭐ 84, ⏰ 2025-07-11)​‌‍) 🏎️ 🏠 - Some useful tools for developer, almost everything an engineer need: confluence, Jira, Youtube, run script, knowledge base RAG, fetch URL, Manage youtube channel, emails, calendar, gitlab
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp (⭐ 51, ⏰ 2025-07-17)​‌‍) - 🐍 Automatic operation of on-screen GUI.
- [offorte/offorte-mcp-server](https://github.com/offorte/offorte-mcp-server (⭐ 3, ⏰ 2025-07-16)​‌‍) 🎖️ 📇 ☁️ 🍎 🪟 🐧 - The Offorte Proposal Software MCP server enables creation and sending of business proposals.
- [olalonde/mcp-human](https://github.com/olalonde/mcp-human (⭐ 16, ⏰ 2025-07-05)​‌‍) 📇 ☁️ - When your LLM needs human assistance (through AWS Mechanical Turk)
- [orellazi/coda-mcp](https://github.com/orellazri/coda-mcp (⭐ 14, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - MCP server for [Coda](https://coda.io/)
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai (⭐ 69, ⏰ 2025-07-10)​‌‍) 🐍 ☁️ - Query OpenAI models directly from Claude using MCP protocol
- [pskill9/hn-server](https://github.com/pskill9/hn-server (⭐ 32, ⏰ 2025-07-18)​‌‍) - 📇 ☁️ Parses the HTML content from news.ycombinator.com (Hacker News) and provides structured data for different types of stories (top, new, ask, show, jobs).
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server (⭐ 99, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - An MCP server that prevents cascading errors and scope creep by calling a "Vibe-check" agent to ensure user alignment.
- [pwh-pwh/cal-mcp](https://github.com/pwh-pwh/cal-mcp (⭐ 10, ⏰ 2025-06-16)​‌‍) - An MCP server for Mathematical expression calculation
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp (⭐ 136, ⏰ 2025-07-19)​‌‍) - Chat with any other OpenAI SDK Compatible Chat Completions API, like Perplexity, Groq, xAI and more
- [quarkiverse/mcp-server-jfx](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jfx) ☕ 🏠 - Draw on JavaFX canvas.
- [QuentinCody/shopify-storefront-mcp-server](https://github.com/QuentinCody/shopify-storefront-mcp-server (⭐ 1, ⏰ 2025-06-03)​‌‍) 🐍 ☁️ - Unofficial MCP server that allows AI agents to discover Shopify storefronts and interact with them to fetch products, collections, and other store data through the Storefront API.
- [r-huijts/ethics-check-mcp](https://github.com/r-huijts/ethics-check-mcp (⭐ 0, ⏰ 2025-06-06)​‌‍) 🐍 🏠 - MCP server for comprehensive ethical analysis of AI conversations, detecting bias, harmful content, and providing critical thinking assessments with automated pattern learning
- [rae-api-com/rae-mcp](https://github.com/rae-api-com/rae-mcp (⭐ 2, ⏰ 2025-07-16)​‌‍) - 🏎️ ☁️ 🍎 🪟 🐧 MPC Server to connect your preferred model with https://rae-api.com, Roya Academy of Spanish Dictionary
- [Rai220/think-mcp](https://github.com/Rai220/think-mcp (⭐ 50, ⏰ 2025-07-14)​‌‍) 🐍 🏠 - Enhances any agent's reasoning capabilities by integrating the think-tools, as described in [Anthropic's article](https://www.anthropic.com/engineering/claude-think-tool).
- [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp (⭐ 24, ⏰ 2025-07-15)​‌‍) 🐍 🏠 - Allows the AI to read .ged files and genetic data
- [rember/rember-mcp](https://github.com/rember/rember-mcp (⭐ 48, ⏰ 2025-07-16)​‌‍) 📇 🏠 - Create spaced repetition flashcards in [Rember](https://rember.com) to remember anything you learn in your chats.
- [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana (⭐ 89, ⏰ 2025-07-19)​‌‍) - 📇 ☁️ This Model Context Protocol server implementation of Asana allows you to talk to Asana API from MCP Client such as Anthropic's Claude Desktop Application, and many more.
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw/blob/main/src/wcgw/client/mcp_server/Readme.md) 🐍 🏠 - Autonomous shell execution, computer control and coding agent. (Mac)
- [inkbytefo/screenmonitormcp](https://github.com/inkbytefo/screenmonitormcp (⭐ 39, ⏰ 2025-07-20)​‌‍) 🐍 🏠 🍎 🪟 🐧 - Real-time screen analysis, context-aware recording, and UI monitoring MCP server. Supports AI vision, event hooks, and multimodal agent workflows.
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha (⭐ 50, ⏰ 2025-07-18)​‌‍) 🐍 ☁️ - An MCP server for querying wolfram alpha API.
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp (⭐ 75, ⏰ 2025-07-18)​‌‍) 📇 ☁️ - Interact with TikTok videos
- [Shopify/dev-mcp](https://github.com/Shopify/dev-mcp (⭐ 421, ⏰ 2025-07-19)​‌‍) 📇 ☁️ - Model Context Protocol (MCP) server that interacts with Shopify Dev.
- [sirmews/apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp (⭐ 111, ⏰ 2025-07-09)​‌‍) 🐍 🏠 - Allows the AI to read from your local Apple Notes database (macOS only)
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian (⭐ 2490, ⏰ 2025-07-19)​‌‍) 🐍 ☁️ - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server (⭐ 788, ⏰ 2025-07-19)​‌‍) 📇 🏠 - Interacting with Notion API
- [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear (⭐ 92, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🍎 🪟 🐧 - Integrates with Linear project management system
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity (⭐ 74, ⏰ 2025-07-08)​‌‍) 🐍 ☁️ - Interacting with Perplexity API.
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp (⭐ 368, ⏰ 2025-07-16)​‌‍) 📇 🏠 - Access Home Assistant data and control devices (lights, switches, thermostats, etc).
- [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server (⭐ 20, ⏰ 2025-07-17)​‌‍) 🐍 ☁️ - An MCP server for Oura, an app for tracking sleep
- [tqiqbal/mcp-confluence-server](https://github.com/tqiqbal/mcp-confluence-server (⭐ 1, ⏰ 2025-05-17)​‌‍) 🐍 - A Model Context Protocol (MCP) server for interacting with Confluence Data Center via REST API.
- [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp (⭐ 259, ⏰ 2025-07-20)​‌‍) 📇 🏠 🍎 🪟 🐧 - Enables interactive LLM workflows by adding local user prompts and chat capabilities directly into the MCP loop.
- [tumf/web3-mcp](https://github.com/tumf/web3-mcp (⭐ 2, ⏰ 2025-04-19)​‌‍) 🐍 ☁️ - An MCP server implementation wrapping Ankr Advanced API. Access to NFT, token, and blockchain data across multiple chains including Ethereum, BSC, Polygon, Avalanche, and more.
- [ujisati/anki-mcp](https://github.com/ujisati/anki-mcp (⭐ 2, ⏰ 2025-05-16)​‌‍) 🐍 🏠 - Manage your Anki collection with AnkiConnect & MCP
- [UnitVectorY-Labs/mcp-graphql-forge](https://github.com/UnitVectorY-Labs/mcp-graphql-forge (⭐ 1, ⏰ 2025-07-19)​‌‍) 🏎️ ☁️ 🍎 🪟 🐧 - A lightweight, configuration-driven MCP server that exposes curated GraphQL queries as modular tools, enabling intentional API interactions from your agents.
- [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku (⭐ 78, ⏰ 2025-07-18)​‌‍) - ☁️ 🏠 The Wanaku MCP Router is a SSE-based MCP server that provides an extensible routing engine that allows integrating your enterprise systems with AI agents.
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli (⭐ 355, ⏰ 2025-07-19)​‌‍) 📇 🏠 - CLI tool for testing MCP servers
- [ws-mcp](https://github.com/nick1udwig/ws-mcp (⭐ 19, ⏰ 2025-06-18)​‌‍) - Wrap MCP servers with a WebSocket (for use with [kitbitz](https://github.com/nick1udwig/kibitz (⭐ 88, ⏰ 2025-07-15)​‌‍))
- [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp (⭐ 30, ⏰ 2025-07-07)​‌‍) 📇 ☁️ - Allows AI models to interact with [HackMD](https://hackmd.io)
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime (⭐ 18, ⏰ 2025-07-13)​‌‍) - MCP server providing date and time functions in various formats
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager (⭐ 252, ⏰ 2025-07-17)​‌‍) 📇 ☁️ - Simple Web UI to install and manage MCP servers for Claude Desktop App.
- [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify (⭐ 15, ⏰ 2025-07-19)​‌‍) 📇 ☁️ 🏠 - An integration that allows Claude Desktop to interact with Spotify using the Model Context Protocol (MCP).

## Frameworks

> [!NOTE]
> More frameworks, utilities, and other developer tools are available at https://github.com/punkpeye/awesome-mcp-devtools (⭐ 256, ⏰ 2025-07-19)​‌‍

- [FastMCP](https://github.com/jlowin/fastmcp (⭐ 14855, ⏰ 2025-07-20)​‌‍) 🐍 - A high-level framework for building MCP servers in Python
- [FastMCP](https://github.com/punkpeye/fastmcp (⭐ 2158, ⏰ 2025-07-19)​‌‍) 📇 - A high-level framework for building MCP servers in TypeScript

## Tips and Tricks

### Official prompt to inform LLMs how to use MCP

Want to ask Claude about Model Context Protocol?

Create a Project, then add this file to it:

https://modelcontextprotocol.io/llms-full.txt

Now Claude can answer questions about writing MCP servers and how they work

- https://www.reddit.com/r/ClaudeAI/comments/1h3g01r/want_to_ask_claude_about_model_context_protocol/

## Star History

<a href="https://star-history.com/#punkpeye/awesome-mcp-servers&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
 </picture>
</a>

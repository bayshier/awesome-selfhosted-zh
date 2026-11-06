# Awesome-Selfhosted 中文版

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome) [![License: CC-BY-SA-3.0](https://img.shields.io/badge/license-CC--BY--SA--3.0-green.svg)](LICENSE)

**自托管（Self-hosting）** 是指把应用托管和管理在自己的服务器上，而不是使用 [SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) 服务商。

这是一份可以在你自己的服务器上托管的[自由软件](https://zh.wikipedia.org/wiki/自由软件)[网络服务](https://zh.wikipedia.org/wiki/网络服务)与 [Web 应用](https://zh.wikipedia.org/wiki/Web应用)清单。非自由软件收录在 [Non-Free](non-free.md) 页面。

**汉化说明**：本仓库是 [awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) 的非官方简体中文版（CC-BY-SA-3.0）。全部 **1200+ 条软件条目的描述已译为中文**（软件名、链接、许可证标签与 Source Code 链接保持原样）；目录、章节说明与贡献指南均为中文。同步基线：上游 2026-11 快照。翻译由 [@bayshier](https://github.com/bayshier) 组织完成，如有出入以上游英文版为准。

**[HTML 版](https://awesome-selfhosted.net/)（上游官方，英文）** · [上游英文 Markdown 版](https://github.com/awesome-selfhosted/awesome-selfhosted)

参见[贡献指南](#贡献)。

--------------------

## 目录

- [软件](#软件)
  - [分析](#分析)
  - [归档与数字保存](#归档与数字保存)
  - [自动化](#自动化)
  - [备份](#备份)
  - [博客平台](#博客平台)
  - [预订与日程](#预订与日程)
  - [书签与链接分享](#书签与链接分享)
  - [日历与联系人](#日历与联系人)
  - [通信 - 自建通信系统](#通信---自建通信系统)
  - [通信 - 邮件 - 完整方案](#通信---邮件---完整方案)
  - [通信 - 邮件 - 投递代理](#通信---邮件---投递代理)
  - [通信 - 邮件 - 传输代理](#通信---邮件---传输代理)
  - [通信 - 邮件 - 邮件列表与新闻组](#通信---邮件---邮件列表与新闻组)
  - [通信 - 邮件 - Webmail 客户端](#通信---邮件---webmail-客户端)
  - [通信 - IRC](#通信---irc)
  - [通信 - SIP](#通信---sip)
  - [通信 - 社交网络与论坛](#通信---社交网络与论坛)
  - [通信 - 视频会议](#通信---视频会议)
  - [通信 - XMPP - 服务器](#通信---xmpp---服务器)
  - [通信 - XMPP - Web 客户端](#通信---xmpp---web-客户端)
  - [社区支持农业（CSA）](#社区支持农业csa)
  - [会议管理](#会议管理)
  - [内容管理系统（CMS）](#内容管理系统cms)
  - [客户关系管理（CRM）](#客户关系管理crm)
  - [数据库管理](#数据库管理)
  - [DNS](#dns)
  - [文档管理](#文档管理)
  - [文档管理 - 电子书](#文档管理---电子书)
  - [文档管理 - 机构知识库与数字图书馆](#文档管理---机构知识库与数字图书馆)
  - [文档管理 - 集成图书馆系统（ILS）](#文档管理---集成图书馆系统ils)
  - [电子商务](#电子商务)
  - [联邦身份与认证](#联邦身份与认证)
  - [Feed 阅读器](#feed-阅读器)
  - [文件传输与同步](#文件传输与同步)
  - [文件传输 - 单次上传与一次性收发](#文件传输---单次上传与一次性收发)
  - [文件传输 - 对象存储与文件服务器](#文件传输---对象存储与文件服务器)
  - [文件传输 - 基于协议的服务器](#文件传输---基于协议的服务器)
  - [文件传输 - 远程备份](#文件传输---远程备份)
  - [游戏](#游戏)
  - [游戏 - 管理服务器与工具](#游戏---管理服务器与工具)
  - [家养自动化](#家养自动化)
  - [IT 资产管理](#it-资产管理)
  - [身份管理 - 单点登录（SSO）](#身份管理---单点登录sso)
  - [墨水屏自带设备同步](#墨水屏自带设备同步)
  - [库存与供应链管理](#库存与供应链管理)
  - [投资](#投资)
  - [知识管理工具](#知识管理工具)
  - [知识管理工具 - 维基](#知识管理工具---维基)
  - [制造](#制造)
  - [地图与 GPS](#地图与-gps)
  - [媒体流 - 音频流](#媒体流---音频流)
  - [媒体流 - 多媒体流](#媒体流---多媒体流)
  - [媒体流 - 视频与电影流](#媒体流---视频与电影流)
  - [媒体流 - 电子书与有声书](#媒体流---电子书与有声书)
  - [媒体流 - 漫画与电子漫画](#媒体流---漫画与电子漫画)
  - [媒体流 - 照片库](#媒体流---照片库)
  - [杂项](#杂项)
  - [货币、预算与管理](#货币预算与管理)
  - [监控](#监控)
  - [笔记与编辑器](#笔记与编辑器)
  - [办公套件](#办公套件)
  - [密码管理器](#密码管理器)
  - [点对点文件共享](#点对点文件共享)
  - [点对点文件共享 - 对象存储](#点对点文件共享---对象存储)
  - [点对点文件共享 - Web 客户端](#点对点文件共享---web-客户端)
  - [个人云存储](#个人云存储)
  - [摄影与拍照应用](#摄影与拍照应用)
  - [轮询与投票](#轮询与投票)
  - [代理](#代理)
  - [食谱管理与餐饮](#食谱管理与餐饮)
  - [远程访问](#远程访问)
  - [资源规划](#资源规划)
  - [搜索引擎](#搜索引擎)
  - [软件打包](#软件打包)
  - [任务管理与待办清单](#任务管理与待办清单)
  - [工单与票务](#工单与票务)
  - [时间追踪](#时间追踪)
  - [翻译管理](#翻译管理)
  - [视频与流媒体](#视频与流媒体)
  - [虚拟化](#虚拟化)
  - [VPN](#vpn)
  - [Web 服务器](#web-服务器)
  - [Wikis](#wikis)
- [清单](#清单)
- [许可证列表](#许可证列表)
- [反特性](#反特性)
- [外部链接](#外部链接)
- [贡献](#贡献)
- [许可证](#许可证-1)

--------------------


## Table of contents

- [Software](#software)
  - [Analytics](#analytics)
  - [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)
  - [Automation](#automation)
  - [Backup](#backup)
  - [Blogging Platforms](#blogging-platforms)
  - [Booking and Scheduling](#booking-and-scheduling)
  - [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)
  - [Calendar & Contacts](#calendar--contacts)
  - [Communication - Custom Communication Systems](#communication---custom-communication-systems)
  - [Communication - Email - Complete Solutions](#communication---email---complete-solutions)
  - [Communication - Email - Mail Delivery Agents](#communication---email---mail-delivery-agents)
  - [Communication - Email - Mail Transfer Agents](#communication---email---mail-transfer-agents)
  - [Communication - Email - Mailing Lists and Newsletters](#communication---email---mailing-lists-and-newsletters)
  - [Communication - Email - Webmail Clients](#communication---email---webmail-clients)
  - [Communication - IRC](#communication---irc)
  - [Communication - SIP](#communication---sip)
  - [Communication - Social Networks and Forums](#communication---social-networks-and-forums)
  - [Communication - Video Conferencing](#communication---video-conferencing)
  - [Communication - XMPP - Servers](#communication---xmpp---servers)
  - [Communication - XMPP - Web Clients](#communication---xmpp---web-clients)
  - [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)
  - [Conference Management](#conference-management)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
  - [Customer Relationship Management (CRM)](#customer-relationship-management-crm)
  - [Database Management](#database-management)
  - [DNS](#dns)
  - [Document Management](#document-management)
  - [Document Management - E-books](#document-management---e-books)
  - [Document Management - Institutional Repository and Digital Library Software](#document-management---institutional-repository-and-digital-library-software)
  - [Document Management - Integrated Library Systems (ILS)](#document-management---integrated-library-systems-ils)
  - [E-commerce](#e-commerce)
  - [Federated Identity & Authentication](#federated-identity--authentication)
  - [Feed Readers](#feed-readers)
  - [File Transfer & Synchronization](#file-transfer--synchronization)
  - [File Transfer - Distributed Filesystems](#file-transfer---distributed-filesystems)
  - [File Transfer - Object Storage & File Servers](#file-transfer---object-storage--file-servers)
  - [File Transfer - Peer-to-peer Filesharing](#file-transfer---peer-to-peer-filesharing)
  - [File Transfer - Single-click & Drag-n-drop Upload](#file-transfer---single-click--drag-n-drop-upload)
  - [File Transfer - Web-based File Managers](#file-transfer---web-based-file-managers)
  - [Games](#games)
  - [Games - Administrative Utilities & Control Panels](#games---administrative-utilities--control-panels)
  - [Genealogy](#genealogy)
  - [Generative Artificial Intelligence (GenAI)](#generative-artificial-intelligence-genai)
  - [Groupware](#groupware)
  - [Health and Fitness](#health-and-fitness)
  - [Human Resources Management (HRM)](#human-resources-management-hrm)
  - [Identity Management](#identity-management)
  - [Internet of Things (IoT)](#internet-of-things-iot)
  - [Inventory Management](#inventory-management)
  - [Knowledge Management Tools](#knowledge-management-tools)
  - [Learning and Courses](#learning-and-courses)
  - [Manufacturing](#manufacturing)
  - [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)
  - [Media Management](#media-management)
  - [Media Streaming](#media-streaming)
  - [Media Streaming - Audio Streaming](#media-streaming---audio-streaming)
  - [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming)
  - [Media Streaming - Video Streaming](#media-streaming---video-streaming)
  - [Miscellaneous](#miscellaneous)
  - [Money, Budgeting & Management](#money-budgeting--management)
  - [Monitoring & Status Pages](#monitoring--status-pages)
  - [Network Utilities](#network-utilities)
  - [Note-taking & Editors](#note-taking--editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo Galleries](#photo-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Recipe Management](#recipe-management)
  - [Remote Access](#remote-access)
  - [Resource Planning](#resource-planning)
  - [Search Engines](#search-engines)
  - [Self-hosting Solutions](#self-hosting-solutions)
  - [Software Development](#software-development)
  - [Software Development - API Management](#software-development---api-management)
  - [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment)
  - [Software Development - FaaS & Serverless](#software-development---faas--serverless)
  - [Software Development - Feature Toggle](#software-development---feature-toggle)
  - [Software Development - IDE & Tools](#software-development---ide--tools)
  - [Software Development - Localization](#software-development---localization)
  - [Software Development - Low Code](#software-development---low-code)
  - [Software Development - Project Management](#software-development---project-management)
  - [Software Development - Testing](#software-development---testing)
  - [Static Site Generators](#static-site-generators)
  - [Task Management & To-do Lists](#task-management--to-do-lists)
  - [Ticketing](#ticketing)
  - [Time Tracking](#time-tracking)
  - [Travel Organization](#travel-organization)
  - [URL Shorteners](#url-shorteners)
  - [Video Surveillance](#video-surveillance)
  - [VPN](#vpn)
  - [Web Servers](#web-servers)
  - [Wikis](#wikis)
- [List of Licenses](#list-of-licenses)
- [Anti-features](#anti-features)
- [External Links](#external-links)
- [Contributing](#contributing)
- [License](#license)

--------------------

## 软件

### 分析

**[`^        back to top        ^`](#awesome-selfhosted)**

[Analytics](https://en.wikipedia.org/wiki/Analytics) is the systematic computational analysis of data or statistics. It is used for the discovery, interpretation, and communication of meaningful patterns in data.

_Related: [Database Management](#database-management), [Personal Dashboards](#personal-dashboards)_

- [ANALOG](https://github.com/orangecoloured/analog) - 极简分析工具。在 10-30 天的时间跨度内跟踪事件。`MIT` `Nodejs/Docker`
- [Aptabase](https://aptabase.com/) - 为移动和桌面应用提供隐私优先、简洁的分析。 ([Source Code](https://github.com/aptabase/aptabase)) `AGPL-3.0` `Docker`
- [AWStats](http://www.awstats.org/) - 从 Web、流媒体、FTP 或邮件服务器日志文件生成统计数据。 ([Demo](https://www.awstats.org/#DEMO), [Source Code](https://github.com/eldy/awstats)) `GPL-3.0` `Perl`
- [Countly Community Edition](https://count.ly) - 实时移动与 Web 分析、崩溃报告和推送通知平台。 ([Source Code](https://github.com/Countly/countly-server)) `AGPL-3.0` `Nodejs/Docker`
- [d8a.tech](https://d8a.tech) - 数据收集服务，与现有的 Google Analytics 设置协同工作，捕获用户活动并直接发送到你自己的私有数据库。 ([Demo](https://lookerstudio.google.com/u/0/reporting/0e4102b6-c38b-4f55-aa25-c1fe91d1c1e9), [Source Code](https://github.com/d8a-tech/d8a)) `MIT` `Go/Docker`
- [Daily Stars Explorer](https://emanuelef.github.io/daily-stars-explorer) `⚠` - Track GitHub repo trends with daily star insights to see growth and community interest over time. ([Demo](https://emanuelef.github.io/daily-stars-explorer), [Source Code](https://github.com/emanuelef/daily-stars-explorer)) `MIT` `Go/Nodejs/Docker`
- [Dreeve](https://dreeve.app/) `⚠` - Statistics dashboard generated from Strava data. ([Demo](https://statistics-for-strava.robiningelbrecht.be/), [Source Code](https://github.com/dreeveapp/dreeve)) `AGPL-3.0` `Docker/K8S`
- [Druid](https://druid.apache.org) - 分布式、面向列的实时分析数据存储。 ([Source Code](https://github.com/apache/druid)) `Apache-2.0` `Java/Docker`
- [EDA](https://github.com/jortilles/EDA) - 用于数据分析和可视化的 Web 应用。`AGPL-3.0` `Nodejs/Docker`
- [GoAccess](http://goaccess.io/) - 在终端中运行的实时 Web 日志分析器和交互式查看器。 ([Source Code](https://github.com/allinurl/goaccess)) `GPL-2.0` `C`
- [GoatCounter](https://www.goatcounter.com) - 简单易用的网站统计，不跟踪个人数据。 ([Source Code](https://github.com/arp242/goatcounter)) `EUPL-1.2` `Go`
- [HitKeep](https://hitkeep.com/) - 隐私优先的 Web 分析，支持目标、漏斗、电商跟踪和团队管理，采用内嵌 DuckDB 的单一二进制文件（Google Analytics、Plausible、Umami 的替代品）。 ([Source Code](https://github.com/HitKeep/hitkeep)) `MIT` `Go/Docker`
- [Litlyx](https://litlyx.com) - 一体化分析解决方案。30 秒完成设置。在 AI 驱动的仪表板上展示你的所有数据。完全可自托管且符合 GDPR。 ([Source Code](https://github.com/Litlyx/litlyx)) `Apache-2.0` `Docker`
- [Liwan](https://liwan.dev/) - 隐私优先的 Web 分析。 ([Demo](https://demo.liwan.dev/p/liwan.dev), [Source Code](https://github.com/explodingcamera/liwan)) `Apache-2.0` `Rust/Docker`
- [Matomo](https://matomo.org/) - 保护你的数据和客户隐私的 Web 分析（Google Analytics 的替代品）。 ([Source Code](https://github.com/matomo-org/matomo)) `GPL-3.0` `PHP`
- [Metabase](https://metabase.com/) - 让公司里的每个人都能轻松提问并从数据中学习的简单方式。 ([Source Code](https://github.com/metabase/metabase)) `AGPL-3.0` `Java/Docker`
- [Middleware](https://middlewarehq.com/) - 帮助工程领导者使用 DORA 指标衡量和分析团队效能的工具。 ([Source Code](https://github.com/middlewarehq/middleware)) `Apache-2.0` `Docker/Python/Nodejs`
- [Netron](https://netron.app/) - 神经网络和机器学习模型的可视化工具。 ([Source Code](https://github.com/lutzroeder/netron)) `MIT` `Python/Nodejs`
- [Offen](https://www.offen.dev/) - 公平、轻量且开放的 Web 分析工具。在获取洞见的同时，你的用户可以完全访问自己的数据。 ([Demo](https://www.offen.dev/try-demo/), [Source Code](https://github.com/offen/offen)) `Apache-2.0` `Go/Docker`
- [Plausible Analytics](https://plausible.io/) - 简洁、轻量（< 1 KB）且注重隐私的 Web 分析。 ([Source Code](https://github.com/plausible/analytics/)) `AGPL-3.0` `Elixir`
- [PostHog](https://posthog.com) - 可自托管的产品分析、会话录制、功能开关和 a/b 测试（Mixpanel、Amplitude、Heap 的替代品）。 ([Source Code](https://github.com/posthog/posthog)) `MIT` `Python`
- [Postiz](https://postiz.com) `⚠` - Schedule posts, track the performance of your content, and manage all your social media accounts in one place (alternative to Buffer, Hootsuite, Sprout Social). ([Source Code](https://github.com/gitroomhq/postiz-app)) `AGPL-3.0` `Docker`
- [Prisme Analytics](https://www.prismeanalytics.com) - 基于 Grafana、注重隐私的渐进式分析服务。 ([Source Code](https://github.com/prismelabs/analytics)) `AGPL-3.0/MIT` `Docker`
- [Redash](http://redash.io) - 连接并查询你的数据源，构建仪表板来可视化数据并与公司共享。 ([Source Code](https://github.com/getredash/redash)) `BSD-2-Clause` `Docker`
- [Rybbit](https://rybbit.com/) - 易于设置且更直观的 Web 和产品分析（Google Analytics 的替代品）。 ([Demo](https://demo.rybbit.com/1), [Source Code](https://github.com/rybbit-io/rybbit)) `AGPL-3.0` `Docker`
- [Shaper](https://taleshape.com/shaper/docs) - 全部用 SQL 构建数据仪表板。由 DuckDB 驱动。 ([Demo](https://demo.taleshape.com/view/pvggvdpiwb9wlyppuqbyx0nt), [Source Code](https://github.com/taleshape-com/shaper)) `MPL-2.0` `Docker/Nodejs/Python/Go`
- [Socioboard](https://github.com/Socioboard-developers/Socioboard-5.0) `⚠` - Social media management, analytics, and reporting platform supporting nine social media networks out-of-the-box. `GPL-3.0` `Nodejs`
- [Superset](http://superset.apache.org/) - 现代化的数据探索与可视化平台。 ([Source Code](https://github.com/apache/superset)) `Apache-2.0` `Python`
- [Swetrix](https://swetrix.com/) - 跟踪网站流量、监控网站速度、分析用户会话和页面流、查看用户流程等的 Web 分析（Google Analytics 的替代品）。 ([Demo](https://swetrix.com/projects/STEzHcB1rALV), [Source Code](https://github.com/Swetrix/selfhosting)) `AGPL-3.0` `Docker`
- [Umami](https://umami.is/) - 简单、快速、注重隐私（Google Analytics 的替代品）。 ([Demo](https://cloud.umami.is/share/LGazGOecbDtaIwDr), [Source Code](https://github.com/umami-software/umami)) `MIT` `Nodejs/Docker`


### 归档与数字保存

**[`^        back to top        ^`](#awesome-selfhosted)**

Digital [archiving](https://en.wikipedia.org/wiki/Archival_science) and [preservation](https://en.wikipedia.org/wiki/Digital_preservation) software.

_Related: [Backup](#backup), [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: [awesome-web-archiving](https://github.com/iipc/awesome-web-archiving)_

- [ArchiveBox](https://archivebox.io/) - 从书签、浏览历史、RSS 订阅源或其他来源创建网站的 HTML 和截图存档（Wayback Machine 的替代品）。 ([Source Code](https://github.com/ArchiveBox/ArchiveBox)) `MIT` `Python/Docker`
- [ArchivesSpace](https://archivesspace.org/) - 档案信息管理应用程序，用于管理档案、手稿和数字对象并提供 Web 访问。 ([Demo](https://archivesspace.org/application/sandbox), [Source Code](https://github.com/archivesspace/archivesspace)) `ECL-2.0` `Ruby`
- [Bichon](https://github.com/rustmailer/bichon) - 邮件归档服务器，从 IMAP 账户同步、为邮件建立全文搜索索引，并提供 REST API。无需外部数据库，包含支持多账户的 WebUI。`AGPL-3.0` `Rust/Docker`
- [bitmagnet](https://bitmagnet.io) - BitTorrent 索引器、DHT 爬虫、内容分类器和种子搜索引擎，具有 Web UI、GraphQL API 和 Servarr 套件集成。 ([Source Code](https://github.com/bitmagnet-io/bitmagnet)) `MIT` `Go/Docker`
- [CKAN](https://ckan.org) - 制作开放数据网站。 ([Source Code](https://github.com/ckan/ckan)) `AGPL-3.0` `Python`
- [Collective Access - Providence](https://collectiveaccess.org/) - 高度可配置的基于 Web 的框架，用于管理和描述数字与实体馆藏并支持其检索发现，支持多种元数据标准、数据类型和媒体格式。 ([Source Code](https://github.com/collectiveaccess/providence)) `GPL-3.0` `PHP`
- [Eonvelope](https://dacid99.gitlab.io/eonvelope) - 邮件归档软件，可让你无限期地长期保存电子邮件。 ([Source Code](https://gitlab.com/dacid99/eonvelope)) `AGPL-3.0` `K8S/Docker`
- [Ganymede](https://github.com/Zibbp/ganymede) `⚠` - Twitch VOD and live stream archiving platform. Includes a rendered chat for each archive. `GPL-3.0` `Docker`
- [mail-archiver](https://github.com/s1t5/mail-archiver) - 用于从多个账户（IMAP、M365 或导入）归档、搜索和导出电子邮件的 Web 应用。具备文件夹同步、附件支持、邮箱迁移和仪表板等功能。`GPL-3.0` `Docker`
- [Omeka S](https://omeka.org/s/) - 新一代 Web 发布平台，面向希望将数字文化遗产馆藏与在线其他资源相连接的机构。 ([Source Code](https://github.com/omeka/omeka-s)) `GPL-3.0` `Nodejs`
- [Open Archiver](https://openarchiver.com/) - 具备全文搜索和 eDiscovery 搜索功能的邮件归档解决方案。 ([Demo](https://github.com/LogicLabs-OU/OpenArchiver?tab=readme-ov-file#-live-demo), [Source Code](https://github.com/LogicLabs-OU/OpenArchiver)) `AGPL-3.0` `Docker`
- [Piler](https://www.mailpiler.org/) - 功能丰富的邮件归档解决方案。 ([Source Code](https://github.com/jsuto/piler/)) `GPL-3.0` `C/Docker/deb`
- [Wallabag](https://www.wallabag.org) - Web 应用，前身为 Poche，让你保存文章以便稍后阅读，并优化阅读体验。 ([Source Code](https://github.com/wallabag/wallabag)) `MIT` `PHP`
- [Wayback](https://github.com/wabarc/wayback) - 将网页归档到 Internet Archive、archive.today、IPFS 和本地文件系统的工具包。`GPL-3.0` `Go`


### 自动化

**[`^        back to top        ^`](#awesome-selfhosted)**

[Automation](https://en.wikipedia.org/wiki/Automation) software designed to reduce human intervention in processes.

_Related: [Internet of Things (IoT)](#internet-of-things-iot), [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment), [Media Management](#media-management)_

- [Activepieces](https://www.activepieces.com) - 类似 Zapier 或 Tray 的无代码业务自动化工具。例如，你可以为每张新的 Trello 卡片发送一条 Slack 通知。 ([Source Code](https://github.com/activepieces/activepieces)) `MIT` `Docker`
- [Apache Airflow](https://airflow.apache.org/) - 以编程方式编写、调度和监控工作流的平台。 ([Source Code](https://github.com/apache/airflow/)) `Apache-2.0` `Python/Docker`
- [Automatisch](https://automatisch.io) - 业务自动化工具，让你连接 Twitter、Slack 等不同服务来自动化你的业务流程（Zapier 的替代品）。 ([Source Code](https://github.com/automatisch/automatisch)) `AGPL-3.0` `Docker`
- [BookBounty](https://github.com/TheWicklowWolf/BookBounty) `⚠` - Retrieve missing Readarr books from Library Genesis. `MPL-2.0` `Docker`
- [changedetection.io](https://changedetection.io/) - 及时了解网站内容的变化。 ([Source Code](https://github.com/dgtlmoon/changedetection.io)) `Apache-2.0` `Python/Docker`
- [ChiefOnboarding](https://chiefonboarding.com) - 员工入职平台，让你能够开通用户账户，并创建包含待办事项、资源、短信/电子邮件/Slack 消息等的入职序列！可作为 Web 门户和 Slack 机器人使用。 ([Source Code](https://github.com/chiefonboarding/ChiefOnboarding)) `AGPL-3.0` `Docker`
- [Cronicle](https://cronicle.net/) - 简洁的分布式任务调度器和执行器，带有基于 Web 的 UI。 ([Source Code](https://github.com/jhuckaby/Cronicle)) `MIT` `Nodejs`
- [Cronmaster](https://github.com/fccview/cronmaster) - Cronjob 管理 UI，为你的定时任务提供人类可读的语法、实时日志和日志历史。`AGPL-3.0` `Docker`
- [Dagu](https://docs.dagu.cloud/) - 功能强大的 Cron 替代品，带有 Web UI。它允许你以声明式 YAML 格式将命令之间的依赖关系定义为有向无环图（DAG）。 ([Source Code](https://github.com/dagucloud/dagu)) `GPL-3.0` `Go/Docker`
- [Discount Bandit](https://discount-bandit.cybrarist.com/) `⚠` - Track pricing, stock status of products across multiple stores such as Amazon, Ebay, Walmart, etc. ([Source Code](https://github.com/Cybrarist/Discount-Bandit)) `GPL-3.0` `PHP/Docker`
- [Dittofeed](https://www.dittofeed.com) - 全渠道客户互动与消息自动化平台（Braze、Customer.io、Iterable 的替代品）。 ([Demo](https://demo.dittofeed.com/dashboard/journeys), [Source Code](https://github.com/dittofeed/dittofeed)) `MIT` `Docker`
- [flowctl](https://flowctl.net) - 自助式工作流执行平台，支持审批、远程执行和调度。 ([Demo](https://demo.flowctl.net), [Source Code](https://github.com/cvhariharan/flowctl)) `Apache-2.0` `Go/Docker`
- [Fredy](https://fredy.orange-coding.net/) `⚠` - Searches for new apartments, houses, and flats in Germany on platforms like ImmoScout24, Immowelt, and others, and instantly delivers the results to you via Slack, Telegram, and more. ([Demo](https://fredy-demo.orange-coding.net), [Source Code](https://github.com/orangecoding/fredy)) `Apache-2.0` `Nodejs/Docker`
- [gocron](https://github.com/flohoss/gocron) - 任务调度器，允许用户通过简单的 YAML 配置文件指定周期性任务。`MIT` `Docker`
- [HandBrake Web](https://github.com/TheNickOfTime/handbrake-web) - 通过 Web 界面在无头设备上使用一个或多个 HandBrake 视频转码器实例。`AGPL-3.0` `Docker`
- [Healthchecks](https://healthchecks.io/) - 监听 ping，并在 ping 延迟时发送警报。 ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD-3-Clause` `Python/Docker`
- [Huginn](https://github.com/huginn/huginn) - 构建代表你进行监控和执行操作的代理。`MIT` `Ruby`
- [Kestra](https://kestra.io) - 事件驱动、语言无关的工作流创建、调度和监控平台，一切皆在代码中。可协调 ETL、ELT 等数据管道和任务。 ([Source Code](https://github.com/kestra-io/kestra)) `Apache-2.0` `Docker`
- [Kibitzr](https://kibitzr.github.io) - 轻量的个人 Web 助手，具备强大的集成能力。 ([Source Code](https://github.com/kibitzr/kibitzr)) `MIT` `Python`
- [LazyLibrarian](https://gitlab.com/LazyLibrarian/LazyLibrarian) `⚠` - Follow authors and grab metadata for all your digital reading needs. It uses a combination of Goodreads, Librarything and optionally GoogleBooks as sources for author info and book info. `GPL-3.0` `Python`
- [Leon](https://getleon.ai) - 可以生活在你服务器上的私人助理。 ([Source Code](https://github.com/leon-ai/leon)) `MIT` `Nodejs`
- [Matchering](https://github.com/sergree/matchering) - 自动化音乐母带处理（LANDR、eMastered 和 MajorDecibel 的替代品）。`GPL-3.0` `Docker`
- [Mylar3](https://mylar.nerdfirehurricane.com/) - 自动化漫画书（cbr/cbz）下载程序，可与 NZB 和种子配合使用。 ([Source Code](https://github.com/MylarComics/mylar3)) `GPL-3.0` `Python/Docker`
- [OliveTin](https://www.olivetin.app/) - 用于运行 Linux shell 命令的 Web 界面。 ([Source Code](https://github.com/OliveTin/OliveTin)) `AGPL-3.0` `Go`
- [pyLoad](https://pyload.net/) - 轻量、可定制且可远程管理的下载器，适用于 rapidshare.com 或 uploaded.to 等一键托管网站。 ([Source Code](https://github.com/pyload/pyload)) `AGPL-3.0` `Python`
- [StackStorm](https://stackstorm.com) - StackStorm（又称运维版 IFTTT）是事件驱动的自动化平台，用于自动修复、安全响应、故障排查、部署等。包含规则引擎、工作流、160 个集成包（含 6000+ 操作）和 ChatOps。 ([Source Code](https://github.com/StackStorm/st2)) `Apache-2.0` `Python`
- [µTask](https://github.com/ovh/utask) - 对以 YAML 声明的业务流程进行建模并执行的自动化引擎。`BSD-3-Clause` `Go/Docker`


### Backup

**[`^        back to top        ^`](#awesome-selfhosted)**

[Backup](https://en.wikipedia.org/wiki/Backup) software.

**Please visit [awesome-sysadmin/Backups](https://github.com/awesome-foss/awesome-sysadmin#backups)**

_Related: [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)_



### 博客平台

**[`^        back to top        ^`](#awesome-selfhosted)**

A [blog](https://en.wikipedia.org/wiki/Blog) is a discussion or informational website consisting of discrete, diary-style text entries (posts).

_Related: [Static Site Generators](#static-site-generators), [Content Management Systems (CMS)](#content-management-systems-cms)_

_See also: [WeblogMatrix](https://www.weblogmatrix.org/)_

- [Antville](https://antville.org) - 功能丰富的博客托管软件，可托管数以万计的博客。 ([Source Code](https://github.com/antville/antville)) `Apache-2.0` `Javascript`
- [bloglite](https://github.com/rikhuijzer/bloglite) - 微博客工具，提供内置语法高亮、移动发布等功能（Twitter、Bluesky 的替代品）。`MIT` `Docker`
- [Chyrp Lite](https://chyrplite.net) - 超赞且超轻量的博客引擎。 ([Source Code](https://github.com/xenocrat/chyrp-lite)) `BSD-3-Clause` `PHP`
- [Dotclear](https://git.dotclear.org/dev/dotclear) - 完全掌控你的博客。`GPL-2.0` `PHP`
- [Ech0](https://ech0.app/) - 轻量的联邦式发布平台，专注于个人想法分享（文档为中文）。 ([Demo](https://memo.vaaat.com/), [Source Code](https://github.com/lin-snow/Ech0)) `AGPL-3.0` `Docker/K8S`
- [FlatPress](https://flatpress.org/) - 轻量、易于搭建的纯文件博客引擎。 ([Source Code](https://github.com/flatpressblog/flatpress)) `GPL-2.0` `PHP`
- [Ghost](https://ghost.org/) - 就是一个博客平台。 ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
- [Haven](https://havenweb.org/) - 私有博客系统，具有 Markdown 编辑和内置 RSS 阅读器。 ([Demo](https://havenweb.org/demo.html), [Source Code](https://github.com/havenweb/haven)) `MIT` `Ruby`
- [HTMLy](https://www.htmly.com/) - 无数据库的 PHP 博客平台。一个纯文件 CMS，让你在几秒内创建快速、安全且强大的网站或博客。 ([Demo](http://demo.htmly.com/), [Source Code](https://github.com/danpros/htmly)) `GPL-2.0` `PHP`
- [Known](https://withknown.com/) - 协作式社交发布平台。 ([Source Code](https://github.com/idno/idno)) `Apache-2.0` `PHP`
- [Mataroa](https://mataroa.blog/) - 为极简主义者打造的极简博客平台。 ([Source Code](https://github.com/mataroablog/mataroa)) `MIT` `Python`
- [PluXml](https://pluxml.org) - 基于 XML 的博客/CMS 平台。 ([Source Code](https://github.com/pluxml/PluXml)) `GPL-3.0` `PHP`
- [Serendipity](https://docs.s9y.org/) - 使用 Smarty 模板的高度可扩展、可定制的 PHP 博客引擎（s9y）。 ([Source Code](https://github.com/s9y/serendipity)) `BSD-3-Clause` `PHP`
- [WriteFreely](https://writefreely.org) - 写作软件，用于开启一个极简的联邦式博客——或一整个社区。 ([Source Code](https://github.com/writefreely/writefreely)) `AGPL-3.0` `Go`


### 预订与日程

**[`^        back to top        ^`](#awesome-selfhosted)**

Event scheduling, reservation, and appointment management software.

_Related: [Polls and Events](#polls-and-events), [Groupware](#groupware)_

- [Alf.io](https://alf.io/) - 票务预订系统。 ([Demo](https://demo.alf.io/authentication), [Source Code](https://github.com/alfio-event/alf.io)) `GPL-3.0` `Java`
- [Cal.diy](https://cal.diy/) - 在线预约排期系统。 ([Source Code](https://github.com/calcom/cal.diy)) `MIT` `Nodejs`
- [Chobble Tickets](https://tickets.chobble.com) - 活动票务系统，支持二维码签到和加密的参与者记录。完整产品采用 AGPL-3.0，无开放核心、无品牌标识要求，可作为边缘脚本运行而无需常驻服务器（Eventbrite 的替代品）。 ([Demo](https://tickets.crumpsallfolkclub.co.uk), [Source Code](https://github.com/chobbledotcom/tickets)) `AGPL-3.0` `Deno/Docker`
- [Easy!Appointments](https://easyappointments.org/) - 让你的客户通过 Web 与你预约。 ([Demo](https://demo.easyappointments.org/), [Source Code](https://github.com/alextselegidis/easyappointments)) `GPL-3.0` `PHP`
- [Hi.Events](https://hi.events) - 面向会议、演唱会等活动的管理和票务平台。提供可自定义的活动页面和可嵌入的票务小组件。 ([Demo](https://demo.hi.events/event/1/dog-conf-2030), [Source Code](https://github.com/HiEventsDev/hi.events)) `AGPL-3.0` `Docker`
- [LibreBooking](https://librebooking.readthedocs.io/) - 资源调度解决方案，为组织提供灵活、移动友好且可扩展的界面来管理资源预订。 ([Demo](https://librebooking-demo.fly.dev/), [Source Code](https://github.com/LibreBooking/librebooking)) `GPL-3.0` `PHP/Docker`
- [QloApps](https://qloapps.com/) - 可定制且直观的基于 Web 的酒店预订系统和预订引擎。 ([Demo](https://demo.qloapps.com/), [Source Code](https://github.com/Qloapps/QloApps)) `OSL-3.0` `PHP/Nodejs`
- [Rallly](https://rallly.co) - 创建投票来对日期和时间进行表决（Doodle 的替代品）。 ([Demo](https://app.rallly.co), [Source Code](https://github.com/lukevella/rallly)) `AGPL-3.0` `Nodejs/Docker`
- [Seatsurfing](https://seatsurfing.app/) - 用于办公室座位、工位和房间预订的 Web 应用。 ([Source Code](https://github.com/seatsurfing/seatsurfing)) `GPL-3.0` `Docker`


### 书签与链接分享

**[`^        back to top        ^`](#awesome-selfhosted)**

Software which allows users to add, annotate, edit, and share [bookmarks](https://en.wikipedia.org/wiki/Bookmark_(digital)) of web documents.

_Related: [Personal Dashboards](#personal-dashboards)_

- [Betula](https://joinbetula.org) - 单用户联邦式书签管理器，支持 Fediverse 并具备归档功能。 ([Source Code](https://codeberg.org/bouncepaw/betula)) `AGPL-3.0` `Go`
- [Buku](https://github.com/jarun/Buku) - 强大的书签管理器和个人文字迷你网站。`GPL-3.0` `Python/deb`
- [Digibunch](https://ladigitale.dev/digibunch/#/) - 创建成组的链接，与你的学员或同事分享。 ([Demo](https://ladigitale.dev/digibunch/#/b/5f67b12092b60), [Source Code](https://codeberg.org/ladigitale/digibunch)) `AGPL-3.0` `Nodejs/PHP`
- [Espial](https://github.com/jonschoning/espial) - 支持多用户账户的基于 Web 的书签服务器。`AGPL-3.0` `Haskell`
- [Faved](https://faved.to/) - 精心打造的书签管理器，结合强大的标签、即时搜索和整洁无干扰的界面。为大型收藏和高级工作流而构建，针对效率与易用性进行了优化。 ([Demo](https://demo.faved.to/), [Source Code](https://github.com/denho/faved)) `MIT` `Docker`
- [Firefox Account Server](https://mozilla-services.readthedocs.io/en/latest/howtos/run-fxa.html) - 托管你自己的 Firefox 账户服务器。 ([Source Code](https://github.com/mozilla/fxa)) `MPL-2.0` `Nodejs/Java`
- [Karakeep](https://karakeep.app/) - 面向数据囤积者的万物皆可收藏的书签应用，带有一点 AI 加持。 ([Demo](https://try.karakeep.app/signin), [Source Code](https://github.com/karakeep-app/karakeep)) `AGPL-3.0` `Docker`
- [LinkAce](https://www.linkace.org/) - 书签存档工具，支持自动备份到 Internet Archive、链接监控和完整的 REST API。可通过 Docker 安装，也可作为简单的 PHP 应用运行。 ([Demo](https://demo.linkace.org/guest/links), [Source Code](https://github.com/Kovah/LinkAce/)) `GPL-3.0` `Docker/PHP`
- [linkding](https://linkding.link/) - 极简书签管理，拥有快速整洁的 UI。通过 Docker 即可轻松安装，并可在你的 Raspberry Pi 上运行。 ([Demo](https://demo.linkding.link/login/), [Source Code](https://github.com/sissbruecker/linkding)) `MIT` `Docker`
- [LinkWarden](https://linkwarden.app/) - 用于存储实用链接的书签和存档管理器。 ([Source Code](https://github.com/linkwarden/linkwarden)) `MIT` `Docker/Nodejs`
- [NeonLink](https://github.com/AlexSciFier/neonlink) - 设计独特、可通过 Docker 轻松安装的书签服务。`MIT` `Docker`
- [Readeck](https://readeck.org/en/) - 保存你喜欢并想永久保留的网页宝贵可读内容。可以把它看作书签管理器和稍后阅读工具。 ([Source Code](https://codeberg.org/readeck/readeck), [Clients](https://codeberg.org/readeck/browser-extension)) `AGPL-3.0` `Go/Docker`
- [Servas](https://github.com/beromir/Servas) - 书签管理工具。支持用标签、分组和一个专供稍后访问的列表来整理书签。支持带 2FA 的多用户。Firefox 和 Chrome 有配套浏览器扩展。 ([Clients](https://github.com/beromir/Servas#browser-extensions)) `GPL-3.0` `Docker/Nodejs/PHP`
- [Shaarli](https://github.com/shaarli/Shaarli) - 个人化、极简、超快、无数据库的书签和链接分享平台。 ([Demo](https://demo.shaarli.org)) `Zlib` `PHP/deb`
- [Shiori](https://github.com/go-shiori/shiori) - 用 Go 构建的简洁书签管理器。`MIT` `Go/Docker`
- [Slash](https://github.com/yourselfhosted/slash) - 书签和链接分享平台。`GPL-3.0` `Docker`
- [SyncMarks](https://codeberg.org/Offerel/SyncMarks-Webapp) - 同步和管理来自 Edge、Firefox 与 Chromium 的浏览器书签。 ([Clients](https://codeberg.org/Offerel/SyncMarks-Extension)) `AGPL-3.0` `PHP`


### 日历与联系人

**[`^        back to top        ^`](#awesome-selfhosted)**

[CalDAV](https://en.wikipedia.org/wiki/CalDAV) and [CardDAV](https://en.wikipedia.org/wiki/CardDAV) protocol servers and web clients/interfaces for [Electronic calendar](https://en.wikipedia.org/wiki/Calendaring_software), [address book](https://en.wikipedia.org/wiki/Address_book) and [contact management](https://en.wikipedia.org/wiki/Contact_manager).

_Related: [Groupware](#groupware)_

- [Baïkal](https://sabre.io/baikal/) - 基于 sabre/dav 的轻量 CalDAV 和 CardDAV 服务器。 ([Source Code](https://github.com/sabre-io/Baikal)) `GPL-3.0` `PHP`
- [DAViCal](https://www.davical.org/) - 日历共享（CalDAV）服务器，使用 PostgreSQL 数据库作为数据存储。 ([Source Code](https://gitlab.com/davical-project/davical)) `GPL-2.0` `PHP/deb`
- [Davis](https://github.com/tchapi/davis) - 为 sabre/dav 打造的简洁、可 Docker 化且完全可翻译的管理界面，基于 Symfony 5 和 Bootstrap 4，很大程度上受 Baïkal 启发。`MIT` `PHP`
- [Keeper.sh](https://keeper.sh/) - 日历同步工具，通过 iCal/ICS 或 OAuth 在日历源和目标之间拉取和推送事件，支持匿名化的忙/闲事件。 ([Source Code](https://github.com/ridafkih/keeper.sh)) `AGPL-3.0` `Docker`
- [Manage My Damn Life](https://intri.in/manage-my-damn-life/) - Manage my Damn Life (MMDL) 是一个用于管理 CalDAV 任务和日历的前端。 ([Source Code](https://github.com/intri-in/manage-my-damn-life-nextjs)) `GPL-3.0` `Nodejs/Docker`
- [Radicale](https://radicale.org/) - 简单的日历和联系人服务器，管理开销极低。 ([Source Code](https://github.com/Kozea/Radicale)) `GPL-3.0` `Python/deb`
- [SabreDAV](https://sabre.io/) - CardDAV、CalDAV 和 WebDAV 框架与服务器。 ([Source Code](https://github.com/sabre-io/dav)) `MIT` `PHP`
- [Xandikos](https://github.com/jelmer/xandikos) - 管理开销极小的 CardDAV 和 CalDAV 服务器，以 Git 仓库作为后端存储。`GPL-3.0` `Python/deb`


### 通信 - 自建通信系统

**[`^        back to top        ^`](#awesome-selfhosted)**

[Communication software](https://en.wikipedia.org/wiki/Communication_software) used to provide remote access to systems and exchange files and messages in text, audio and/or video formats between different computers or users, using their own custom protocols.

- [AnyCable](https://anycable.io/) - 实时服务器，通过 WebSockets、Server-sent events 等实现可靠的双向通信。 ([Demo](https://demo.anycable.io), [Source Code](https://github.com/anycable/anycable)) `MIT` `Go/Docker`
- [Apprise](https://github.com/caronc/apprise) - Apprise 允许你向当今几乎所有最流行的通知服务发送通知，例如 Telegram、Discord、Slack、Amazon SNS、Gotify 等。`MIT` `Python/Docker/deb`
- [Centrifugo](https://centrifugal.dev/) - 语言无关的实时消息（Websocket 或 SockJS）服务器。 ([Demo](https://github.com/centrifugal/centrifugo#demo), [Source Code](https://github.com/centrifugal/centrifugo)) `MIT` `Go/Docker/K8S`
- [Chitchatter](https://chitchatter.im/) - 无服务器、去中心化且临时性的点对点聊天应用。 ([Source Code](https://github.com/jeremyckahn/chitchatter)) `GPL-2.0` `Nodejs`
- [Conduit](https://conduit.rs/) - 由 Matrix 驱动的简单、快速且可靠的聊天服务器。 ([Source Code](https://gitlab.com/famedly/conduit)) `Apache-2.0` `Rust`
- [Continuwuity](https://continuwuity.org/) - 社区驱动的 Matrix homeserver，是 conduwuit 的延续，专注于用户体验和新功能（Conduit 的分支）。 ([Source Code](https://forgejo.ellis.link/continuwuation/continuwuity)) `Apache-2.0` `Rust/Docker/K8S/deb`
- [Databag](https://github.com/balzack/databag) - 面向 Web、iOS 和 Android 的联邦式端到端加密消息服务，支持文字、照片、视频以及 WebRTC 视频和音频通话。`Apache-2.0` `Docker`
- [Element](https://element.io) - 功能齐全的 Matrix 客户端，支持 Web、iOS 和 Android。 ([Source Code](https://github.com/element-hq/element-web)) `Apache-2.0` `Nodejs`
- [Fluxer](https://fluxer.app) - 为朋友、群组和社区打造的即时通讯和 VoIP 平台（Discord 的替代品）。 ([Demo](https://fluxer.app), [Source Code](https://github.com/fluxerapp/fluxer), [Clients](https://github.com/awesome-fluxer/awesome-fluxer)) `AGPL-3.0` `Docker`
- [GlobaLeaks](https://www.globaleaks.org/) - 举报软件，让任何人都能轻松搭建和维护安全的举报平台。 ([Demo](https://demo.globaleaks.org), [Source Code](https://github.com/globaleaks/globaleaks-whistleblowing-software)) `AGPL-3.0` `Python/deb/Docker`
- [GNUnet](https://gnunet.org/) - 用于去中心化点对点网络的软件框架。 ([Source Code](https://gnunet.org/git/)) `GPL-3.0` `C`
- [Gotify](https://gotify.net/) - 带 Android 和 CLI 客户端的通知服务器（PushBullet 的替代品）。 ([Source Code](https://github.com/gotify/server), [Clients](https://github.com/gotify/android)) `MIT` `Go/Docker`
- [Hyphanet](https://hyphanet.org/) - 匿名分享文件、浏览和发布 freesites（仅可通过 Hyphanet 访问的网站）并在论坛上聊天。 ([Source Code](https://github.com/hyphanet/fred)) `GPL-2.0` `Java`
- [Jami](https://jami.net/) - 保护用户隐私与自由的通用通信平台。 ([Source Code](https://git.jami.net/savoirfairelinux?sort=latest_activity_desc&filter=jami)) `GPL-3.0` `C++`
- [Live Helper Chat](https://livehelperchat.com/) - 为你的网站提供实时支持聊天。 ([Source Code](https://github.com/LiveHelperChat/livehelperchat)) `Apache-2.0` `PHP`
- [Mumble](https://wiki.mumble.info/wiki/Main_Page) - 低延迟、高质量的语音/文字聊天软件。 ([Source Code](https://github.com/mumble-voip/mumble), [Clients](https://wiki.mumble.info/wiki/3rd_Party_Applications)) `BSD-3-Clause` `C++/deb`
- [Notifo](https://github.com/notifo-io/notifo) - 多渠道通知服务器，支持电子邮件、移动推送、Web 推送、短信、消息传送和 javascript 插件。`MIT` `C#`
- [Novu](https://novu.co/) - 面向开发者的通知基础设施。 ([Source Code](https://github.com/novuhq/novu/)) `MIT` `Docker/Nodejs`
- [ntfy](https://ntfy.sh/) - 使用 HTTP PUT/POST 向手机或桌面推送通知，提供 Android 应用、CLI 和 Web 应用，类似于 Pushover 和 Gotify。 ([Demo](https://ntfy.sh/app), [Source Code](https://github.com/binwiederhier/ntfy), [Clients](https://github.com/binwiederhier/ntfy-android)) `Apache-2.0/GPL-2.0` `Go/Docker/K8S`
- [One Time Secret](https://docs.onetimesecret.com) - 通过仅可查看一次的自毁链接安全地分享敏感信息。 ([Demo](https://onetimesecret.com), [Source Code](https://github.com/onetimesecret/onetimesecret)) `MIT` `Docker/Ruby/Nodejs`
- [OpenWA](https://www.open-wa.org) `⚠` - WhatsApp API gateway exposing messaging as REST endpoints, with a web dashboard, multi-account sessions, and webhook events (alternative to WhatsApp Business API providers). ([Source Code](https://github.com/rmyndharis/OpenWA), [Clients](https://github.com/rmyndharis/OpenWA-plugins)) `MIT` `Docker`
- [OTS](https://ots.fyi/) - 一次性机密分享平台，在浏览器中进行对称 256 位 AES 加密。 ([Source Code](https://github.com/Luzifer/ots)) `Apache-2.0` `Go`
- [PushBits](https://github.com/pushbits/server) - 通过 Matrix 中继推送通知的通知服务器，类似于 PushBullet 和 Gotify。`ISC` `Go`
- [RetroShare](https://retroshare.cc) - 安全且去中心化的通信系统。提供去中心化聊天、论坛、消息传送和文件传输。 ([Source Code](https://github.com/RetroShare/RetroShare)) `GPL-2.0` `C++`
- [Rocket.Chat](https://rocket.chat/) - 将数据保护放在首位的通信平台（Gitter.im 和 Slack 的替代品）。 ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs/Docker/K8S`
- [SAMA](https://samacloud.io) - 新一代自托管聊天服务器和客户端。 ([Demo](https://app.samacloud.io/demo), [Source Code](https://github.com/SAMA-Communications/sama-server), [Clients](https://github.com/SAMA-Communications/sama-client)) `GPL-3.0` `Nodejs/Docker`
- [Screego](https://screego.net) - 通过 Web 浏览器快速向一人或多人共享屏幕的简单工具。 ([Demo](https://app.screego.net/), [Source Code](https://github.com/screego/server)) `GPL-3.0` `Docker/Go`
- [Shhh](https://github.com/smallwat3r/shhh) - 让机密信息远离电子邮件或聊天日志，使用带密码短语和有效期的安全链接来分享。`MIT` `Python`
- [SimpleX Chat](https://github.com/simplex-chat/simplex-chat) - 最私密、最安全的聊天和应用平台——现已支持双棘轮（double ratchet）E2E 加密。`AGPL-3.0` `Haskell`
- [Spectrum 2](https://spectrum.im/) - 即时通讯传输工具。即使用户使用的是不同的 IM 网络，也可以一起聊天。 ([Source Code](https://github.com/SpectrumIM/spectrum2)) `GPL-3.0` `C++`
- [Stoat](https://stoat.chat/) - 以用户为先、用现代 Web 技术构建的聊天平台。 ([Source Code](https://github.com/stoatchat/self-hosted)) `AGPL-3.0/MIT` `Rust`
- [Synapse](https://element-hq.github.io/synapse/latest/index.html) - Matrix 的服务器，一个面向去中心化持久通信的开放标准。 ([Source Code](https://github.com/element-hq/synapse)) `Apache-2.0` `Python/deb`
- [Tiledesk](https://tiledesk.com) - 一体化客户互动平台，从获客到售后，从 WhatsApp 到你的网站。提供全渠道人工客服和 AI 驱动的聊天机器人（Intercom、Zendesk、Tawk.to 的替代品）。 ([Source Code](https://github.com/Tiledesk/tiledesk)) `MIT` `Docker/K8S`
- [Tinode](https://github.com/tinode) - 即时通讯平台。后端用 Go 编写。客户端：Swift iOS、Java Android、JS Web 应用、可脚本化的命令行；聊天机器人。 ([Demo](https://sandbox.tinode.co/), [Source Code](https://github.com/tinode/chat), [Clients](https://github.com/tinode/webapp)) `GPL-3.0` `Go`
- [Tox](https://tox.chat/) - 分布式安全即时通讯工具，具备音频和视频聊天功能。 ([Source Code](https://github.com/TokTok/c-toxcore)) `GPL-3.0` `C`
- [Tuwunel](https://tuwunel.chat) - 面向 Matrix 的高性能、功能丰富的聊天服务器，是 conduwuit 的后继者（Conduit 的分支）。 ([Demo](https://try.tuwunel.chat/), [Source Code](https://github.com/matrix-construct/tuwunel)) `Apache-2.0` `deb/Docker/Nix/Rust`
- [Typebot](https://typebot.io) - 对话式应用构建器（Typeform 和 Landbot 的替代品）。 ([Source Code](https://github.com/baptisteArno/typebot.io)) `AGPL-3.0` `Docker`
- [WBO](https://github.com/lovasoa/whitebophir) - Web 白板，用于围绕图表、绘图和笔记进行实时协作。 ([Demo](https://wbo.ophir.dev/)) `AGPL-3.0` `Nodejs/Docker`
- [Zulip](https://zulip.org) - 强大的群聊应用。 ([Source Code](https://github.com/zulip/zulip)) `Apache-2.0` `Python`


### 通信 - 邮件 - 完整方案

**[`^        back to top        ^`](#awesome-selfhosted)**

Simple deployment of [E-mail](https://en.wikipedia.org/wiki/Email) servers, e.g. for inexperienced or impatient admins.

- [AnonAddy](https://anonaddy.com) - 用于创建别名的电子邮件转发服务。 ([Source Code](https://github.com/anonaddy/anonaddy)) `MIT` `PHP/Docker`
- [b1gMail](https://www.b1gmail.eu) - 完整的电子邮件解决方案，可在任何支持 PHP 和 MariaDB 的网页空间上运行。支持 POP3 catchall（全域接收）邮箱，如果你运行自己的服务器，还可以与 Postfix 或 b1gMailServer 集成。 ([Source Code](https://codeberg.org/b1gMail/b1gMail), [Clients](https://www.b1gmail.eu/en/start/addon-b1gmailserver/)) `GPL-2.0` `PHP`
- [DebOps](https://docs.debops.org/) - 一套开箱即用的基于 Debian 的数据中心。一组通用 Ansible roles，可用于管理 Debian 或 Ubuntu 主机。 ([Source Code](https://github.com/debops/debops)) `GPL-3.0` `Ansible/Python`
- [docker-mailserver](https://docker-mailserver.github.io/docker-mailserver/edge/) - 生产级全栈但简洁的邮件服务器（SMTP、IMAP、LDAP、反垃圾邮件、反病毒等），运行在容器内。只需配置文件，无需 SQL 数据库。 ([Source Code](https://github.com/docker-mailserver/docker-mailserver)) `MIT` `Docker`
- [Inboxen](https://inboxen.org) - 让你拥有无限数量的独立收件箱。 ([Source Code](https://codeberg.org/Inboxen/Inboxen)) `GPL-3.0` `Python`
- [iRedMail](https://www.iredmail.org/) - 基于 Postfix 和 Dovecot 的全功能邮件服务器解决方案。 ([Source Code](https://github.com/iredmail/iRedMail)) `GPL-3.0` `Shell`
- [Maddy Mail Server](https://maddy.email/) - 一体化邮件服务器，实现 SMTP（同时作为 MTA 和 MX）和 IMAP。用单个守护进程取代 Postfix、Dovecot、OpenDKIM、OpenSPF、OpenDMARC。 ([Source Code](https://github.com/foxcpp/maddy)) `GPL-3.0` `Go`
- [Mail-in-a-Box](https://mailinabox.email/) - 一条命令即可将任何 Ubuntu 服务器变成功能完备的邮件服务器。 ([Source Code](https://github.com/mail-in-a-box/mailinabox)) `CC0-1.0` `Shell`
- [Mailcow](https://mailcow.email/) - 基于 Dovecot、Postfix 和其他软件的邮件服务器套件，提供现代化的管理 Web UI。 ([Source Code](https://github.com/mailcow/mailcow-dockerized)) `GPL-3.0` `Docker/PHP`
- [Mailu](https://mailu.io/) - 以一组 Docker 镜像形式提供的简洁而全功能的邮件服务器。 ([Source Code](https://github.com/Mailu/Mailu)) `MIT` `Docker/Python`
- [Modoboa](https://modoboa.org/en/) - 邮件托管和管理平台，包含现代化且简化的 Web 用户界面。 ([Source Code](https://github.com/modoboa/modoboa)) `ISC` `Python`
- [Mox](https://www.xmox.nl/) - 完整的电子邮件解决方案，具备 IMAP4、SMTP、SPF、DKIM、DMARC、MTA-STS、DANE 和 DNSSEC，基于信誉与内容的垃圾邮件过滤，国际化（IDNA），通过 ACME 和 Let's Encrypt 的自动 TLS，账户自动配置以及网页邮箱。 ([Source Code](https://github.com/mjl-/mox)) `MIT` `Go`
- [Postal](https://docs.postalserver.io/) - 供网站和 Web 服务器使用的完整且全功能的邮件服务器。 ([Source Code](https://github.com/postalserver/postal)) `MIT` `Docker/Ruby`
- [Simple NixOS Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) - 利用 Nix 生态系统的完整邮件服务器解决方案。`GPL-3.0` `Nix`
- [SimpleLogin](https://simplelogin.io) - 保护你电子邮件地址的邮件别名解决方案。附带浏览器扩展和移动应用。 ([Source Code](https://github.com/simple-login/app)) `MIT` `Docker/Python`
- [Stalwart Mail Server](https://stalw.art) - 一体化邮件服务器，支持 JMAP、IMAP4 和 SMTP，具备广泛的现代功能。 ([Source Code](https://github.com/stalwartlabs/stalwart)) `AGPL-3.0` `Rust/Docker`
- [wildduck](https://wildduck.email/) - 可扩展且无单点故障（SPOF）的 IMAP/POP3 邮件服务器。 ([Source Code](https://github.com/zone-eu/wildduck)) `EUPL-1.2` `Nodejs/Docker`


### 通信 - 邮件 - 投递代理

**[`^        back to top        ^`](#awesome-selfhosted)**

[Mail Delivery Agents](https://en.wikipedia.org/wiki/Message_delivery_agent) (MDAs) - [IMAP](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol)/[POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) server software.

- [Cyrus IMAP](https://www.cyrusimap.org/) - 电子邮件（IMAP/POP3）、联系人和日历服务器。 ([Source Code](https://github.com/cyrusimap/cyrus-imapd)) `BSD-3-Clause-Attribution` `C`
- [DavMail](https://davmail.sourceforge.net/) `⚠` - POP/IMAP/SMTP/Caldav/Carddav/LDAP exchange gateway allowing users to use any mail/calendar client with an Exchange server, even from the internet or behind a firewall through Outlook Web Access. ([Source Code](https://github.com/mguessan/davmail)) `GPL-2.0` `Java`
- [Dovecot](https://www.dovecot.org/) - 以安全为核心考量的 IMAP 和 POP3 服务器。 ([Source Code](https://github.com/dovecot/core)) `MIT/LGPL-2.1` `C/deb`


### 通信 - 邮件 - 传输代理

**[`^        back to top        ^`](#awesome-selfhosted)**

[Mail Transfer Agents](https://en.wikipedia.org/wiki/Message_transfer_agent) (MTAs) - [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol) servers.

- [chasquid](https://blitiri.com.ar/p/chasquid/) - 注重简单、安全和易操作性的 SMTP（电子邮件）服务器。 ([Source Code](https://blitiri.com.ar/git/r/chasquid/)) `Apache-2.0` `Go`
- [Courier MTA](https://www.courier-mta.org/) - 快速、可扩展的企业级邮件/群件服务器，提供 ESMTP、IMAP、POP3、网页邮箱、邮件列表以及基本的基于 Web 的日历和日程安排服务。 ([Source Code](https://www.courier-mta.org/repo.html)) `GPL-3.0` `C/deb`
- [DragonFly](https://github.com/corecode/dma) - 面向家庭和办公室使用的小型 MTA。可在 Linux 和 FreeBSD 上运行。`BSD-3-Clause` `C`
- [EmailRelay](https://emailrelay.sourceforge.net/) - 面向 Windows 和 Linux 的小型、易于配置的 SMTP 和 POP3 服务器。 ([Source Code](https://sourceforge.net/p/emailrelay/code/HEAD/tree/)) `GPL-3.0` `C++`
- [Exim](https://www.exim.org/) - 剑桥大学开发的消息传输代理（MTA）。 ([Source Code](https://git.exim.org/exim.git)) `GPL-3.0` `C/deb`
- [Haraka](https://haraka.github.io/) - 快速、高度可扩展且事件驱动的 SMTP 服务器。 ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Nodejs`
- [OpenSMTPD](https://opensmtpd.org/) - 来自 OpenBSD 项目的安全 SMTP 服务器实现。 ([Source Code](https://github.com/OpenSMTPD/OpenSMTPD/)) `ISC` `C/deb`
- [Postfix](http://www.postfix.org/) - 快速、易于管理且安全的 Sendmail 替代品。`IPL-1.0` `C/deb`
- [Sendmail](https://www.proofpoint.com/us/products/email-protection/open-source-email-solution) - 消息传输代理（MTA）。`Sendmail` `C/deb`


### 通信 - 邮件 - 邮件列表与新闻组

**[`^        back to top        ^`](#awesome-selfhosted)**

[Mailing list](https://en.wikipedia.org/wiki/Mailing_list) servers and mass mailing software - one message to many recipients.

_Related: [Customer Relationship Management (CRM)](#customer-relationship-management-crm)_

- [HyperKitty](https://wiki.list.org/HyperKitty) - 访问 GNU Mailman v3 归档。 ([Demo](https://lists.mailman3.org/), [Source Code](https://gitlab.com/mailman/hyperkitty)) `GPL-3.0` `Python`
- [Keila](https://www.keila.io) - 可靠且易于使用的邮件简报工具（Mailchimp 和 Sendinblue 的替代品）。 ([Demo](https://app.keila.io), [Source Code](https://github.com/pentacent/keila)) `AGPL-3.0` `Docker`
- [Listmonk](https://listmonk.app/) - 高性能的邮件简报和邮件列表管理器，配有现代化仪表板。 ([Demo](https://demo.listmonk.app/), [Source Code](https://github.com/knadh/listmonk)) `AGPL-3.0` `Go/Docker`
- [Mailman](https://www.list.org/) - 管理电子邮件讨论列表和电子简报列表。 ([Source Code](https://gitlab.com/mailman/)) `GPL-3.0` `Python`
- [Mautic](https://www.mautic.org/) - 营销自动化软件（电子邮件、社交等）。 ([Source Code](https://github.com/mautic/mautic)) `GPL-3.0` `PHP`
- [mlmmj](https://mlmmj.org/) - 让邮件列表管理变得愉悦。 ([Source Code](https://codeberg.org/mlmmj/mlmmj)) `MIT` `C`
- [phpList](https://www.phplist.org) - 邮件简报和电子邮件营销，支持订阅者、退信和插件的高级管理。 ([Source Code](https://github.com/phpList/phplist3)) `AGPL-3.0` `PHP`
- [Postorius](https://docs.mailman3.org/projects/postorius/en/latest/) - 用于访问 GNU Mailman 的 Web 用户界面。 ([Source Code](https://gitlab.com/mailman/postorius/)) `GPL-3.0` `Python`
- [Schleuder](https://schleuder.nadir.org/) - 支持 GPG 且具备重发能力的邮件列表管理器。 ([Source Code](https://0xacab.org/schleuder/schleuder/tree/master)) `GPL-3.0` `Ruby`
- [Sympa](https://www.sympa.community/) - 邮件列表管理器。 ([Source Code](https://github.com/sympa-community/sympa)) `GPL-2.0` `Perl`


### 通信 - 邮件 - Webmail 客户端

**[`^        back to top        ^`](#awesome-selfhosted)**

[Webmail](https://en.wikipedia.org/wiki/Webmail) clients.

- [Cypht](https://cypht.org) - 适用于你电子邮件账户的订阅源阅读器。 ([Source Code](https://github.com/cypht-org/cypht)) `LGPL-2.1` `PHP`
- [Roundcube](https://roundcube.net) - 基于浏览器的 IMAP 客户端，拥有类似应用的用户界面。 ([Source Code](https://github.com/roundcube/roundcubemail)) `GPL-3.0` `PHP/deb`
- [SnappyMail](https://github.com/the-djmaze/snappymail) - 简洁、现代、轻量且快速的基于 Web 的电子邮件客户端（RainLoop 的分支）。`AGPL-3.0` `PHP`
- [SquirrelMail](https://squirrelmail.org) - 另一款基于浏览器的 IMAP 客户端。 ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPL-2.0` `PHP`


### 通信 - IRC

**[`^        back to top        ^`](#awesome-selfhosted)**

[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software.

- [Ergo](https://ergo.chat/) - 用 Go 编写的现代 IRCv3 服务器，集 ircd、服务框架和 bouncer 功能于一身。 ([Source Code](https://github.com/ergochat/ergo)) `MIT` `Go/Docker`
- [Glowing Bear](https://github.com/glowing-bear/glowing-bear) - WeeChat 的 Web 前端。 ([Demo](https://www.glowing-bear.org)) `GPL-3.0` `Nodejs`
- [InspIRCd](https://www.inspircd.org/) - 用 C++ 编写的模块化 IRC 服务器，支持 Linux、BSD、Windows 和 macOS。 ([Source Code](https://github.com/inspircd/inspircd)) `GPL-2.0` `C++/Docker`
- [Kiwi IRC](https://kiwiirc.com/) - 支持主题定制、响应式的 Web IRC 客户端。 ([Demo](https://kiwiirc.com/nextclient/), [Source Code](https://github.com/kiwiirc/kiwiirc)) `Apache-2.0` `Nodejs`
- [ngircd](https://ngircd.barton.de/) - 面向小型或私有网络的便携式轻量级 IRC 服务器。 ([Source Code](https://github.com/ngircd/ngircd)) `GPL-2.0` `C/deb`
- [Quassel IRC](https://quassel-irc.org/) - 分布式 IRC 客户端，即一个（或多个）客户端可以连接到中央核心或从中断开。 ([Source Code](https://github.com/quassel/quassel)) `GPL-2.0` `C++`
- [Robust IRC](https://robustirc.net/) - 没有 netsplit 的 IRC。基于 RobustSession 协议的分布式 IRC 服务器。 ([Source Code](https://github.com/robustirc/robustirc)) `BSD-3-Clause` `Go`
- [The Lounge](https://thelounge.chat/) - Web IRC 客户端。 ([Demo](https://demo.thelounge.chat/), [Source Code](https://github.com/thelounge/thelounge)) `MIT` `Nodejs/Docker`
- [UnrealIRCd](https://www.unrealircd.org/) - 用 C 编写的模块化、先进且高度可配置的 IRC 服务器，支持 Linux、BSD、Windows 和 macOS。 ([Source Code](https://github.com/unrealircd/unrealircd)) `GPL-2.0` `C`
- [Weechat](https://weechat.org/) - 快速、轻量且可扩展的聊天客户端。 ([Source Code](https://github.com/weechat/weechat)) `GPL-3.0` `C/Docker/deb`
- [ZNC](https://wiki.znc.in/ZNC) - 高级 IRC bouncer。 ([Source Code](https://github.com/znc/znc)) `Apache-2.0` `C++/deb`


### 通信 - SIP

**[`^        back to top        ^`](#awesome-selfhosted)**

[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)/[IPBX](https://en.wikipedia.org/wiki/IP_PBX) telephony software.

- [Asterisk](https://www.asterisk.org/) - 易于使用且功能先进的 IP PBX 系统、VoIP 网关和会议服务器。 ([Source Code](https://github.com/asterisk/asterisk)) `GPL-2.0` `C/deb`
- [Flexisip](https://www.linphone.org/en/flexisip-sip-server/) - 完整、模块化且可扩展的 SIP 服务器，包含推送网关，用于在应用不在前台时需要依靠推送通知接收信息的移动设备平台上，投递 SIP 来电或文本消息。 ([Source Code](https://github.com/BelledonneCommunications/flexisip)) `AGPL-3.0` `C/Docker`
- [Freepbx](https://www.freepbx.org) - 用于控制和管理 Asterisk 的基于 Web 的 GUI。 ([Source Code](https://git.freepbx.org/projects/FREEPBX)) `GPL-2.0` `PHP`
- [FreeSWITCH](https://freeswitch.org/) - 可扩展的跨平台电话平台。 ([Source Code](https://github.com/signalwire/freeswitch)) `MPL-2.0` `C`
- [FusionPBX](https://www.fusionpbx.com/) - 名为 FreeSWITCH 的多平台语音交换机的 Web 界面。 ([Source Code](https://github.com/fusionpbx/fusionpbx)) `MPL-1.1` `PHP`
- [Kamailio](https://www.kamailio.org/w/) - 模块化 SIP 服务器（注册服务器/代理/路由器等）。 ([Source Code](https://github.com/kamailio/kamailio)) `GPL-2.0` `C/deb`
- [openSIPS](https://opensips.org/) - 面向语音、视频、即时消息、在线状态及其他任何 SIP 扩展的 SIP 代理/服务器。 ([Source Code](https://github.com/OpenSIPS/opensips)) `GPL-2.0` `C`
- [Routr](https://routr.io) - 用于构建可靠且可扩展 SIP 基础设施的轻量级 SIP 代理、位置服务器和注册服务器。 ([Source Code](https://github.com/fonoster/routr)) `MIT` `Docker/K8S`
- [SIP3](https://sip3.io/) - VoIP 故障排查与监控平台。 ([Demo](https://demo.sip3.io), [Source Code](https://github.com/sip3io/)) `Apache-2.0` `Java`
- [SIPCAPTURE Homer](https://www.sipcapture.org/) - 对 VoIP 通话进行故障排查与监控。 ([Source Code](https://github.com/sipcapture/homer)) `AGPL-3.0` `Nodejs/Go/Docker`
- [Wazo](https://wazo-platform.org/) - 基于 Asterisk 构建的全功能 IPBX 解决方案，集成 Web 管理界面和 RESTful API。 ([Source Code](https://github.com/wazo-platform)) `GPL-3.0` `Python`
- [Yeti-Switch](https://yeti-switch.org/) - 带集成计费与路由引擎及 REST API 的转接级 class4 软交换（SBC）。 ([Demo](https://demo.yeti-switch.org/), [Source Code](https://github.com/yeti-switch)) `GPL-2.0` `C++/Ruby`


### 通信 - 社交网络与论坛

**[`^        back to top        ^`](#awesome-selfhosted)**

[Social Networking](https://en.wikipedia.org/wiki/Social_networking_service) and [Forum](https://en.wikipedia.org/wiki/Internet_forum) software.

- [Akkoma](https://akkoma.social/) - 联合微博客服务器，兼容 Mastodon、GNU social 和 ActivityPub。 ([Source Code](https://akkoma.dev/AkkomaGang/akkoma)) `AGPL-3.0` `Elixir/Docker`
- [Answer](https://answer.apache.org) - 基于知识的社区软件。可用它快速搭建问答社区，用于产品技术支持、客户支持、用户交流等场景。 ([Source Code](https://github.com/apache/answer)) `Apache-2.0` `Docker/Go`
- [Artalk](https://artalk.js.org/) - 用 Golang 构建的评论系统，为网站添加评论提供轻量且高度可定制的解决方案。 ([Source Code](https://github.com/ArtalkJS/Artalk)) `MIT` `Go/Docker`
- [AsmBB](https://board.asm32.info) - 用 ASM 编写、由 SQLite 驱动的高速论坛引擎。 ([Source Code](https://asm32.info/fossil/asmbb/index)) `EUPL-1.2` `Assembly`
- [BuddyPress](https://buddypress.org/about/) - 功能强大的插件，通过用户资料、动态流、用户群组等社交网络功能，让基于 WordPress.org 的网站超越博客。 ([Source Code](https://github.com/buddypress/BuddyPress)) `GPL-2.0` `PHP`
- [Coral](https://coralproject.net/) - 来自 Vox Media 的更佳评论体验。 ([Source Code](https://github.com/coralproject/talk)) `Apache-2.0` `Docker/Nodejs`
- [diaspora*](https://diasporafoundation.org/) - 分布式社交网络服务器。 ([Source Code](https://github.com/diaspora/diaspora)) `AGPL-3.0` `Ruby`
- [Discourse](https://www.discourse.org/) - 基于 Ruby 和 JS 的高级论坛/社区解决方案。 ([Demo](https://try.discourse.org/), [Source Code](https://github.com/discourse/discourse)) `GPL-2.0` `Docker`
- [Elgg](https://elgg.org/) - 功能强大的社交网络引擎。 ([Source Code](https://github.com/Elgg/Elgg)) `GPL-2.0` `PHP`
- [Enigma 1/2 BBS](https://nuskooler.github.io/enigma-bbs/) - 现代多平台 BBS 引擎，支持不限数量的“callers”（拨入用户）以及传统 DOS door 游戏。 ([Source Code](https://github.com/NuSkooler/enigma-bbs)) `BSD-2-Clause` `Shell/Docker/Nodejs`
- [Flarum](https://flarum.org) - 令人愉悦的简洁论坛。让线上讨论重拾乐趣的新一代论坛软件。 ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
- [Friendica](https://friendi.ca/) - 社交通信服务器。 ([Source Code](https://github.com/friendica/friendica)) `AGPL-3.0` `PHP`
- [GoToSocial](https://docs.gotosocial.org/en/latest/) - 实现 Mastodon 客户端 API 的 ActivityPub 联合社交网络服务器。 ([Source Code](https://codeberg.org/superseriousbusiness/gotosocial)) `AGPL-3.0` `Docker/Go`
- [Habitat](https://gethabitat.org/) - 面向本地社区的平台。 ([Source Code](https://github.com/carlnewton/habitat)) `AGPL-3.0` `Docker`
- [Hatsu](https://hatsu.cli.rs/) - 代表你的静态站点与 Fediverse 交互的桥接器。 ([Source Code](https://github.com/importantimport/hatsu)) `AGPL-3.0` `Docker/Rust`
- [Hubzilla](https://hubzilla.org) - 去中心化的身份、隐私、发布、共享、云存储与通信/社交平台。 ([Source Code](https://framagit.org/hubzilla/core)) `MIT` `PHP`
- [HumHub](https://www.humhub.org/) - 用于搭建私有社交网络的灵活套件。 ([Source Code](https://github.com/humhub/humhub)) `AGPL-3.0` `PHP`
- [Iceshrimp.NET](https://iceshrimp.net) - 通过 ActivityPub 通信的联合微博客服务器。 ([Source Code](https://iceshrimp.dev/iceshrimp/iceshrimp.net)) `EUPL-1.2` `.NET/C#/Docker`
- [Isso](https://isso-comments.de/) - 用 Python 和 JavaScript 编写的轻量级评论服务器，旨在即插即用地替代 Disqus。 ([Source Code](https://github.com/isso-comments/isso)) `MIT` `Python/Docker`
- [Lemmy](https://join-lemmy.org/) - 面向 fediverse 的链接聚合器（Reddit 的替代品）。 ([Source Code](https://github.com/LemmyNet/lemmy)) `AGPL-3.0` `Docker/Rust`
- [Loomio](https://www.loomio.org/) - 协作决策工具，让任何人都能轻松参与影响自己的决策。 ([Source Code](https://github.com/loomio/loomio)) `AGPL-3.0` `Docker`
- [Mastodon](https://joinmastodon.org/) - 联合微博客服务器。 ([Source Code](https://github.com/mastodon/mastodon), [Clients](https://github.com/hyperupcall/awesome-mastodon)) `AGPL-3.0` `Ruby`
- [Misago](https://misago-project.org/) - 功能完备的现代论坛应用，快速、可扩展且响应式。 ([Source Code](https://github.com/rafalp/Misago)) `GPL-2.0` `Docker`
- [Misskey](https://misskey.io/) - 面向 Fediverse 的去中心化应用式微博客服务器/SNS，与 GNU social 和 Mastodon 一样使用 ActivityPub 协议。 ([Source Code](https://github.com/misskey-dev/misskey)) `AGPL-3.0` `Nodejs/Docker`
- [Movim](https://movim.eu/) - 基于 XMPP 的现代联合社交网络，具备全功能的群聊、订阅和微博客。 ([Source Code](https://github.com/movim/movim)) `AGPL-3.0` `PHP/Docker`
- [MyBB](https://mybb.com/) - 免费且可扩展的论坛软件包。 ([Source Code](https://github.com/mybb/mybb)) `LGPL-3.0` `PHP`
- [NodeBB](https://nodebb.org/) - 为现代 Web 打造的论坛软件。 ([Demo](https://try.nodebb.org/), [Source Code](https://github.com/NodeBB/NodeBB)) `GPL-3.0` `Nodejs/Docker`
- [OSSN](https://www.opensource-socialnetwork.org/) - 社交网络软件，让你创建社交网络网站，帮助成员与拥有相似职业或个人兴趣的人建立社交关系。 ([Source Code](https://github.com/opensource-socialnetwork/opensource-socialnetwork)) `CAL-1.0` `PHP`
- [phpBB](https://www.phpbb.com/) - 扁平结构论坛的公告板软件解决方案，既可用于与一群人保持联系，也可为你的整个网站提供支持。 ([Source Code](https://github.com/phpbb/phpbb)) `GPL-2.0` `PHP`
- [PieFed](https://join.piefed.social) - 面向 fediverse 的链接聚合器/reddit 克隆（Reddit 的替代品）。 ([Demo](https://piefed.social), [Source Code](https://codeberg.org/rimu/pyfedi)) `AGPL-3.0` `Python/Docker`
- [PixelFed](https://pixelfed.social) - 注重伦理的照片分享平台，由 ActivityPub 联合机制驱动（Instagram 的替代品）。 ([Source Code](https://github.com/pixelfed/pixelfed)) `AGPL-3.0` `PHP`
- [Pleroma](https://pleroma.social) - 联合微博客服务器，兼容 Mastodon、GNU social 和 ActivityPub。 ([Source Code](https://git.pleroma.social/pleroma/pleroma)) `AGPL-3.0` `Elixir`
- [qpixel](https://codidact.com/) - 基于问答的社区知识共享软件。 ([Source Code](https://github.com/codidact/qpixel)) `AGPL-3.0` `Ruby`
- [Redlib](https://github.com/redlib-org/redlib) `⚠` - Private alternative front-end to Reddit, with its origins in Libreddit. `AGPL-3.0` `Rust`
- [remark42](https://remark42.com/) - 轻量简洁、不窥探用户的评论引擎。可嵌入博客、文章或任何读者发表评论的地方。 ([Demo](https://remark42.com/demo/), [Source Code](https://github.com/umputun/remark42)) `MIT` `Docker/Go`
- [Scoold](https://scoold.com) - 装在 JAR 包里的 Stack Overflow。企业级问答平台，支持全文搜索、SAML 和 LDAP 集成以及社交登录。 ([Demo](https://live.scoold.com), [Source Code](https://github.com/Erudika/scoold)) `Apache-2.0` `Java/Docker/K8S`
- [Simple Machines Forum](https://www.simplemachines.org/) - 免费的专业级软件包，让你在几分钟内搭建自己的在线社区。 ([Source Code](https://github.com/SimpleMachines/SMF)) `BSD-3-Clause` `PHP`
- [Socialhome](https://socialhome.network) - 联合且去中心化的个人主页构建器和社交网络引擎。 ([Demo](https://socialhome.network/), [Source Code](https://github.com/jaywink/socialhome)) `AGPL-3.0` `Docker/Python`
- [Talkyard](https://www.talkyard.io/) - 创建一个社区，让你的用户提出想法、获得问题解答，并进行友好的开放式讨论和聊天（Slack/StackOverflow/Discourse/Reddit/Disqus 的混合体）。 ([Demo](https://www.talkyard.io/forum/latest), [Source Code](https://github.com/debiki/talkyard)) `AGPL-3.0` `Docker/Scala`
- [yarn.social](https://yarn.social) - 类似 Twitter™ 的去中心化微博客平台。无广告、无追踪，内容和数据属于你。 ([Source Code](https://git.mills.io/yarnsocial/yarn)) `MIT` `Go`


### 通信 - 视频会议

**[`^        back to top        ^`](#awesome-selfhosted)**

[Video/Web Conferencing](https://en.wikipedia.org/wiki/Web_conferencing) tools and software.

_Related: [Conference Management](#conference-management)_

- [BigBlueButton](https://bigbluebutton.org/) - 支持实时共享音频、视频、幻灯片（带白板控制）、聊天和屏幕。讲师可通过投票、表情和分组讨论室与远程学生互动。 ([Source Code](https://github.com/bigbluebutton/bigbluebutton)) `LGPL-3.0` `Java`
- [Galene](https://galene.org/) - 易于部署且服务器资源需求适中的视频会议服务器。 ([Source Code](https://github.com/jech/galene)) `MIT` `Go`
- [Janus](https://janus.conf.meetecho.com/) - 通用、轻量、极简的 WebRTC 服务器。 ([Demo](https://janus.conf.meetecho.com/demos/), [Source Code](https://github.com/meetecho/janus-gateway)) `GPL-3.0` `C`
- [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - WebRTC 应用，使用 Jitsi Videobridge 提供高质量、可扩展的视频会议。 ([Demo](https://meet.jit.si), [Source Code](https://github.com/jitsi/jitsi-meet)) `Apache-2.0` `Nodejs/Docker/deb`
- [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - 兼容 WebRTC 的选择性转发单元（SFU），支持多用户视频通信。 ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache-2.0` `Java/deb`
- [MiroTalk C2C](https://c2c.mirotalk.com) - 实时 cam-2-cam 视频通话与屏幕共享，端到端加密，可通过简单的 iframe 嵌入任何网站。 ([Source Code](https://github.com/miroslavpejic85/mirotalkc2c)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk P2P](https://p2p.mirotalk.com) - 简单、安全、快速的实时视频会议，最高支持 4k 和 60fps，兼容所有浏览器和平台。 ([Demo](https://p2p.mirotalk.com/newcall), [Source Code](https://github.com/miroslavpejic85/mirotalk)) `AGPL-3.0` `Nodejs/Docker`
- [MiroTalk SFU](https://sfu.mirotalk.com) - 简单、安全、可扩展的实时视频会议，最高支持 4k，兼容所有浏览器和平台。 ([Demo](https://sfu.mirotalk.com/newroom), [Source Code](https://github.com/miroslavpejic85/mirotalksfu)) `AGPL-3.0` `Nodejs/Docker`
- [plugNmeet](https://www.plugnmeet.org/) - 可扩展的高性能 Web 会议系统。 ([Demo](https://demo.plugnmeet.com/login.html), [Source Code](https://github.com/mynaparrot/plugNmeet-server)) `MIT` `Docker/Go`


### 通信 - XMPP - 服务器

**[`^        back to top        ^`](#awesome-selfhosted)**

[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) servers.

- [ejabberd](https://www.ejabberd.im/) - XMPP 即时消息服务器。 ([Source Code](https://github.com/processone/ejabberd)) `GPL-2.0` `Erlang/Docker`
- [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - 专注于性能和可扩展性的移动消息平台。 ([Source Code](https://github.com/esl/MongooseIM)) `GPL-2.0` `Erlang/Docker/K8S`
- [Openfire](https://www.igniterealtime.org/projects/openfire/) - 实时协作（RTC）服务器。 ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache-2.0` `Java`
- [Prosody IM](https://prosody.im/) - 功能丰富且易于配置的 XMPP 服务器。 ([Source Code](https://hg.prosody.im/)) `MIT` `Lua`
- [Snikket](https://snikket.org/) - 一体化、Docker 化的简易 XMPP 解决方案，包含 Web 管理端和客户端。 ([Source Code](https://github.com/snikket-im/snikket-server), [Clients](https://snikket.org/app/)) `Apache-2.0` `Docker`
- [Tigase](https://tigase.net/xmpp-server) - 用 Java 实现的 XMPP 服务器。 ([Source Code](https://github.com/tigase/tigase-server)) `GPL-3.0` `Java`


### 通信 - XMPP - Web 客户端

**[`^        back to top        ^`](#awesome-selfhosted)**

[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) Web clients/interfaces.

- [Converse.js](https://conversejs.org/) - 浏览器中的 XMPP 聊天客户端。 ([Source Code](https://github.com/conversejs/converse.js)) `MPL-2.0` `Javascript`
- [Libervia](https://repos.goffi.org/libervia-web) - 来自 Salut à Toi 的 Web 前端。`AGPL-3.0` `Python`
- [Salut à Toi](https://www.salut-a-toi.org/) - 多用途、多前端、自由且去中心化的通信工具。 ([Source Code](https://repos.goffi.org/libervia-backend)) `AGPL-3.0` `Python`


### 社区支持农业（CSA）

**[`^        back to top        ^`](#awesome-selfhosted)**

Management and administration tools for community supported agriculture and food cooperatives.

_Related: [E-commerce](#e-commerce)_

- [ACP Admin](https://acp-admin.ch/) - CSA（社区支持农业）管理。管理成员、订阅、配送、取货点、成员参与、发票和邮件（文档为法语）。 ([Source Code](https://github.com/csa-admin-org/csa-admin)) `MIT` `Ruby`
- [FoodCoopShop](https://www.foodcoopshop.com/) - 面向食品合作社的易用软件。 ([Source Code](https://github.com/foodcoopshop/foodcoopshop)) `AGPL-3.0` `PHP/Docker`
- [Foodsoft](https://foodcoops.net/) - 管理非营利食品合作社（产品目录、订购、会计、任务排班）。 ([Source Code](https://github.com/foodcoops/foodsoft)) `AGPL-3.0` `Docker/Ruby`
- [Hive-Pal](https://hivepal.app) - 移动优先的养蜂管理应用，用于跟踪蜂箱、检查、蜂王记录和设备，数据录入精简，专为现场使用而优化。 ([Demo](https://hivepal.app), [Source Code](https://github.com/martinhrvn/hive-pal)) `MIT` `Nodejs/Docker`
- [juntagrico](https://juntagrico.org/) - 面向社区花园和蔬菜合作社的管理平台。 ([Source Code](https://github.com/juntagrico/juntagrico)) `LGPL-3.0` `Python`
- [Open Food Network](https://www.openfoodnetwork.org/) - 本地食品在线市场。它构建了一个独立在线食品商店网络，将农民和食品集散中心与个人及本地企业连接起来。 ([Source Code](https://github.com/openfoodfoundation/openfoodnetwork)) `AGPL-3.0` `Ruby`
- [OpenOlitor](https://openolitor.org/) - 面向社区支持农业（CSA）团体的管理平台。 ([Source Code](https://github.com/OpenOlitor/openolitor-server)) `AGPL-3.0` `Scala`
- [teikei](https://github.com/teikei/teikei) - 基于众包数据绘制社区支持农业（CSA）地图的 Web 应用。 ([Demo](https://ernte-teilen.org/karte/#/)) `AGPL-3.0` `Nodejs`


### 会议管理

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for submission of [abstracts](https://en.wikipedia.org/wiki/Abstract_management) and preparation/management of academic conferences.

_Related: [Communication - Video Conferencing](#communication---video-conferencing)_

- [indico](https://getindico.io/) - 功能丰富的活动管理系统，由 Web 的诞生地 CERN 打造。 ([Demo](https://sandbox.getindico.io/), [Source Code](https://github.com/indico/indico)) `MIT` `Python`
- [motion.tools (Antragsgrün)](https://motion.tools/) - 管理（政治）会议的动议和修正案。 ([Demo](https://sandbox.motion.tools/createsite), [Source Code](https://github.com/CatoTH/antragsgruen)) `AGPL-3.0` `PHP/Docker`
- [OpenSlides](https://openslides.com/) - 用于管理和展示大会议程、动议和选举的演示与会议系统。 ([Demo](https://demo.openslides.org/login), [Source Code](https://github.com/OpenSlides/OpenSlides)) `MIT` `Docker`
- [osem](https://osem.io/) - 为自由软件会议量身定制的活动管理。 ([Source Code](https://github.com/openSUSE/osem)) `MIT` `Ruby/Docker`
- [pretalx](https://pretalx.org) - 基于 Web 的活动管理，包括运行征集论文（Call for Papers）流程、评审投稿和安排演讲日程。支持与多种相关工具的导入导出。 ([Source Code](https://github.com/pretalx/pretalx)) `Apache-2.0` `Python`


### 内容管理系统（CMS）

**[`^        back to top        ^`](#awesome-selfhosted)**

[Content Management Systems](https://en.wikipedia.org/wiki/Content_management_system) offer a practical way to setup a website with many features, using third party plugins, themes and functionality that are easy to add and customize.

_Related: [Blogging Platforms](#blogging-platforms), [Static Site Generators](#static-site-generators), [Photo Galleries](#photo-galleries)_

- [Alfresco Community Edition](https://www.alfresco.com/products/community/download) - 企业内容管理软件，可处理任何类型的内容，让用户轻松共享和协作处理内容。 ([Source Code](https://github.com/Alfresco/alfresco-community-repo)) `LGPL-3.0` `Java`
- [Apostrophe](https://apostrophecms.com/) - 专注于可扩展的上下文内编辑工具的 CMS。 ([Demo](https://demo.apostrophecms.com/), [Source Code](https://github.com/apostrophecms/apostrophe)) `MIT` `Nodejs`
- [Automad](https://automad.org/) - 扁平文件内容管理系统和模板引擎。 ([Demo](https://try.automad.org/), [Source Code](https://github.com/marcantondahmen/automad)) `MIT` `PHP/Docker`
- [Backdrop CMS](https://backdropcms.org/) - 面向中小型企业和非营利组织的综合 CMS。 ([Source Code](https://github.com/backdrop/backdrop)) `GPL-2.0` `PHP`
- [Bludit](https://www.bludit.com/) `⚠` - Build a site or blog in seconds. Bludit uses flat-files (text files in JSON format) to store posts and pages. ([Source Code](https://github.com/bludit/bludit)) `MIT` `PHP`
- [Bolt CMS](https://boltcms.io/) - 内容管理工具，力求尽可能简单直接。 ([Source Code](https://github.com/bolt/core)) `MIT` `PHP`
- [CMS Made Simple](https://www.cmsmadesimple.org/) - 更快更轻松地管理网站内容，从小企业到大型企业均可扩展适用。 ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL-2.0` `PHP`
- [Cockpit](https://getcockpit.com) - 管理任何结构化内容的简单内容平台。 ([Source Code](https://github.com/Cockpit-HQ/Cockpit)) `MIT` `PHP`
- [Concrete 5 CMS](https://www.concretecms.com) - 开源内容管理系统。 ([Source Code](https://github.com/concretecms/concretecms)) `MIT` `PHP`
- [Contao](https://contao.org/) - 功能强大的 CMS，让你创建专业网站和可扩展的 Web 应用。 ([Demo](https://demo.contao.org/contao), [Source Code](https://github.com/contao/contao/)) `LGPL-3.0` `PHP`
- [CouchCMS](https://www.couchcms.com/) - 面向设计师的 CMS。 ([Source Code](https://github.com/CouchCMS/CouchCMS)) `CPAL-1.0` `PHP`
- [Drupal](https://www.drupal.org/) - 高级内容管理平台。 ([Source Code](https://git.drupalcode.org/project/drupal)) `GPL-2.0` `PHP`
- [eLabFTW](https://www.elabftw.net) - 面向研究实验室的在线实验记录本。可存储实验、用数据库查找试剂或实验方案、使用可信时间戳为实验进行具有法律效力的时间标记、导出为 pdf 或 zip 归档、与协作者共享等。 ([Demo](https://demo.elabftw.net), [Source Code](https://github.com/elabftw/elabftw)) `AGPL-3.0` `PHP`
- [Expressa](https://github.com/thomas4019/expressa) - 使用 JSON 模式驱动数据库网站的内容管理系统。提供权限管理和自动 REST API。`MIT` `Nodejs`
- [Joomla!](https://www.joomla.org/) - 高级内容管理系统（CMS）。 ([Source Code](https://github.com/joomla/joomla-cms)) `GPL-2.0` `PHP`
- [KeystoneJS](https://keystonejs.com/) - CMS 和 Web 应用平台。 ([Source Code](https://github.com/keystonejs/keystone)) `MIT` `Nodejs`
- [Localess](https://localess.org/home) `⚠` - Powerful translation management and content management system. Manage and translate your website or app content into multiple languages, using AI to translate faster. ([Source Code](https://github.com/Lessify/localess)) `MIT` `Docker`
- [MODX](https://modx.com/) - 高级内容管理与发布平台。当前版本名为“Revolution”（革命）。 ([Source Code](https://github.com/modxcms/revolution)) `GPL-2.0` `PHP`
- [Neos](https://www.neos.io) - 现代 CMS。Neos 或 TYPO3 Neos（针对版本 1）。 ([Source Code](https://github.com/neos)) `GPL-3.0` `PHP`
- [Noosfero](https://gitlab.com/noosfero/noosfero) - 面向社会与团结经济网络的平台，在同一系统中集成了博客、电子作品集、CMS、RSS、主题讨论、活动日程以及团结经济集体智慧。`AGPL-3.0` `Ruby`
- [Omeka](https://omeka.org) - 在你的服务器上用 Omeka 遵循 Dublin Core 标准创建复杂叙事并分享丰富藏品，专为学者、博物馆、图书馆、档案馆和爱好者设计。 ([Demo](https://omeka.org/classic/showcase/), [Source Code](https://github.com/omeka/Omeka)) `GPL-3.0` `PHP`
- [Payload CMS](https://payloadcms.com/) - 开发者优先的无头 CMS 和应用框架。 ([Source Code](https://github.com/payloadcms/payload)) `MIT` `Nodejs`
- [Pimcore](http://www.pimcore.com/) - 多渠道体验与互动管理平台。 ([Source Code](https://github.com/pimcore/pimcore)) `GPL-3.0` `PHP/Docker`
- [Plone](https://plone.org/) - 用于创建、编辑和管理数字内容（如网站、内网和定制解决方案）的 CMS 系统。 ([Source Code](https://github.com/plone)) `ZPL-2.0` `Python/Docker`
- [Publify](https://publify.github.io/) - 简洁但功能齐全的 Web 发布软件。 ([Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
- [Pushword](https://pushword.piedweb.com) - 基于 Symfony 构建的内容管理系统，页面使用 Markdown，主题使用 Twig，可选基于 Git 的扁平文件存储。 ([Source Code](https://github.com/Pushword/Pushword), [Clients](https://pushword.piedweb.com/extensions)) `MIT` `PHP`
- [REDAXO](https://www.redaxo.org) - 简单、灵活且实用的内容管理系统（文档为德语）。 ([Source Code](https://github.com/redaxo/core)) `MIT` `PHP/Docker`
- [SilverStripe](https://www.silverstripe.org) - 易于使用的 CMS，底层拥有强大的 MVC 框架。 ([Demo](https://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD-3-Clause` `PHP`
- [SPIP](https://www.spip.net/fr) - 面向互联网的发布系统，致力于协作工作、多语言环境，并让 Web 作者易于使用。 ([Source Code](https://git.spip.net/)) `GPL-3.0` `PHP`
- [Squidex](https://squidex.io) - 基于 MongoDB、CQRS 和事件溯源的无头 CMS。 ([Demo](https://cloud.squidex.io), [Source Code](https://github.com/Squidex/squidex)) `MIT` `.NET`
- [Strapi](https://strapi.io/) - 无头 CMS，让开发者快速构建内容 API，同时为内容创作者提供友好的编辑界面。 ([Source Code](https://github.com/strapi/strapi)) `MIT` `Nodejs`
- [Superdesk](https://superdesk.org/) `⚠` - End-to-end news creation, production, curation, distribution, and publishing platform. ([Source Code](https://github.com/superdesk/superdesk)) `AGPL-3.0` `Docker/Python/PHP`
- [Textpattern](https://textpattern.com/) - 灵活、优雅且易用的 CMS。 ([Demo](https://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPL-2.0` `PHP`
- [Typemill](https://typemill.net/) - 对作者友好的扁平文件 CMS，配备基于 vue.js 的可视化 Markdown 编辑器。 ([Source Code](https://github.com/typemill/typemill)) `MIT` `PHP`
- [TYPO3](https://typo3.org/) - 功能强大且先进的 CMS，拥有庞大的社区。 ([Source Code](https://github.com/TYPO3/typo3)) `GPL-2.0` `PHP`
- [Umbraco](https://umbraco.com/) - 友好的 CMS，拥有出色的社区。 ([Source Code](https://github.com/umbraco/Umbraco-CMS)) `MIT` `.NET`
- [Vvveb CMS](https://www.vvveb.com) - 功能强大且易用的 CMS，用于构建网站、博客或电商商店。 ([Demo](https://demo.vvveb.com), [Source Code](https://github.com/givanz/Vvveb)) `AGPL-3.0` `PHP/Docker`
- [Wagtail](https://wagtail.io/) - 专注于灵活性和用户体验的 Django 内容管理系统。 ([Source Code](https://github.com/wagtail/wagtail)) `BSD-3-Clause` `Python`
- [WinterCMS](https://wintercms.com/) - 基于 Laravel PHP 框架构建的快速且安全的内容管理系统。 ([Source Code](https://github.com/wintercms/winter)) `MIT` `PHP`
- [WonderCMS](https://www.wondercms.com) - 自 2008 年以来最小的扁平文件 CMS。 ([Demo](https://www.wondercms.com/demo), [Source Code](https://github.com/WonderCMS/wondercms)) `MIT` `PHP`
- [WordPress](https://wordpress.org/) - 世界上使用最广泛的博客与 CMS 引擎。 ([Source Code](https://github.com/WordPress/WordPress)) `GPL-2.0` `PHP`


### 客户关系管理（CRM）

**[`^        back to top        ^`](#awesome-selfhosted)**

[Customer relationship management (CRM)](https://en.wikipedia.org/wiki/Customer_relationship_management) is a strategic process that organizations use to manage, analyze, and improve their interactions with customers.

_Related: [Communication - Email - Mailing Lists and Newsletters](#communication---email---mailing-lists-and-newsletters), [Analytics](#analytics), [Calendar & Contacts](#calendar--contacts)_

- [Corteza](https://docs.cortezaproject.org) - CRM，包含统一工作区、企业消息传递和低代码环境，可快速、安全地交付基于记录的管理解决方案。 ([Demo](https://latest.cortezaproject.org), [Source Code](https://github.com/cortezaproject/corteza)) `Apache-2.0` `Go`
- [Django-CRM](https://DjangoCRM.github.io/info/) - 分析型 CRM，具备任务管理、邮件营销等诸多功能。Django CRM 面向个人、任意规模的企业或自由职业者，旨在提供轻松定制和快速开发。 ([Source Code](https://github.com/DjangoCRM/django-crm)) `AGPL-3.0` `Python`
- [EspoCRM](https://www.espocrm.com/) - 前端采用单页应用设计并带有 REST API 的 CRM。 ([Demo](https://demo.espocrm.com/), [Source Code](https://github.com/espocrm/espocrm)) `AGPL-3.0` `PHP`
- [Krayin](https://krayincrm.com/) - 面向中小企业和大型企业的 CRM 解决方案，提供完整的客户生命周期管理。 ([Demo](https://demo.krayincrm.com/), [Source Code](https://github.com/krayin/laravel-crm)) `MIT` `PHP`
- [Relaticle](https://relaticle.com) - 带 MCP 服务器、REST API、自定义字段和看板的 CRM，其 AI 助手的变更需经人工批准。 ([Source Code](https://github.com/relaticle/relaticle)) `AGPL-3.0` `PHP/Docker`
- [SuiteCRM](https://suitecrm.com) - 屡获殊荣的企业级 CRM。 ([Source Code](https://github.com/SuiteCRM/SuiteCRM)) `AGPL-3.0` `PHP`
- [Twenty](https://twenty.com) - 现代 CRM，提供灵活性、高级功能和时尚的设计。 ([Source Code](https://github.com/twentyhq/twenty)) `AGPL-3.0` `Docker`


### 数据库管理

**[`^        back to top        ^`](#awesome-selfhosted)**

Web interfaces for [database](https://en.wikipedia.org/wiki/Database) management. Includes tools for database analytics and visualization.

_Related: [Analytics](#analytics), [Automation](#automation)_

_See also: [dbdb.io - Database of Databases](https://dbdb.io/)_

- [Adminer](https://www.adminer.org/) - 单个 PHP 文件即可实现数据库管理。支持 MySQL、MariaDB、PostgreSQL、SQLite、MS SQL、Oracle、Elasticsearch、MongoDB 等。 ([Source Code](https://github.com/vrana/adminer)) `Apache-2.0/GPL-2.0` `PHP`
- [Azimutt](https://azimutt.app) - 为真实世界数据库（庞大且混乱）打造的视觉化数据库探索工具。探索数据库模式与数据、为其编写文档、进行扩展，甚至获得分析和指导建议。 ([Demo](https://azimutt.app/gallery/gospeak), [Source Code](https://github.com/azimuttapp/azimutt)) `MIT` `Elixir/Nodejs/Docker`
- [Baserow](https://baserow.io/) - 无需技术经验即可创建自己的数据库（Airtable 的替代品）。 ([Source Code](https://gitlab.com/baserow/baserow)) `MIT` `Docker`
- [Bytebase](https://www.bytebase.com/) - 为 DevOps 团队提供安全的数据库模式变更和版本控制，支持 MySQL、PostgreSQL、TiDB、ClickHouse 和 Snowflake。 ([Source Code](https://github.com/bytebase/bytebase)) `MIT` `Docker/K8S/Go`
- [Chartbrew](https://chartbrew.com) - 直接连接数据库和 API，利用数据创建精美图表。 ([Demo](https://app.chartbrew.com/live-demo), [Source Code](https://github.com/chartbrew/chartbrew)) `MIT` `Nodejs/Docker`
- [ChartDB](https://chartdb.io/) - 数据库图表编辑器，只需一条查询即可可视化和设计你的数据库。 ([Demo](https://app.chartdb.io), [Source Code](https://github.com/chartdb/chartdb)) `AGPL-3.0` `Nodejs/Docker`
- [CloudBeaver](https://dbeaver.com/) - 管理数据库，支持 PostgreSQL、MySQL、SQLite 等。DBeaver 的 Web/托管版本。 ([Source Code](https://github.com/dbeaver/cloudbeaver)) `Apache-2.0` `Docker`
- [d9](https://d9.webcapsule.io) - 通过直观的管理界面将 SQL 数据库转化为安全 API。数据平台和无头 CMS（Directus 的分支）。 ([Source Code](https://github.com/LaWebcapsule/d9)) `GPL-3.0` `Nodejs`
- [Databunker](https://databunker.org/) - 基于网络、符合 GDPR、用于存储个人数据或 PII 的安全数据库。 ([Source Code](https://github.com/securitybunker/databunker)) `MIT` `Docker`
- [datannur](https://datannur.com) - 轻量级数据目录，用于记录和探索结构化数据文件与数据库。 ([Demo](https://dev.datannur.com/), [Source Code](https://github.com/datannur/datannur)) `MIT` `Python`
- [Datasette](https://datasette.io/) - 探索和发布数据，支持便捷的导入导出和数据库管理。 ([Source Code](https://github.com/simonw/datasette)) `Apache-2.0` `Python/Docker`
- [drawDB](https://www.drawdb.app) - 基于浏览器的可视化数据库图表编辑器和 SQL 生成器，支持 DBML 以及 MySQL、PostgreSQL、SQLite、MariaDB、MSSQL 和 Oracle。 ([Demo](https://www.drawdb.app/editor), [Source Code](https://github.com/drawdb-io/drawdb)) `AGPL-3.0` `Nodejs/Docker`
- [Evidence](https://evidence.dev) - 基于代码的 BI 工具。用 SQL 和 Markdown 编写报告，并渲染为网站。 ([Source Code](https://github.com/evidence-dev/evidence)) `MIT` `Nodejs`
- [LibreDB Studio](https://libredb.org) - 基于浏览器的 SQL IDE，支持 PostgreSQL、MySQL、Oracle、SQL Server、MongoDB、Redis、ClickHouse、DuckDB 等，具备 SSO、审计日志、ER 图，并可通过自己的模型密钥获得可选的 AI 辅助（DataGrip、DBeaver、CloudBeaver 的替代品）。 ([Source Code](https://github.com/libredb/libredb-studio)) `MIT` `Docker/K8S`
- [Limbas](https://www.limbas.com/en/) - 用于创建数据库驱动业务应用的数据库框架。作为图形化数据库前端，它支持高效处理数据资产，并灵活开发易用的数据库应用。 ([Source Code](https://github.com/limbas/limbas)) `GPL-2.0` `PHP`
- [Mathesar](https://mathesar.org/) - 直观的界面，供各种技术水平的用户协作管理数据。基于 Postgres 构建——可连接现有数据库，也可新建数据库。 ([Source Code](https://github.com/mathesar-foundation/mathesar)) `GPL-3.0` `Docker/Python`
- [OrcaQ](https://orca-q.com) - 现代数据库客户端和 IDE，用于管理、查询和探索多种数据库类型，内置 AI 助手。 ([Source Code](https://github.com/cin12211/orca-q)) `MIT` `Nodejs/deb/Docker`
- [StackRender](https://stackrender.io/) - 数据库模式设计和 SQL 迁移生成器，支持 PostgreSQL、MySQL、MariaDB、SQLite、SQL Server 和 Oracle。 ([Demo](https://app.stackrender.io/), [Source Code](https://github.com/stackrender/stackrender)) `AGPL-3.0` `Nodejs/Docker`


### DNS

**[`^        back to top        ^`](#awesome-selfhosted)**

[DNS](https://en.wikipedia.org/wiki/Domain_Name_System) servers and management tools with advertisement blocking functionality, primarily aimed at home or small networks.

_See also: [awesome-sysadmin/DNS - Servers](https://github.com/awesome-foss/awesome-sysadmin#dns---servers), [awesome-sysadmin/DNS - Control Panels & Domain Management](https://github.com/awesome-foss/awesome-sysadmin#dns---control-panels--domain-management)_

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - 易用的广告与跟踪器拦截 DNS 服务器。 ([Source Code](https://github.com/AdguardTeam/AdGuardHome)) `GPL-3.0` `Docker`
- [blocky](https://0xerr0r.github.io/blocky/latest/) - 快速轻量的 DNS 代理，作为局域网广告拦截器使用，功能丰富（Pi-hole 的替代品）。 ([Source Code](https://github.com/0xERR0R/blocky)) `Apache-2.0` `Go/Docker`
- [Maza ad blocking](https://maza-ad-blocking.andros.dev/) - 本地广告拦截器。类似 Pi-hole，但完全在本地运行并使用你的操作系统。 ([Source Code](https://github.com/tanrax/maza-ad-blocking)) `Apache-2.0` `Shell`
- [Numa](https://numa.rs/) - 广告拦截 DNS 解析器，具备 DNSSEC 验证的递归解析、DoH/DoT/Oblivious DoH、临时覆盖规则和本地服务域名，打包为单个 Rust 二进制文件（Pi-hole、AdGuard Home、NextDNS 的替代品）。 ([Source Code](https://github.com/razvandimescu/numa)) `MIT` `Rust/Docker/Nix`
- [Pi-hole](https://pi-hole.net/) - 互联网广告的黑洞，带有用于管理和监控的 GUI。 ([Source Code](https://github.com/pi-hole/pi-hole)) `EUPL-1.2` `Shell/PHP/Docker`
- [Technitium DNS Server](https://technitium.com/dns/) - 带广告拦截功能的权威/递归 DNS 服务器。 ([Source Code](https://github.com/TechnitiumSoftware/DnsServer)) `GPL-3.0` `Docker/C#`


### 文档管理

**[`^        back to top        ^`](#awesome-selfhosted)**

A [document management system](https://en.wikipedia.org/wiki/Document_management_system) (DMS) is a system used to receive, track, manage and store documents and reduce paper.

- [BentoPDF](https://bentopdf.com) `⚠` - Powerful, privacy-first, client-side PDF toolkit that allows you to manipulate, edit, merge, and process PDF files directly in your browser. ([Demo](https://bentopdf.com), [Source Code](https://github.com/alam00000/bentopdf)) `AGPL-3.0` `Nodejs/Docker`
- [Bottle Rocket](https://bottle-rocket.app/) - 文档扫描和管理应用，兼容 Rocketbook 和 Scribzee 格式。 ([Source Code](https://github.com/gman-au/bottle-rocket-server)) `MIT` `C#/Docker`
- [Docspell](https://docspell.org) - 自动打标签的文档整理与归档工具。 ([Source Code](https://github.com/eikek/docspell)) `GPL-3.0` `Scala/Java/Docker`
- [Documenso](https://documenso.com) - 数字文档签署平台（DocuSign 的替代品）。 ([Source Code](https://github.com/documenso/documenso)) `AGPL-3.0` `Nodejs/Docker`
- [Docuseal](https://www.docuseal.co) - 创建、填写和签署数字文档（DocuSign 的替代品）。 ([Demo](https://demo.docuseal.tech/), [Source Code](https://github.com/docusealco/docuseal)) `AGPL-3.0` `Docker`
- [EveryDocs](https://github.com/jonashellmann/everydocs-core) - 面向个人使用的简单文档管理系统，具备数字化整理文档的基本功能。`GPL-3.0` `Docker/Ruby`
- [Gotenberg](https://gotenberg.dev) - 对开发者友好的 API，可与 Chromium 和 LibreOffice 等强大工具交互，将众多文档格式（HTML、Markdown、Word、Excel 等）转换为 PDF 文件，以及更多功能。 ([Source Code](https://github.com/gotenberg/gotenberg)) `MIT` `Docker`
- [I, Librarian](https://i-librarian.net) - 整理 PDF 论文和办公文档。为业界和学术界的学生及研究团队提供许多额外功能。 ([Demo](https://eu1.i-librarian.net/demo), [Source Code](https://github.com/mkucej/i-librarian-free)) `GPL-3.0` `PHP`
- [Mayan EDMS](https://www.mayan-edms.com) - 电子文档管理系统，具备预览生成、OCR 和自动分类等功能。 ([Source Code](https://gitlab.com/mayan-edms/mayan-edms)) `GPL-2.0` `Docker/K8S`
- [OpenSign](https://www.opensignlabs.com) `⚠` - Document signing software (alternative to DocuSign). ([Source Code](https://github.com/opensignlabs/opensign)) `AGPL-3.0` `Nodejs/Docker`
- [Paperless-ngx](https://docs.paperless-ngx.com/) - 通过改进的界面对所有纸质文档进行扫描、索引和归档（Paperless 的分支）。 ([Demo](https://demo.paperless-ngx.com/), [Source Code](https://github.com/paperless-ngx/paperless-ngx)) `GPL-3.0` `Python/Docker`
- [Papermerge](https://papermerge.com) - 专注于扫描文档（电子档案）的文档管理系统。文件浏览方式类似 dropbox/google drive。支持 OCR、全文搜索和文本叠加/选择。 ([Source Code](https://github.com/papermerge/papermerge-core)) `Apache-2.0` `Docker/K8S`
- [Papra](https://papra.app) - 极简主义的文档存储、管理与归档平台，设计上简单易用、人人可用。 ([Demo](https://demo.papra.app/), [Source Code](https://github.com/papra-hq/papra/)) `AGPL-3.0` `Docker`
- [PdfDing](https://www.pdfding.com) - PDF 管理器、查看器和编辑器，在多设备上提供无缝的用户体验。设计极简、快速，可使用 Docker 轻松部署。 ([Demo](https://demo.pdfding.com), [Source Code](https://codeberg.org/mrmn/PdfDing)) `AGPL-3.0` `Docker/K8S`
- [SeedDMS](https://www.seeddms.org) - 文档管理系统，具备工作流、访问权限、全文搜索等功能。 ([Demo](https://www.seeddms.org/about/), [Source Code](https://sourceforge.net/p/seeddms/code/ci/master/tree/)) `GPL-2.0` `PHP`
- [Signature PDF](https://github.com/24eme/signaturepdf) - 签署和操作 PDF，支持协作、整理、压缩和元数据编辑。 ([Demo](https://pdf.24eme.fr/)) `AGPL-3.0` `PHP/deb/Docker`
- [SimpleDMS](https://simpledms.eu) - 易用的、元数据驱动的文档管理系统（DMS），面向小型企业，几乎可以自动完成文档分类。 ([Source Code](https://github.com/simpledms/simpledms), [Clients](https://simpledms.eu/en/product/integrations)) `AGPL-3.0` `Docker`
- [SnapOtter](https://snapotter.com) - 包含 200 多个 Web 工具的套件，用于转换和编辑图像、视频、音频和 PDF，包括基于图层的图像编辑器、OCR、转录、背景移除和批量处理流水线（SmallPDF、iLovePDF、CloudConvert 的替代品）。 ([Demo](https://demo.snapotter.com), [Source Code](https://github.com/snapotter-hq/SnapOtter)) `AGPL-3.0` `Docker`
- [Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF) - 本地托管的 Web 应用，可对 PDF 文件执行多种操作，如合并、拆分、格式转换和 OCR。`Apache-2.0` `Docker/Java`


### 文档管理 - 电子书

**[`^        back to top        ^`](#awesome-selfhosted)**

[Ebook](https://en.wikipedia.org/wiki/Ebook) library management software.

- [Atsumeru](https://atsumeru.xyz) - 漫画/连环画/轻小说媒体服务器，提供 Windows、Linux、macOS 和 Android 客户端。 ([Source Code](https://github.com/Atsumeru-xyz/Atsumeru), [Clients](https://atsumeru.xyz/guides/#how-does-it-work)) `MIT` `Java/Docker`
- [Bindery](https://github.com/jarynclouatre/bindery) - 监视文件夹的电子书和漫画转换器。通过 kepubify 将 EPUB 转为 Kobo KEPUB，通过 Kindle Comic Converter 处理 CBZ/CBR/PDF，支持按设备配置档案、ComicInfo.xml 命名、章节合并成卷以及 Web 界面。`MIT` `Docker`
- [BookLogr](https://github.com/Mozzo1000/booklogr) - 轻松管理你的个人藏书。 ([Demo](https://demo.booklogr.app/)) `Apache-2.0` `Docker`
- [Calibre Web Automated](https://github.com/crocodilestick/Calibre-Web-Automated) - 一体化解决方案，结合了 Calibre-Web 的现代轻量 Web 界面与 Calibre 强大多样的功能集（Calibre Web 的分支）。`GPL-3.0` `Docker`
- [Calibre Web](https://github.com/janeczku/calibre-web) - 使用现有的 Calibre 数据库浏览、阅读和下载电子书。`GPL-3.0` `Python`
- [Calibre](https://calibre-ebook.com/) - 电子书库管理器，可查看、转换和编目绝大多数主流电子书格式的电子书，并提供内置 Web 服务器供远程客户端使用。 ([Demo](https://calibre-ebook.com/demo), [Source Code](https://github.com/kovidgoyal/calibre)) `GPL-3.0` `Python/deb`
- [Grimmory](https://grimmory.org/) - 电子书、漫画和有声书库，内置阅读器、元数据查询、多用户支持、OPDS 以及 Kobo/KOReader 同步。 ([Source Code](https://github.com/grimmory-tools/grimmory)) `AGPL-3.0` `Docker`
- [Inkheart](https://gitlab.com/Nystik/inkheart) - 轻量级 PDF 书库与阅读器。`Apache-2.0` `Docker`
- [Kapowarr](https://casvt.github.io/Kapowarr/) - 构建和管理漫画书库。按你的喜好下载、重命名、移动和转换卷中的各期漫画。 ([Source Code](https://github.com/Casvt/Kapowarr)) `GPL-3.0` `Docker/Python`
- [Kavita](https://www.kavitareader.com/) - 跨平台电子书/漫画/连环画/pdf 服务器和 Web 阅读器，支持用户管理、评分评论和元数据。 ([Demo](https://www.kavitareader.com/#demo), [Source Code](https://github.com/Kareadita/Kavita)) `GPL-3.0` `.NET/Docker`
- [kiwix-serve](https://github.com/kiwix/kiwix-tools) - 用于从 ZIM 文件提供 wiki 服务的 HTTP 守护进程。`GPL-3.0` `C++`
- [Komga](https://komga.org) - 面向漫画（comics/manga/BD）的媒体服务器，支持 API 和 OPDS，提供用于浏览书库的现代 Web 界面以及 Web 阅读器。 ([Source Code](https://github.com/gotson/komga)) `MIT` `Java/Docker`
- [MyMangaDB](https://github.com/FabianRolfMatthiasNoll/MyMangaDB) `⚠` - Manga collection manager with automatic metadata, MyAnimeList import and detailed collection statistics. `GPL-3.0` `Docker`
- [Stump](https://www.stumpapp.dev) - 支持 OPDS 的快速漫画、日本漫画和数字图书服务器。 ([Source Code](https://github.com/stumpapp/stump)) `MIT` `Rust`
- [Tome](https://tome.bndct.sh) - 电子书和漫画书库服务器，带 Web 阅读器、OPDS 和元数据抓取。KOReader 插件记录每次阅读会话并双向同步进度，支持连续阅读天数、阅读速度、热力图和每本书的统计。 ([Source Code](https://github.com/bndct-devops/tome), [Clients](https://github.com/bndct-devops/tome/blob/main/docs/koreader-plugin.md)) `AGPL-3.0` `Docker`


### 文档管理 - 机构知识库与数字图书馆

**[`^        back to top        ^`](#awesome-selfhosted)**

[Institutional repository](https://en.wikipedia.org/wiki/Institutional_repository) and [digital library](https://en.wikipedia.org/wiki/Digital_library) management software.

- [DSpace](http://www.dspace.org/) - 开箱即用的仓储库应用，为数字资源提供持久访问。 ([Source Code](https://github.com/DSpace/DSpace)) `BSD-3-Clause` `Java`
- [EPrints](https://www.eprints.org/) - 数字文档管理系统，具备灵活的元数据和工作流模型，主要面向学术机构。 ([Demo](http://tryme.demo.eprints-hosting.org/), [Source Code](https://github.com/eprints/eprints3.4)) `GPL-3.0` `Perl`
- [Fedora Commons Repository](https://wiki.lyrasis.org/display/FF/Fedora+Repository+Home) - 健壮且模块化的仓储库系统，用于管理和传播数字内容，尤其适合数字图书馆和档案馆的访问与保存。 ([Source Code](https://github.com/fcrepo/fcrepo)) `Apache-2.0` `Java`
- [InvenioRDM](https://inveniordm.docs.cern.ch/) - 高度可扩展的开箱即用研究数据管理平台，用户体验出色。 ([Demo](https://inveniordm.web.cern.ch/), [Source Code](https://github.com/inveniosoftware/invenio-app-rdm), [Clients](https://inveniosoftware.org/products/rdm/)) `MIT` `Python`
- [Islandora](https://www.islandora.ca/) - 用于浏览和管理基于 Fedora 的数字仓储库的 Drupal 模块。 ([Demo](https://sandbox.islandora.ca/), [Source Code](https://github.com/Islandora/islandora)) `GPL-3.0` `PHP`
- [Samvera Hyrax](https://samvera.org/) - Samvera 框架的前端，Samvera 本身是一个用于浏览和管理基于 Fedora 的数字仓储库的 Ruby on Rails 应用。 ([Source Code](https://github.com/samvera/hyrax)) `Apache-2.0` `Ruby`


### 文档管理 - 集成图书馆系统（ILS）

**[`^        back to top        ^`](#awesome-selfhosted)**

An [integrated library system](https://en.wikipedia.org/wiki/Integrated_library_system) is an enterprise resource planning system for a library, used to track items owned, orders made, bills paid, and patrons who have borrowed.

_Related: [Content Management Systems (CMS)](#content-management-systems-cms), [Archiving and Digital Preservation (DP)](#archiving-and-digital-preservation-dp)_

- [Evergreen](https://evergreen-ils.org) - 面向图书馆的高可扩展软件，帮助读者查找图书馆资料，并帮助图书馆管理、编目和流通这些资料。 ([Source Code](https://github.com/evergreen-library-system/Evergreen)) `GPL-2.0` `PLpgSQL`
- [Koha](https://koha-community.org/) - 企业级 ILS，包含采访、流通、编目、标签打印、断网时离线流通等模块，功能丰富。 ([Demo](https://koha-community.org/demo/), [Source Code](https://github.com/Koha-Community/Koha)) `GPL-3.0` `Perl`
- [RERO ILS](https://rero21.ch/) - 可作为服务运行的大型 ILS，具备联盟功能，主要面向图书馆网络。包含大多数标准模块（流通、采访、编目等）以及基于 Web 的公众界面和专业界面。 ([Demo](https://ils.test.rero.ch/), [Source Code](https://github.com/rero/rero-ils)) `AGPL-3.0` `Python/Docker`


### 电子商务

**[`^        back to top        ^`](#awesome-selfhosted)**

[E-commerce](https://en.wikipedia.org/wiki/E-commerce) software.

_Related: [Community-Supported Agriculture (CSA)](#community-supported-agriculture-csa)_

- [Aimeos](https://aimeos.org/) - 电商框架，基于 Laravel 构建定制在线商店、市集以及可扩展至数十亿商品的复杂 B2B 应用。 ([Demo](https://demo.aimeos.org/), [Source Code](https://github.com/aimeos/aimeos)) `LGPL-3.0/MIT` `PHP`
- [Bagisto](https://bagisto.com/en/) - 领先的 Laravel 电商框架，具备多库存来源、税务、本地化、代发货等众多出色功能。 ([Demo](https://demo.bagisto.com/), [Source Code](https://github.com/bagisto/bagisto)) `MIT` `PHP`
- [CoreShop](https://www.coreshop.org) - Pimcore 的电商插件。 ([Source Code](https://github.com/coreshop/CoreShop)) `GPL-3.0` `PHP`
- [Drupal Commerce](https://drupalcommerce.org) - Drupal CMS 的热门电商模块，支持数十个支付、配送和购物相关模块。 ([Source Code](https://git.drupalcode.org/project/commerce)) `GPL-2.0` `PHP`
- [EverShop](https://evershop.io/) `⚠` - E-commerce platform with essential commerce features. Modular architecture and fully customizable. ([Demo](https://demo.evershop.io/), [Source Code](https://github.com/evershopcommerce/evershop)) `GPL-3.0` `Docker/Nodejs`
- [Magento Open Source](https://business.adobe.com/products/magento/magento-commerce.html) - 开放全渠道创新领域的领先者。 ([Source Code](https://github.com/magento/magento2)) `OSL-3.0` `PHP`
- [MedusaJs](https://medusajs.com/) - 无头商务引擎，让开发者打造出色的数字商务体验。 ([Demo](https://next.medusajs.com/), [Source Code](https://github.com/medusajs/medusa)) `MIT` `Nodejs`
- [myCart](https://github.com/shurco/mycart) `⚠` - Shopping cart in 1 file (with support for payment by card or cryptocurrency). `MIT` `Go/Docker`
- [Open Source POS](https://github.com/opensourcepos/opensourcepos) - 基于 Web 的销售点（POS）系统。`MIT` `PHP`
- [OpenCart](https://www.opencart.com) - 购物车解决方案。 ([Source Code](https://github.com/opencart/opencart)) `GPL-3.0` `PHP`
- [PrestaShop](https://www.prestashop.com/) - 完全可扩展的电子商务解决方案。 ([Demo](https://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL-3.0` `PHP`
- [Pretix](https://pretix.eu/) - 活动门票销售平台。 ([Source Code](https://github.com/pretix/pretix)) `AGPL-3.0` `Python/Docker`
- [s-cart](https://s-cart.org/) - 面向个人和企业的电子商务网站，基于 Laravel 框架构建。 ([Demo](https://demo.s-cart.org/), [Source Code](https://github.com/gp247net/s-cart)) `MIT` `PHP`
- [Saleor](https://saleor.io) - GraphQL 原生、仅提供 API 的平台，用于构建可扩展、可组合的电子商务店面。 ([Demo](https://demo.saleor.io/), [Source Code](https://github.com/saleor/saleor)) `BSD-3-Clause` `Docker/Python`
- [Shopware Community Edition](https://www.shopware.com/en/community/community-edition/) - 源自德国的基于 PHP 的开源电子商务软件。 ([Demo](https://www.shopware.com/en/test-demo/), [Source Code](https://github.com/shopware/shopware)) `MIT` `PHP`
- [Solidus](https://solidus.io/) - 让你对商店拥有完全控制权的电子商务平台。 ([Source Code](https://github.com/solidusio/solidus)) `BSD-3-Clause` `Ruby/Docker`
- [Spree Commerce](https://spreecommerce.org) - 面向 Ruby on Rails 的完整、模块化且由 API 驱动的电子商务解决方案。 ([Demo](https://demo.spreecommerce.org/), [Source Code](https://github.com/spree/spree)) `BSD-3-Clause` `Ruby`
- [Sylius](https://sylius.com) - 基于 Symfony2 的电子商务全栈平台。 ([Demo](https://sylius.com/try/), [Source Code](https://github.com/Sylius/Sylius)) `MIT` `PHP`
- [Thelia](https://thelia.net/) - 灵活的电子商务解决方案。 ([Demo](https://demo.thelia.net/), [Source Code](https://github.com/thelia/thelia)) `LGPL-3.0` `PHP`
- [Vendure](https://www.vendure.io) - 无头商务框架。 ([Demo](https://demo.vendure.io), [Source Code](https://github.com/vendurehq/vendure)) `MIT` `Nodejs`
- [WooCommerce](https://woocommerce.com/) - 基于 WordPress 的电子商务解决方案。 ([Source Code](https://github.com/woocommerce/woocommerce)) `GPL-3.0` `PHP`


### Federated Identity & Authentication

**[`^        back to top        ^`](#awesome-selfhosted)**

[Federated identity](https://en.wikipedia.org/wiki/Federated_identity) and [authentication](https://en.wikipedia.org/wiki/Electronic_authentication) software.

**Please visit [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### Feed 阅读器

**[`^        back to top        ^`](#awesome-selfhosted)**

A [news aggregator](https://en.wikipedia.org/wiki/News_aggregator), also termed a feed aggregator, feed reader, news reader, [RSS](https://en.wikipedia.org/wiki/RSS) reader, is an application that aggregates web content such as newspapers/blogs/vlogs/podcasts in one location for easy viewing.

- [Bubo Reader](https://github.com/georgemandis/bubo-rss) - 极简到极致的 RSS 订阅源阅读器。 ([Demo](https://bubo-rss-demo.netlify.app/)) `MIT` `Nodejs`
- [CommaFeed](https://www.commafeed.com/) - 受 Google Reader 启发的 RSS 阅读器。 ([Demo](https://www.commafeed.com/#/app/category/all), [Source Code](https://github.com/Athou/commafeed)) `Apache-2.0` `Java/Docker`
- [Feeds Fun](https://feeds.fun/) - 带标签、评分和 AI 的新闻阅读器。 ([Source Code](https://github.com/Tiendil/feeds.fun)) `BSD-3-Clause` `Python`
- [FreshRSS](https://freshrss.org/) - 可自托管的 RSS 订阅源聚合器。 ([Demo](https://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS)) `AGPL-3.0` `PHP/Docker`
- [Fusion](https://github.com/0x2E/fusion) - 轻量级 RSS 聚合器与阅读器。
- [Goeland](https://github.com/slurdge/goeland) - 将任意 RSS/Atom 订阅源转换为精美的电子邮件摘要。
- [JARR](https://1pxsolidblack.pl/jarr-en.html) - JARR（Just Another RSS Reader）是一个基于 Web 的新闻聚合器与阅读器（Newspipe 的分支）。 ([Demo](https://www.jarr.info/), [Source Code](https://github.com/jaesivsm/JARR)) `AGPL-3.0` `Docker/Python`
- [Kriss Feed](https://github.com/tontof/kriss_feed) - 简单而智能（或愚笨）的订阅源阅读器。
- [Leed](https://github.com/LeedRSS/Leed) - 极简的 RSS 聚合器（Leed 是 Light Feed 的缩写）。
- [Miniflux](https://miniflux.app/) - 极简的新闻阅读器。 ([Source Code](https://github.com/miniflux/v2)) `Apache-2.0` `Go/deb/Docker`
- [NewsBlur](https://www.newsblur.com/) - 让人们聚在一起谈论世界的个人新闻阅读器。旧乐器奏出的新声音。 ([Source Code](https://github.com/samuelclay/NewsBlur)) `MIT` `Python`
- [Newspipe](https://git.sr.ht/~cedric/newspipe) - Web 新闻阅读器。 ([Demo](https://www.newspipe.org/signup)) `AGPL-3.0` `Python`
- [reader](https://github.com/lemon24/reader) - 订阅源阅读器 Web 应用与程序库（因此你可以用它构建自己的阅读器），仅依赖标准库和纯 Python 依赖。
- [Readflow](https://readflow.app) - 轻量级新闻阅读器，具有现代界面与功能：全文搜索、自动分类、归档、离线支持和通知。 ([Source Code](https://github.com/ncarlier/readflow)) `AGPL-3.0` `Go/Docker`
- [RSS-Bridge](https://github.com/RSS-Bridge/rss-bridge) - 为没有订阅源的网站生成 RSS/ATOM 订阅源。
- [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - 易于使用的基于 Web 的 RSS 聚合器与阅读器，兼容 Fever API（Google Reader 的替代品）。
- [RSS2EMail](https://github.com/rss2email/rss2email) - 获取 RSS/Atom 订阅源并将新内容推送到任意电子邮件接收器，支持 OPML。
- [RSSHub](https://docs.rsshub.app) - 易于使用且可扩展的 RSS 订阅源聚合器，能够从几乎任何来源生成 RSS 订阅源，涵盖社交媒体到大学院系。 ([Demo](https://rsshub.app), [Source Code](https://github.com/DIYgod/RSSHub)) `MIT` `Nodejs/Docker`
- [Selfoss](https://selfoss.aditu.de/) - 新一代多用途 RSS 阅读器、实时流、混搭与聚合 Web 应用。 ([Source Code](https://github.com/fossar/selfoss)) `GPL-3.0` `PHP`
- [Stringer](https://github.com/stringer-rss/stringer) - 尚在开发中的反社交 RSS 阅读器。
- [Tiny Tiny RSS](https://tt-rss.org) - 基于 Web 的新闻订阅（RSS/Atom）阅读器与聚合器。 ([Source Code](https://github.com/tt-rss/tt-rss)) `GPL-3.0` `Docker/PHP`
- [TinyFeed](https://feed.lovergne.dev/) - 通过简单的 CLI 从一组订阅源生成静态 HTML 页面。 ([Demo](https://feed.lovergne.dev/demo), [Source Code](https://github.com/TheBigRoomXXL/tinyfeed)) `MIT` `Go/Docker`
- [Upvote RSS](https://www.upvote-rss.com/) `⚠` - Generate rich RSS feeds from Reddit, Hacker News, Lemmy, Mbin, and more. ([Demo](https://www.upvote-rss.com/), [Source Code](https://github.com/johnwarne/upvote-rss)) `MIT` `Docker/PHP`
- [Yarr](https://github.com/nkanaev/yarr) - Yarr（yet another rss reader）是一个基于 Web 的订阅源聚合器，既可用作桌面应用，也可用作个人服务器。


### 文件传输与同步

**[`^        back to top        ^`](#awesome-selfhosted)**

[File transfer](https://en.wikipedia.org/wiki/File_transfer), [sharing](https://en.wikipedia.org/wiki/File_sharing) and [synchronization software](https://en.wikipedia.org/wiki/File_synchronization) software.

_Related: [Groupware](#groupware)_

- [bewCloud](https://bewcloud.com) - 文件共享与同步、笔记和照片（Nextcloud 及 ownCloud RSS 阅读器的替代品）。 ([Source Code](https://github.com/bewcloud/bewcloud), [Clients](https://github.com/bewcloud)) `AGPL-3.0` `Docker`
- [Cloudreve](https://cloudreve.org/) - 文件管理与共享系统，支持多种存储提供商。 ([Demo](https://demo.cloudreve.org), [Source Code](https://github.com/cloudreve/cloudreve)) `GPL-3.0` `Docker/Go`
- [Git Annex](https://git-annex.branchable.com/) - 在计算机、服务器和外部硬盘之间进行文件同步。 ([Source Code](https://git.joeyh.name/index.cgi/git-annex.git/)) `GPL-3.0` `Haskell`
- [Kinto](https://kinto.readthedocs.org) - 具备同步和共享能力的极简 JSON 存储服务。 ([Source Code](https://github.com/Kinto/kinto)) `Apache-2.0` `Python`
- [Nextcloud](https://nextcloud.com/) - 以自己的方式从任意设备访问和共享文件、日历、联系人、邮件等。 ([Demo](https://try.nextcloud.com/), [Source Code](https://github.com/nextcloud/server), [Clients](https://apps.nextcloud.com)) `AGPL-3.0` `PHP/deb`
- [OpenCloud](https://docs.opencloud.eu/) - 文件共享与协作平台。 ([Source Code](https://github.com/opencloud-eu/opencloud)) `Apache-2.0` `Docker/Go/Nodejs`
- [OpenSSH SFTP server](https://www.openssh.com/) - 安全文件传输程序。 ([Source Code](https://cvsweb.openbsd.org/src/usr.bin/ssh?sort=File)) `BSD-2-Clause` `C/deb`
- [ownCloud](https://owncloud.org/) - 保存、同步、查看、编辑和共享文件、日历、通讯录等的一体化解决方案。 ([Source Code](https://github.com/owncloud/core), [Clients](https://github.com/owncloud/core/wiki/Apps)) `AGPL-3.0` `PHP/Docker/deb`
- [Peergos](https://peergos.org) - 安全且私密的在线空间，可存储、共享和查看照片、视频、音乐和文档，还包含日历、新闻订阅源、任务列表、聊天和电子邮件客户端。 ([Source Code](https://github.com/Peergos/Peergos)) `AGPL-3.0` `Java`
- [Puter](https://puter.com/) - 基于 Web 的操作系统，设计上功能丰富、速度极快且高度可扩展。 ([Demo](https://puter.com/), [Source Code](https://github.com/heyputer/puter)) `AGPL-3.0` `Nodejs/Docker`
- [Pydio](https://pydio.com/) - 将任意 Web 服务器转变为强大的文件管理系统，可作为主流云存储服务商的替代品。 ([Demo](https://pydio.com/en/demo), [Source Code](https://github.com/pydio/cells)) `AGPL-3.0` `Go`
- [Samba](https://www.samba.org/) - 面向 Linux 和 Unix 的标准 Windows 互操作程序套件。它为所有使用 SMB/CIFS 协议的客户端提供安全、稳定且快速的文件和打印服务。 ([Source Code](https://git.samba.org/samba.git/)) `GPL-3.0` `C`
- [Seafile](https://www.seafile.com/en/home/) - 主要面向团队和组织的文件托管与共享解决方案。 ([Source Code](https://github.com/haiwen/seafile)) `GPL-2.0/GPL-3.0/AGPL-3.0/Apache-2.0` `C`
- [Sync-in](https://sync-in.com) - 文件存储、同步、共享与协作，具备实时编辑、权限管理以及桌面/CLI 客户端。 ([Demo](https://sync-in.com/docs/demo), [Source Code](https://github.com/Sync-in/server), [Clients](https://github.com/Sync-in/desktop)) `AGPL-3.0` `Nodejs/Docker`
- [Syncthing](https://syncthing.net/) - 点对点文件同步工具。 ([Source Code](https://github.com/syncthing/syncthing)) `MPL-2.0` `Go/Docker/deb`
- [Unison](https://www.cis.upenn.edu/~bcpierce/unison/) - 适用于 OSX、Unix 和 Windows 的文件同步工具。 ([Source Code](https://github.com/bcpierce00/unison)) `GPL-3.0` `deb/OCaml`


### File Transfer - Distributed Filesystems

**[`^        back to top        ^`](#awesome-selfhosted)**

Network distributed filesystems.

**Please visit [awesome-sysadmin/Distributed Filesystems](https://github.com/awesome-foss/awesome-sysadmin#distributed-filesystems)**



### 文件传输 - 对象存储与文件服务器

**[`^        back to top        ^`](#awesome-selfhosted)**

[Object storage](https://en.wikipedia.org/wiki/Object_storage) is a computer data storage that manages data as objects, as opposed to other storage architectures like file systems which manages data as a file hierarchy, and block storage which manages data as blocks within sectors and tracks.

- [GarageHQ](https://garagehq.deuxfleurs.fr/) - 地理分布式、兼容 S3 的存储服务，可满足多种需求。 ([Source Code](https://git.deuxfleurs.fr/Deuxfleurs/garage)) `AGPL-3.0` `Docker/Rust`
- [Harbor](https://goharbor.io/) - 云原生镜像仓库，可存储、签名和扫描内容。 ([Source Code](https://github.com/goharbor/harbor)) `Apache-2.0` `Docker/K8S`
- [s3-orchestrator](https://s3-orchestrator.munchbox.cc) - 存储编排层，将多个云提供商呈现为单一 S3 端点，并在其间保留 N 个副本并支持读取故障转移；此外还可选支持按后端设置字节、请求、入站和出站流量限制、zstd 压缩和信封加密。 ([Source Code](https://github.com/afreidah/s3-orchestrator)) `MIT` `Go/Docker/deb/K8S`
- [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - 分布式文件系统，支持 WebDAV、S3 API、FUSE 挂载、HDFS 等，针对大量小文件优化，且易于扩容。
- [Zenko CloudServer](https://www.zenko.io/cloudserver) - 前端实现 Amazon S3 协议，后端将存储能力对接至多个云，包括 Azure 和 Google。 ([Source Code](https://github.com/scality/cloudserver)) `Apache-2.0` `Docker/Nodejs`
- [ZOT OCI Registry](https://zotregistry.dev) - 生产就绪、供应商中立的 OCI 原生容器镜像仓库。 ([Demo](https://zothub.io), [Source Code](https://github.com/project-zot/zot)) `Apache-2.0` `Go/Docker`


### 文件传输 - 点对点分享

**[`^        back to top        ^`](#awesome-selfhosted)**

[Peer-to-peer file sharing](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing) is the distribution and [sharing](https://en.wikipedia.org/wiki/File_sharing) of digital media using [peer-to-peer](https://en.wikipedia.org/wiki/Peer-to-peer) (P2P) networking technology.

- [bittorrent-tracker](https://webtorrent.io/) - 简单、健壮的 BitTorrent tracker（客户端与服务器）实现。 ([Source Code](https://github.com/webtorrent/bittorrent-tracker)) `MIT` `Nodejs`
- [DashBeam](https://dashbeam.net) - 采用点对点网络的文件传输工具，可传输任意大小的文件。 ([Demo](https://app.dashbeam.net/), [Source Code](https://github.com/tonyantony300/dashbeam)) `AGPL-3.0` `deb/Docker`
- [Deluge](https://deluge-torrent.org/) - 轻量级、跨平台的 BitTorrent 客户端。 ([Source Code](https://git.deluge-torrent.org/deluge/tree/?h=develop)) `GPL-3.0` `Python/deb`
- [PrivyDrop](https://www.privydrop.app) - 基于 WebRTC 的简单易用、支持断点续传的点对点文本、图片和文件传输工具。 ([Source Code](https://github.com/david-bai00/PrivyDrop)) `MIT` `Docker/Nodejs`
- [qBittorrent](https://www.qbittorrent.org/) - 免费的跨平台 BitTorrent 客户端，带有功能丰富的 Web UI 用于远程访问。 ([Source Code](https://github.com/qbittorrent/qBittorrent)) `GPL-2.0` `C++`
- [slskd](https://github.com/slskd/slskd) `⚠` - Modern client-server application for the Soulseek file sharing network. `AGPL-3.0` `Docker/C#`
- [Transmission](https://transmissionbt.com/) - 快速、易用、免费的 BitTorrent 客户端。 ([Source Code](https://github.com/transmission/transmission)) `GPL-3.0` `C++/deb`
- [Webtor](https://github.com/webtor-io/self-hosted) - 基于 Web 的种子客户端，支持即时音频/视频流播放。 ([Demo](https://webtor.io)) `MIT` `Docker`


### 文件传输 - 单击与拖拽上传

**[`^        back to top        ^`](#awesome-selfhosted)**

Simplified file servers for sharing of one-time/short-lived/temporary files, providing single-click or [drag-and-drop](https://en.wikipedia.org/wiki/Drag_and_drop) upload functionality.

- [015](https://send.fudaoyuan.icu) - 临时文件共享平台，专注于提供一次性的临时文件和文本上传、处理与共享服务。 ([Source Code](https://github.com/keven1024/015)) `AGPL-3.0` `Docker`
- [Chibisafe](https://chibisafe.app) - 旨在易于使用和搭建的文件上传服务。它接受文件、照片、文档以及任何你能想到的内容，并生成一个可共享的链接供你发送给他人。 ([Source Code](https://github.com/chibisafe/chibisafe)) `MIT` `Docker/Nodejs`
- [Digirecord](https://ladigitale.dev/digirecord/) - 录制并共享音频文件（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digirecord)) `AGPL-3.0` `Nodejs/PHP`
- [elixire](https://gitlab.com/elixire/elixire) - 简单而先进的截图上传与链接缩短服务。 ([Clients](https://gitlab.com/elixire/elixiremanager)) `AGPL-3.0` `Python`
- [Files Sharing](https://github.com/axeloz/filesharing) - 基于唯一且临时链接的文件共享应用。
- [Flare](https://github.com/FlintSH/Flare) - 无臃肿、现代且高度可配置的文件/截图仓库服务器，支持 ShareX、Flameshot 和 Spectacle，并提供 OCR 搜索等更多功能。
- [Gokapi](https://github.com/Forceu/gokapi) - 轻量级文件共享服务器，文件在达到设定下载次数或天数后过期。类似于已停止服务的 Firefox Send，区别在于仅允许管理员上传文件。
- [goploader](https://depado.github.io/goploader/) - 轻松的文件共享，支持服务器端加密，兼容 curl/httpie/wget。 ([Source Code](https://github.com/Depado/goploader)) `MIT` `Go`
- [GoSƐ](https://codeberg.org/stv0g/gose) - 专注于可扩展性和简洁性的现代文件上传器。它仅依赖 S3 存储后端，因此可水平扩展，无需额外的数据库或缓存。
- [Jirafeau](https://gitlab.com/jirafeau/Jirafeau) - 一键文件共享项目。选择文件、上传、分享链接，仅此而已。
- [OnionShare](https://github.com/onionshare/onionshare) - 安全且匿名地共享任意大小的文件。
- [PicoShare](https://github.com/mtlynch/picoshare) - 极简且易于托管的图片及其他文件共享服务。 ([Clients](https://github.com/mtlynch/picoshare#third-party-clients)) `AGPL-3.0` `Go/Docker`
- [PictShare](https://www.pictshare.net/) - 多语言图片托管服务，提供简单的缩放与上传 API。 ([Source Code](https://github.com/HaschekSolutions/pictshare)) `Apache-2.0` `PHP/Docker`
- [Pingvin Share X](https://github.com/smp46/pingvin-share-x) - 文件共享平台，支持登录、反向共享、共享过期、S3 Buckets、高级身份验证、用于安全扫描的 ClamAV 等（Pingvin Share 的分支）。
- [Plik](https://github.com/root-gg/plik) - 可扩展且友好的临时文件上传系统。 ([Demo](https://plik.root.gg/)) `MIT` `Go/Docker`
- [ProjectSend](https://www.projectsend.org/) - 上传文件并将其分配给你创建的特定客户，让这些客户可以访问这些文件。 ([Source Code](https://github.com/projectsend/projectsend)) `GPL-2.0` `PHP`
- [PsiTransfer](https://github.com/psi-4ward/psitransfer) - 简单的文件共享解决方案，具备强大的上传/下载断点续传和密码保护功能。
- [QuickShare](https://ihexxa.github.io/quickshare.site/) - 在不同设备之间快速、简单地共享文件。 ([Source Code](https://github.com/ihexxa/quickshare)) `LGPL-3.0` `Docker/Go`
- [Safebucket](https://docs.safebucket.io/) - 文件共享平台，采用可插拔基础设施，上传和下载直接在客户端与兼容 S3 的存储之间进行。 ([Source Code](https://github.com/safebucket/safebucket)) `Apache-2.0` `Go/Docker`
- [sE2EEnd](https://github.com/sE2EEnd/sE2EEnd) - 端到端加密的文件共享，具备密码保护、下载限制和自动过期功能，并集成 Keycloak 进行身份验证。
- [Sharry](https://github.com/eikek/sharry) - 在已认证用户与匿名用户之间通过互联网轻松共享文件（双向均可），支持断点续传的上传和下载。
- [Shifter](https://github.com/TobySuch/Shifter) - 简单的文件共享 Web 应用。
- [Slink](https://docs.slinkapp.io/) - 图片共享平台，旨在让用户完全掌控自己的媒体共享体验。 ([Source Code](https://github.com/andrii-kryvoviaz/slink)) `AGPL-3.0` `Docker`
- [snowshare](https://github.com/TuroYT/snowshare) - 文件和链接共享平台，提供 URL 缩短、代码片段共享和文件上传功能，支持自定义过期时间、隐私设置和二维码。 ([Demo](https://s.romain-pinsolle.fr)) `CC0-1.0` `Nodejs/Docker`
- [transfer.sh](https://github.com/dutchcoders/transfer.sh) - 从命令行轻松共享文件。
- [Uguu](https://github.com/nokonoko/uguu) - 存储文件并在一段时间后删除。
- [XBackBone](https://xbackbone.app/) - 简单、快速且轻量的文件管理器，集成了 ShareX 等即时共享工具。 ([Source Code](https://github.com/SergiX44/XBackBone)) `AGPL-3.0` `PHP/Docker`
- [Zipline](https://github.com/diced/zipline) - 轻量、快速且可靠的文件共享服务器，通常与 ShareX 搭配使用，提供基于 React 的 Web UI 和快速 API。


### 文件传输 - 基于 Web 的文件管理器

**[`^        back to top        ^`](#awesome-selfhosted)**

Web-based [file managers](https://en.wikipedia.org/wiki/File_manager).

_Related: [Groupware](#groupware)_

- [Apaxy](https://oupala.github.io/apaxy/) - 旨在提升 Web 目录浏览体验的主题，使用 mod_autoindex Apache 模块和一些 CSS 覆盖目录列表的默认样式。 ([Source Code](https://github.com/oupala/apaxy)) `GPL-3.0` `Javascript`
- [ClyoCloud](https://clyo.cloud/) - 为隐私、效率和美观而打造的个人云存储与媒体管理应用。 ([Source Code](https://code.weexnes.dev/ClyoCloud)) `AGPL-3.0` `Nodejs`
- [copyparty](https://github.com/9001/copyparty) - 便携式文件服务器，具备加速的可续传上传、去重、WebDAV、FTP、zeroconf、媒体索引、视频缩略图、音频转码和只写文件夹等功能，单文件即可运行且无强制依赖。 ([Demo](https://a.ocv.me/pub/demo/)) `MIT` `Python`
- [Directory Lister](https://www.directorylister.com/) - 基于 PHP 的简单目录列表工具，可列出目录及其所有子目录并支持在其中导航。 ([Source Code](https://github.com/DirectoryLister/DirectoryLister)) `MIT` `PHP/Docker`
- [FileGator](https://filegator.io/) - 功能强大的多用户文件管理器，带有单页前端。 ([Demo](https://demo.filegator.io), [Source Code](https://github.com/filegator/filegator)) `MIT` `PHP/Docker`
- [FileRise](https://github.com/error311/FileRise) - Web 文件管理器，具备上传、标签、共享链接、画廊/表格视图和浏览器内编辑器。 ([Demo](https://github.com/error311/FileRise?tab=readme-ov-file#live-demo)) `MIT` `Docker/PHP`
- [Filestash](https://www.filestash.app/) - Web 文件管理器，让你管理位于任何地方的数据：FTP、SFTP、WebDAV、Git、S3、Minio、Dropbox 或 Google Drive。 ([Demo](https://demo.filestash.app/), [Source Code](https://github.com/mickael-kerjean/filestash)) `AGPL-3.0` `Docker`
- [IFM](https://github.com/misterunknown/ifm) - 单脚本文件管理器。
- [mikochi](https://github.com/zer0tonin/Mikochi) - 浏览远程文件夹，上传、删除、重命名、下载文件，并将文件流式播放到 VLC/mpv。
- [miniserve](https://github.com/svenstaro/miniserve) - 通过 HTTP 提供文件和目录服务的 CLI 工具。
- [ResourceSpace](https://www.resourcespace.com) - 整理数字资产的简单、快速且免费的方式。 ([Demo](https://www.resourcespace.com/trial), [Source Code](https://www.resourcespace.com/svn)) `BSD-4-Clause` `PHP`
- [slcl](https://codeberg.org/xavidcr/slcl) - 简单轻量的 Web 云存储。
- [Surfer](https://git.cloudron.io/cloudron/surfer) - 带有 Web UI 管理文件的简单静态文件服务器。
- [TagSpaces](https://www.tagspaces.org/) - 离线、跨平台的文件管理器与整理工具，也可用作笔记应用。其 WebDAV 版本可安装在 Nextcloud 或 ownCloud 等 WebDAV 服务器之上。 ([Demo](https://demo.tagspaces.com), [Source Code](https://github.com/tagspaces/tagspaces)) `AGPL-3.0` `Nodejs`
- [Tiny File Manager](https://tinyfilemanager.github.io) - 基于 PHP 的 Web 文件管理器，单文件即可实现简单、快速、小巧的文件管理。 ([Demo](https://tinyfilemanager.github.io/demo/), [Source Code](https://github.com/prasathmani/tinyfilemanager)) `GPL-3.0` `PHP`


### 游戏

**[`^        back to top        ^`](#awesome-selfhosted)**

Multiplayer game servers and [browser games](https://en.wikipedia.org/wiki/Browser_game).

_Related: [Games - Administrative Utilities & Control Panels](#games---administrative-utilities--control-panels)_

- [0 A.D.](https://play0ad.com/) - 跨平台的古代战争实时战略游戏。 ([Source Code](https://gitea.wildfiregames.com/0ad/0ad)) `MIT/GPL-2.0/Zlib` `C++/C/deb`
- [A Dark Room](https://github.com/doublespeakgames/adarkroom) - 面向浏览器的极简文字冒险游戏。 ([Demo](https://adarkroom.doublespeakgames.com/)) `MPL-2.0` `Javascript`
- [DDraceNetwork](https://ddnet.org/) - DDRace 的合作横版过关版本，是 Teeworlds 的一个改版，以独特的合作玩法为特色。 ([Source Code](https://github.com/ddnet/ddnet)) `Zlib` `C++`
- [Digibuzzer](https://digibuzzer.app/) - 围绕联网抢答器创建虚拟游戏室（文档为法语）。 ([Demo](https://digibuzzer.app/), [Source Code](https://codeberg.org/ladigitale/digibuzzer)) `AGPL-3.0` `Nodejs`
- [Hypersomnia](https://github.com/TeamHypersomnia/Hypersomnia) - 竞技性俯视角射击游戏，融合了 Counter-Strike 与 Hotline Miami 的风格。可运行于 Linux、Windows、MacOS 和 Web。 ([Demo](https://hypersomnia.io)) `AGPL-3.0` `C++/Docker`
- [Lila](https://lichess.org/) - 为 lichess.org 提供支持的无广告国际象棋服务器，配有官方 iOS 和 Android 客户端。 ([Source Code](https://github.com/lichess-org/lila)) `AGPL-3.0` `Scala`
- [Luanti](https://www.luanti.org/) - 体素游戏引擎（前身为 Minetest）。可以游玩我们的众多游戏之一、按自己的喜好修改游戏、制作自己的游戏，或在多人服务器上游玩。 ([Source Code](https://github.com/luanti-org/luanti)) `LGPL-2.1/MIT/Zlib` `C++/Lua/deb`
- [Mindustry](https://mindustrygame.github.io/) - 类 Factorio 的塔防游戏。构建生产线以收集更多资源，并建造复杂的设施。 ([Source Code](https://github.com/Anuken/Mindustry)) `GPL-3.0` `Java`
- [MTA:SA](https://multitheftauto.com/) `⚠` - Add network play functionality to Rockstar North's Grand Theft Auto game series, in which this functionality is not originally found. ([Source Code](https://github.com/multitheftauto/mtasa-blue)) `GPL-3.0` `C++`
- [OpenTTD](https://www.openttd.org/) - 运输大亨模拟游戏。 ([Source Code](https://github.com/OpenTTD/OpenTTD), [Clients](https://bananas.openttd.org/)) `GPL-2.0` `C++/Docker`
- [piqueserver](https://github.com/piqueserver/piqueserver) - openspades 的服务器，这是一款在可破坏体素世界中的第一人称射击游戏。 ([Clients](https://github.com/yvt/openspades)) `GPL-3.0` `Python/C++`
- [Posio](https://github.com/abrenaut/posio) - 地理多人游戏。
- [Razzia](https://github.com/Ralex91/Razzia) - 问答游戏平台，为小型活动设计（Kahoot! 的替代品）。
- [Red Eclipse 2](https://www.redeclipse.net/) - 类似 Unreal Tournament 的竞技场第一人称射击游戏。 ([Source Code](https://github.com/redeclipse/base)) `Zlib/MIT/CC-BY-SA-4.0` `C/C++/deb`
- [Scribble.rs](https://github.com/scribble-rs/scribble.rs) - 基于 Web 的你画我猜游戏。 ([Demo](https://scribblers.fly.dev)) `BSD-3-Clause` `Go/Docker`
- [Suroi](https://suroi.io/) - 受 surviv.io 启发的 2D 大逃杀游戏。 ([Demo](https://suroi.io/), [Source Code](https://github.com/HasangerGames/suroi)) `GPL-3.0` `Nodejs`
- [The Battle for Wesnoth](https://github.com/wesnoth/wesnoth) - 高奇幻主题的回合制战术策略游戏，包含单人模式和在线/热座多人对战。
- [Veloren](https://veloren.net/) - 多人 RPG，灵感来自 Cube World、Legend of Zelda、Dwarf Fortress 和 Minecraft。 ([Source Code](https://gitlab.com/veloren/veloren)) `GPL-3.0` `Rust`
- [Zero-K](https://zero-k.info/) - 基于 Springrts 引擎的传统实时战略游戏，注重通过地形操纵、物理效果和大量独特单位来激发玩家创造力，同时保持平衡以支持竞技对战。 ([Source Code](https://github.com/ZeroK-RTS/Zero-K)) `GPL-2.0` `Lua`


### 游戏 - 管理工具与控制面板

**[`^        back to top        ^`](#awesome-selfhosted)**

Utilities for managing game servers and game libraries.

_Related: [Games](#games)_

- [auto-mcs](https://www.auto-mcs.com) - 跨平台的 Minecraft 服务器管理器。 ([Source Code](https://github.com/macarooni-man/auto-mcs)) `AGPL-3.0` `Python`
- [Calagopus](https://calagopus.com) - 现代游戏服务器管理面板。以业界领先的性能部署、监控和管理 Minecraft、Hytale 及其他游戏服务器。 ([Source Code](https://github.com/calagopus/panel)) `MIT` `Rust/Docker/deb`
- [Crafty Controller](https://craftycontrol.com/) - Minecraft 启动器和管理器，允许用户通过友好的界面启动和管理 Minecraft 服务器。 ([Source Code](https://gitlab.com/crafty-controller/crafty-4)) `GPL-3.0` `Docker/Python`
- [Drop](https://droposs.org) - 游戏分发平台，旨在高效分发和共享无 DRM 的游戏（Steam、GameVault 的替代品）。 ([Source Code](https://github.com/Drop-OSS/drop), [Clients](https://github.com/Drop-OSS/drop-app)) `AGPL-3.0` `Docker`
- [EasyWI](https://easy-wi.com) - 允许管理游戏服务器等服务器守护进程的 Web 界面。此外还提供 CMS，包含完全自动化的游戏和语音服务器租用服务。 ([Source Code](https://github.com/easy-wi/developer/)) `GPL-3.0` `PHP/Shell`
- [GameAP](https://gameap.com/) - 用于管理 Linux 和 Windows 上游戏服务器的游戏管理面板。 ([Demo](https://demo.gameap.com/), [Source Code](https://github.com/gameap/gameap), [Clients](https://plugins.gameap.dev/)) `MIT` `Go/Docker`
- [Gameyfin](https://gameyfin.org) - 视频游戏库管理器，支持自动扫描、Web 访问、下载和插件。 ([Source Code](https://github.com/gameyfin/gameyfin)) `AGPL-3.0` `Docker`
- [Gaseous Server](https://github.com/gaseous-project/gaseous-server) `⚠` - Game ROM manager with a built-in web-based emulator using multiple sources to identify and provide metadata. `AGPL-3.0` `Docker/.NET`
- [Lancache](https://lancache.net) `⚠` - LAN Party game caching made easy. ([Source Code](https://github.com/lancachenet/monolithic)) `MIT` `Docker/Shell`
- [LinuxGSM](https://linuxgsm.com/) - 在 Linux 上部署和管理专用游戏服务器的 CLI 工具：支持超过 120 款游戏。 ([Source Code](https://github.com/GameServerManagers/LinuxGSM)) `MIT` `Shell`
- [Minus Games](https://accessory.github.io/minus_games_user_guide) - 在多台设备之间同步游戏和存档文件。 ([Source Code](https://github.com/Accessory/minus_games)) `MIT` `Rust`
- [Ownfoil](https://github.com/a1ex4/ownfoil) - Nintendo Switch 游戏库管理器，支持自动化管理任务（文件识别与整理、缺失更新/DLC 检测），将游戏库提供给 Switch 上多个受支持的客户端，并支持商店自定义和多用户身份验证。
- [Pelican Panel](https://pelican.dev/) - 用于轻松管理游戏服务器的 Web 应用，提供友好的界面用于部署、配置和管理服务器、服务器监控工具以及丰富的自定义选项（Pterodactyl 的分支）。 ([Source Code](https://github.com/pelican/panel)) `AGPL-3.0` `PHP/Docker`
- [PKVault](https://github.com/Chnapy/PKVault) - 集中式宝可梦存储管理与图鉴应用（Pokémon Home 的替代品）。 ([Demo](https://pkvault-demo.chnapy.dev)) `GPL-3.0` `Docker`
- [Pterodactyl](https://pterodactyl.io/) - 游戏服务器管理面板，为最终用户提供直观的 UI。 ([Source Code](https://github.com/pterodactyl/panel)) `MIT` `PHP`
- [PufferPanel](https://www.pufferpanel.com/) - 为小型网络和游戏服务器提供商设计的游戏服务器管理面板。 ([Source Code](https://github.com/pufferpanel/pufferpanel)) `Apache-2.0` `Go`
- [RetroArr](https://retroarr.app) `⚠` - Game library manager for PC and retro consoles, with metadata scraping, indexer search, download automation and browser-based emulation (alternative to RomM). ([Source Code](https://github.com/RiDDiX/RetroArr)) `MIT` `Docker/.NET`
- [Retrom](https://github.com/JMBeresford/retrom) - 私有云游戏库分发服务器 + 前端/启动器。
- [RomM](https://romm.app/) `⚠` - ROM manager for organizing, enriching, and playing retro games, with support for 400+ platforms. ([Demo](https://demo.romm.app/), [Source Code](https://github.com/rommapp/romm)) `AGPL-3.0` `Docker`
- [SourceBans++](https://sbpp.github.io/) - 针对 Source 引擎游戏的管理员、封禁和通信管理系统。 ([Source Code](https://github.com/sbpp/sourcebans-pp)) `CC-BY-SA-4.0` `PHP`
- [Sunshine](https://app.lizardbyte.dev/Sunshine/) - 面向 Moonlight 的远程游戏串流主机，支持最高每秒 120 帧和 4K 分辨率。 ([Source Code](https://github.com/LizardByte/Sunshine)) `GPL-3.0` `C++/deb/Docker`


### 家谱

**[`^        back to top        ^`](#awesome-selfhosted)**

[Genealogy software](https://en.wikipedia.org/wiki/Genealogy_software) used to record, organize, and publish genealogical data.

- [Genea.app](https://www.genea.app/) - 以隐私为设计理念的系谱工具，任何人都可以用它创建或编辑自己的家谱。数据以 GEDCOM 格式存储，所有处理均在浏览器中完成。 ([Source Code](https://github.com/genea-app/genea-app)) `MIT` `Javascript`
- [Genealogy](https://genealogy.kreaweb.be/) - 记录家庭成员及其关系并构建家谱。 ([Demo](https://genealogy.kreaweb.be/), [Source Code](https://github.com/MGeurts/genealogy)) `MIT` `PHP`
- [GeneWeb](https://github.com/geneweb/geneweb/wiki) - 可离线使用或作为 Web 服务使用的系谱软件。 ([Source Code](https://github.com/geneweb/geneweb)) `GPL-2.0` `OCaml`
- [Gramps Web](https://www.grampsweb.org/) - 用于协作系谱的 Web 应用，基于系谱桌面应用 Gramps 并与其互操作。 ([Demo](https://gramps-project.github.io/gramps-web-api/), [Source Code](https://github.com/gramps-project/gramps-web-api)) `AGPL-3.0` `Docker`
- [webtrees](https://www.webtrees.net) - Web 上领先的在线协作系谱应用。 ([Demo](https://dev.webtrees.net/demo-stable/index.php?ctype=gedcom&ged=demo), [Source Code](https://github.com/fisharebest/webtrees)) `GPL-3.0` `PHP`


### 生成式人工智能（GenAI）

**[`^        back to top        ^`](#awesome-selfhosted)**

[Generative Artificial Intelligence (GenAI)](https://en.wikipedia.org/wiki/Generative_artificial_intelligence) is a subset of [artificial intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) that uses generative models to produce text, images, videos, or other forms of data.

- [Agenta](https://agenta.ai/) - 用于提示词管理、LLM 评估和可观测性的 LLMOps 平台。通过协作式提示词工程构建、评估和监控生产级 LLM 应用。 ([Source Code](https://github.com/agenta-ai/agenta)) `MIT` `Docker`
- [AnythingLLM](https://anythingllm.com/) - 一体化的桌面与 Docker AI 应用，内置 RAG、AI 代理、无代码代理构建器、MCP 兼容等更多功能。 ([Source Code](https://github.com/Mintplex-Labs/anything-llm)) `MIT` `Nodejs/Docker`
- [GoModel](https://gomodel.enterpilot.io/) - 用 Go 编写的 AI 网关，为多个 LLM 提供商提供统一的 OpenAI 兼容 API，具备美元成本跟踪、预算、使用分析、防护栏、缓存和管理仪表板。 ([Source Code](https://github.com/ENTERPILOT/GoModel)) `MIT` `Go/Docker`
- [Khoj](https://khoj.dev/) - 你的 AI 第二大脑。从网络或你的文档中获取答案。构建自定义代理、安排自动化任务、进行深度研究。将任何在线或本地 LLM 变成你的个人自主 AI。 ([Demo](https://app.khoj.dev/), [Source Code](https://github.com/khoj-ai/khoj)) `AGPL-3.0` `Python/Docker`
- [LibreChat](https://www.librechat.ai) `⚠` - Enhanced ChatGPT-compatible AI chat interface supporting multiple AI providers, with multi-user auth, message search, and plugin support. ([Demo](https://chat.librechat.ai), [Source Code](https://github.com/LibreChat-AI/LibreChat)) `MIT` `Nodejs/Docker`
- [LLM Harbor](https://github.com/av/harbor) - 容器化的 LLM 工具箱。通过简洁的 CLI 运行 LLM 后端、API、前端和附加服务。
- [LLMKube](https://llmkube.com) - 用于 LLM 推理的 Kubernetes 操作器，支持可插拔运行时（llama.cpp、vLLM、TGI、Ollama、vllm-swift）、多 GPU 分片、NVIDIA CUDA 与 Apple Silicon Metal 支持，以及 OpenAI 兼容 API。 ([Source Code](https://github.com/defilantech/LLMKube)) `Apache-2.0` `Go/Docker/K8S`
- [Local Deep Research](https://github.com/LearningCircuit/local-deep-research) - AI 驱动的深度研究工具，具备多源搜索（arXiv、PubMed、Web）、PDF 文本提取和加密本地存储功能。
- [LocalAI](https://localai.io/) - 在本地运行你的 AI 模型并生成图像和音频（OpenAI 和 Claude 的替代品）。 ([Source Code](https://github.com/mudler/LocalAI), [Clients](https://localai.io/gallery.html)) `MIT` `Docker/K8S`
- [Ollama](https://ollama.com/) - 快速上手运行 Llama 3.3、DeepSeek-R1、Phi-4、Gemma 3 及其他大语言模型。 ([Source Code](https://github.com/ollama/ollama)) `MIT` `Docker/Python`
- [Onyx Community Edition](https://onyx.app) - 可与任何 LLM 配合使用的聊天 UI。内置代理、Web 搜索、RAG、MCP、深度研究、40 多个知识源的连接器等高级功能。 ([Source Code](https://github.com/onyx-dot-app/onyx)) `MIT` `Docker/K8S`
- [Open-WebUI](https://openwebui.com) - 用户友好的 AI 界面，支持 Ollama、OpenAI API。 ([Source Code](https://github.com/open-webui/open-webui)) `BSD-3-Clause` `Docker/Python`
- [Vane](https://github.com/ItzCrazyKns/Vane) - AI 驱动的搜索引擎（Perplexity AI 的替代品）。


### 群件

**[`^        back to top        ^`](#awesome-selfhosted)**

Collaborative software or [groupware](https://en.wikipedia.org/wiki/Collaborative_software) is designed to help people working on a common task to attain their goals. Groupware often regroups multiple services such as file sharing, calendar/events management, appointment scheduling, address books... in a single, integrated application.

_Related: [Booking and Scheduling](#booking-and-scheduling)_

- [Citadel](https://www.citadel.org/) - 群件，包括电子邮件、日历/日程安排、通讯录、论坛、邮件列表、即时通讯、Wiki 和博客引擎、RSS 聚合等。 ([Source Code](https://www.citadel.org/source.html)) `GPL-3.0` `C/Docker/Shell`
- [Colanode](https://colanode.com) - 协作套件，具备实时消息、富文本页面、文件管理和动态数据库，为离线工作而设计（Slack、Notion 的替代品）。 ([Source Code](https://github.com/colanode/colanode)) `Apache-2.0` `K8S/Docker`
- [Cozy Cloud](https://cozy.io/) - 个人云，可用于管理和同步文件、笔记、联系人、密码和文档。 ([Source Code](https://github.com/cozy/), [Clients](https://github.com/cozy/cozy-store)) `GPL-3.0` `Nodejs`
- [Digipad](https://digipad.app/) - 用于创建协作式数字记事板的在线应用（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digipad)) `AGPL-3.0` `Nodejs`
- [Digistorm](https://digistorm.app/) - 创建协作式调查、测验、头脑风暴和词云（文档为法语）。 ([Demo](https://digistorm.app/), [Source Code](https://codeberg.org/ladigitale/digistorm)) `AGPL-3.0` `Nodejs`
- [Digiwall](https://digiwall.app/) - 创建用于现场或远程协作的多媒体协作墙（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digiwall)) `AGPL-3.0` `Nodejs`
- [egroupware](https://www.egroupware.org/) - 软件套件，包括日历、通讯录、记事本、项目管理工具、客户关系管理工具（CRM）、知识管理工具、Wiki 和 CMS。 ([Source Code](https://github.com/EGroupware/egroupware)) `GPL-2.0` `PHP`
- [Group Office](https://www.group-office.com) - 企业级 CRM 和群件工具。与同事和客户在线共享项目、日历、文件和电子邮件。 ([Source Code](https://github.com/Intermesh/groupoffice/)) `AGPL-3.0` `PHP`
- [Openmeetings](https://openmeetings.apache.org/index.html) - 视频会议、即时通讯、白板、协作文档编辑和其他群件工具，使用 Red5 流媒体服务器的 API 功能实现远程与流媒体。 ([Source Code](https://github.com/apache/openmeetings)) `Apache-2.0` `Java`
- [SOGo](https://www.sogo.nu/) - SOGo 提供多种访问日历和消息数据的方式，包括 CalDAV、CardDAV、GroupDAV 以及 ActiveSync，还支持原生 Outlook 兼容和 Web 界面。 ([Demo](https://demo.sogo.nu/SOGo/), [Source Code](https://github.com/Alinto/sogo)) `LGPL-2.1` `Objective-C`
- [Tine](https://www.tine-groupware.de/) - 用于企业和组织数字化协作的软件。从强大的群件功能到巧妙的附加组件，tine 集一切所需，让日常团队协作更加轻松。 ([Source Code](https://github.com/tine-groupware/tine)) `AGPL-3.0` `Docker`
- [Tracim](https://github.com/tracim/tracim) - 面向团队协作的协作平台：文件、讨论串、笔记、日程等。
- [Zimbra Collaboration](https://www.zimbra.com/) - 带有 Web 界面和大量集成的电子邮件、日历、协作服务器。 ([Source Code](https://github.com/zimbra)) `GPL-2.0/CPAL-1.0` `Java`


### 健康与健身

**[`^        back to top        ^`](#awesome-selfhosted)**

[Medical](https://en.wikipedia.org/wiki/Medical_software), [Health](https://en.wikipedia.org/wiki/Health_information_technology) and [Fitness](https://en.wikipedia.org/wiki/Fitness_tracker) software.

- [Endurain](https://docs.endurain.com/) - 健身追踪服务，旨在让用户完全掌控自己的数据和托管环境。 ([Source Code](https://codeberg.org/endurain-project/endurain)) `AGPL-3.0` `Docker`
- [FitTrackee](https://docs.fittrackee.org/) - 简单的锻炼/活动追踪器。 ([Source Code](https://github.com/SamR1/FitTrackee)) `AGPL-3.0` `Python/Docker`
- [Mere Medical](https://meremedical.co/) `⚠` - Manage all of your medical records from Epic MyChart, Cerner, and OnPatient patient portals in one place. Privacy-focused and offline-first. ([Demo](https://demo.meremedical.co), [Source Code](https://github.com/cfu288/mere-medical)) `GPL-3.0` `Docker/Nodejs`
- [NutriTrace](https://traceapps.github.io/docs/) - 营养与饮食追踪器，具备条形码扫描、可穿戴设备集成（Fitbit、Withings、Garmin、Health Connect）、自适应卡路里目标、多用户共享和内置 AI 助手（MyFitnessPal、Cronometer 的替代品）。 ([Source Code](https://github.com/TraceApps/nutritrace)) `AGPL-3.0` `Docker`
- [OpenELIS Global](https://openelis-global.org) - 面向临床、公共卫生、环境和病媒监测实验室的实验室信息系统（LIS/LIMS）。FHIR 原生，支持分析仪器集成（ASTM/HL7）、质量控制和国家级规模报告。 ([Demo](https://openelis-global.org/getting-started/demo/), [Source Code](https://github.com/DIGI-UW/OpenELIS-Global-2)) `MPL-2.0` `Java/Docker`
- [OpenEMR](https://www.open-emr.org/) - 电子健康记录和医疗诊所管理解决方案。 ([Demo](https://www.open-emr.org/demo/), [Source Code](https://github.com/openemr/openemr)) `GPL-3.0` `PHP/Docker`
- [wger](https://wger.de/) - 基于 Web 的个人锻炼、健身和体重记录/追踪器。也可用作简单的健身房管理工具，并提供完整的 REST API。 ([Demo](https://wger.de/en/dashboard), [Source Code](https://github.com/wger-project/wger)) `AGPL-3.0` `Python/Docker`


### 人力资源管理（HRM）

**[`^        back to top        ^`](#awesome-selfhosted)**

A [human resources management system](https://en.wikipedia.org/wiki/Human_resource_management_system) combines a number of systems and processes to ensure the easy management of [human resources](https://en.wikipedia.org/wiki/Human_resources), business processes and data.

- [admidio](https://www.admidio.org/) - 面向组织和团体网站的用户管理系统。系统具有灵活的角色模型，可以反映你所在组织的结构和权限。 ([Demo](https://www.admidio.org/demo/), [Source Code](https://github.com/Admidio/admidio)) `GPL-2.0` `PHP/Docker`
- [Frappe HR](https://frappe.io/hr) - 完整的 HRMS 解决方案，包含超过 13 个不同模块，涵盖从员工管理、入职、休假到薪资、税务等。 ([Source Code](https://github.com/frappe/hrms)) `GPL-3.0` `Docker/Python/Nodejs`
- [MintHCM](https://minthcm.org/) - 基于两款流行知名商业应用 SugarCRM Community Edition 和 SuiteCRM 的人力资本管理工具。 ([Source Code](https://github.com/minthcm/minthcm)) `AGPL-3.0` `PHP`


### Identity Management

**[`^        back to top        ^`](#awesome-selfhosted)**

[Identity management](https://en.wikipedia.org/wiki/Identity_management) (IdM), also known as identity and access management (IAM or IdAM), is a framework of policies and technologies to ensure that the right users have the appropriate access to technology resources.

**Please visit [awesome-sysadmin/Identity Management](https://github.com/awesome-foss/awesome-sysadmin#identity-management)**



### 物联网（IoT）

**[`^        back to top        ^`](#awesome-selfhosted)**

[Internet of Things](https://en.wikipedia.org/wiki/Internet_of_things) describes physical objects with sensors, processing ability, software, and other technologies that connect and exchange data with other devices over the Internet.

_Related: [Automation](#automation)_

- [Domoticz](https://www.domoticz.com/) - 家庭自动化系统，可监控和配置各种设备，如灯光、开关，以及温度、雨量、风速、紫外线、电力、燃气、水等各类传感器/仪表。 ([Source Code](https://github.com/domoticz/domoticz), [Clients](https://github.com/domoticz/domoticz-android)) `GPL-3.0` `C/C++/Docker/Shell`
- [EMQX](https://www.emqx.com/) - 可扩展的 MQTT 代理。单个集群可连接超过 1 亿台物联网设备，以每秒 100 万条消息的吞吐量和 1 毫秒的延迟移动和处理实时物联网数据。 ([Demo](https://www.emqx.com/en/mqtt/public-mqtt5-broker), [Source Code](https://github.com/emqx/emqx)) `Apache-2.0` `Docker/Erlang`
- [evcc](https://evcc.io/) - 可扩展的电动汽车充电控制器和家庭能源管理系统。 ([Source Code](https://github.com/evcc-io/evcc)) `MIT` `deb/Docker/Go`
- [FHEM](https://fhem.de/fhem.html) - 自动化家庭中的常见任务，如开关灯具和供暖。还可用于记录温度或功耗等事件。可以通过 Web 或智能手机前端、telnet 或直接通过 TCP/IP 进行控制。 ([Source Code](https://svn.fhem.de/trac)) `GPL-3.0` `Perl`
- [FlowForge](https://flowforge.com/) - 以可靠、可扩展且安全的方式部署 Node-RED 应用。FlowForge 平台为 Node-RED 开发团队提供 DevOps 能力。 ([Source Code](https://github.com/FlowFuse/flowfuse)) `Apache-2.0` `Nodejs/Docker/K8S`
- [FMD Server](https://fmd-foss.org) - 与 FMD（Find My Device）Android 应用通信的服务器，用于定位和控制你的设备。 ([Source Code](https://gitlab.com/fmd-foss/fmd-server), [Clients](https://gitlab.com/fmd-foss/fmd-android)) `GPL-3.0` `Docker/Go`
- [Gladys](https://gladysassistant.com/) - 隐私至上的家庭助手。 ([Source Code](https://github.com/GladysAssistant/Gladys)) `Apache-2.0` `Nodejs/Docker`
- [Home Assistant](https://home-assistant.io/) - 家庭自动化平台。 ([Demo](https://home-assistant.io/demo/), [Source Code](https://github.com/home-assistant/core)) `Apache-2.0` `Python/Docker`
- [ioBroker](https://www.iobroker.net/) - 面向物联网的集成平台，专注于楼宇自动化、智能计量、环境辅助生活、流程自动化、可视化和数据记录。 ([Source Code](https://github.com/ioBroker/ioBroker)) `MIT` `Nodejs`
- [LHA](https://github.com/javalikescript/lha) - 轻量级家庭自动化应用，可使用 Blockly、HTML 或 Lua 完全扩展。包含 ConBee、Philips Hue 或 Z-Wave JS 等扩展。
- [Node RED](https://nodered.org/) - 基于浏览器的流程编辑器，帮助你连接硬件设备、API 和在线服务以创建物联网解决方案。 ([Source Code](https://github.com/node-red/node-red)) `Apache-2.0` `Nodejs/Docker`
- [Onloc](https://onloc.app) - 实时追踪和共享你的位置。控制和锁定被盗或丢失的手机。 ([Source Code](https://github.com/onloc-app/onloc-api), [Clients](https://github.com/onloc-app/onloc-android)) `AGPL-3.0` `Docker`
- [openHAB](https://www.openhab.org) - 与供应商和技术无关的家庭自动化软件。 ([Source Code](https://github.com/openhab/openhab-core)) `EPL-2.0` `Java`
- [OpenRemote](https://openremote.io) - 物联网资产管理、流程规则和 WHEN-THEN 规则、数据可视化、边缘网关。 ([Demo](https://demo.openremote.io/), [Source Code](https://github.com/openremote/core)) `AGPL-3.0` `Java`
- [polluSensWeb](https://wespeakenglish.github.io/polluSensWeb/) - 基于 Web 的串行接口和图表工具，用于可视化并记录 UART 污染传感器（PM2.5、VOC 等）的数据。具备实时数据采集、动态图表、CSV 导出和 webhook 集成功能。 ([Demo](https://wespeakenglish.github.io/polluSensWeb/), [Source Code](https://github.com/WeSpeakEnglish/polluSensWeb), [Clients](https://github.com/WeSpeakEnglish/polluSensWeb/releases)) `MIT` `Javascript`
- [SIP Irrigation Control](https://dan-in-ca.github.io/SIP/) - 喷灌/灌溉控制软件。 ([Source Code](https://github.com/Dan-in-CA/SIP)) `GPL-3.0` `Python`
- [SOLECTRUS](https://solectrus.de) - 光伏仪表板，显示能源生产和消耗情况，并计算成本和节省金额。 ([Demo](https://demo.solectrus.de), [Source Code](https://github.com/solectrus/solectrus)) `AGPL-3.0` `Docker`
- [Tasmota](https://tasmota.com) - ESP 设备固件。完全本地控制，设置和更新快捷。可通过 MQTT、Web UI、HTTP 或串口控制。可使用定时器、规则或脚本实现自动化。可与家庭自动化解决方案集成。 ([Source Code](https://github.com/arendst/Tasmota)) `GPL-3.0` `C/C++`
- [Thingsboard](https://thingsboard.io/) - 物联网平台——设备管理、数据收集、处理和可视化。 ([Demo](https://demo.thingsboard.io/signup), [Source Code](https://github.com/thingsboard/thingsboard)) `Apache-2.0` `Java/Docker/K8S`
- [WebThings Gateway](https://webthings.io/gateway/) - Web of Things 的实现，包括 WebThings Gateway 和 WebThings Framework。 ([Source Code](https://github.com/WebThingsIO/gateway)) `MPL-2.0` `Nodejs`


### 库存管理

**[`^        back to top        ^`](#awesome-selfhosted)**

[Inventory management software](https://en.wikipedia.org/wiki/Inventory_management_software).

_Related: [Money, Budgeting & Management](#money-budgeting--management), [Resource Planning](#resource-planning)_

_See also: [awesome-sysadmin/IT Asset Management](https://github.com/awesome-foss/awesome-sysadmin#it-asset-management)_

- [Cannery](https://cannery.app) - 枪支与弹药追踪应用。 ([Source Code](https://gitlab.com/shibaobun/cannery)) `AGPL-3.0` `Docker`
- [CellarBoss](https://cellarboss.org) - 葡萄酒库存管理系统。 ([Source Code](https://github.com/CellarBoss/cellarboss)) `GPL-3.0` `Docker/Nodejs`
- [DVinyl](https://github.com/Kyonew/DVinyl) `⚠` - Modern collection manager for physical media (vinyls, CDs, cassettes, books, movies, and video games). `MIT` `Nodejs/Docker`
- [HomeBox (SysAdminsMedia)](https://homebox.software/) - 为家庭用户打造的库存与整理系统。 ([Demo](https://demo.homebox.software/), [Source Code](https://github.com/sysadminsmedia/homebox)) `AGPL-3.0` `Docker/Go`
- [Inventaire](https://inventaire.io/welcome) - 协作式资源映射项目，目前仅专注于探索图书与 wikidata 和 ISBN 的映射。 ([Source Code](https://codeberg.org/inventaire/inventaire)) `AGPL-3.0` `Nodejs`
- [Inventree](https://docs.inventree.org/en/latest/) - 提供直观零件管理与库存控制的库存管理系统。 ([Demo](https://inventree.org/demo), [Source Code](https://github.com/inventree/InvenTree)) `MIT` `Python`
- [Open QuarterMaster](https://openquartermaster.com/) - 功能强大的库存管理系统，设计上灵活且可扩展。 ([Source Code](https://github.com/Epic-Breakfast-Productions/OpenQuarterMaster)) `GPL-3.0` `deb/Docker`
- [Part-DB](https://docs.part-db.de/) - 面向电子元器件的库存管理系统。 ([Demo](https://demo.part-db.de/en/), [Source Code](https://github.com/Part-DB/Part-DB-server)) `AGPL-3.0` `Docker/PHP/Nodejs`
- [Spoolman](https://github.com/Donkie/Spoolman) - 追踪你的 3D 打印机耗材线轴库存。`MIT` `Docker/Python`


### 知识管理工具

**[`^        back to top        ^`](#awesome-selfhosted)**

[Knowledge management](https://en.wikipedia.org/wiki/Knowledge_management) is the collection of methods relating to creating, sharing, using and managing the knowledge and information.

_Related: [Note-taking & Editors](#note-taking--editors), [Wikis](#wikis), [Database Management](#database-management)_

- [Atomic Server](https://atomicserver.eu/) - 具备文档（类似 Notion）、表格、搜索和强大关联数据 API 的知识图谱数据库。轻量、极速且无运行时依赖。 ([Demo](https://atomicdata.dev/), [Source Code](https://github.com/ontola/atomic-server)) `MIT` `Docker/Rust`
- [Digimindmap](https://ladigitale.dev/digimindmap/#/) - 创建简单的思维导图（文档为法语）。 ([Demo](https://ladigitale.dev/digimindmap/#/), [Source Code](https://codeberg.org/ladigitale/digimindmap)) `AGPL-3.0` `Nodejs/PHP`
- [LibreKB](https://librekb.com/) - 基于 Web 的知识库解决方案。这是一个简单的 Web 应用，几乎可在任何具备 PHP 和 MySQL 的 Web 服务器或托管服务商上运行。 ([Source Code](https://github.com/michaelstaake/LibreKB/)) `GPL-3.0` `PHP`
- [Marmot](https://marmotdata.io) - 用于发现和整理技术栈中数据资产的数据目录，涵盖数据库、API、消息队列和数据管道。 ([Demo](https://demo.marmotdata.io), [Source Code](https://github.com/marmotdata/marmot)) `MIT` `Docker`
- [memEx](https://memex-app.shibao.dev) - 结构化个人知识库，灵感来自 zettlekasten 和 org-mode。 ([Source Code](https://gitlab.com/shibaobun/memex)) `AGPL-3.0` `Docker`
- [SiYuan](https://b3log.org/siyuan/) - 隐私优先的个人知识管理软件，使用 typescript 和 golang 编写。 ([Source Code](https://github.com/siyuan-note/siyuan)) `AGPL-3.0` `Docker/Go`
- [TeamMapper](https://github.com/b310-digital/teammapper) - 托管并创建你自己的思维导图。与团队分享思维导图会话，并在思维导图上实时协作。 ([Demo](https://map.kits.blog)) `MIT` `Docker/Nodejs`


### 学习与课程

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software to help with education and learning.

- [Canvas LMS](https://www.instructure.com/canvas/) - 正在革新教育方式的学习管理系统（LMS）。 ([Source Code](https://github.com/instructure/canvas-lms)) `AGPL-3.0` `Ruby`
- [Chamilo LMS](https://chamilo.org/) - 创建虚拟校园，以提供在线或半在线培训。 ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPL-3.0` `PHP`
- [Digiscreen](https://ladigitale.dev/digiscreen/) - 面向课堂的交互式白板/墙面，可用于现场或远程教学（文档为法语）。 ([Demo](https://ladigitale.dev/digiscreen/), [Source Code](https://codeberg.org/ladigitale/digiscreen)) `AGPL-3.0` `Nodejs/PHP`
- [Digitools](https://ladigitale.dev/digitools) - 一套简单工具，用于辅助现场或远程授课（文档为法语）。 ([Demo](https://ladigitale.dev/digitools/), [Source Code](https://codeberg.org/ladigitale/digitools)) `AGPL-3.0` `PHP`
- [edX](https://www.edx.org/) - 为 edX.org 网站提供支持的在线学习平台。 ([Source Code](https://github.com/edx/)) `AGPL-3.0` `Python`
- [Gibbon](https://gibbonedu.org/) - 灵活的学校管理平台，旨在让教师、学生、家长和管理者的生活更美好。 ([Source Code](https://github.com/GibbonEdu/core)) `GPL-3.0` `PHP`
- [Helium](https://www.heliumedu.com) - 面向学生的彩色标记计划工具，管理课程、作业、成绩和笔记，配备智能通知与多设备同步。 ([Demo](https://app.heliumedu.com), [Source Code](https://github.com/HeliumEdu/platform)) `MIT` `Python/Docker`
- [ILIAS](https://www.ilias.de) - 能够应对任何挑战的学习管理系统。 ([Demo](https://demo.ilias.de), [Source Code](https://github.com/ILIAS-eLearning/ILIAS)) `GPL-3.0` `PHP`
- [INGInious](https://inginious.org/?lang=en) - 智能评分系统，可对学生编写的代码进行安全且自动化的测试。 ([Source Code](https://github.com/INGInious/INGInious), [Clients](https://github.com/INGInious/plugins)) `AGPL-3.0` `Python/Docker`
- [Moodle](https://moodle.org/) - 拥有全球最大社区之一的学习与课程平台。 ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL-3.0` `PHP`
- [Open eClass](https://www.openeclass.org/) - 可提升教学与学习过程的先进电子学习解决方案。 ([Demo](https://demo.openeclass.org/), [Source Code](https://github.com/gunet/openeclass)) `GPL-2.0` `PHP`
- [OpenOLAT](https://www.openolat.com/?lang=en) - 用于教学、教育、评估和沟通的学习管理系统。 ([Demo](https://learn.olat.com), [Source Code](https://github.com/OpenOLAT/OpenOLAT)) `Apache-2.0` `Java`
- [QST](https://qstonline.org) - 在线测评软件。从手机上的快速测验到大规模、高利害、带监考的桌面考试，皆轻松、安全且经济。 ([Demo](https://qstonline.org/free_account.htm), [Source Code](https://sourceforge.net/projects/qstonline/)) `GPL-2.0` `Perl`
- [RELATE](https://documen.tician.de/relate/) - 课件包，包含灵活规则、统计、多课程支持、课程日历等功能。 ([Source Code](https://github.com/inducer/relate)) `MIT` `Python`
- [RosarioSIS](https://www.rosariosis.org/) - 用于学校管理的学生信息系统。功能包括学生人口统计、成绩、排课、考勤、学生账单、纪律与餐饮服务模块。 ([Demo](https://www.rosariosis.org/demo/), [Source Code](https://gitlab.com/francoisjacquet/rosariosis/)) `GPL-2.0` `PHP`


### 制造

**[`^        back to top        ^`](#awesome-selfhosted)**

Software to manage [3D printers](https://en.wikipedia.org/wiki/3D_printing), [CNC machines](https://en.wikipedia.org/wiki/Numerical_control) and other physical manufacturing tools.

- [CNCjs](https://cnc.js.org/) - 适用于运行 Grbl、Smoothieware 或 TinyG 的 CNC 铣床控制器的 Web 界面。 ([Source Code](https://github.com/cncjs/cncjs/)) `MIT` `Nodejs`
- [Fluidd](https://docs.fluidd.xyz/) - 为 3D 打印机固件 Klipper 打造的轻量级响应式用户界面。 ([Source Code](https://github.com/fluidd-core/fluidd)) `GPL-3.0` `Docker/Nodejs`
- [LinuxCNC](https://www.linuxcnc.org/) - 基于 Linux 的 CNC 机床控制器。可驱动铣床、车床、3D 打印机、激光切割机、等离子切割机、机械臂、六足机器人等。 ([Source Code](https://github.com/LinuxCNC/linuxcnc)) `GPL-2.0/LGPL-3.0` `C/deb`
- [Mainsail](https://docs.mainsail.xyz/) - 为 Klipper 3D 打印机固件打造的现代响应式用户界面。随时随地、在任何设备上控制和监控你的打印机。 ([Source Code](https://github.com/mainsail-crew/mainsail)) `GPL-3.0` `Docker/Python`
- [Manyfold](https://manyfold.app) - 面向 3D 打印文件的数字资产管理系统，支持 STL、OBJ、3MF 等格式。 ([Source Code](https://github.com/manyfold3d/manyfold)) `MIT` `Docker`
- [Octoprint](https://octoprint.org/) - 用于控制消费级 3D 打印机的敏捷 Web 界面。 ([Source Code](https://github.com/OctoPrint/OctoPrint)) `AGPL-3.0` `Docker/Python`
- [Orkyo Community](https://orkyo.com) - 面向制造团队的生产排程——为执行生产任务的机器、人员和工具制定统一计划。 ([Demo](https://orkyo.com/demo), [Source Code](https://github.com/Kymr10n/orkyo-community)) `AGPL-3.0` `C#/Docker`


### 地图与全球定位系统（GPS）

**[`^        back to top        ^`](#awesome-selfhosted)**

[Maps](https://en.wikipedia.org/wiki/Map), [cartography](https://en.wikipedia.org/wiki/Cartography), [GIS](https://en.wikipedia.org/wiki/Geographic_information_system) and [GPS](https://en.wikipedia.org/wiki/Global_Positioning_System) software.

_Related: [Travel Organization](#travel-organization)_

_See also: [awesome-openstreetmap](https://github.com/osmlab/awesome-openstreetmap), [awesome-gis](https://github.com/sshuair/awesome-gis)_

- [AdventureLog](https://adventurelog.app) - 旅行追踪与行程规划工具。 ([Demo](https://demo.adventurelog.app/signup), [Source Code](https://github.com/seanmorley15/AdventureLog)) `GPL-3.0` `Docker`
- [AirTrail](https://airtrail.johan.ohly.dk) - 个人航班追踪系统。 ([Source Code](https://github.com/johanohly/AirTrail)) `GPL-3.0` `Docker/Nodejs`
- [Bicimon](https://github.com/knrdl/bicimon) - 以渐进式 Web 应用（PWA）形式打造的自行车速度计。 ([Demo](https://knrdl.github.io/bicimon/)) `MIT` `Javascript`
- [Dawarich](https://dawarich.app/) - 以完全的隐私和控制权，可视化你的位置历史、追踪你的行动并分析出行模式（Google Timeline（又称 Google Location History）的替代品）。 ([Source Code](https://github.com/Freika/dawarich)) `AGPL-3.0` `Docker`
- [Geo2tz](https://github.com/noandrea/geo2tz) - 根据地理坐标（lat, lon）获取时区。`MIT` `Go/Docker`
- [GraphHopper](https://graphhopper.com/) - 基于 OpenStreetMap 的快速路径规划库与服务器。 ([Source Code](https://github.com/graphhopper/graphhopper)) `Apache-2.0` `Java`
- [NextGIS Web](https://nextgis.com/nextgis-web/) - 用于地理空间数据管理、Web 地图发布和以 QGIS 为核心的协作式工作流的 Web GIS 服务器。 ([Demo](https://sandbox.nextgis.com), [Source Code](https://github.com/nextgis/nextgisweb)) `GPL-3.0` `Docker`
- [Nominatim](https://nominatim.org/) - 基于 OpenStreetMap 数据的地理编码（地址 -> 坐标）与逆地理编码（坐标 -> 地址）服务器应用。 ([Source Code](https://github.com/osm-search/Nominatim)) `GPL-2.0` `C`
- [Open Source Routing Machine (OSRM)](http://project-osrm.org/) - 基于 OpenStreetMap 数据运行的高性能路径规划引擎，提供 HTTP API、C++ 库接口和 Nodejs 封装。 ([Demo](https://map.project-osrm.org/), [Source Code](https://github.com/Project-OSRM/osrm-backend)) `BSD-2-Clause` `C++`
- [OpenRouteService](https://openrouteservice.org/) - 提供路线指引、等时圈、时间-距离矩阵、路线优化等功能的路径服务。 ([Demo](https://openrouteservice.org/dev/#/api-docs/introduction), [Source Code](https://github.com/GIScience/openrouteservice)) `GPL-3.0` `Docker/Java`
- [OpenStreetMap](https://www.openstreetmap.org/) - 创建可自由编辑的全球地图的协作项目。 ([Source Code](https://github.com/openstreetmap/openstreetmap-website), [Clients](https://wiki.openstreetmap.org/wiki/Software)) `GPL-2.0` `Ruby`
- [OpenTripPlanner](https://www.opentripplanner.org/) - 基于 OpenStreetMap 数据的多模式行程规划软件，通过读取已发布的 GTFS 格式数据，推荐使用当地公共交通系统的路线。 ([Source Code](https://github.com/opentripplanner/OpenTripPlanner)) `LGPL-3.0` `Java/Javascript`
- [OwnTracks Recorder](https://github.com/owntracks/recorder) `⚠` - Store and access data published by OwnTracks location tracking apps. `GPL-2.0` `C/Lua/deb/Docker`
- [TileServer GL](https://tileserver.readthedocs.io/) - 带 GL 样式的矢量与栅格地图，由 Mapbox GL Native 进行服务端渲染。是面向 Mapbox GL JS、Android、iOS、Leaflet、OpenLayers 以及经 WMTS 访问的 GIS 等的地图瓦片服务器。 ([Source Code](https://github.com/maptiler/tileserver-gl)) `BSD-2-Clause` `Nodejs/Docker`
- [Traccar](https://www.traccar.org/) - 追踪 GPS 位置的 Java 应用。支持大量追踪设备和协议，提供 Android 和 iOS 应用，并带有查看行程的 Web 界面。 ([Demo](https://demo.traccar.org/), [Source Code](https://github.com/traccar)) `Apache-2.0` `Java`
- [TRIP](https://itskovacs-trip.netlify.app/) - 极简的 POI 地图追踪与行程规划工具。 ([Demo](https://itskovacs-trip.netlify.app/home), [Source Code](https://github.com/itskovacs/trip)) `MIT` `Docker`
- [wanderer](https://github.com/open-wanderer/wanderer) - 步道数据库，可上传你的记录轨迹或创建新轨迹，并添加各种元数据，构建易于检索的目录。 ([Demo](https://demo.wanderer.to)) `AGPL-3.0` `Docker/Go/Nodejs`


### 媒体管理

**[`^        back to top        ^`](#awesome-selfhosted)**

[Digital media](https://en.wikipedia.org/wiki/Digital_media) management tools and software.

_Related: [Automation](#automation), [Media Streaming](#media-streaming), [Media Streaming - Audio Streaming](#media-streaming---audio-streaming), [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Media Management](#media-management)_

- [ChannelTube](https://github.com/TheWicklowWolf/ChannelTube) `⚠` - Download video or audio from YouTube channels on a schedule via yt-dlp. `AGPL-3.0` `Docker`
- [Deleterr](https://github.com/rfsbraz/deleterr) - 自动化媒体清理工具，根据可配置规则从 Plex、Sonarr 和 Radarr 中移除已观看和过期的内容。`MIT` `Docker`
- [Downtify](https://downtify.henriquesebastiao.com) `⚠` - Download Spotify music with album art and metadata. ([Source Code](https://github.com/henriquesebastiao/downtify)) `GPL-3.0` `Docker`
- [Elengrab](https://github.com/neosy/elengrab) - 快速跨平台的视频音频下载与媒体查看工具，提供灵活的格式和画质选项。支持 1000 多个网站，包括 YouTube、Instagram、TikTok、Twitch 等。 ([Demo](https://elengrab.n-hub.ru)) `AGPL-3.0` `Go/Docker`
- [HomeTube](https://hometube.latentnoise.dev) `⚠` - Web UI to download videos and playlists from 1700+ sites into a Plex or Jellyfin library, with quality selection, SponsorBlock sponsor removal, subtitles, clip cutting and resilient playlist sync. ([Source Code](https://github.com/EgalitarianMonkey/hometube)) `AGPL-3.0` `Python/Docker`
- [Houndarr](https://av1155.github.io/houndarr/) - 为 Radarr、Sonarr、Lidarr、Readarr 和 Whisparr 提供定时补漏搜索。以受速率限制的小批量方式逐批处理缺失和未达画质标准的条目，并带逐条冷却与每小时上限，避免索引站过载。 ([Source Code](https://github.com/av1155/houndarr)) `AGPL-3.0` `Python/Docker`
- [Lidarr](https://lidarr.audio/) - 面向 Usenet 和 BitTorrent 用户的音乐收藏管理工具。 ([Source Code](https://github.com/Lidarr/Lidarr)) `GPL-3.0` `C#/Docker`
- [LidaTube](https://github.com/TheWicklowWolf/LidaTube) `⚠` - Finding and fetch missing Lidarr albums via yt-dlp. `GPL-3.0` `Docker`
- [Lidify](https://github.com/TheWicklowWolf/Lidify) `⚠` - Music discovery tool that provides recommendations based on selected Lidarr artists, using Spotify or LastFM. `MIT` `Docker`
- [Lingarr](https://lingarr.com) - 使用 LibreTranslate、本地 AI 模型或 SaaS 翻译服务，自动翻译 Radarr 和 Sonarr 媒体库中的字幕文件。 ([Source Code](https://github.com/lingarr-translate/lingarr)) `AGPL-3.0` `Docker`
- [Medusa](https://github.com/pymedusa/Medusa) - 电视剧自动视频库管理工具。它会监视你喜爱剧集的新一集，一经发布便自动完成下载处理。 ([Clients](https://github.com/medusajs/nextjs-starter-medusa)) `GPL-3.0` `Python`
- [MeTube](https://github.com/alexta69/metube) - youtube-dl 的 Web 图形界面，支持播放列表。可从数十个网站下载视频。`AGPL-3.0` `Python/Nodejs/Docker`
- [MKVPriority](https://github.com/kennethsible/mkvpriority) - 使用可配置的优先级评分选择首选音轨和字幕轨，并设置相应的默认与强制标志。`MIT` `Python/Docker`
- [MyTube](https://github.com/franklioxygen/MyTube) `⚠` - Downloader and player for yt-dlp-supported sites with channel subscriptions, cloud upload support, and local library organization. ([Demo](https://mytube-demo.vercel.app)) `MIT` `Nodejs/Docker`
- [nefarious](https://lardbit.github.io/nefarious/) - 自动下载电影和电视剧。 ([Source Code](https://github.com/lardbit/nefarious)) `GPL-3.0` `Python`
- [Ombi](https://ombi.io/) - 面向 Plex/Emby 的内容请求系统，可连接 SickRage、CouchPotato、Sonarr，功能集不断扩充。 ([Demo](https://app.ombi.io/), [Source Code](https://github.com/Ombi-app/Ombi)) `GPL-2.0` `C#/deb`
- [Pinchflat](https://github.com/kieraneglin/pinchflat) `⚠` - Download YouTube content built using yt-dlp. `AGPL-3.0` `Docker`
- [PodFetch](https://samtv12345.github.io/PodFetch) - 时尚高效的播客下载工具。 ([Source Code](https://github.com/SamTV12345/PodFetch)) `Apache-2.0` `Docker/Rust`
- [Radarr](https://radarr.video/) - 通过 Usenet 和 BitTorrent 自动下载电影（Sonarr 的分支）。 ([Source Code](https://github.com/Radarr/Radarr)) `GPL-3.0` `C#/Docker`
- [Ratelog](https://ratelog.org) - 电影追踪与评分应用（Letterboxd 的替代品）。 ([Source Code](https://github.com/golmenero/ratelog)) `AGPL-3.0` `Docker`
- [Reaparr](https://www.reaparr.rocks/) `⚠` - Cross-platform Plex media downloader that seamlessly adds media from other Plex servers to your own. ([Source Code](https://github.com/Reaparr/Reaparr)) `GPL-3.0` `Docker`
- [Seerr](https://github.com/seerr-team/seerr) - 管理媒体库的请求，支持 Plex、Jellyfin 和 Emby 媒体服务器（Overseerr 的分支）。`MIT` `Docker/Nodejs`
- [Sonarr](https://sonarr.tv/) - 面向 Usenet 和 BitTorrent 的电视剧自动下载与管理工具。可抓取、排序和重命名新剧集，并在更高画质格式可用时自动升级已下载文件的画质。 ([Source Code](https://github.com/Sonarr/Sonarr)) `GPL-3.0` `C#/Docker`
- [TrackWatch](https://trackwatch.emlopezr.com) `⚠` - Automated music release tracker for Spotify with email notifications, discography generator, and ghost track cleaner (alternative to Release Radar). ([Source Code](https://github.com/emlopezr/trackwatch)) `MIT` `Docker`
- [tubesync](https://github.com/meeb/tubesync) `⚠` - Syncs YouTube channels and playlists to a locally hosted media server. `AGPL-3.0` `Docker/Python`
- [Watcharr](https://github.com/sbondCo/Watcharr) - 添加并追踪你在看的所有剧集和电影。自带用户认证、现代简洁的 UI 和非常简单的安装设置。`MIT` `Docker`
- [ydl_api_ng](https://github.com/Totonyus/ydl_api_ng) - 简单的 youtube-dl REST API，用于在远程服务器上启动下载。`GPL-3.0` `Python`
- [Youtarr](https://github.com/DialmasterOrg/Youtarr) `⚠` - Download videos from YouTube channels on a schedule via yt-dlp, with a web UI to browse and selectively download videos. Integrates with Plex Media Server and generates NFO metadata for Jellyfin, Kodi, and Emby. `ISC` `Docker`
- [youtube-dl-nas](https://hyeonsangjeon.github.io/youtube-dl-nas/) `⚠` - Authenticated yt-dlp download queue for video, audio and subtitles, with history, mobile sharing and NAS file management (fork of youtube-dl-server). ([Source Code](https://github.com/hyeonsangjeon/youtube-dl-nas)) `MIT` `Python/Docker`
- [YoutubeDL-Server](https://github.com/nbr23/youtube-dl-server) - Youtube-DL 的 Web 与 REST 界面，可将视频下载到服务器。`MIT` `Python/Docker`


### Media Streaming

**[`^        back to top        ^`](#awesome-selfhosted)**

[Streaming media](https://en.wikipedia.org/wiki/Streaming_media) is multimedia that is delivered and consumed in a continuous manner from a source, with little or no intermediate storage in network elements.

**Please visit [Media streaming - Audio Streaming](#media-streaming---audio-streaming), [Media streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Media streaming - Video Streaming](#media-streaming---video-streaming), [Media Management](#media-management)**

_Related: [Media Streaming](#media-streaming)_

_See also: [List of streaming media systems - Wikipedia](https://en.wikipedia.org/wiki/List_of_streaming_media_systems), [Comparison of streaming media systems - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_streaming_media_systems)_



### 媒体流 - 音频流

**[`^        back to top        ^`](#awesome-selfhosted)**

[Audio](https://en.wikipedia.org/wiki/Audio) streaming tools and software.

_Related: [Media Management](#media-management)_

- [Ampache](https://ampache.org/) - 基于 Web 的音频/视频流媒体应用。 ([Demo](https://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPL-3.0` `PHP`
- [Audiobookshelf](https://www.audiobookshelf.org/) - 有声书与播客服务器。支持流式传输所有音频格式，跨设备保存并同步进度。附带 Android 和 iOS 应用。 ([Source Code](https://github.com/advplyr/audiobookshelf), [Clients](https://github.com/advplyr/audiobookshelf-app)) `GPL-3.0` `Docker/deb/Nodejs`
- [Audioserve](https://github.com/izderadicka/audioserve) - 简单的个人服务器，从目录提供音频文件（有声书、音乐、播客等）。专注于简洁，支持在客户端之间同步播放进度。`MIT` `Rust`
- [AzuraCast](https://www.azuracast.com/) - 现代且易用的网络电台管理套件。 ([Source Code](https://github.com/AzuraCast/AzuraCast)) `Apache-2.0` `Docker`
- [Beets](https://beets.io/) - 音乐库管理器和 MusicBrainz 标签工具（命令行与 Web 界面）。 ([Source Code](https://github.com/beetbox/beets)) `MIT` `Python/deb`
- [Black Candy](https://github.com/blackcandy-org/blackcandy) - 音乐流媒体服务器。`MIT` `Docker/Ruby`
- [BotWave](https://botwave.dpip.lol) - 采用服务器-客户端架构的 FM 广播系统，可远程管理多台 Raspberry Pi 发射器。 ([Source Code](https://github.com/dpipstudio/botwave)) `GPL-3.0` `Python`
- [Funkwhale](https://dev.funkwhale.audio/funkwhale) - 现代、基于 Web、欢乐、多用户且免费的音乐服务器。`BSD-3-Clause` `Python`
- [gonic](https://github.com/sentriz/gonic) - 轻量级音乐流媒体服务器，兼容 Subsonic。`GPL-3.0` `Go/Docker`
- [koel](https://koel.dev/) - 真正能用的个人音乐流媒体服务器。 ([Demo](https://demo.koel.dev/), [Source Code](https://github.com/koel/koel)) `MIT` `PHP`
- [LibreTime](https://libretime.org) - 在 Web 上广播流媒体电台（Airtime 的分支）。 ([Source Code](https://github.com/LibreTime/libretime)) `AGPL-3.0` `Docker/PHP`
- [LMS](https://github.com/epoupon/lms) - 通过 Web 界面访问你自己的音乐。`GPL-3.0` `Docker/deb/C++`
- [Lyrion Music Server](https://lyrion.org/) - 控制多种 Squeezebox/Slim Devices 音频播放器及兼容硬件的服务器软件（前身为 Logitech Media Server）。 ([Source Code](https://github.com/lms-community/slimserver), [Clients](https://lyrion.org/extensions/applications/)) `GPL-2.0` `deb/Docker/Perl`
- [moOde Audio](https://moodeaudio.org/) - 为出色的 Raspberry Pi 系列单板计算机提供发烧级音质的音乐播放。 ([Source Code](https://github.com/moode-player/moode)) `GPL-3.0` `PHP`
- [Mopidy](https://docs.mopidy.com/) `⚠` - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([Source Code](https://github.com/mopidy/mopidy)) `Apache-2.0` `Python/deb`
- [mpd](https://www.musicpd.org/) - 用于远程播放音乐、流式传输音乐以及管理和整理播放列表的守护进程。有众多客户端可用。 ([Source Code](https://github.com/MusicPlayerDaemon/MPD), [Clients](https://www.musicpd.org/clients/)) `GPL-2.0` `C++`
- [mStream](https://mstream.io/) - 带 GUI 管理工具的音乐流媒体服务器。可运行于 Mac、Windows 和 Linux。 ([Source Code](https://github.com/IrosTheBeggar/mStream)) `GPL-3.0` `Nodejs`
- [multi-scrobbler](https://foxxmd.github.io/multi-scrobbler) - 将来自多个来源的播放记录 scrobble 到多个 scrobble 服务。 ([Source Code](https://github.com/FoxxMD/multi-scrobbler)) `MIT` `Nodejs/Docker`
- [musikcube](https://github.com/clangen/musikcube) - 带 Linux/macOS/Windows/Android 客户端的流式音频服务器。`BSD-3-Clause` `C++/deb`
- [Navidrome Music Server](https://www.navidrome.org) - 现代的音乐服务器与流媒体播放器，兼容 Subsonic/Airsonic。 ([Demo](https://www.navidrome.org/demo), [Source Code](https://github.com/navidrome/navidrome), [Clients](https://www.navidrome.org/docs/overview/#apps)) `GPL-3.0` `Docker/Go`
- [Pinepods](https://www.pinepods.online/) - 支持多用户的播客管理系统。Pinepods 使用中央数据库，让收听进度和主题等设置在设备之间保持一致。 ([Demo](https://try.pinepods.online), [Source Code](https://github.com/madeofpendletonwool/PinePods)) `GPL-3.0` `Docker`
- [Polaris](https://github.com/agersant/polaris) - 为大型音乐收藏、易用性和高性能优化的音乐浏览与流媒体应用。`MIT` `Rust/Docker`
- [Snapcast](https://github.com/snapcast/snapcast) - 同步多房间音频服务器。`GPL-3.0` `C++/deb`
- [Stretto](https://github.com/benkaiser/stretto) `⚠` - Music player with Youtube/Soundcloud import and iTunes/Spotify discovery. ([Demo](https://next.kaiserapps.com), [Clients](https://github.com/benkaiser/stretto-mobile-next)) `MIT` `Nodejs`
- [Supysonic](https://github.com/spl0k/supysonic) - Subsonic 服务器 API 的 Python 实现。`AGPL-3.0` `Python/deb`
- [SwingMusic](https://swingmusic.vercel.app/) - 为本地音频文件打造的精美音乐播放器与流媒体服务器。就像一个更酷的 Spotify……但音乐由你自带。 ([Source Code](https://github.com/swingmx/swingmusic)) `MIT` `Python/Docker`
- [vod2pod-rss](https://github.com/madiele/vod2pod-rss) `⚠` - Convert YouTube and Twitch channels to podcasts, no storage required. Transcodes VoDs to MP3 192k on the fly, generates an RSS feed to use in podcast clients. `MIT` `Docker`


### 媒体流 - 多媒体流

**[`^        back to top        ^`](#awesome-selfhosted)**

[Multimedia](https://en.wikipedia.org/wiki/Multimedia) streaming tools and software.

_Related: [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Media Streaming - Audio Streaming](#media-streaming---audio-streaming), [Media Management](#media-management)_

- [ClipBucket](https://clipbucket.fr/) - 几分钟内启动你自己的视频分享网站（YouTube/Netflix 克隆）。 ([Demo](https://demo.clipbucket.oxygenz.fr/), [Source Code](https://github.com/MacWarrior/clipbucket-v5)) `AAL` `Docker/PHP`
- [cmyflix](https://github.com/farfalleflickan/cmyflix) - 用于流式播放视频的极简 Plex/Jellyfin 替代品。`AGPL-3.0` `C/deb`
- [Gerbera](https://gerbera.io/) - UPnP 媒体服务器，可让你在家庭网络中流式传输数字媒体，并在各种兼容 UPnP 的设备上收听/观看。 ([Source Code](https://github.com/gerbera/gerbera)) `GPL-2.0` `Docker/deb/C++`
- [Icecast 2](https://icecast.org) - 音频/视频流服务器，可用于创建网络电台或私人点唱机，以及介于两者之间的多种用途。 ([Source Code](https://gitlab.xiph.org/xiph/icecast-server), [Clients](https://icecast.org/apps/)) `GPL-2.0` `C`
- [Jellyfin](https://jellyfin.org) - 面向音频、视频、图书、漫画和照片的媒体服务器，界面时尚，转码能力强大。几乎所有现代平台都有客户端，包括 Roku、Android TV、iOS 和 Kodi。 ([Demo](https://demo.jellyfin.org/stable), [Source Code](https://github.com/jellyfin/jellyfin), [Clients](https://github.com/awesome-jellyfin/awesome-jellyfin)) `GPL-2.0` `C#/deb/Docker`
- [Karaoke Eternal](https://www.karaoke-eternal.com) - 举办精彩的卡拉 OK 聚会，每个人都能通过手机浏览器轻松查找歌曲并加入点播队列。播放器也完全基于浏览器，支持 MP3+G、MP4 和 WebGL 可视化效果。 ([Source Code](https://github.com/bhj/KaraokeEternal)) `ISC` `Docker/Nodejs`
- [Kodi](https://kodi.tv/) - 多媒体/娱乐中心，前身为 XBMC。可运行于 Android、BSD、Linux、macOS、iOS 和 Windows。 ([Source Code](https://github.com/xbmc/xbmc)) `GPL-2.0` `C++/deb`
- [Kyoo](https://github.com/zoriya/kyoo) - 创新媒体浏览器，专为无缝流式播放动漫、剧集和电影设计，提供动态转码、自动观看历史和智能元数据获取等高级功能。 ([Demo](https://kyoo.zoriya.dev)) `GPL-3.0` `Docker`
- [MediaMTX](https://mediamtx.org) - 开箱即用、零依赖的实时媒体服务器与代理，可通过 SRT、WebRTC、RTSP、RTMP、HLS、MPEG-TS、RTP 发布、读取、录制、回放和路由视频/音频流。 ([Source Code](https://github.com/bluenviron/mediamtx), [Clients](https://mediamtx.org/docs/kickoff/introduction)) `MIT` `Go/Docker`
- [Meelo](https://github.com/Arthi-chaud/Meelo) - 个人音乐服务器，为收藏家和音乐狂热者设计。`GPL-3.0` `Docker`
- [MistServer](https://mistserver.org/) - 公共领域的流媒体服务器，适用于任何设备和任何格式。 ([Source Code](https://github.com/DDVTECH/mistserver)) `Unlicense` `C++`
- [NymphCast](http://nyanko.ws/nymphcast.php) - 将你选择的可运行 Linux 的硬件变成电视或有源音箱的音视频源（Chromecast 的替代品）。 ([Source Code](https://github.com/MayaPosch/NymphCast)) `BSD-3-Clause` `C++`
- [Rygel](https://gnome.pages.gitlab.gnome.org/rygel/) - UPnP AV 媒体服务器，可轻松共享音频、视频和图片。媒体播放器软件可借助 Rygel 成为 MediaRenderer，由 UPnP 或 DLNA 控制器远程控制。 ([Source Code](https://gitlab.gnome.org/GNOME/rygel/)) `LGPL-2.1` `C`
- [Stash](https://stashapp.cc) - 基于 Web 的成人媒体收藏管理与播放工具，支持自动打标签和元数据抓取。 ([Source Code](https://github.com/stashapp/stash)) `AGPL-3.0` `Docker/Go`
- [µStreamer](https://github.com/pikvm/ustreamer) - 轻量极速的服务器，可将任何 V4L2 设备的 MJPEG 视频流式传输到网络。`GPL-3.0` `C/deb`
- [üWave](https://u-wave.net/) `⚠` - Collaborative listening platform. Users take turns playing media—songs, talks, gameplay videos, or anything else—from a variety of media sources like YouTube and SoundCloud. ([Demo](https://wlk.yt/), [Source Code](https://github.com/u-wave)) `MIT` `Nodejs`


### 媒体流 - 视频流

**[`^        back to top        ^`](#awesome-selfhosted)**

[Video](https://en.wikipedia.org/wiki/Video) streaming tools and software.

_Related: [Video Surveillance](#video-surveillance), [Media Streaming - Multimedia Streaming](#media-streaming---multimedia-streaming), [Photo Galleries](#photo-galleries), [Media Management](#media-management)_

- [CyTube](https://github.com/calzoneman/sync) - 为任意数量的频道同步媒体、聊天等内容。 ([Demo](https://cytu.be)) `MIT` `Nodejs`
- [Invidious](https://github.com/iv-org/invidious) `⚠` - Alternative YouTube front-end. ([Demo](https://docs.invidious.io/instances/)) `AGPL-3.0` `Docker/Crystal`
- [MediaCMS](https://mediacms.io) - 现代的全功能视频与媒体 CMS，使用 Python/Django/React 编写，提供 REST API。 ([Source Code](https://github.com/mediacms-io/mediacms)) `AGPL-3.0` `Python/Docker`
- [OvenMediaEngine](https://github.com/OvenMediaLabs/OvenMediaEngine) - 亚秒级延迟的流媒体服务器。 ([Demo](https://demo.ovenplayer.com)) `AGPL-3.0` `C++/Docker`
- [Owncast](https://owncast.online/) - 去中心化的单用户直播视频流与聊天服务器，用于运行风格类似大型主流平台的个人直播。 ([Source Code](https://github.com/owncast/owncast)) `MIT` `Go`
- [PeerTube](https://joinpeertube.org/en/) - 直接在浏览器中使用 P2P（BitTorrent）的去中心化视频流平台。 ([Source Code](https://github.com/Chocobozzz/PeerTube)) `AGPL-3.0` `Nodejs`
- [Rapidbay](https://github.com/hauxir/rapidbay/) - 视频流服务/种子客户端，可在浏览器或 Chromecast/AppleTV/智能电视上搜索并播放来自种子的视频。`MIT` `Python/Docker`
- [Restreamer](https://datarhei.github.io/restreamer/) - 无需流媒体服务商，即可在你的网站上使用 H.264 实时视频流。 ([Source Code](https://github.com/datarhei/restreamer)) `Apache-2.0` `Nodejs/Docker`
- [SRS](https://ossrs.io/) - 简单、高效、实时的视频服务器，支持 RTMP、WebRTC、HLS、HTTP-FLV 和 SRT。 ([Source Code](https://github.com/ossrs/srs)) `MIT` `Docker/C++`
- [SyncTube](https://github.com/RblSb/SyncTube) - 轻量且设置非常简单的 CyTube 替代品，可与朋友一起看视频并聊天。`MIT` `Nodejs/Haxe`
- [Tiramisu](https://github.com/MrRobotoGit/tiramisu) - 带 FUSE 虚拟文件系统的 BitTorrent 引擎，无需下载即可将种子实时流式供给 Plex/Jellyfin（Real-Debrid 的替代品）。`GPL-2.0` `Go/Docker`
- [Tube Archivist](https://tubearchivist.com/) `⚠` - Organize, search, and enjoy your YouTube collection. Subscribe, download, and track viewed content with metadata indexing and a user-friendly interface. ([Source Code](https://github.com/tubearchivist/tubearchivist), [Clients](https://docs.tubearchivist.com/faq/#how-do-i-import-my-videos-to-emby-plex-jellyfin-kodi)) `GPL-3.0` `Docker`
- [Tube](https://git.mills.io/prologic/tube) - 类 YouTube（没有审查和你不需要的功能！）的视频分享应用，使用 Go 编写，还支持自动转码为 MP4 H.265 AAC、多个收藏集和 RSS 订阅。`MIT` `Go`
- [VideoLAN Client (VLC)](https://www.videolan.org/) - 跨平台多媒体播放器客户端与服务器，支持大多数多媒体文件以及 DVD、Audio CD、VCD 和各种流媒体协议。 ([Source Code](https://code.videolan.org/videolan/vlc)) `GPL-2.0` `C/deb`


### 杂项

**[`^        back to top        ^`](#awesome-selfhosted)**

Software that does not fit in another section.

- [2FAuth](https://github.com/Bubka/2FAuth) - 管理你的双因素认证（2FA）账户并生成其安全码。 ([Demo](https://demo.2fauth.app/)) `AGPL-3.0` `PHP/Docker`
- [Anchr](https://anchr.io) - 互联网小任务工具箱，包括书签收藏、URL 缩短和（加密）图片上传。 ([Source Code](https://github.com/muety/anchr)) `GPL-3.0` `Nodejs`
- [Anubis](https://anubis.techaro.lol/) - Web AI 防火墙工具，保护上游资源免遭爬虫机器人抓取。 ([Source Code](https://github.com/TecharoHQ/anubis)) `MIT` `Docker/deb/Go`
- [asciinema](https://asciinema.org/) - 用于托管 asciicasts 的 Web 应用。 ([Demo](https://asciinema.org/explore), [Source Code](https://github.com/asciinema/asciinema-server)) `Apache-2.0` `Elixir/Docker`
- [Baby Buddy](https://github.com/babybuddy/babybuddy) - 帮助照护者记录婴儿的睡眠、喂养、换尿布和俯卧练习时间。 ([Demo](https://github.com/babybuddy/babybuddy#-demo)) `BSD-2-Clause` `Python`
- [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade) - 无需按任何按钮，即可在多台设备间即时同步剪贴板。支持 Windows、macOS、Linux 和 Android，通过端到端数据加密提供无缝且安全的剪贴板共享。`GPL-3.0` `Java/Docker`
- [Cloudlog](https://magicbug.co.uk/cloudlog/) - 随时随地记录你的业余无线电通联日志。 ([Source Code](https://github.com/magicbug/cloudlog)) `MIT` `PHP/Docker`
- [ConvertX](https://github.com/C4illin/ConvertX) - 支持一千多种不同格式的在线文件转换器。`AGPL-3.0` `Docker`
- [CUPS](https://www.cups.org/) - 通用 Unix 打印系统，使用互联网打印协议（IPP）支持向本地和网络打印机打印。 ([Source Code](https://github.com/OpenPrinting/cups)) `GPL-2.0` `C`
- [CyberChef](https://github.com/gchq/CyberChef) - 在 Web 浏览器内执行各种操作，如 AES、DES 和 Blowfish 加密解密、创建十六进制转储、计算哈希等。 ([Demo](https://gchq.github.io/CyberChef)) `Apache-2.0` `Javascript`
- [Digiboard](https://digiboard.app/) - 创建协作式白板（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digiboard)) `AGPL-3.0` `Nodejs`
- [Digicard](https://codeberg.org/ladigitale/digicard) - 创建简单的图形作品（文档为法语）。 ([Demo](https://ladigitale.dev/digicard/)) `AGPL-3.0` `Nodejs`
- [Digicut](https://ladigitale.dev/digicut/) - 使用 FFMPEG.wasm 剪辑音频和视频文件（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digicut)) `AGPL-3.0` `Nodejs`
- [Digiface](https://ladigitale.dev/digiface/) - 使用 Avataaars 库创建头像（文档为法语）。 ([Demo](https://ladigitale.dev/digiface/), [Source Code](https://codeberg.org/ladigitale/digiface)) `AGPL-3.0` `Nodejs`
- [Digiflashcards](https://ladigitale.dev/digiflashcards/) - 创建抽认卡的在线应用（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digiflashcards)) `AGPL-3.0` `Nodejs/PHP`
- [Digimerge](https://ladigitale.dev/digimerge/) - 直接在浏览器中拼接音频和视频文件（文档为法语）。 ([Demo](https://ladigitale.dev/digimerge/), [Source Code](https://codeberg.org/ladigitale/Digimerge)) `AGPL-3.0` `Nodejs`
- [Digiquiz](https://ladigitale.dev/digiquiz/) - 发布 H5P 所创建内容的在线应用（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digiquiz)) `AGPL-3.0` `Nodejs`
- [Digiread](https://ladigitale.dev/digiread/) `⚠` - Clean up online pages and articles using Mozilla's Readability (documentation in French). ([Source Code](https://codeberg.org/ladigitale/digiread)) `AGPL-3.0` `Nodejs/PHP`
- [Digisteps](https://ladigitale.dev/digisteps/) - 用于创建在线教育路径的简单应用（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digisteps)) `AGPL-3.0` `Nodejs/PHP`
- [Digitranscode](https://ladigitale.dev/digitranscode) - 直接在浏览器中转换音频文件和视频（文档为法语）。 ([Demo](https://ladigitale.dev/digitranscode), [Source Code](https://codeberg.org/ladigitale/digitranscode)) `AGPL-3.0` `Nodejs`
- [Digiview](https://ladigitale.dev/digiview/) `⚠` - View YouTube videos in a distraction-free interface (documentation in French). ([Demo](https://ladigitale.dev/digiview/), [Source Code](https://codeberg.org/ladigitale/digiview)) `AGPL-3.0` `Nodejs/PHP`
- [Digiwords](https://ladigitale.dev/digiwords/) - 创建词云的简单在线应用（文档为法语）。 ([Source Code](https://codeberg.org/ladigitale/digiwords)) `AGPL-3.0` `Nodejs/PHP`
- [DOCAT](https://github.com/docat-org/docat) - 托管你的文档。简单、带版本、美观。`MIT` `Python/Docker`
- [Domain Locker](https://domain-locker.com) - 域名组合管理与追踪工具。 ([Demo](https://demo.domain-locker.com), [Source Code](https://github.com/lissy93/domain-locker)) `MIT` `Deno/Docker`
- [DOMJudge](https://www.domjudge.org/) - 用于运行编程竞赛的系统，例如 ICPC 区域赛和世界总决赛等编程竞赛。 ([Demo](https://www.domjudge.org/demo), [Source Code](https://github.com/DOMjudge/domjudge)) `GPL-2.0/BSD-3-Clause/MIT` `PHP`
- [ESMira](https://esmira.kl.ac.at) - 运行纵向研究（ESM、AA、EMA），数据收集和与参与者的沟通完全匿名。 ([Demo](https://demo-esmira.kl.ac.at/#admin,username:demo,password:demodemodemo), [Source Code](https://github.com/KL-Psychological-Methodology/ESMira)) `AGPL-3.0` `PHP`
- [F-Droid](https://f-droid.org) - 维护 F-Droid 仓库系统的服务器工具。 ([Source Code](https://gitlab.com/fdroid/fdroidserver)) `AGPL-3.0` `Python/Docker/deb`
- [Flyimg](https://flyimg.io) - 即时调整图像大小并裁剪。使用 ImageMagick 以 MozJPEG、WebP 或 PNG 获取优化图像，并配备高效缓存系统。 ([Demo](https://demo.flyimg.io), [Source Code](https://github.com/flyimg/flyimg)) `MIT` `Docker`
- [Garlic-Hub](https://garlic-signage.com/garlic-hub/) - 带 SMIL 播放列表支持与定时排期的数字标牌设备与内容管理系统。 ([Source Code](https://github.com/garlic-signage/garlic-hub)) `AGPL-3.0` `Docker`
- [Geeftlist](https://codeberg.org/nanawel/geeftlist) - 供亲友之间管理、分享和预订礼物的协作平台。`GPL-3.0` `Docker`
- [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper) `⚠` - Hassle-Free Way to Self-Host Google Fonts. Get eot, ttf, svg, woff and woff2 files + CSS snippets. ([Demo](https://gwfh.mranftl.com/fonts)) `MIT` `Nodejs`
- [Habitica](https://habitica.com/) - 把你的目标当作角色扮演游戏来对待的习惯追踪应用。 ([Source Code](https://github.com/HabitRPG/habitica)) `GPL-3.0/CC-BY-SA-3.0` `Nodejs/Docker`
- [HortusFox](https://hortusfox.github.io) - 面向植物爱好者的协作式植物管理与追踪系统。 ([Source Code](https://github.com/danielbrendel/hortusfox-web)) `MIT` `PHP/Docker`
- [ImgCompress](https://imgcompress.karimzouine.com) - 完全在 Docker 中运行的图像处理工具。使用本地 AI 压缩、转换、调整大小、批量处理图像并移除背景，无需依赖云端。 ([Source Code](https://github.com/karimz1/imgcompress)) `GPL-3.0` `Docker`
- [Infisical Community Edition](https://infisical.com/) - 用于机密信息、证书和特权访问管理的平台。 ([Source Code](https://github.com/Infisical/infisical)) `MIT` `Docker/K8S/deb`
- [iSponsorBlockTV](https://github.com/dmunozv04/iSponsorBlockTV) `⚠` - Block and skip sponsors, while also muting and skipping ads on YouTube. `GPL-3.0` `Docker/Python`
- [IT-Tools by sharevb](https://github.com/sharevb/it-tools) - 面向开发者的实用在线工具集（it-tools 的分支）。 ([Demo](https://sharevb-it-tools.vercel.app/)) `GPL-3.0` `Docker`
- [Jelu](https://bayang.github.io/jelu-web) - 已读与想读书单的图书追踪工具。 ([Source Code](https://github.com/bayang/jelu)) `MIT` `Java/Docker`
- [jetlog](https://github.com/pbogre/jetlog) - 个人航班追踪与查看工具。`GPL-2.0` `Docker`
- [Kasm Workspaces](https://kasmweb.com/) - 将容器化的应用和桌面流式交付给最终用户。例如在浏览器中运行 Ubuntu，或仅运行 Chrome、OpenOffice、Gimp、Filezilla 等单个应用。 ([Demo](https://www.kasmweb.com/#demo), [Source Code](https://github.com/kasmtech)) `GPL-3.0` `Docker`
- [Koillection](https://koillection.github.io/) - 允许用户管理任意类型收藏的服务。 ([Source Code](https://github.com/benjaminjonard/koillection)) `MIT` `Docker/PHP`
- [LanguageTool](https://languagetool.org/) - 可校对 20 多种语言。能发现简单拼写检查器无法检测的许多错误。 ([Source Code](https://github.com/languagetool-org/languagetool), [Clients](https://languagetool.org/insights/post/product-windows-app/)) `LGPL-2.1` `Java/Docker`
- [Libre Translate](https://libretranslate.com/) - 机器翻译 API。 ([Source Code](https://github.com/LibreTranslate/LibreTranslate)) `AGPL-3.0` `Docker/Python`
- [LubeLogger](https://lubelogger.com) - 基于 Web 的车辆保养与油耗追踪工具。 ([Demo](https://github.com/hargata/lubelog?tab=readme-ov-file#demo), [Source Code](https://github.com/hargata/lubelog)) `MIT` `Docker/K8S/C#`
- [Mirumoji](https://svdc1.github.io/mirumoji/docs) - 日语沉浸式学习工具包，提供可点击的分词字幕，支持词典查询和转录生成。 ([Demo](https://svdc1.github.io/mirumoji/), [Source Code](https://github.com/svdC1/mirumoji)) `MIT` `Docker/Python`
- [mosparo](https://mosparo.io/) - 现代垃圾信息防护工具。以简单易用的垃圾信息防护方案取代其他验证码方式。 ([Source Code](https://github.com/mosparo/mosparo)) `MIT` `PHP`
- [Movary](https://github.com/leepeuker/movary) `⚠` - Web app to track and rate your watched movies. ([Demo](https://github.com/leepeuker/movary?tab=readme-ov-file#demo)) `MIT` `Docker/PHP`
- [Neko](https://neko.m1k1o.net) - 在 Docker 中运行并使用 WebRTC 的虚拟浏览器。 ([Source Code](https://github.com/m1k1o/neko)) `Apache-2.0` `Docker/Go`
- [OmniTools](https://omnitools.app/) - 面向日常任务（编码、处理图像/视频、PDF 或数字计算等）的强大基于 Web 的工具集。 ([Source Code](https://github.com/iib0011/omni-tools)) `MIT` `Docker`
- [Open-Meteo](https://open-meteo.com/) - 天气 API，提供来自各大国家气象服务的开放数据预报、历史和气候数据。 ([Demo](https://open-meteo.com/en/docs), [Source Code](https://github.com/open-meteo/open-meteo)) `AGPL-3.0` `Docker`
- [OpenReader](https://docs.openreader.richardr.dev/) - 支持 EPUB、PDF、DOCX、MD 和 TXT 文件的文本转语音文档阅读器。使用高质量 TTS 实时朗读文档，或提取有声书。 ([Source Code](https://github.com/richardr1126/openreader)) `MIT` `Docker`
- [OpenZiti](https://openziti.io/) - 功能完备、零信任的全网状覆盖网络。开箱即支持 2FA，并配备适用于所有主流桌面/移动操作系统的客户端。 ([Source Code](https://github.com/openziti/ziti)) `Apache-2.0` `Go`
- [Operational.co](https://operational.co) - 在实时时间线中接收来自你产品的警报。 ([Demo](https://app.operational.co/?signinas=kevin), [Source Code](https://github.com/operational-co/operational.co)) `AGPL-3.0` `Nodejs/Docker`
- [penpot](https://penpot.app/) - 面向跨领域团队的基于 Web 的设计与原型平台。 ([Source Code](https://github.com/penpot/penpot)) `MPL-2.0` `Docker`
- [POMjs](https://password.oppetmoln.se/) - 随机密码生成器。 ([Source Code](https://github.com/joho1968/POMjs)) `GPL-2.0` `Javascript`
- [Pønskelisten](https://github.com/aunefyren/poenskelisten) - 分享愿望清单，协作挑选礼物。`GPL-3.0` `Docker/Go`
- [re:Director](https://re-director.github.io/) - 简单的域名重定向管理工具。 ([Source Code](https://github.com/re-Director/re-director)) `Apache-2.0` `Java/Docker`
- [Reactive Resume](https://rxresu.me/) - 独一无二的简历构建工具，注重你的隐私。完全安全、可定制且可移植。 ([Demo](https://rxresu.me/), [Source Code](https://github.com/reactive-resume/reactive-resume)) `MIT` `Docker/Nodejs`
- [revealjs](https://revealjs.com) - 使用 HTML 轻松创建精美演示文稿的框架。 ([Demo](https://revealjs.com/), [Source Code](https://github.com/hakimel/reveal.js)) `MIT` `Javascript`
- [Revive Adserver](https://www.revive-adserver.com/) - 广告投放系统。前身为 OpenX Adserver 和 phpAdsNew。 ([Source Code](https://github.com/revive-adserver/revive-adserver)) `GPL-2.0` `PHP`
- [SANE Network Scanning](http://sane-project.org/) - 允许远程客户端访问本地主机上的图像采集设备（扫描仪）。 ([Source Code](http://www.sane-project.org/cvs.html)) `GPL-2.0` `C`
- [string.is](https://string.is/) - 面向开发者的在线字符串工具箱。 ([Source Code](https://github.com/recurser/string-is)) `AGPL-3.0` `Nodejs`
- [Teleport](https://goteleport.com/) - 面向 SSH、Kubernetes、Web 应用和数据库的证书颁发机构与访问平面。 ([Source Code](https://github.com/gravitational/teleport)) `Apache-2.0` `Go/Docker/K8S`
- [TeslaMate](https://github.com/teslamate-org/teslamate) - 功能强大的 Tesla 车辆数据记录器。`MIT` `Elixir/Docker`
- [Transmute](https://transmute.sh) - 支持图像、视频、音频、json、excel 等的文件转换器，支持超过 2,000 种转换。 ([Source Code](https://github.com/transmute-app/transmute)) `MIT` `Docker`
- [URL-to-PNG](https://github.com/jasonraimondi/url-to-png) - URL 转 PNG 工具，使用 Playwright 并行渲染截图，支持通过本地、S3 或 CouchDB 进行存储缓存。`MIT` `Nodejs/Docker`
- [Usertour](https://www.usertour.io/) - 用户引导平台，让你几分钟内轻松创建应用内产品导览、清单和调查问卷。 ([Source Code](https://github.com/usertour/usertour/)) `AGPL-3.0` `Docker`
- [Warracker](https://warracker.com) - 保修追踪工具，可监控到期日、上传收据/文件，并在保修到期前收到提醒。 ([Source Code](https://github.com/sassanix/Warracker)) `AGPL-3.0` `Docker`
- [Wavelog](https://www.wavelog.org) - 面向业余无线电爱好者的基于 Web 的日志软件。为你的浏览器提供增强的 QSO 日志、统计和地图。 ([Demo](https://demo.wavelog.org), [Source Code](https://github.com/wavelog/wavelog)) `MIT` `PHP/Docker`
- [WeeWX](https://weewx.com/) - 为你的气象站打造的软件。 ([Demo](https://weewx.com/showcase.html), [Source Code](https://github.com/weewx/weewx)) `GPL-3.0` `Python/deb`
- [WeTTY](https://butlerx.github.io/wetty/#/) - 基于 http/https 的浏览器内终端。 ([Source Code](https://github.com/butlerx/wetty)) `MIT` `Docker/Nodejs`
- [Wishlist](https://github.com/cmintey/wishlist) - 可与朋友和家人分享的愿望清单应用。`MIT` `Docker/K8S`
- [Yamtrack](https://github.com/FuzzyGrim/Yamtrack) `⚠` - Media tracker for movies, tv shows, anime, manga, video games and books. ([Demo](https://github.com/FuzzyGrim/Yamtrack?tab=readme-ov-file#demo)) `AGPL-3.0` `Docker/Python`
- [Zero-TOTP](https://zero-totp.com) - 基于零知识加密的完整、可靠、安全且零信任的 Web 应用，用于存储你的 TOTP 验证码。 ([Source Code](https://github.com/SeaweedbrainCY/zero-totp)) `GPL-3.0` `Docker`


### 货币、预算与管理

**[`^        back to top        ^`](#awesome-selfhosted)**

[Money management](https://en.wikipedia.org/wiki/Money_management) and budgeting software.

_Related: [Inventory Management](#inventory-management), [Resource Planning](#resource-planning)_

- [Actual](https://actualbudget.org) - 基于零和预算的本地优先个人财务工具，支持跨设备同步、自定义规则、手动导入交易（来自 QIF、OFX 和 QFX 文件），以及可选的与多家银行自动同步。 ([Source Code](https://github.com/actualbudget/actual)) `MIT` `Nodejs/Docker`
- [Bigcapital](https://bigcapital.app/) - 面向中小企业的财务会计与库存管理软件。 ([Source Code](https://github.com/bigcapitalhq/bigcapital)) `AGPL-3.0` `Docker`
- [Bitcart](https://bitcart.ai) - 加密货币支付处理与开发平台。 ([Demo](https://admin.bitcart.ai), [Source Code](https://github.com/bitcart/bitcart)) `MIT` `Docker/Python/Nodejs`
- [BTCPay Server](https://btcpayserver.org/) - 比特币及其他加密货币支付处理器。 ([Demo](https://mainnet.demo.btcpayserver.org/), [Source Code](https://github.com/btcpayserver/btcpayserver)) `MIT` `C#`
- [Budget Board](https://budgetboard.net/) - 追踪每月支出并努力实现财务目标的简单应用。 ([Source Code](https://github.com/teelur/budget-board)) `GPL-3.0` `Docker`
- [DePay](https://depay.com) - 以点对点（P2P）方式将 Web3 支付直接收入你的钱包。 ([Demo](https://depay.com/products/payments), [Source Code](https://github.com/depayfi/widgets)) `MIT` `Nodejs`
- [Econumo](https://econumo.com) - 用于管理个人和家庭财务的预算应用，支持多种货币、联名账户和预算。 ([Demo](https://demo.econumo.com), [Source Code](https://github.com/econumo/econumo)) `MIT` `Docker`
- [Expensave](https://github.com/algirdasc/expensave) - 用于个人和家庭预算管理的支出追踪工具。在共享日历上追踪支出、导入银行对账单，并通过报告监控财务状况。`GPL-3.0` `Docker`
- [ezbookkeeping](https://ezbookkeeping.mayswind.net/) - 自行托管的轻量级个人记账应用。 ([Demo](https://ezbookkeeping-demo.mayswind.net/), [Source Code](https://github.com/mayswind/ezbookkeeping)) `MIT` `Go/Docker`
- [Family Accounting Tool](https://github.com/nymanjens/facto) - 面向有部分共同开支的伴侣的基于 Web 的财务管理工具。`Apache-2.0` `Scala`
- [Fava](https://beancount.github.io/fava/) - Beancount 的 Web 前端，Beancount 是一个基于文本的复式记账系统。 ([Demo](https://fava.pythonanywhere.com/example-with-budgets/income_statement/), [Source Code](https://github.com/beancount/fava)) `MIT` `Python`
- [Firefly III](https://firefly-iii.org/) - 现代财务管理器。帮助你记录资金动向并进行预算预测。支持信用卡，拥有先进的规则引擎，并可从多家银行导入数据。 ([Demo](https://demo.firefly-iii.org/), [Source Code](https://github.com/firefly-iii/firefly-iii)) `AGPL-3.0` `PHP/Docker`
- [FOSSBilling](https://fossbilling.org/) - 托管与计费自动化。与 WHM、CWP、cPanel 和 HestiaCP 集成，提供完整 API 且易于扩展。 ([Demo](https://fossbilling.org/demo), [Source Code](https://github.com/FOSSBilling/FOSSBilling)) `Apache-2.0` `PHP/Docker`
- [Galette](https://galette.eu/) - 面向非营利组织的会员管理 Web 应用。 ([Source Code](https://github.com/galette/galette)) `GPL-3.0` `PHP`
- [Ghostfolio](https://ghostfol.io/) - 财富管理软件，用于跟踪股票、ETF 和加密货币。 ([Source Code](https://github.com/ghostfolio/ghostfolio)) `AGPL-3.0` `Docker/Nodejs`
- [GRR](https://grr.devome.com/?lang=en) - 面向中小企业的资产管理和预约。 ([Source Code](https://github.com/JeromeDevome/GRR)) `GPL-2.0` `PHP`
- [HyperSwitch](https://hyperswitch.io/) `⚠` - Payment switch to make payments fast, reliable and affordable. Connect with multiple payment processors and route traffic effortlessly, all with a single API integration. ([Source Code](https://github.com/juspay/hyperswitch)) `Apache-2.0` `Docker/Rust`
- [IHateMoney](https://ihatemoney.org/) - 轻松管理你的共享开支。 ([Demo](https://ihatemoney.org/demo/), [Source Code](https://github.com/spiral-project/ihatemoney)) `BSD-3-Clause` `Docker/Python`
- [InvoicePlane](https://www.invoiceplane.com/) - 为你的小型企业管理报价、发票、付款和客户。 ([Source Code](https://github.com/InvoicePlane/InvoicePlane)) `MIT` `PHP`
- [InvoiceShelf](https://invoiceshelf.com/) - 跟踪支出与付款，并创建专业的发票与估价单（Crater 的分支）。 ([Source Code](https://github.com/InvoiceShelf/InvoiceShelf)) `AGPL-3.0` `PHP/Docker`
- [Kill Bill](https://killbill.io/) - 订阅计费与支付平台。可使用实时分析和财务报表。 ([Source Code](https://github.com/killbill/killbill)) `Apache-2.0` `Java/Docker`
- [Kresus](https://kresus.org/) - 个人财务管理器。 ([Demo](https://kresus.org/en/demo.html), [Source Code](https://github.com/kresusapp/kresus)) `AGPL-3.0` `Nodejs/Docker`
- [Lago](https://www.getlago.com/) - 计量与按用量计费。 ([Source Code](https://github.com/getlago/lago)) `AGPL-3.0` `Docker`
- [Mybucks.online](https://mybucks.online) - 安全、基于浏览器、仅凭密码即可使用的自主保管加密货币钱包。 ([Demo](https://app.mybucks.online), [Source Code](https://github.com/mybucks-online/app)) `MIT` `Nodejs`
- [MyFin Budget](https://myfinbudget.com) - 个人财务平台（Web + REST API + Android），帮助你制定预算、记录收入/支出并预测财务前景。 ([Demo](https://github.com/afaneca/myfin?tab=readme-ov-file#demo-account---try-it-for-yourself), [Source Code](https://github.com/afaneca/myfin), [Clients](https://github.com/afaneca/myfin-api)) `GPL-3.0` `Nodejs/Docker`
- [OctoBot](https://www.octobot.cloud/) - 加密货币交易机器人。 ([Source Code](https://github.com/Drakkar-Software/OctoBot)) `GPL-3.0` `Python/Docker`
- [Ocular](https://simonwep.github.io/ocular/) - 简洁直观的预算应用，可跨月份和年份跟踪预算。 ([Demo](https://simonwep.github.io/ocular/demo/#demo), [Source Code](https://github.com/simonwep/ocular)) `MIT` `Docker`
- [OpenBudgeteer](https://github.com/TheAxelander/OpenBudgeteer) - 基于桶式预算原则（Bucket Budgeting Principle）的预算应用。`AGPL-3.0` `Docker/C#`
- [Receipt Wrangler](https://receiptwrangler.io) `⚠` - Easy-to-use receipt manager, powered by AI. Allows users to create receipts effortlessly and quickly, categorize and more. ([Demo](https://demo.receiptwrangler.io), [Source Code](https://github.com/Receipt-Wrangler/receipt-wrangler)) `AGPL-3.0` `Docker`
- [REI3](https://rei3.de/home_en/) - 管理企业内的任务、时间、资产等。 ([Demo](https://rei3.de/demo_en/), [Source Code](https://github.com/r3-team/r3)) `MIT` `Go`
- [SHKeeper](https://shkeeper.io/) - 加密货币支付处理器，独特地集网关与商户功能于一体，让你无需手续费和中介即可接受多种加密货币付款。 ([Demo](https://github.com/vsys-host/shkeeper.io?tab=readme-ov-file#11-demo), [Source Code](https://github.com/vsys-host/shkeeper.io)) `GPL-3.0` `Python`
- [SolidInvoice](https://solidinvoice.co) - 发票与报价应用。 ([Source Code](https://github.com/SolidInvoice/SolidInvoice)) `MIT` `PHP`
- [Sure](https://github.com/we-promise/sure) - 面向所有人的个人财务应用（Maybe 的分支）。`AGPL-3.0` `Docker`
- [VoucherVault](https://github.com/l4rm4nd/VoucherVault) - 以数字化方式存储和管理代金券、优惠券、会员卡和礼品卡。支持到期通知、交易历史、文件上传和 OIDC SSO。`GPL-3.0` `Docker`
- [Wallos](https://wallosapp.com) - 轻量级个人订阅跟踪器，提供统计功能和可选通知。 ([Demo](https://github.com/ellite/wallos?tab=readme-ov-file#demo), [Source Code](https://github.com/ellite/wallos)) `GPL-3.0` `PHP/Docker`
- [WYGIWYH](https://github.com/eitchtee/WYGIWYH) - 简单而强大的财务跟踪器。 ([Demo](https://wygiwyh-demo.herculino.com/)) `AGPL-3.0` `Docker/Python`
- [YAFFA](https://www.yaffa.cc) - 个人财务 Web 应用，可用于跟踪你的资金、支出、预算和投资，并有助于长期财务规划。 ([Demo](https://sandbox.yaffa.cc), [Source Code](https://github.com/kantorge/yaffa)) `MIT` `PHP`


### Monitoring & Status Pages

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for [monitoring](https://en.wikipedia.org/wiki/Monitoring#Computing) systems, networks, applications and websites. 

**Please visit [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring--status-pages), [awesome-sysadmin/Metrics and Metric Collection](https://github.com/awesome-foss/awesome-sysadmin#metrics--metric-collection)**

_Related: [Personal Dashboards](#personal-dashboards)_



### 网络工具

**[`^        back to top        ^`](#awesome-selfhosted)**

Network utilities are tools and software that help manage, monitor, and troubleshoot computer networks.

_See also: [awesome-sysadmin/Monitoring](https://github.com/awesome-foss/awesome-sysadmin#monitoring)_

- [beelzebub](https://beelzebub-honeypot.com/) `⚠` - Honeypot framework designed to provide a highly secure environment for detecting and analyzing cyber attacks. ([Source Code](https://github.com/beelzebub-labs/beelzebub)) `MIT` `Docker/K8S/Go`
- [Canary Tokens](https://canarytokens.org) - 生成轻量级的内嵌蜜罐触发器（称为 canary tokens），用于检测未经授权的访问。 ([Source Code](https://github.com/thinkst/opencanary)) `BSD-3-Clause` `Docker/Python`
- [MyIP](https://ipcheck.ing) `⚠` - All in one IP Toolbox. Easy to check what's your IPs, IP geolocation, check for DNS leaks, examine WebRTC connections, speed test, ping test, MTR test, check website availability and more. ([Demo](https://ipcheck.ing), [Source Code](https://github.com/jason5ng32/MyIP)) `MIT` `Nodejs/Docker`
- [MySpeed](https://myspeed.dev/) - 网速测试分析软件，可展示最长 30 天的网络速度。 ([Source Code](https://github.com/gnmyt/myspeed)) `MIT` `Docker/Nodejs`
- [NetAlertX](https://netalertx.com/) - 网络入侵与设备存在检测器。扫描连接到你网络中的设备，并在发现新的未知设备时向你发出警报。 ([Source Code](https://github.com/netalertx/NetAlertX)) `GPL-3.0` `Docker`
- [PlugNPiN](https://deepspace2.github.io/PlugNPiN) - 自动抓取带有特定标签的容器，在 Pi-Hole/AdGuard Home 中创建本地 DNS/CNAME 记录，并在 Nginx Proxy Manager 中创建代理主机。 ([Source Code](https://github.com/deepspace2/plugnpin)) `GPL-3.0` `Docker`
- [Speed Test by OpenSpeedTest™](https://openspeedtest.com/) - HTML5 网络性能评估工具。 ([Source Code](https://github.com/openspeedtest/Speed-Test)) `MIT` `Docker`
- [Speedtest Tracker](https://docs.speedtest-tracker.dev/) - 监控你互联网连接的性能和正常运行时间。 ([Source Code](https://github.com/alexjustesen/speedtest-tracker)) `MIT` `Docker/K8S`
- [Upsnap](https://github.com/seriousm4x/UpSnap) - 简单的局域网唤醒（WOL）面板应用。唤醒网络中的设备并查看当前状态。`MIT` `Go/Docker`
- [Wakupator](https://github.com/Gibus21250/Wakupator) - 基于网络流量的局域网唤醒（Wake On LAN）机器管理器。`MIT` `C`
- [whois](https://github.com/KincaidYang/whois) - 面向域名、IP 地址、CIDR 前缀和 ASN 的 WHOIS/RDAP 查询 API，提供统一的 JSON 输出、缓存、API 密钥认证、批量查询，并支持供 AI 助手使用的 MCP。 ([Demo](https://whois.ddnsip.cn/example.com)) `MIT` `Go/Docker`


### 笔记与编辑器

**[`^        back to top        ^`](#awesome-selfhosted)**

[Note taking](https://en.wikipedia.org/wiki/Note-taking) editors.

_Related: [Wikis](#wikis)_

- [Blinko](https://blinko.space/) - 具备 AI 功能的个人笔记工具。 ([Source Code](https://github.com/blinkospace/blinko)) `AGPL-3.0` `Docker`
- [DailyTxT](https://github.com/PhiTux/DailyTxT) - 加密日记 Web 应用，用于保存你的每日个人记忆。包含搜索功能和加密文件上传。 ([Demo](https://dailytxt.phitux.de)) `MIT` `Docker`
- [Docs](https://docs.numerique.gouv.fr/) - 可扩展的协作笔记、Wiki 与文档平台。 ([Source Code](https://github.com/suitenumerique/docs)) `MIT` `K8S`
- [draw.io](https://draw.io) - 图表软件，用于制作流程图、过程图、组织结构图、UML、ER 和网络图。 ([Source Code](https://github.com/jgraph/drawio)) `Apache-2.0` `Javascript/Docker`
- [flatnotes](https://github.com/dullage/flatnotes) - 无需数据库的笔记 Web 应用，使用扁平的 Markdown 文件文件夹进行存储。 ([Demo](https://demo.flatnotes.io)) `MIT` `Docker`
- [HedgeDoc](https://hedgedoc.org/) - 支持所有平台的实时协作 Markdown 笔记，前身为 CodiMD 和 HackMD CE。 ([Demo](https://demo.hedgedoc.org/), [Source Code](https://github.com/hedgedoc/hedgedoc)) `AGPL-3.0` `Docker/Nodejs`
- [Joplin](https://joplinapp.org/) - 笔记应用，配备 Markdown 编辑器并支持加密，适用于移动和桌面平台。在客户端运行，可通过你自己的 Nextcloud 实例或类似服务同步（Evernote 的替代品）。 ([Source Code](https://github.com/laurent22/joplin)) `MIT` `Nodejs`
- [Jotty](https://jotty.page) - 轻量但强大的替代方案，用于管理基于文件的个人笔记和清单。 ([Source Code](https://github.com/fccview/jotty)) `AGPL-3.0` `Docker`
- [Livebook](https://livebook.dev) - 基于 Markdown 的实时协作笔记本应用，支持运行 Elixir 代码片段、TeX 和 Mermaid 图表。可使用 Docker 或 Elixir 轻松部署。 ([Source Code](https://github.com/livebook-dev/livebook)) `Apache-2.0` `Elixir/Docker`
- [Many Notes](https://github.com/brufdev/many-notes) - 为简洁而设计的 Markdown 笔记 Web 应用。`MIT` `Docker`
- [Memos](https://usememos.com/) - 使用 SQLite 数据库文件运行的知识库。 ([Demo](https://demo.usememos.com/explore), [Source Code](https://github.com/usememos/memos)) `MIT` `Docker/Go`
- [Neverkin](https://neverkin.com/) - 协作写作、世界观构建和 D&D 跑团规划应用，提供整理笔记和故事的工具。 ([Demo](https://app.neverkin.com/guest-login), [Source Code](https://github.com/Tenebrie/neverkin/)) `GPL-3.0` `Nodejs/Docker`
- [Note Mark](https://notemark.docs.enchantedcode.co.uk/) - 极简的基于 Web 的 Markdown 笔记应用。 ([Source Code](https://github.com/enchant97/note-mark)) `AGPL-3.0` `Docker`
- [NoteDiscovery](https://www.notediscovery.com/) - Markdown 笔记应用，具有纯文件存储、图谱视图和 MCP 集成（Obsidian、Notion 的替代品）。 ([Demo](https://gamosoft-notediscovery-demo.hf.space), [Source Code](https://github.com/gamosoft/NoteDiscovery)) `MIT` `Docker/Python`
- [Overleaf](https://www.overleaf.com/) - 基于 Web 的协作 LaTeX 编辑器。 ([Source Code](https://github.com/overleaf/overleaf)) `AGPL-3.0` `Ruby`
- [Plainpad](https://plainpad.org) - 面向云端的现代笔记应用，充分利用渐进式 Web 应用技术的最佳特性。 ([Demo](https://demo.plainpad.org), [Source Code](https://github.com/alextselegidis/plainpad)) `GPL-3.0` `PHP`
- [plumio](https://plumio.app/) - Markdown 笔记应用，具备实时预览、文档加密、多用户支持、多组织能力等更多特性。 ([Demo](https://demo.plumio.app/homepage), [Source Code](https://github.com/albertasaftei/plumio)) `AGPL-3.0` `Nodejs/Docker`
- [SilverBullet](https://silverbullet.md/) - 为具有黑客思维的人优化的笔记应用。 ([Demo](https://play.silverbullet.md/), [Source Code](https://github.com/silverbulletmd/silverbullet), [Clients](https://silverbullet.md/Libraries)) `MIT` `Docker/Deno`
- [Standard Notes](https://docs.standardnotes.com/self-hosting/getting-started) - 简单且私密的笔记应用。在完成更多工作的同时保护你的隐私。这就是 Standard Notes。 ([Demo](https://app.standardnotes.com/), [Source Code](https://github.com/standardnotes/app)) `GPL-3.0` `Ruby`
- [TriliumNext Notes](https://github.com/TriliumNext/Trilium) - 跨平台的层级式笔记应用，专注于构建大型个人知识库（Trilium Notes 的分支）。`AGPL-3.0` `Nodejs/Docker/K8S`
- [Turtl](https://turtl.it/) - 完全私密的个人数据库与笔记应用。 ([Source Code](https://github.com/turtl)) `GPL-3.0` `CommonLisp`
- [Writing](https://josephernest.github.io/writing/) - 浏览器中的轻量级无干扰文本编辑器（支持 Markdown 和 LaTeX），书写毫无延迟。 ([Source Code](https://github.com/josephernest/writing)) `MIT` `Javascript`


### 办公套件

**[`^        back to top        ^`](#awesome-selfhosted)**

An [office suite](https://en.wikipedia.org/wiki/List_of_office_suites) is a collection of productivity software usually containing at least a word processor, spreadsheet and a presentation program.

- [Collabora Online Development Edition](https://www.collaboraoffice.com/code) - Collabora Online Development Edition（CODE）是一个功能强大的基于 LibreOffice 的在线办公套件，支持所有主流文档、电子表格和演示文稿文件格式，可集成到你自己的基础设施中。 ([Source Code](https://gerrit.collaboraoffice.com/plugins/gitiles/online)) `MPL-2.0` `C++`
- [CryptPad](https://cryptpad.org) - 为协作而构建的协作套件，可实时同步文档更改。 ([Source Code](https://github.com/cryptpad/cryptpad)) `AGPL-3.0` `Nodejs/Docker`
- [Digislides](https://ladigitale.dev/digislides/) - 快速轻松地创建多媒体演示文稿（文档为法语）。 ([Demo](https://ladigitale.dev/digislides/), [Source Code](https://codeberg.org/ladigitale/Digislides)) `AGPL-3.0` `Nodejs/PHP`
- [Etherpad](https://etherpad.org/) - 高度可定制的在线编辑器，提供实时协作编辑。 ([Demo](https://demo.sandstorm.io/appdemo/h37dm17aa89yrd8zuqpdn36p6zntumtv08fjpu8a8zrte7q1cn60), [Source Code](https://github.com/ether/etherpad)) `Apache-2.0` `Nodejs/Docker`
- [Grist](https://getgrist.com/) - 新一代电子表格，具有关系型结构、基于公式的访问控制以及可移植的自包含格式（Airtable 的替代品）。 ([Demo](https://docs.getgrist.com), [Source Code](https://github.com/gristlabs/grist-core)) `Apache-2.0` `Nodejs/Python/Docker`
- [ONLYOFFICE](https://helpcenter.onlyoffice.com/faq/server-opensource.aspx) - 办公套件，让你在一处管理文档、项目、团队和客户关系。 ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPL-3.0` `Nodejs/Docker`


### 密码管理器

**[`^        back to top        ^`](#awesome-selfhosted)**

A [password manager](https://en.wikipedia.org/wiki/Password_manager) allows users to store, generate, and manage their passwords for local applications and online services.

- [AliasVault](https://www.aliasvault.net) - 端到端加密的密码管理器，内置电子邮件别名生成器和邮件服务器。 ([Source Code](https://github.com/aliasvault/aliasvault)) `MIT` `Docker`
- [Bitwarden](https://bitwarden.com/) `⚠` - Password manager with a webapp, browser extension, and mobile app. ([Source Code](https://github.com/bitwarden/server)) `AGPL-3.0` `Docker/C#`
- [Passbolt](https://www.passbolt.com/) - 协作式密码管理器。 ([Source Code](https://github.com/passbolt/passbolt_api)) `AGPL-3.0` `PHP/deb/K8S/Docker`
- [PassIt](https://passit.io/) - 简单的密码管理工具，支持按组和用户共享，但没有管理界面。 ([Demo](https://app.passit.io/), [Source Code](https://gitlab.com/passit)) `AGPL-3.0` `Docker/Python`
- [Psono](https://psono.com/) - 面向企业的密码管理器。 ([Demo](https://www.psono.pw), [Source Code](https://gitlab.com/esaqa/psono/psono-fileserver)) `Apache-2.0` `Python`
- [Teampass](https://teampass.net/) - 专用于以协作方式管理密码的密码管理器。使用一个对称密钥加密所有共享/团队密码，并以文件和数据库形式存储在服务器端。可运行在任何具备 Apache、MySQL 和 PHP 的服务器上。 ([Source Code](https://github.com/nilsteampassnet/TeamPass)) `GPL-3.0` `PHP`
- [Vaultwarden](https://github.com/dani-garcia/vaultwarden) - 用 Rust 编写的轻量级 Bitwarden 服务器 API 实现。`GPL-3.0` `Rust/Docker`


### Pastebin

**[`^        back to top        ^`](#awesome-selfhosted)**

A [pastebin](https://en.wikipedia.org/wiki/Pastebin) is a type of online content-hosting service used for sharing and storing code and text.

- [1time](https://1time.io) - 零知识的一次性机密分享。为密码、API 密钥或文件创建一次性链接。在浏览器端加密，永不以明文到达服务器，在允许的查看次数（默认一次）用尽后自毁。 ([Demo](https://1time.io), [Source Code](https://github.com/shingrus/1time.io)) `MIT` `Docker`
- [BinPastes](https://github.com/querwurzel/BinPastes) - 极简 pastebin，支持客户端加密、全文搜索和一次性消息。面向寻求简单 pastebin 部署的少量用户。`Apache-2.0` `Java`
- [ByteStash](https://github.com/jordan-dalby/ByteStash) - 带有简洁 Web 界面的 pastebin 和文件存储服务。支持语法高亮、可选用户认证和公开分享。 ([Demo](https://github.com/jordan-dalby/ByteStash?tab=readme-ov-file#demo)) `GPL-3.0` `Docker`
- [Chiyogami](https://github.com/rhee876527/chiyogami) - pastebin，提供 API、客户端加密、用户账户、语法高亮、Markdown 渲染等功能。 ([Demo](https://chiyogami.myaddr.dev/)) `BSD-3-Clause` `Docker`
- [dpaste](https://dpaste.org/) - 简单的 pastebin，提供多种文本和代码选项，并生成易于记忆的短网址。 ([Source Code](https://github.com/DarrenOfficial/dpaste)) `MIT` `Docker/Python`
- [lesma](https://lesma.eu) - 对浏览器和命令行都友好的简单粘贴应用。 ([Demo](https://lesma.eu), [Source Code](https://gitlab.com/ogarcia/lesma)) `GPL-3.0` `Rust/Docker`
- [Local Content Share](https://github.com/Tanq16/local-content-share) - 在本地网络内存储和分享文本片段与文件。`MIT` `Docker/Go`
- [not-th.re](https://not-th.re) - 简单的粘贴分享平台，支持客户端加密，采用 monaco 浏览器版代码编辑器。 ([Demo](https://not-th.re), [Source Code](https://github.com/not-three/main)) `AGPL-3.0` `Nodejs/Docker`
- [Opengist](https://opengist.io) - 由 Git 驱动的 pastebin。 ([Demo](https://demo.opengist.io), [Source Code](https://github.com/thomiceli/opengist)) `AGPL-3.0` `Docker/Go/Nodejs`
- [paaster](https://paaster.io) - 以简洁为设计目标的端到端加密 pastebin。 ([Source Code](https://github.com/WardPearce/paaster)) `AGPL-3.0` `Docker`
- [pacebin](https://git.crueter.xyz/crueter/pacebin) - 超极简的 pastebin 和文件上传服务，专注于可执行文件体积小、可移植性和易于配置。 ([Demo](https://paste.crueter.xyz)) `AGPL-3.0` `C`
- [Password Pusher](https://pwpush.com) - 极其简单的应用，用于通过 Web 安全传递密码（或文本）。密码在达到一定查看次数和/或经过一定时间后自动过期。 ([Source Code](https://github.com/pglombardo/PasswordPusher)) `Apache-2.0` `Docker/K8S/Ruby`
- [Pastefy](https://pastefy.app/) - 美观、简单且易于部署的 Pastebin，支持可选的客户端加密、多标签页粘贴、API、高亮编辑器等更多功能。 ([Source Code](https://github.com/interaapps/pastefy), [Clients](https://github.com/topics/pastefy-addon)) `MIT` `Docker/K8S/Java`
- [PrivateBin](https://privatebin.info/) - 极简的 pastebin/讨论板，服务器对所托管的数据零知识。 ([Demo](https://privatebin.net/), [Source Code](https://github.com/PrivateBin/PrivateBin)) `Zlib` `PHP`
- [rustypaste](https://github.com/orhun/rustypaste) - 极简的文件上传/pastebin 服务。`MIT` `Rust`
- [Snipo](https://github.com/MohamedElashri/snipo) - 轻量级自托管代码片段管理器，用于保存和组织代码与文本片段，支持文件夹、标签、API 和 GitHub Gist 同步。 ([Demo](https://snipo.melashri.dev/)) `AGPL-3.0` `Go/Docker`
- [SnyPy](https://snypy.com) - 本地部署的代码片段管理器。 ([Demo](https://app.snypy.com), [Source Code](https://github.com/snypy)) `MIT` `Docker`
- [Sup3rS3cretMes5age](https://github.com/algolia/sup3rS3cretMes5age) - 非常简单（部署和使用都很容易）的机密消息服务，使用 Hashicorp Vault 作为密钥存储。`MIT` `Go`
- [Wastebin](https://github.com/matze/wastebin) - 轻量、极简且快速的 pastebin，采用 SQLite 后端。 ([Demo](https://bin.bloerg.net)) `MIT` `Rust/Docker`
- [Yopass](https://github.com/jhaals/yopass) - 安全地分享机密、密码和文件。 ([Demo](https://yopass.se/)) `Apache-2.0` `Go/Docker`


### 个人仪表盘

**[`^        back to top        ^`](#awesome-selfhosted)**

Dashboards for accessing information and applications.

_Related: [Monitoring & Status Pages](#monitoring--status-pages), [Bookmarks and Link Sharing](#bookmarks-and-link-sharing)_

- [Compass](https://adinhodovic.github.io/compass/) - 面向服务、仪表盘和文档的落地页，支持从 Docker、Kubernetes、Tailscale 等来源自动发现。 ([Source Code](https://github.com/adinhodovic/compass)) `Apache-2.0` `Go/Docker/K8S`
- [Dashy](https://dashy.to/) - 功能丰富的家庭实验室主页，支持简便的 YAML 配置。 ([Demo](https://demo.dashy.to/), [Source Code](https://github.com/lissy93/dashy)) `MIT` `Nodejs/Docker`
- [Glance](https://github.com/glanceapp/glance) - 高度可定制的仪表盘，将你所有的信息源汇集在一处。`AGPL-3.0` `Docker/Go`
- [gobookmarks](https://github.com/arran4/gobookmarks) - 用于展示存储在 GitHub、GitLab 或本地 Git 中书签的落地页。`AGPL-3.0` `Go/Docker`
- [Heimdall](https://heimdall.site/) - 整理你所有 Web 应用的优雅方案。 ([Source Code](https://github.com/linuxserver/Heimdall)) `MIT` `PHP`
- [Homarr](https://homarr.dev) - 时尚现代的仪表盘，拥有众多集成和基于 Web 的配置。 ([Source Code](https://github.com/homarr-labs/homarr)) `MIT` `Docker/Nodejs`
- [Homepage by gethomepage](https://github.com/gethomepage/homepage) - 高度可定制的主页（或起始页/应用仪表盘），集成 Docker 和服务 API。`GPL-3.0` `Docker/Nodejs`
- [Homepage by tomershvueli](https://github.com/tomershvueli/homepage) - 简单、独立的 PHP 页面，是你通往服务器和网络的窗口。`MIT` `PHP`
- [Homer](https://github.com/bastienwirtz/homer) - 极简的静态主页，用于展示你的服务器服务，配有简单的 yaml 配置和连通性检查。 ([Demo](https://homer-demo.netlify.app)) `Apache-2.0` `Docker/K8S/Nodejs`
- [Hubleys](https://github.com/knrdl/hubleys-dashboard) - 个人仪表盘，通过中央 yaml 配置为多个用户组织链接。`MIT` `Docker`
- [LinkStack](https://linkstack.org/) - 在一个页面上便捷地链接你的所有社交媒体平台，可通过直观易用的用户/管理界面自定义（Linktree 和 Manylink 的替代品）。 ([Demo](https://linksta.cc/), [Source Code](https://github.com/LinkStackOrg/LinkStack)) `AGPL-3.0` `PHP/Docker`
- [LittleLink](https://littlelink.io/) - 极简的个人主页链接方案，提供 100 多个品牌按钮（Linktree 的替代品）。 ([Demo](https://littlelink.io/), [Source Code](https://github.com/sethcottle/littlelink)) `MIT` `Javascript`
- [Mafl](https://mafl.hywax.space/) - 极简而灵活的主页。 ([Source Code](https://github.com/hywax/mafl)) `MIT` `Docker/Nodejs`
- [Nimbus](https://nimbus.turboot.com/) - 现代的拖拽式家庭实验室仪表盘，配有可视化编辑器和简单配置。 ([Demo](https://nimbus.turboot.com/), [Source Code](https://github.com/Turbootzz/Nimbus)) `AGPL-3.0` `Docker`
- [Personal Management System](https://volmarg.github.io/) - 整理日常生活的各类要务，从简单的待办清单、笔记到付款和日程安排，一应俱全。 ([Demo](https://github.com/Volmarg/personal-management-system#documentation--demo), [Source Code](https://github.com/Volmarg/personal-management-system)) `MIT` `Docker`
- [portkey](https://portkey.page) - 简单的 Web 门户，可用作启动页，展示链接和网址的集合，同时允许添加自定义页面，全部通过单一配置文件管理。 ([Demo](https://demo.portkey.page), [Source Code](https://github.com/kodehat/portkey)) `AGPL-3.0` `Go/Docker`
- [ryot](https://github.com/ignisda/ryot) - 跟踪你生活的方方面面——媒体、健身等。 ([Demo](https://github.com/IgnisDa/ryot?tab=readme-ov-file#-demo)) `GPL-3.0` `Docker`
- [Starbase 80](https://github.com/notclickable-jordan/starbase-80) - 简单的主页，采用 iPad 风格的应用网格，适用于移动端和桌面端。仅需一个 JSON 配置文件。`MIT` `Docker`
- [Your Spotify](https://github.com/Yooooomi/your_spotify) `⚠` - Allows you to record your Spotify listening activity and have statistics about them served through a Web application. `MIT` `Nodejs/Docker`


### 照片库

**[`^        back to top        ^`](#awesome-selfhosted)**

A [gallery](https://en.wikipedia.org/wiki/Gallery_Software) is software that helps the user publish or share photos, pictures, videos or other digital media.

_Related: [Static Site Generators](#static-site-generators), [Media Streaming - Video Streaming](#media-streaming---video-streaming), [Content Management Systems (CMS)](#content-management-systems-cms)_

- [Chevereto](https://chevereto.com/) - 终极图片分享软件。几分钟即可创建你专属的个人图床网站。 ([Source Code](https://github.com/chevereto/chevereto)) `AGPL-3.0` `PHP/Docker`
- [ChronoFrame](https://chronoframe.bh8.ga/) - 个人相册应用，支持在线照片管理、Live/Motion Photos 和探索地图。 ([Demo](https://lens.bh8.ga/), [Source Code](https://github.com/HoshinoSuzumi/chronoframe)) `MIT` `Nodejs/Docker`
- [Damselfly](https://damselfly.info) - 面向大型图片集合的快速服务器端照片管理系统。包含人脸检测、人脸与物体识别、强大搜索以及 EXIF 关键词标记。可运行于 Linux、MacOS 和 Windows。 ([Source Code](https://github.com/webreaper/damselfly)) `GPL-3.0` `Docker/C#/.NET`
- [Ente](https://ente.com/) - 端到端加密的照片分享平台（Google Photos、Apple Photos 的替代品）。 ([Source Code](https://github.com/ente/ente)) `AGPL-3.0` `Docker/Nodejs/Go`
- [HomeGallery](https://home-gallery.org) - 浏览个人照片和视频，支持标签、移动端友好访问和 AI 驱动的图片发现。 ([Demo](https://demo.home-gallery.org), [Source Code](https://github.com/xemle/home-gallery)) `MIT` `Nodejs/Docker`
- [Immich Kiosk](https://github.com/damongolding/immich-kiosk) - 轻量级幻灯片应用，可在 kiosk 设备和浏览器上运行，使用 Immich 作为数据源。 ([Clients](https://github.com/immich-app/immich)) `GPL-3.0` `Docker/Go`
- [Immich](https://immich.app/) - 直接来自手机的照片和视频备份解决方案（Google Photos 的替代品）。 ([Demo](https://github.com/immich-app/immich#demo), [Source Code](https://github.com/immich-app/immich)) `AGPL-3.0` `Docker`
- [LibrePhotos](https://github.com/LibrePhotos/librephotos) - 照片管理服务，略侧重于酷炫的图表（Google Photos 的替代品）。 ([Clients](https://docs.librephotos.com/docs/user-guide/mobile/)) `MIT` `Python/Docker`
- [Lychee](https://lycheeorg.github.io/) - 基于网格和相册的照片管理系统。 ([Source Code](https://github.com/LycheeOrg/Lychee)) `MIT` `PHP/Docker`
- [Mediagoblin](https://mediagoblin.org) - 任何人都可以运行的媒体发布平台（Flickr、YouTube、SoundCloud 的替代品）。 ([Source Code](https://git.savannah.gnu.org/cgit/mediagoblin.git/tree/)) `AGPL-3.0` `Python`
- [Memtly](https://docs.memtly.com/) - 活动照片分享平台和相册，带幻灯片放映，宾客可通过二维码查看和分享回忆。 ([Demo](https://demo.memtly.com/), [Source Code](https://github.com/Memtly/Memtly.Community)) `GPL-3.0` `C#/Docker`
- [Nextcloud Memories](https://memories.gallery/) - 快速、现代且先进的照片管理套件，作为 Nextcloud 应用运行。 ([Demo](https://demo.memories.gallery/apps/memories/), [Source Code](https://github.com/pulsejet/memories)) `AGPL-3.0` `PHP`
- [Photofield](https://github.com/SmilyOrg/photofield) - 实验性的快速照片查看器。`MIT` `Docker/Go`
- [PhotoPrism](https://photoprism.org) - 由 Go 和 Google TensorFlow 驱动的个人照片管理。浏览、组织和分享你的个人照片集，运用最新技术自动标记和查找图片。 ([Demo](https://demo.photoprism.app/library/browse), [Source Code](https://github.com/photoprism/photoprism)) `AGPL-3.0` `Go/Docker`
- [Photoview](https://photoview.github.io/) - 面向个人服务器的简单易用的照片库。为摄影师打造，旨在提供简单快捷的目录浏览方式，轻松应对数千张高分辨率照片。 ([Demo](https://photoview.github.io/), [Source Code](https://github.com/photoview/photoview)) `GPL-3.0` `Go/Docker`
- [PiGallery 2](https://bpatrik.github.io/pigallery2/) - 目录优先的照片库网站，界面丰富，针对低资源服务器优化运行。 ([Source Code](https://github.com/bpatrik/pigallery2)) `MIT` `Docker/Nodejs`
- [Piwigo](https://piwigo.org/) - 面向 Web 的照片库软件，由活跃的用户和开发者社区打造。 ([Source Code](https://github.com/Piwigo/Piwigo)) `GPL-2.0` `PHP`
- [SPIS](https://github.com/gbbirkisson/spis) - 简单、轻量、快速的媒体服务器，具备不错的移动端支持。`GPL-3.0` `Docker/Rust`
- [This week in past](https://github.com/RouHim/this-week-in-past) - 汇总往年同一周拍摄的照片，并通过简单的幻灯片呈现在网页上。`MIT` `Docker/Rust`
- [Thumbor](http://thumbor.org/) - 智能图像服务，支持按需裁剪、缩放、应用滤镜和优化图片。 ([Source Code](https://github.com/thumbor/thumbor)) `MIT` `Python/Docker`
- [Zenphoto](https://www.zenphoto.org/) - 相册与 CMS 项目。 ([Source Code](https://github.com/zenphoto/zenphoto)) `GPL-2.0` `PHP`


### 投票与活动

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for organising [polls](https://en.wikipedia.org/wiki/Opinion_poll) and [events](https://en.wikipedia.org/wiki/Event).

_Related: [Booking and Scheduling](#booking-and-scheduling)_

- [Bitpoll](https://github.com/fsinfuhh/Bitpoll) - 就日期、时间或一般问题发起投票。 ([Demo](https://bitpoll.de/)) `GPL-3.0` `Docker/Python`
- [Bracket](https://docs.bracketapp.nl/) - 灵活的锦标赛系统，可用于搭建赛事、添加队伍、安排比赛、记录比分，并向公众实时展示排名。 ([Demo](https://www.bracketapp.nl/demo), [Source Code](https://github.com/evroon/bracket)) `AGPL-3.0` `Docker/Nodejs`
- [Christmas Community](https://github.com/Wingysam/Christmas-Community) - 为全家创建一个简单的空间，用来查找大家想要的礼物并避免重复送礼。`AGPL-3.0` `Docker/Nodejs`
- [Claper](https://claper.co/) - 为你的幻灯片添加问答、投票、测验、表单、实时字幕和互动反应（Slido、AhaSlides 和 Mentimeter 的替代品）。 ([Source Code](https://github.com/ClaperCo/Claper)) `GPL-3.0` `Elixir/Docker`
- [ClearFlask](https://clearflask.com) - 社区反馈工具，用于管理收到的反馈并为公开路线图排定优先级（Canny、UserVoice、Upvoty 的替代品）。 ([Demo](https://product.clearflask.com), [Source Code](https://github.com/clearflask/clearflask)) `AGPL-3.0` `Docker`
- [docassemble](https://docassemble.org/) - 基于 Python、YAML 和 Markdown 的引导式访谈与文档组装系统。 ([Demo](https://demo.docassemble.org/run/legal), [Source Code](https://github.com/jhpyle/docassemble)) `MIT` `Docker/Python`
- [EventSchedule](https://eventschedule.com/) - 分享活动、销售门票，让社区凝聚起来。 ([Source Code](https://github.com/eventschedule/eventschedule)) `AAL` `PHP/Docker`
- [Fider](https://fider.io) - 收集反馈并为反馈排定优先级的开放平台（UserVoice 的替代品）。 ([Demo](https://demo.fider.io), [Source Code](https://github.com/getfider/fider)) `MIT` `Docker`
- [Formbricks](https://formbricks.com) - 构建于全球最大调查技术栈之上的体验管理套件。在客户旅程的每一步优雅地收集反馈，了解你的客户需要什么。 ([Demo](https://app.formbricks.com), [Source Code](https://github.com/formbricks/formbricks)) `AGPL-3.0` `Nodejs/Docker`
- [Framadate](https://framadate.org/abc/) - 用于快速轻松地安排约会或做出决策的在线服务：发起投票、定义可供选择的日期或主题、把投票链接发送给你的朋友或同事、讨论并做出决策。 ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://framagit.org/framasoft/framadate?)) `CECILL-B` `PHP`
- [Gancio](https://gancio.org/) - 本地社区活动与日程分享。 ([Demo](https://demo.gancio.org/), [Source Code](https://framagit.org/les/gancio)) `AGPL-3.0` `Nodejs`
- [gathio](https://docs.gath.io/) - 可自毁、可分享、无需注册的活动页面。 ([Demo](https://gath.io/), [Source Code](https://github.com/lowercasename/gathio)) `GPL-3.0` `Nodejs/Docker`
- [HeyForm](https://heyform.net) - 表单构建器，让任何人都能创建用于调查、问卷、测验和投票的引人入胜的对话式表单。 ([Source Code](https://github.com/heyform/heyform)) `AGPL-3.0` `Docker`
- [hitobito](https://hitobito.com) - 管理复杂的群组层级，涵盖成员、活动以及更多内容。 ([Demo](https://demo.hitobito.com/en/users/sign_in), [Source Code](https://github.com/hitobito/hitobito)) `AGPL-3.0` `Ruby`
- [LimeSurvey](https://www.limesurvey.org) - 功能丰富的基于 Web 的投票软件，支持广泛的问卷逻辑。 ([Demo](https://demo.limesurvey.org), [Source Code](https://github.com/LimeSurvey/LimeSurvey)) `GPL-2.0` `PHP`
- [Meetable](https://events.indieweb.org) - 极简的活动聚合器。 ([Source Code](https://github.com/aaronpk/Meetable)) `MIT` `PHP`
- [Mobilizon](https://mobilizon.org) - 联邦化工具，帮助你查找、创建和组织活动与群组。 ([Source Code](https://framagit.org/framasoft/mobilizon/)) `AGPL-3.0` `Elixir/Docker`
- [OpnForm](https://opnform.com) - 美观的表单构建器。 ([Demo](https://opnform.com/forms/create/guest), [Source Code](https://github.com/OpnForm/OpnForm)) `AGPL-3.0` `PHP/Nodejs/Docker`
- [Revel](https://www.letsrevel.io) `⚠` - Community-focused event management and ticketing platform. ([Demo](https://demo.letsrevel.io), [Source Code](https://github.com/letsrevel/revel-backend), [Clients](https://github.com/letsrevel)) `MIT` `Python/Docker`


### 代理

**[`^        back to top        ^`](#awesome-selfhosted)**

A [proxy](https://en.wikipedia.org/wiki/Proxy_server) is a server application that acts as an intermediary between a client requesting a resource and the server providing that resource. This section about forward (i.e. outgoing) proxies. For reverse proxies, see the Web Server section.

_Related: [Web Servers](#web-servers)_

- [g3proxy](https://g3-project.readthedocs.io/projects/g3proxy/en/latest/) - 正向代理服务器，支持代理链、协议检查、MITM 拦截、ICAP 适配和透明代理。 ([Source Code](https://github.com/bytedance/g3/tree/master/g3proxy)) `Apache-2.0` `Rust/deb`
- [GitProxy](https://git-proxy.finos.org/) - Git 代理，对所有外发的 git push 操作应用规则和工作流并确保其合规。支持 HTTP/HTTPS 和 SSH 协议，具备安全扫描与校验功能。 ([Source Code](https://github.com/finos/git-proxy)) `Apache-2.0` `Nodejs/Docker`
- [imagor](https://github.com/cshum/imagor) - 基于 libvips 构建的快速、安全的图像处理服务器和 Go 库，支持按需缩放、裁剪、滤镜、格式转换和图像合成，具备签名 URL 和面向高并发吞吐的流式管道。`Apache-2.0` `Docker`
- [imgproxy](https://imgproxy.net/) - 快速且安全的独立服务器，用于缩放和转换远程图片。 ([Source Code](https://github.com/imgproxy/imgproxy)) `MIT` `Go/Docker/K8S`
- [Outline Server](https://getoutline.org/) - 代理服务器，为每个访问密钥运行一个 Shadowsocks 实例，并提供用于管理访问密钥的 REST API。 ([Source Code](https://github.com/OutlineFoundation/outline-server)) `Apache-2.0` `Docker/Nodejs`
- [Privoxy](https://www.privoxy.org) - 无缓存的 Web 代理，具备高级过滤能力，可用于增强隐私、修改网页数据和 HTTP 头、控制访问，以及去除广告和其他恼人的网络垃圾。`GPL-2.0` `C/deb`
- [sish](https://github.com/antoniomika/sish) - 仅使用 SSH 的 HTTP(S)/WS(S)/TCP localhost 隧道（serveo/ngrok 的替代品）。`MIT` `Go/Docker`
- [socks5-proxy-server](https://github.com/nskondratev/socks5-proxy-server) - 内置认证功能的 SOCKS5 代理服务器，配有用于用户管理和按流量用量统计用户数据的 Telegram 机器人（按 GB 流量付费时很实用）。已容器化且易于安装。`Apache-2.0` `Docker`
- [Squid](http://www.squid-cache.org/) - 支持 HTTP、HTTPS、FTP 等协议的 Web 缓存代理。通过缓存和复用频繁请求的网页来降低带宽消耗并缩短响应时间。 ([Source Code](https://code.launchpad.net/squid)) `GPL-2.0` `C/deb`
- [Tinyproxy](https://tinyproxy.github.io/) - 轻量级 HTTP/HTTPS 代理守护进程。 ([Source Code](https://github.com/tinyproxy/tinyproxy)) `GPL-2.0` `C/deb`


### 食谱管理

**[`^        back to top        ^`](#awesome-selfhosted)**

Software and tools for managing [recipes](https://en.wikipedia.org/wiki/Recipe).

- [Bar Assistant](https://barassistant.app/) - 管理你的家庭酒吧：添加原料、搜索鸡尾酒并创建自定义鸡尾酒配方。 ([Demo](https://demo.barassistant.app/), [Source Code](https://github.com/karlomikus/bar-assistant)) `MIT` `PHP/Docker`
- [CookCLI](https://cooklang.org) - 命令行工具，使用 Cooklang 食谱实现膳食计划和购物自动化，可脚本化融入 UNIX 工作流，并包含 Web 服务器。 ([Source Code](https://github.com/cooklang/CookCLI)) `MIT` `Rust`
- [Fork Recipes](https://mikebgrep.github.io/forkapi/latest/clients/) - 简单地管理你的美食食谱。 ([Source Code](https://github.com/mikebgrep/fork.recipes)) `BSD-3-Clause` `Docker`
- [ManageMeals](https://managemeals.com/) - 管理食谱、通过 URL 导入食谱并进行整理，没有任何广告或多余文字。 ([Source Code](https://github.com/managemeals/manage-meals-web)) `GPL-3.0` `Docker`
- [Mealie](https://nightly.mealie.io/) - 受 Material Design 启发的食谱管理器，具备分类和标签管理、购物清单、膳食计划器和站点自定义功能。Mealie 专注于简单的用户交互，让全家都愿意使用这款应用。 ([Demo](https://demo.mealie.io), [Source Code](https://github.com/mealie-recipes/mealie)) `MIT` `Python`
- [RecipeSage](https://github.com/julianpoy/recipesage) - 食谱收藏、膳食计划组织和购物清单管理工具，可直接从任意 URL 导入食谱。 ([Demo](https://recipesage.com)) `AGPL-3.0` `Nodejs`
- [Recipya](https://recipes.musicavis.ca) - 干净、简单而强大的食谱管理器，全家都会喜欢。 ([Demo](https://recipes.musicavis.ca/guide/login), [Source Code](https://github.com/reaper47/recipya)) `GPL-3.0` `Docker/Go`
- [Tamari](https://tamariapp.com) - 食谱管理 Web 应用，内置食谱合集。可按收藏和分类进行整理、创建购物清单并规划膳食。 ([Demo](https://app.tamariapp.com), [Source Code](https://github.com/alexbates/Tamari)) `GPL-3.0` `Docker/Python`
- [Vanilla Cookbook](https://vanilla-cookbook.readthedocs.io/en/) - 食谱管理器，将复杂性藏在底层，让用户体验尽可能简洁纯粹。 ([Source Code](https://github.com/jt196/vanilla-cookbook)) `GPL-3.0` `Docker/Nodejs`
- [What To Cook?](https://github.com/kassner/whattocook) - 根据你家里现有的食材，获取今天可以烹饪的食谱。`AGPL-3.0` `Docker`


### 远程访问

**[`^        back to top        ^`](#awesome-selfhosted)**

[Remote desktop](https://en.wikipedia.org/wiki/Remote_desktop_software) and [SSH](https://en.wikipedia.org/wiki/Secure_Shell) servers and web interfaces for remote management of computer systems.

- [Cardea](https://github.com/hectorm/cardea) - SSH 堡垒服务器，具备访问控制、会话录制和可选的 TPM 密钥保护。`EUPL-1.2` `Go/Docker`
- [Engity's Bifröst](https://bifroest.engity.org/) - 高度可定制的 SSH 服务器，提供多种用户授权方式，并可选择用户会话的执行位置和方式。 ([Source Code](https://github.com/engity-com/bifroest)) `Apache-2.0` `Go/Docker`
- [Firezone](https://www.firezone.dev/) - 支持 WireGuard 协议的安全远程访问网关。提供 Web 图形界面、一行式安装脚本、多因素认证（MFA）和 SSO。 ([Source Code](https://github.com/firezone/firezone)) `Apache-2.0` `Elixir/Docker`
- [Guacamole](https://guacamole.apache.org) - 无客户端的远程桌面网关，支持 VNC 和 RDP 等标准协议。 ([Source Code](https://github.com/apache/guacamole-server)) `Apache-2.0` `Java/C`
- [MeshCentral](https://meshcentral.com/) - 运行你自己的 Web 服务器，远程管理和控制局域网或互联网上任意位置的计算机。 ([Source Code](https://github.com/Ylianst/MeshCentral)) `Apache-2.0` `Nodejs`
- [ShellHub](https://www.shellhub.io) - 现代 SSH 服务器，可通过命令行（使用任意 SSH 客户端）或基于 Web 的用户界面远程访问 Linux 设备（sshd 的替代品）。 ([Source Code](https://github.com/shellhub-io/shellhub)) `Apache-2.0` `Docker`
- [Sshwifty](https://github.com/nirui/sshwifty) - 为 Web 打造的 SSH 和 Telnet 连接器。 ([Demo](https://sshwifty-demo.nirui.org)) `AGPL-3.0` `Go/Docker`
- [Termix](https://docs.termix.site/) - 无客户端的基于 Web 的服务器管理平台，具备 SSH 终端、隧道和文件编辑功能。 ([Source Code](https://github.com/Termix-SSH/Termix)) `Apache-2.0` `Docker`
- [Warpgate](https://github.com/warp-tech/warpgate) - 完全透明的 SSH、HTTPS、Kubernetes、MySQL 和 Postgres 堡垒/PAM，无需额外的客户端软件。`Apache-2.0` `Rust/Docker`


### 资源规划

**[`^        back to top        ^`](#awesome-selfhosted)**

Software and tools to help with [resource and supply planning](https://en.wikipedia.org/wiki/Resource_planning), including [enterprise resource and supply planning (ERP)](https://en.wikipedia.org/wiki/Enterprise_resource_planning).

_Related: [Money, Budgeting & Management](#money-budgeting--management), [Inventory Management](#inventory-management)_

- [Dolibarr](https://www.dolibarr.org/) - 现代 CRM 软件包，用于管理你的公司或基金会的业务（联系人、供应商、发票、订单、库存、日程、会计等）。 ([Demo](https://www.dolibarr.org/onlinedemo.php), [Source Code](https://github.com/Dolibarr/dolibarr)) `GPL-3.0` `PHP/deb`
- [ERPNext](https://frappe.io/erpnext) - 帮助你运营业务的 ERP 系统。 ([Source Code](https://github.com/frappe/erpnext)) `GPL-3.0` `Python/Docker`
- [farmOS](https://farmos.org/) - 基于 Web 的农场记录应用。 ([Demo](https://farmos-demo.rootedsolutions.io/), [Source Code](https://github.com/farmOS/farmOS)) `GPL-2.0` `PHP/Docker`
- [grocy](https://grocy.info/) - 冰箱之外的 ERP。面向家庭的食品杂货与家居用品管理解决方案。 ([Demo](https://en.demo.grocy.info/), [Source Code](https://github.com/grocy/grocy)) `MIT` `PHP/Docker`
- [LedgerSMB](https://ledgersmb.org/) - 面向中小型企业的集成会计与 ERP 系统，具备复式记账、预算、开票、报价、项目、订单和库存管理、发货等更多功能。 ([Source Code](https://github.com/ledgersmb/LedgerSMB)) `GPL-2.0` `Docker/Perl`
- [Odoo](https://www.odoo.com) - 面向 ERP 的基于 Web 的商业应用套件。 ([Demo](https://demo.odoo.com/), [Source Code](https://github.com/odoo/odoo)) `LGPL-3.0` `Python/deb/Docker`
- [OFBiz](https://ofbiz.apache.org/) - 企业资源规划（ERP）系统，其商业应用套件足够灵活，可适用于任何行业。 ([Source Code](https://github.com/apache/ofbiz-framework)) `Apache-2.0` `Java`
- [Tryton](https://www.tryton.org/) - 商业解决方案。 ([Demo](https://www.tryton.org/demo), [Source Code](https://foss.heptapod.net/tryton/tryton)) `GPL-3.0` `Python`


### 搜索引擎

**[`^        back to top        ^`](#awesome-selfhosted)**

A [search engine](https://en.wikipedia.org/wiki/Search_engine_(computing)) is an [information retrieval system](https://en.wikipedia.org/wiki/Information_retrieval) designed to help find information stored on a computer system. This includes [Web search engines](https://en.wikipedia.org/wiki/Web_search_engine).

- [Aleph](https://aleph.occrp.org/) - 用于索引海量文档（PDF、Word、HTML）和结构化数据（CSV、XLS、SQL）的工具，便于浏览和搜索。以调查报道作为主要用例构建。 ([Demo](https://aleph.occrp.org/), [Source Code](https://github.com/alephdata/aleph)) `MIT` `Docker/K8S`
- [Amgix](https://amgix.io) - 为灵活部署和真实世界杂乱数据而构建的混合搜索引擎。 ([Demo](https://findgovdata.org), [Source Code](https://github.com/amgix/amgix-server), [Clients](https://github.com/orgs/amgix/repositories)) `AGPL-3.0` `Docker/K8S`
- [Apache Solr](https://lucene.apache.org/solr/) - 企业搜索平台，具备全文搜索、命中高亮、分面搜索、实时索引、动态聚类以及富文档（如 Word、PDF）处理等功能。 ([Source Code](https://github.com/apache/solr)) `Apache-2.0` `Java/Docker/K8S`
- [Fess](https://fess.codelibs.org/) - 功能强大且易于部署的企业搜索服务器。 ([Demo](https://search.n2sm.co.jp/), [Source Code](https://github.com/codelibs/fess)) `Apache-2.0` `Java/Docker`
- [Hister](https://hister.org/) - 个人 Web 搜索引擎，自动索引访问过的网站。支持离线本地结果预览、本地文件、多用户处理以及可选的语义搜索。 ([Demo](https://demo.hister.org/), [Source Code](https://github.com/asciimoo/hister)) `AGPL-3.0` `Go/Docker`
- [Manticore Search](https://github.com/manticoresoftware/manticoresearch/) - 全文搜索和数据分析，对小型、中型和大数据均能快速响应（Elasticsearch 的替代品）。`GPL-3.0` `Docker/deb/C++/K8S`
- [MeiliSearch](https://www.meilisearch.com) - 超高相关性、即时且容错的全文搜索 API。 ([Source Code](https://github.com/meilisearch/MeiliSearch)) `MIT` `Rust/Docker/deb`
- [Meme Search](https://github.com/neonwatty/meme-search) - AI 驱动的表情包搜索引擎。使用视觉语言模型自动从图片中提取描述，再通过向量嵌入建立索引，支持语义搜索和关键词搜索。 ([Source Code](https://github.com/meme-search/meme-search)) `Apache-2.0` `Docker`
- [OpenSearch](https://opensearch.org) - 分布式的 RESTful 搜索引擎。 ([Source Code](https://github.com/opensearch-project/OpenSearch)) `Apache-2.0` `Java/Docker/K8S/deb`
- [SearXNG](https://docs.searxng.org/) `⚠` - Internet metasearch engine which aggregates results from various search services and databases (fork of Searx). ([Source Code](https://github.com/searxng/searxng/)) `AGPL-3.0` `Python/Docker`
- [Sosse](https://sosse.readthedocs.io/en/stable/) - 基于 Selenium 的搜索引擎和爬虫，支持离线归档。 ([Source Code](https://gitlab.com/biolds1/sosse)) `AGPL-3.0` `Python/Docker`
- [Typesense](https://typesense.org) - 极速、容错的搜索引擎，为开发者体验和易用性而优化。 ([Source Code](https://github.com/typesense/typesense)) `GPL-3.0` `C++/Docker/K8S/deb`
- [Websurfx](https://github.com/neon-mmd/websurfx) `⚠` - Aggregate results from other search engines (metasearch engine) without ads while keeping privacy and security in mind. It is extremely fast and provides a high level of customization (alternative to SearX). `AGPL-3.0` `Rust/Docker`
- [Yacy](https://yacy.net/en/index.html) - 基于 P2P 的去中心化搜索引擎服务器。 ([Source Code](https://github.com/yacy/yacy_search_server)) `GPL-2.0` `Java/Docker/K8S`


### 自托管解决方案

**[`^        back to top        ^`](#awesome-selfhosted)**

Software for easy installation, management and configuration of self-hosted services and applications.

- [DietPi](https://dietpi.com/) - 针对单板计算机优化的极简 Debian 操作系统，让你轻松安装和管理多项家庭自托管服务。 ([Source Code](https://github.com/MichaIng/DietPi)) `GPL-2.0` `Shell`
- [DockSTARTer](https://dockstarter.com/) - DockSTARTer 帮助你快速上手运行在 Docker 中的家庭服务器应用。 ([Source Code](https://github.com/GhostWriters/DockSTARTer)) `MIT` `Shell`
- [Dropserver](https://dropserver.org) - 面向个人 Web 服务的应用平台。 ([Source Code](https://github.com/teleclimber/Dropserver/)) `Apache-2.0` `Go/Deno`
- [FreedomBox](https://freedombox.org/) - 社区项目，致力于开发、设计和推广运行自由软件的个人服务器，用于私密和个人通信。 ([Source Code](https://salsa.debian.org/freedombox-team/freedombox)) `AGPL-3.0` `Python/deb`
- [HomeButler](https://homebutler.dev) - 通过 Docker Compose 安装并管理精选应用目录，映射容器与已暴露端口，验证备份可恢复，并通过 CLI、JSON、Web 和 MCP 接口报告自上次运行以来的变更。 ([Source Code](https://github.com/Higangssh/homebutler)) `MIT` `Docker/Go`
- [HomelabOS](https://homelabos.com) - 离线、以隐私为中心的数据中心。只需几条命令即可部署 100 多个服务。 ([Source Code](https://gitlab.com/NickBusey/HomelabOS)) `MIT` `Docker`
- [HomeServerHQ](https://www.homeserverhq.com/) - 一体化家庭服务器基础设施与安装器。即使处于 CGNAT 之后，也能在一小时内完成全配置的电子邮件服务器、VPN 和公开网站的搭建。 ([Source Code](https://github.com/homeserverhq/hshq)) `GPL-3.0` `Shell`
- [LibreServer](https://libreserver.org/) - 基于 Debian 的家庭服务器配置。 ([Source Code](https://github.com/bashrc2/libreserver)) `AGPL-3.0` `Shell`
- [Mother-of-All-Self-Hosting](https://github.com/mother-of-all-self-hosting/mash-playbook) - 帮助你在自己的服务器上以 Docker 容器形式托管服务的 Ansible playbook。
- [NextCloudPi](https://github.com/nextcloud/nextcloudpi) - 预装并预配置好的 Nextcloud，提供文本和 Web 管理界面以及自托管私有数据所需的全部工具。提供适用于 Raspberry Pi、Odroid、Rock64、Docker 的安装镜像，以及适用于 Armbian/Debian 的 curl 安装器。
- [Nirvati](https://nirvati.org) - 通过便捷的 Web 界面一键轻松启动热门应用。 ([Source Code](https://gitlab.com/nirvati-ug/nirvati/backend)) `AGPL-3.0` `Rust/K8S`
- [OpenMediaVault](https://www.openmediavault.org/) - 基于 Debian Linux 的网络附加存储（NAS）解决方案。包含 SSH、(S)FTP、SMB/CIFS、DAAP 媒体服务器、RSync、BitTorrent 客户端等诸多服务。 ([Source Code](https://github.com/openmediavault/openmediavault)) `GPL-3.0` `PHP`
- [Sandstorm](https://sandstorm.io/) - 用于在自己硬件上轻松安全地运行应用的个人服务器。 ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache-2.0` `C++/Shell`
- [Self Host Blocks](https://github.com/ibizaman/selfhostblocks) `⚠` - Modular server management based on NixOS modules and focused on best practices. `AGPL-3.0` `Nix`
- [StartOS](https://start9.com) - 基于浏览器的图形化操作系统（OS），让运行个人服务器像使用个人电脑一样简单。 ([Source Code](https://github.com/Start9Labs/start-technologies)) `MIT` `Rust`
- [Syncloud](https://syncloud.org/) - 带应用商店和自动更新功能的操作系统，支持 Nextcloud、Jellyfin、Bitwarden 和 Paperless 等应用，并提供 HTTPS、域名以及无需公网 IP 的远程访问。 ([Source Code](https://github.com/syncloud/platform)) `GPL-3.0` `Go/Shell`
- [Tipi](https://runtipi.io/) - 家庭服务器管理器。一条命令完成安装，一键部署你喜爱的家庭服务器应用。 ([Source Code](https://github.com/runtipi/runtipi)) `GPL-3.0` `Shell`
- [UBOS](https://ubos.net/) - 运行于独立设备（个人服务器和物联网设备）的 Linux 发行版。支持以单条命令安装和管理 Jenkins、Mediawiki、Owncloud、WordPress 等应用及其他功能。
- [Websoft9](https://www.websoft9.com) `⚠` - GitOps-driven, multi-application hosting for cloud servers and home servers, one-click deployment of 200+ apps. ([Demo](https://www.websoft9.com/demo), [Source Code](https://github.com/websoft9/websoft9), [Clients](https://www.websoft9.com/apps)) `LGPL-3.0` `Shell/Python`
- [WikiSuite](https://wikisuite.org) - 最全面且高度集成的自由/开源企业软件套件。 ([Source Code](https://wikisuite.org/Source-Code)) `GPL-3.0/LGPL-2.1/Apache-2.0/MPL-2.0/MPL-1.1/MIT/AGPL-3.0` `Shell/Perl/deb`
- [xsrv](https://xsrv.readthedocs.io/) - 在自己的服务器上安装和管理服务/应用。 ([Source Code](https://github.com/nodiscc/xsrv)) `GPL-3.0` `Ansible/Shell`
- [YunoHost](https://yunohost.org/) - 旨在让每个人都能轻松自托管的服务器操作系统。 ([Demo](https://yunohost.org/#/try), [Source Code](https://github.com/YunoHost)) `AGPL-3.0` `Python/Shell`


### Software Development

**[`^        back to top        ^`](#awesome-selfhosted)**

[Software development](https://en.wikipedia.org/wiki/Software_development) is the process of conceiving, specifying, designing, programming, documenting, testing, and bug fixing involved in creating and maintaining applications, frameworks, or other software components.

**Please visit [Software Development - API Management](#software-development---api-management), [Software Development - Continuous Integration & Deployment](#software-development---continuous-integration--deployment), [Software Development - FaaS & Serverless](#software-development---faas--serverless), [Software Development - IDE & Tools](#software-development---ide--tools), [Software Development - Localization](#software-development---localization), [Software Development - Low Code](#software-development---low-code), [Software Development - Project Management](#software-development---project-management), [Software Development - Testing](#software-development---testing), [Software Development - Feature Toggle](#software-development---feature-toggle)**



### 软件开发 - API 管理

**[`^        back to top        ^`](#awesome-selfhosted)**

[API management](https://en.wikipedia.org/wiki/API_management) is the process of creating and publishing [application programming interfaces (APIs)](https://en.wikipedia.org/wiki/API), enforcing their usage policies, controlling access, nurturing the subscriber community, collecting and analyzing usage statistics, and reporting on performance. 

- [Aastro](https://voidrunner3074.github.io/aastro-docs) - 用 Go 编写的可扩展 API 网关。 ([Source Code](https://github.com/voidrunner3074/aastro)) `Apache-2.0` `Go/Docker`
- [DreamFactory](https://www.dreamfactory.com/) - 将任何 SQL/NoSQL/结构化数据转换为 RESTful API。 ([Source Code](https://github.com/dreamfactorysoftware/dreamfactory)) `Apache-2.0` `PHP/Docker/K8S`
- [Fusio](https://www.fusio-project.org/) - 帮助构建和管理 REST API 的 API 管理平台。 ([Demo](https://fusio-project.org/demo), [Source Code](https://github.com/apioo/fusio)) `AGPL-3.0` `PHP/Docker`
- [Graphweaver](https://graphweaver.com/) - 将多个数据源整合为单一 GraphQL API。 ([Source Code](https://github.com/exogee-technology/graphweaver)) `MIT` `Nodejs`
- [Hasura](https://hasura.io) - 在 Postgres 上提供快速、即时的实时 GraphQL API，支持细粒度访问控制，还可基于数据库事件触发 webhook。 ([Source Code](https://github.com/hasura/graphql-engine)) `Apache-2.0` `Haskell/Docker/K8S`
- [Hoppscotch Community Edition](https://hoppscotch.io) - 快速美观的 API 请求构建工具。 ([Source Code](https://github.com/hoppscotch/hoppscotch)) `MIT` `Nodejs/Docker`
- [Kong](https://konghq.com/kong/) - 微服务 API 网关与平台。 ([Source Code](https://github.com/Kong/kong)) `Apache-2.0` `Lua/Docker/K8S/deb`
- [Lura](https://luraproject.org/) - 高性能 API 网关。 ([Source Code](https://github.com/luraproject/lura)) `Apache-2.0` `Go`
- [Opik](https://www.comet.com/site/products/opik/) `⚠` - Evaluate, test, and ship LLM applications with a suite of observability tools to calibrate language model outputs across your dev and production lifecycle. ([Source Code](https://github.com/comet-ml/opik)) `Apache-2.0` `Docker/Python`
- [Para](https://paraio.org) - 用于对象持久化、API 开发和身份验证的灵活模块化后端框架/服务器。 ([Source Code](https://github.com/erudika/para)) `Apache-2.0` `Java/Docker`
- [Svix](https://svix.com) - webhook 即服务，让 API 提供方发送 webhook 变得超级简单。 ([Source Code](https://github.com/svix/svix-webhooks)) `MIT` `Docker/Rust`
- [Tyk](https://tyk.io) - 快速、可扩展的 API 网关。开箱即用，Tyk 提供 API 管理平台，包括 API 网关、API 分析、开发者门户和 API 管理仪表盘。 ([Source Code](https://github.com/TykTechnologies/tyk)) `MPL-2.0` `Go/Docker/K8S`


### Software Development - Continuous Integration & Deployment

**[`^        back to top        ^`](#awesome-selfhosted)**

[Continuous integration](https://en.wikipedia.org/wiki/Continuous_integration) and [Continuous deployment](https://en.wikipedia.org/wiki/Continuous_deployment) software and tools.

**Please visit [awesome-sysadmin/Continuous Integration & Continuous Deployment](https://github.com/awesome-foss/awesome-sysadmin#continuous-integration--continuous-deployment)**

_Related: [Automation](#automation)_



### Software Development - FaaS & Serverless

**[`^        back to top        ^`](#awesome-selfhosted)**

[Serverless computing](https://en.wikipedia.org/wiki/Serverless_computing), [Function as a Service (FaaS)](https://en.wikipedia.org/wiki/Function_as_a_service) and [Platform as a Service (Paas)](https://en.wikipedia.org/wiki/Platform_as_a_service) management software.

**Please visit [awesome-sysadmin/PaaS](https://github.com/awesome-foss/awesome-sysadmin#paas)**



### 软件开发 - 功能开关

**[`^        back to top        ^`](#awesome-selfhosted)**

A [feature toggle](https://en.wikipedia.org/wiki/Feature_toggle) in software development provides an alternative to maintaining multiple feature branches in source code.

_Related: [Software Development - IDE & Tools](#software-development---ide--tools)_

- [Featbit](https://www.featbit.co/) - 可自托管的企业级特性开关平台。 ([Source Code](https://github.com/featbit/featbit)) `MIT` `Docker/K8S`
- [Flagsmith](https://flagsmith.com) - 用于为应用添加特性开关的仪表盘、API 和 SDK（LaunchDarkly 的替代品）。 ([Source Code](https://github.com/flagsmith/flagsmith)) `BSD-3-Clause` `Docker/K8S`
- [Flipt](https://flipt.io) - 支持多种数据后端的特性开关解决方案（LaunchDarkly 的替代品）。 ([Source Code](https://github.com/flipt-io/flipt)) `GPL-3.0` `Docker/K8S/Go`
- [GO Feature Flag](https://gofeatureflag.org) - 简单、完整且轻量的特性开关解决方案（LaunchDarkly 的替代品）。 ([Source Code](https://github.com/thomaspoignant/go-feature-flag)) `MIT` `Go`
- [Nona](https://nonaconfig.com) - 通过单一 REST API 提供远程配置和特性开关的服务，支持多环境，并提供官方 JavaScript 和 .NET 客户端（Firebase Remote Config 的替代品）。 ([Source Code](https://github.com/Ryware/nona-config)) `Apache-2.0` `Docker`


### 软件开发 - IDE 与工具

**[`^        back to top        ^`](#awesome-selfhosted)**

An [integrated development environment (IDE)](https://en.wikipedia.org/wiki/Integrated_development_environment) is a software application that provides comprehensive facilities to computer programmers for software development.

_Related: [Software Development - Low Code](#software-development---low-code)_

- [Atheos](https://www.atheos.io) - 轻量小巧、要求极低的基于 Web 的 IDE 框架，由 Codiad 延续而来。 ([Source Code](https://github.com/Atheos/Atheos)) `MIT` `PHP/Docker`
- [code-server](https://github.com/coder/code-server) - 运行在浏览器中的 VS Code，托管于远程服务器。
- [Coder](https://coder.com/) - 在你自己的基础设施上运行的远程开发机。 ([Source Code](https://github.com/coder/coder)) `AGPL-3.0` `Go/Docker/K8S/deb`
- [Eclipse Che](https://www.eclipse.org/che/) - 工作区服务器和云端 IDE。 ([Source Code](https://github.com/eclipse-che/che)) `EPL-1.0` `Docker/Java`
- [Hopp](https://gethopp.app) - 远程结对编程应用，具有低延迟 4K 屏幕共享、绘图和远程控制功能，提供 macOS 和 Windows 客户端（Tuple、Pop、Drovio 的替代品）。 ([Source Code](https://github.com/gethopp/hopp)) `AGPL-3.0` `Docker`
- [Judge0 CE](https://judge0.com) - 用于编译和运行源代码的 API。 ([Source Code](https://github.com/judge0/judge0)) `GPL-3.0` `Docker`
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - 用于交互式和可复现计算的基于 Web 的环境。 ([Demo](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/try.jupyter.org?urlpath=lab), [Source Code](https://github.com/jupyterlab/jupyterlab/)) `BSD-3-Clause` `Python/Docker`
- [Langfuse](https://langfuse.com) - 用于模型追踪、提示词管理和应用评估的 LLM 工程平台。Langfuse 帮助团队协作调试、分析并迭代其聊天机器人或 AI 智能体等 LLM 应用。 ([Demo](https://langfuse.com/docs/demo), [Source Code](https://github.com/langfuse/langfuse), [Clients](https://langfuse.com/docs/integrations/overview)) `MIT` `Docker`
- [LiveCodes](https://livecodes.io/docs/features/self-hosting) `⚠` - Feature-rich client-side code playground for React, Vue, Svelte, Solid, Typescript, Python, Go, Ruby, PHP and 90+ other languages. ([Demo](https://livecodes.io), [Source Code](https://github.com/live-codes/livecodes)) `MIT` `Nodejs`
- [Lowdefy](https://www.lowdefy.com/) - 使用 YAML/JSON 在几分钟内构建内部工具、BI 仪表盘、管理面板、CRUD 应用和工作流。 ([Source Code](https://github.com/lowdefy/lowdefy)) `Apache-2.0` `Nodejs/Docker`
- [RapidForge](https://rapidforge.io/) - 用于构建 webhook、定时任务和页面的轻量平台。使用 Bash 或 Lua 实现你的逻辑。 ([Source Code](https://github.com/rapidforge-io/rapidforge)) `Apache-2.0` `Go/Nodejs`
- [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - 基于 Web 浏览器的 R 语言 IDE。 ([Source Code](https://github.com/rstudio/rstudio)) `AGPL-3.0` `Java/C++`


### 软件开发 - 本地化

**[`^        back to top        ^`](#awesome-selfhosted)**

[Localization](https://en.wikipedia.org/wiki/Internationalization_and_localization) is the process of adapting code and software to other languages.

- [Accent](https://www.accent.reviews/) - 面向开发者的翻译工具。 ([Source Code](https://github.com/mirego/accent)) `BSD-3-Clause` `Elixir/Docker`
- [Tolgee](https://tolgee.io) - 对开发者和译者友好的基于 Web 的本地化平台，让用户可以直接在所开发的应用中进行翻译。 ([Source Code](https://github.com/tolgee/tolgee-platform)) `Apache-2.0` `Docker/Java`
- [Traduora](https://traduora.co) - 面向团队的翻译管理平台。 ([Source Code](https://github.com/ever-co/ever-traduora)) `AGPL-3.0` `Docker/K8S/Nodejs`
- [Weblate](https://weblate.org) - 与版本控制紧密集成的基于 Web 的翻译工具。 ([Source Code](https://github.com/WeblateOrg/weblate)) `GPL-3.0` `Python/Docker/K8S`


### 软件开发 - 低代码

**[`^        back to top        ^`](#awesome-selfhosted)**

A [low-code](https://en.wikipedia.org/wiki/Low-code_development_platform) development platform (LCDP) provides a development environment used to create application software through a graphical user interface.

_Related: [Software Development - IDE & Tools](#software-development---ide--tools)_

- [Appsmith](https://www.appsmith.com/) - 构建管理面板、CRUD 应用和工作流。以 10 倍的速度构建你所需的一切。 ([Source Code](https://github.com/appsmithorg/appsmith)) `Apache-2.0` `Java/Docker/K8S`
- [Appwrite](https://appwrite.io) - 为 Web、原生和移动开发者打造的端到端后端服务器。 ([Source Code](https://github.com/appwrite/appwrite)) `BSD-3-Clause` `Docker`
- [Halo](https://www.halo.run) - 强大且易用的网站构建工具（提供中文文档）。 ([Demo](https://docs.halo.run/#%E5%9C%A8%E7%BA%BF%E4%BD%93%E9%AA%8C), [Source Code](https://github.com/halo-dev/halo), [Clients](https://github.com/halo-sigs/awesome-halo)) `GPL-3.0` `Java/Docker`
- [Manifest](https://manifest.build) - 能装进单个 YAML 文件的完整后端。 ([Demo](https://manifest.new), [Source Code](https://github.com/mnfst/llm-gateway)) `MIT` `Nodejs`
- [PocketBase](https://pocketbase.io/) - 为你的下一个 SaaS 和移动应用准备的单文件后端。 ([Source Code](https://ganigeorgiev.com/pocketbase/pocketbase)) `MIT` `Go/Docker`
- [Saltcorn](https://saltcorn.com/) - 面向 Web 和移动应用的无代码数据库应用构建器。一个平台涵盖用户界面、数据后端、持久化工作流、电子邮件、PDF 生成和 AI 应用。 ([Source Code](https://github.com/saltcorn/saltcorn)) `MIT` `Docker/Nodejs`
- [SQLPage](https://sql-page.com) - 仅用 SQL 的动态网站构建器。 ([Source Code](https://github.com/sqlpage/SQLPage)) `MIT` `Rust/Docker`
- [ToolJet](https://tooljet.io/) - 以最少的工程投入构建和部署内部工具的低代码框架（Retool 和 Mendix 的替代品）。 ([Source Code](https://github.com/ToolJet/ToolJet)) `GPL-3.0` `Nodejs/Docker/K8S`
- [TrailBase](https://trailbase.io/) - 开放、亚毫秒级、单可执行文件的 FireBase 替代品，具有类型安全的 REST 与实时 API、内置 JS/TS 运行时、身份验证和管理界面。 ([Demo](https://demo.trailbase.io), [Source Code](https://github.com/trailbaseio/trailbase)) `OSL-3.0` `Rust/Docker`


### 软件开发 - 项目管理

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software for [software project management](https://en.wikipedia.org/wiki/Software_project_management).

_Related: [Ticketing](#ticketing), [Task Management & To-do Lists](#task-management--to-do-lists)_

- [Cgit](https://git.zx2c4.com/cgit/about/) - 面向 git 仓库的快速轻量 Web 界面。 ([Source Code](https://git.zx2c4.com/cgit/tree/)) `GPL-2.0` `C`
- [Forgejo](https://forgejo.org) - 专注于可扩展性、联邦化和隐私的轻量级软件 forge（Gitea 的分支）。 ([Demo](https://next.forgejo.org), [Source Code](https://codeberg.org/forgejo/forgejo/), [Clients](https://codeberg.org/forgejo-contrib/delightful-forgejo)) `MIT` `Docker/Go`
- [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - 具备 wiki 和缺陷跟踪功能的分布式版本控制系统。
- [Gerrit](https://www.gerritcodereview.com/) - 面向基于 Git 项目的代码评审和项目管理工具。 ([Source Code](https://github.com/GerritCodeReview/gerrit)) `Apache-2.0` `Java/Docker`
- [gitbucket](https://gitbucket.github.io/) - 具备轻松安装、高可扩展性和 GitHub API 兼容性的 Git 平台（GitHub 的替代品）。 ([Source Code](https://github.com/gitbucket/gitbucket)) `Apache-2.0` `Scala/Java`
- [Gitea](https://gitea.com) - 来杯茶，惬意享受 Git！轻松无忧的一站式软件开发服务，包括 Git 托管、代码评审、团队协作、软件包仓库和 CI/CD。 ([Demo](https://gitea.com/explore/repos), [Source Code](https://github.com/go-gitea/gitea)) `MIT` `Go/Docker/K8S`
- [GitLab](https://about.gitlab.com) - Git 仓库管理、代码评审、议题跟踪、活动动态和 wiki。 ([Demo](https://gitlab.com/), [Source Code](https://gitlab.com/gitlab-org/gitlab-foss)) `MIT` `Ruby/deb/Docker/K8S`
- [Gogs](https://gogs.io/) - 用 Go 编写的轻松易用的 Git 服务。 ([Source Code](https://github.com/gogs/gogs)) `MIT` `Go`
- [Huly](https://huly.io) - 一体化项目管理平台（Linear、Jira、Slack 的替代品）。 ([Demo](https://app.huly.io), [Source Code](https://github.com/hcengineering/platform)) `EPL-2.0` `Docker/K8S/Nodejs`
- [Ideon](https://www.theideon.com) - 围绕无限画布构建的项目工作区；可嵌入 GitHub、GitLab、Gitea 和 Forgejo 仓库，与笔记、链接和任务并列，支持实时协作。 ([Source Code](https://github.com/3xpyth0n/ideon)) `AGPL-3.0` `Docker`
- [Kaneo](https://kaneo.app/) - 专注于简洁高效的项目管理平台。 ([Demo](https://demo.kaneo.app/), [Source Code](https://github.com/usekaneo/kaneo)) `MIT` `K8S/Docker`
- [Leantime](https://leantime.io) - 面向小型团队和初创公司的精益项目管理系统，帮助管理从构思到交付的全过程。 ([Source Code](https://github.com/leantime/leantime)) `AGPL-3.0` `PHP/Docker`
- [Mindwendel](https://www.mindwendel.com/) - 在团队内进行头脑风暴并为想法和观点点赞。 ([Demo](https://www.mindwendel.com), [Source Code](https://github.com/b310-digital/mindwendel)) `AGPL-3.0` `Docker/Elixir`
- [minimal-git-server](https://github.com/mcarbonne/minimal-git-server) - 轻量级 git 服务器，带有用于管理仓库的基础 CLI，支持多账户并可运行在容器中。
- [Octobox](https://octobox.io/) `⚠` - Take back control of your GitHub Notifications. ([Source Code](https://github.com/octobox/octobox)) `AGPL-3.0` `Ruby/Docker`
- [OneDev](https://onedev.io/) - 一体化 DevOps 平台，具备 Git 管理、议题跟踪和 CI/CD。简单却强大。 ([Source Code](https://github.com/theonedev/onedev)) `MIT` `Java/Docker/K8S`
- [OpenProject](https://www.openproject.org) - 管理你的项目、任务和目标。通过工作包进行协作，并将其关联到你在 GitHub 上的拉取请求。 ([Source Code](https://github.com/opf/openproject)) `GPL-3.0` `Ruby/deb/Docker`
- [Paca](https://paca-ai.org) - AI 原生项目管理平台，AI 智能体与人类作为 Scrum 队友在同一看板和冲刺中协作。可通过配置文件和 WASM 插件进行配置（Jira、Trello、ClickUp 的替代品）。 ([Source Code](https://github.com/Paca-AI/paca)) `Apache-2.0` `Docker/K8S`
- [Pagure](https://pagure.io/pagure) - 轻量、强大且灵活的以 git 为中心的 forge，其特性为联邦化和去中心化开发奠定基础。 ([Demo](https://pagure.io/)) `GPL-2.0` `Docker/Python/deb`
- [Phorge](https://we.phorge.it/) - 由社区驱动的平台，用于协作、管理、组织和评审软件开发项目。 ([Source Code](https://we.phorge.it/source/phorge/)) `Apache-2.0` `PHP`
- [Plane](https://plane.so) - 以尽可能简单的方式跟踪议题、史诗和产品路线图（JIRA、Linear 和 Height 的替代品）。 ([Demo](https://app.plane.so), [Source Code](https://github.com/makeplane/plane)) `AGPL-3.0` `Docker`
- [ProjeQtOr](https://www.projeqtor.org/) - 完整、成熟的多用户项目管理系统，为项目的各个阶段提供丰富功能。 ([Demo](https://demo.projeqtor.org/), [Source Code](https://sourceforge.net/p/projectorria/code/HEAD/tree/branches/)) `AGPL-3.0` `PHP`
- [Redmine](https://www.redmine.org/) - 灵活的项目管理 Web 应用。 ([Source Code](https://svn.redmine.org/redmine/)) `GPL-2.0` `Ruby`
- [Review Board](https://www.reviewboard.org/) - 可扩展且友好的代码评审工具，适用于各种规模的项目和公司。 ([Demo](https://demo.reviewboard.org/), [Source Code](https://github.com/reviewboard/reviewboard)) `MIT` `Python/Docker`
- [RhodeCode](https://rhodecode.com/) - 统一并简化 Git、Subversion 和 Mercurial 的仓库管理。 ([Source Code](https://code.rhodecode.com/)) `AGPL-3.0` `Python`
- [Rukovoditel](https://www.rukovoditel.net/) - 可配置的基于 Web 的项目管理应用。 ([Source Code](https://www.rukovoditel.net/download.php)) `GPL-2.0` `PHP`
- [SCM Manager](https://www.scm-manager.org/) - 通过 http 共享和管理 Git、Mercurial 及 Subversion 仓库的最简单方式。 ([Source Code](https://github.com/scm-manager/scm-manager)) `BSD-3-Clause` `Java/deb/Docker/K8S`
- [Smederee](https://smeder.ee) - 节俭的平台，致力于借助 Darcs 版本控制系统的力量帮助人们共同构建优秀软件。 ([Source Code](https://smeder.ee/~jan0sch/smederee)) `AGPL-3.0` `Scala`
- [Sourcehut](https://sourcehut.org/) - 不使用 JavaScript 的完整 git Web 界面。 ([Demo](https://sr.ht/), [Source Code](https://git.sr.ht/~sircmpwn/git.sr.ht/tree)) `GPL-2.0` `Go`
- [Taiga](https://www.taiga.io/) - 基于看板和 Scrum 方法的敏捷项目管理工具。 ([Source Code](https://github.com/kaleidos-ventures)) `MPL-2.0` `Docker/Python/Nodejs`
- [Titra](https://titra.io/) - 面向自由职业者和小型团队的时间跟踪解决方案。 ([Source Code](https://github.com/titraio/titra)) `GPL-3.0` `Javascript/Docker`
- [Trac](https://trac.edgewall.org/) - 面向软件开发项目的增强版 wiki 和议题跟踪系统。
- [Traq](https://traq.io/) - 用 PHP 编写的项目管理和议题跟踪系统。 ([Source Code](https://github.com/nirix/traq)) `GPL-3.0` `PHP/Nodejs`
- [Tuleap](https://www.tuleap.org/) - 用于软件项目规划、跟踪、编码和协作的自由软件套件。 ([Source Code](https://tuleap.net/plugins/git/tuleap/tuleap/stable?p=tuleap%2Fstable.git&a=tree)) `GPL-2.0` `PHP`
- [ZenTao](https://www.zentao.pm/) - 敏捷（Scrum）项目管理系统/工具。 ([Source Code](https://github.com/easysoft/zentaopms)) `AGPL-3.0` `PHP`


### 软件开发 - 测试

**[`^        back to top        ^`](#awesome-selfhosted)**

Tools and software for [software testing](https://en.wikipedia.org/wiki/Software_testing).

- [Bencher](https://bencher.dev/) - 旨在捕获 CI 中性能回归的持续基准测试工具套件。 ([Source Code](https://github.com/bencherdev/bencher)) `MIT/Apache-2.0` `Rust`
- [Request Inbox](https://request-inbox.com/) - 收集和检查 HTTP 请求以进行测试和调试。创建和管理收件箱、捕获详细的请求数据、配置自定义响应。 ([Demo](https://request-inbox.com/), [Source Code](https://github.com/jesusnoseq/request-inbox)) `Apache-2.0` `Docker`
- [WebHook Tester](https://github.com/tarampampam/webhook-tester) - 用于测试 WebHook 等的强大工具。


### Static Site Generators

**[`^        back to top        ^`](#awesome-selfhosted)**

[Static site generators](https://en.wikipedia.org/wiki/Web_template_system#Static_site_generators) generate full static HTML websites based on raw data, plain text files and a set of templates. 

**Please visit [staticsitegenerators.bevry.me](https://staticsitegenerators.bevry.me), [staticgen.com](https://www.staticgen.com)**

_Related: [Blogging Platforms](#blogging-platforms), [Photo Galleries](#photo-galleries), [Content Management Systems (CMS)](#content-management-systems-cms)_



### 任务管理与待办清单

**[`^        back to top        ^`](#awesome-selfhosted)**

[Task management](https://en.wikipedia.org/wiki/Task_management#Task_management_software) software.

_Related: [Software Development - Project Management](#software-development---project-management), [Ticketing](#ticketing)_

- [4ga Boards](https://4gaboards.com) - 简单直接的实时看板管理，实现直观的任务跟踪。配备优雅的深色模式、可折叠的待办列表和多任务工具，让团队生产力更上一层楼。 ([Demo](https://demo.4gaboards.com), [Source Code](https://github.com/RARgames/4gaBoards)) `MIT` `Nodejs/Docker/K8S`
- [AppFlowy](https://appflowy.io/) - 为不同项目构建详细的待办列表，并跟踪每一项的状态（Notion 的替代品）。 ([Source Code](https://github.com/AppFlowy-IO/appflowy)) `AGPL-3.0` `Rust/Dart/Docker`
- [dayGLANCE](https://dayglance.app) - 日程规划工具，具有拖放式时间块、收件箱、重复任务、习惯、日常惯例、目标、项目和番茄钟专注模式，并支持 iCal 和 CalDAV 日历同步。数据保留在浏览器中，可选 WebDAV 或 GLANCEvault 同步。 ([Source Code](https://github.com/krelltunez/dayGLANCE), [Clients](https://github.com/glance-apps/glance-vault)) `MIT` `Javascript/Docker`
- [Donetick](https://donetick.com) - 面向个人和家庭使用的任务与家务管理工具，具有高级调度、灵活分配、群组共享功能、详细历史记录、基于 API 的自动化以及简洁现代的设计。 ([Demo](https://app.donetick.com/), [Source Code](https://github.com/donetick/donetick)) `AGPL-3.0` `Go/Docker`
- [Focus Flow](https://github.com/francesco-gaglione/focus_flow_cloud) - 使用番茄工作法进行时间管理的完整生态系统。
- [HamsterBase Tasks](https://tasks.hamsterbase.com) - 帮助你整理想法、成就佳作的工具。规划、组织、构建并交付。 ([Demo](https://tasks-app.hamsterbase.com), [Source Code](https://github.com/hamsterbase/tasks)) `AGPL-3.0` `Docker`
- [Kan](https://kan.bn/) - 灵活的看板应用，帮助你组织工作、跟踪进度并交付成果（Trello 的替代品）。 ([Source Code](https://github.com/kanbn/kan)) `AGPL-3.0` `Docker`
- [Kanboard](https://kanboard.org/) - 简单的可视化任务看板。 ([Source Code](https://github.com/kanboard/kanboard)) `MIT` `PHP`
- [Listaway](https://github.com/jeffrpowell/listaway/) - 用于创建和公开分享条目列表的列表管理应用。支持身份验证、管理工具、条目备注和优先级，以及可选择的随机 URL 公开只读链接（Amazon Lists 的替代品）。 ([Source Code](https://github.com/jeffrpowell/listaway)) `MIT` `Docker`
- [myTinyTodo](https://www.mytinytodo.net/) - 以 AJAX 风格管理待办列表的简单方式。使用 PHP、jQuery、SQLite/MySQL。符合 GTD 原则。 ([Demo](https://www.mytinytodo.net/demo/), [Source Code](https://github.com/maxpozdeev/mytinytodo/)) `GPL-2.0` `PHP`
- [Nullboard](https://github.com/apankrat/nullboard) - 单页极简看板；紧凑、高可读性且上手迅速。 ([Demo](https://nullboard.io/preview)) `BSD-2-Clause` `Javascript`
- [OpenHabitTracker](https://openhabittracker.net) - 跟踪习惯、任务和笔记，提供时间跟踪、日历视图和完成统计。 ([Demo](https://pwa.openhabittracker.net), [Source Code](https://github.com/Jinjinov/OpenHabitTracker)) `GPL-3.0` `Docker`
- [Our Shopping List](https://codeberg.org/nanawel/our-shopping-list) - 简单的共享列表应用，包括购物清单和任何其他需要协作使用的小型待办列表。 ([Demo](https://osl.lanterne-rouge.info/)) `AGPL-3.0` `Docker`
- [Super Productivity](https://super-productivity.com) - 高级待办列表应用，集成时间盒和时间跟踪功能。可与 Jira、GitHub、GitLab、Redmine 和 OpenProject 集成。 ([Source Code](https://github.com/super-productivity/super-productivity)) `MIT` `Docker`
- [Task Keeper](https://github.com/nymanjens/piga) - 面向高级用户的列表编辑器，由服务器提供支持。
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) - 基于文件、支持 Markdown 语法的任务管理看板。
- [Taskwarrior](https://taskwarrior.org/) - 管理 TODO 列表的命令行工具。灵活、快速、高效且不碍事。做好本职工作后便悄然退场。 ([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
- [Tellor](https://tellor.cc/) - 极简单用户看板待办应用。界面干净、简约而紧凑。可从 Trello 导入看板。 ([Demo](https://tellor.cc/demo/?b=18486f63be6bb5f2), [Source Code](https://github.com/Voldrix/Tellor)) `MIT` `PHP`
- [Tracks](https://www.getontracks.org/) - 基于 Web 的应用，帮助你践行 David Allen 的 Getting Things Done™（把事情做完）方法论。 ([Source Code](https://github.com/TracksApp/tracks)) `GPL-2.0` `Ruby`
- [tududi](https://tududi.com/) - 具有层级结构、智能重复任务和无缝 Telegram 集成的任务管理工具。 ([Source Code](https://github.com/chrisvel/tududi)) `MIT` `Docker`
- [Vikunja](https://vikunja.io/) - 整理你生活的待办应用。 ([Demo](https://try.vikunja.io/login), [Source Code](https://github.com/go-vikunja/vikunja)) `AGPL-3.0/GPL-3.0` `Go`
- [Wekan](https://wekan.github.io/) - 类 Trello 的看板。 ([Source Code](https://github.com/wekan/wekan)) `MIT` `Nodejs`
- [Will Be Done](https://will-be-done.app/) - 离线优先的任务管理器，具有每周规划、项目看板、实时同步、Vim 快捷键、桌面快速添加以及从热门任务管理器导入等功能（TickTick、Todoist 的替代品）。 ([Demo](https://demo.will-be-done.app/), [Source Code](https://github.com/will-be-done/will-be-done)) `AGPL-3.0` `Docker/Nodejs`


### 工单

**[`^        back to top        ^`](#awesome-selfhosted)**

[Helpdesk](https://en.wikipedia.org/wiki/Help_desk_software), [bug](https://en.wikipedia.org/wiki/Bug_tracking_system) and [issue](https://en.wikipedia.org/wiki/Issue_tracking_system) tracking software to help the tracking of user requests, bugs and missing features.

_Related: [Task Management & To-do Lists](#task-management--to-do-lists), [Software Development - Project Management](#software-development---project-management)_

- [BugPin](https://bugpin.io) - 面向 Web 应用的可视化缺陷报告和工单工具。 ([Source Code](https://github.com/aranticlabs/bugpin)) `AGPL-3.0/MIT` `Docker`
- [Bugzilla](https://www.bugzilla.org/) - 最初由 Mozilla 项目开发和使用的通用缺陷跟踪与测试工具。 ([Source Code](https://github.com/bugzilla/bugzilla)) `MPL-2.0` `Perl`
- [Frappe Helpdesk](https://frappe.io/helpdesk) - 帮助你理顺公司支持工作的工单软件，提供简易的安装设置、清爽的用户界面以及高效解决客户咨询的自动化工具。 ([Source Code](https://github.com/frappe/helpdesk)) `AGPL-3.0` `Docker`
- [FreeScout](https://freescout.net/) - 基于电子邮件的客户支持应用、服务台和共享邮箱（Zendesk 和 Help Scout 的替代品）。 ([Demo](https://demo.freescout.net/login), [Source Code](https://github.com/freescout-help-desk/freescout)) `AGPL-3.0` `PHP/Docker`
- [GlitchTip](https://glitchtip.com) - 收集应用所报告错误的错误跟踪应用。 ([Source Code](https://gitlab.com/glitchtip/glitchtip)) `MIT` `Python/Docker/K8S`
- [ITFlow](https://itflow.org) - 面向 MSP（托管服务提供商）的客户 IT 文档、工单、开票和会计工具。 ([Demo](https://demo.itflow.org), [Source Code](https://github.com/itflow-org/itflow)) `GPL-3.0` `PHP`
- [Libredesk](https://libredesk.io/) - 现代的全渠道客户支持台。实时聊天、电子邮件及更多功能集于单一二进制文件。 ([Demo](https://demo.libredesk.io), [Source Code](https://github.com/abhinavxd/libredesk)) `AGPL-3.0` `Docker/Go/Nodejs`
- [MantisBT](https://www.mantisbt.org/) - 缺陷跟踪工具，最适合软件开发场景。 ([Demo](https://www.mantisbt.org/bugs/my_view_page.php), [Source Code](https://github.com/mantisbt/mantisbt)) `GPL-2.0` `PHP`
- [OTOBO](https://otobo.io/en/) - 灵活的基于 Web 的工单系统，用于客户服务、服务台和 IT 服务管理。 ([Demo](https://otobo.io/en/service-management-plattform/otobo-demo/), [Source Code](https://github.com/RotherOSS/otobo)) `GPL-3.0` `Perl/Docker`
- [Request Tracker](https://www.bestpractical.com/rt/) - 企业级议题跟踪系统。 ([Source Code](https://github.com/bestpractical/rt)) `GPL-2.0` `Perl`
- [Roundup Issue Tracker](https://www.roundup-tracker.org/) - 简单易用、易于安装的议题跟踪系统，提供命令行、Web、REST、XML-RPC 和电子邮件接口。设计上注重灵活性——不仅仅是又一个缺陷跟踪工具。 ([Source Code](https://www.roundup-tracker.org/code.html)) `MIT/ZPL-2.0` `Python/Docker`
- [Rustrak](https://rustrak.github.io/rustrak/) - 兼容 Sentry SDK 的错误跟踪服务器，空闲时仅占用 32 MB 内存，使用 SQLite 存储。 ([Source Code](https://github.com/rustrak/rustrak)) `GPL-3.0` `Rust/Docker`
- [Zammad](https://zammad.org/) - 易用而强大的支持与工单系统。 ([Source Code](https://github.com/zammad/zammad)) `AGPL-3.0` `Ruby/deb`


### 时间追踪

**[`^        back to top        ^`](#awesome-selfhosted)**

[Time-tracking software](https://en.wikipedia.org/wiki/Time-tracking_software) is a category of computer software that allows its users to record time spent on tasks or projects.

- [ActivityWatch](https://activitywatch.net) - 自动跟踪你在设备上的时间使用情况。 ([Source Code](https://github.com/ActivityWatch/activitywatch)) `MPL-2.0` `Python`
- [Beaver Habit Tracker](https://github.com/daya0576/beaverhabits) - 习惯跟踪应用，为你定格流逝生活中的珍贵时刻。 ([Demo](https://beaverhabits.com/demo)) `BSD-3-Clause` `Docker`
- [Ever Gauzy](https://gauzy.co) - 为协作、按需和共享经济打造的开放企业管理平台（ERP/CRM/HRM/ATS/PM）。 ([Demo](https://demo.gauzy.co), [Source Code](https://github.com/ever-co/ever-gauzy)) `AGPL-3.0` `Docker/Nodejs`
- [Kimai](https://www.kimai.org/) - 跟踪工作时间，并按需打印你的活动摘要。 ([Demo](https://www.kimai.org/demo/), [Source Code](https://github.com/kimai/kimai)) `AGPL-3.0` `PHP`
- [solidtime](https://www.solidtime.io) - 面向自由职业者和代理机构的现代时间跟踪应用。 ([Source Code](https://github.com/solidtime-io/solidtime)) `AGPL-3.0` `Docker`
- [TimeTagger](https://timetagger.app) - 基于交互式时间线和强大报表功能的时间跟踪器。 ([Demo](https://timetagger.app/app/demo), [Source Code](https://github.com/almarklein/timetagger)) `GPL-3.0` `Python`
- [TimeTracker](https://timetracker.drytrix.com/) - 跨项目和客户跟踪时间，具有计时器、看板任务、CRM、费用跟踪、多币种开票（PDF、Peppol/ZugFerd 电子发票）、报表、OIDC/SSO 和 REST API。 ([Source Code](https://github.com/drytrix/TimeTracker)) `GPL-3.0` `Docker`
- [Traggo](https://traggo.net/) - 基于标签的时间跟踪工具。在 Traggo 中没有任务，只有带标签的时间段。 ([Source Code](https://github.com/traggo/server)) `GPL-3.0` `Docker/Go`
- [Wakapi](https://wakapi.dev/) - 编码统计跟踪工具，兼容 WakaTime。 ([Source Code](https://github.com/muety/wakapi)) `GPL-3.0` `Go/Docker`
- [Ziit](https://ziit.app) - 代码时间跟踪的瑞士军刀（WakaTime 的替代品）。 ([Source Code](https://github.com/0pandadev/ziit)) `AGPL-3.0` `Docker`


### 旅行组织

**[`^        back to top        ^`](#awesome-selfhosted)**

Travel organization software to record bookings, view itinerary, plan activities and track expenses.

_Related: [Booking and Scheduling](#booking-and-scheduling), [Maps and Global Positioning System (GPS)](#maps-and-global-positioning-system-gps)_

- [Surmai](https://surmai.app/) - 协作式的个人与家庭旅行规划整理工具。 ([Demo](https://demo.surmai.app), [Source Code](https://github.com/rohitkumbhar/surmai)) `MIT` `Docker`
- [TREK](https://github.com/liketrek/TREK) - 协作式旅行规划工具，具有交互式地图、逐日行程、预算、行李清单、预订、旅程日志和 PWA 支持。 ([Demo](https://demo.liketrek.com/)) `AGPL-3.0` `Docker/K8S`


### 短链接

**[`^        back to top        ^`](#awesome-selfhosted)**

[URL shortening](https://en.wikipedia.org/wiki/URL_shortening) is the action of shortening a [URL](https://en.wikipedia.org/wiki/Uniform_Resource_Locator) to make it substantially shorter and still direct to the required page. Before hosting one, please see [disadvantages](https://en.wikipedia.org/wiki/URL_shortening#Disadvantages) of URL shorteners.

- [bit](https://github.com/sjdonado/bit) - 快速、轻量、资源高效的编译型 URL 缩短器。
- [Chhoto URL](https://chhoto.link) - 简单、闪电般快速的 URL 缩短器，毫无臃肿（simply-shorten 的分支）。 ([Demo](https://github.com/SinTan1729/chhoto-url?tab=readme-ov-file#demo), [Source Code](https://github.com/SinTan1729/chhoto-url), [Clients](https://github.com/SinTan1729/chhoto-url/blob/main/TOOLS.md)) `MIT` `Rust/Docker`
- [clink](https://git.crueter.xyz/crueter/clink) - 用纯 C 编写的超精简链接缩短服务，专注于小巧的可执行文件、可移植性和易配置性。 ([Demo](https://short.crueter.xyz)) `AGPL-3.0` `C`
- [Flink](https://gitlab.com/rtraceio/web/flink) - 创建二维码、为网站生成可嵌入的链接预览，并抓取元数据。 ([Demo](https://flink.is)) `MIT` `Docker`
- [Kutt](https://kutt.to) - 支持自定义域名和自定义 URL 的现代 URL 缩短器。 ([Demo](https://kutt.to), [Source Code](https://github.com/thedevs-network/kutt)) `MIT` `Nodejs/Docker`
- [rs-short](https://git.42l.fr/42l/rs-short) - 用 Rust 编写的轻量级链接缩短器，具有缓存、垃圾机器人防护和钓鱼检测等功能。 ([Demo](https://s.42l.fr/)) `MPL-2.0` `Rust`
- [Shlink](https://shlink.io) - 提供 REST API 和命令行界面的 URL 缩短器。包含官方渐进式 Web 应用和 Docker 镜像。 ([Source Code](https://github.com/shlinkio/shlink), [Clients](https://shlink.io/apps)) `MIT` `PHP/Docker`
- [Simple-URL-Shortener](https://github.com/azlux/Simple-URL-Shortener) - 遵循 KISS 原则的 URL 缩短器，可公开或私有（带账户）使用。极简且轻量，无任何依赖。 ([Demo](https://u.azlux.fr)) `MIT` `PHP`
- [YOURLS](https://yourls.org/) - 一套让你运行自己的 URL 缩短服务的 PHP 脚本。功能包括密码保护、URL 自定义、书签小程序、统计、API、插件和 jsonp。 ([Source Code](https://github.com/YOURLS/YOURLS)) `MIT` `PHP`


### 视频监控

**[`^        back to top        ^`](#awesome-selfhosted)**

Video surveillance, also known as [Closed-circuit television (CCTV)](https://en.wikipedia.org/wiki/Closed-circuit_television), is the use of video cameras for surveillance in areas that require additional security or ongoing monitoring.

_Related: [Media Streaming - Video Streaming](#media-streaming---video-streaming)_

- [Bluecherry](https://github.com/bluecherrydvr/bluecherry-apps) - 支持 IP 和模拟摄像头的闭路电视（CCTV）软件应用。
- [Frigate](https://frigate.video/) - 使用本地处理的 AI 监控你的安防摄像头。 ([Source Code](https://github.com/blakeblackshear/frigate)) `MIT` `Docker/Python/Nodejs`
- [motionEye](https://github.com/motioneye-project/motioneye) - 软件 Motion 的在线界面，Motion 是一款带移动侦测功能的视频监控程序。
- [Secluso](https://secluso.com) - 面向 Raspberry Pi 的私有 DIY 家庭安防摄像头系统，提供端到端加密的远程访问和移动应用，支持实时视频、警报和录像回放。 ([Source Code](https://github.com/secluso/core)) `GPL-3.0` `Rust`
- [SentryShot](https://codeberg.org/SentryShot/sentryshot) - 视频监控管理系统。
- [Strix](https://github.com/eduard256/Strix) - 自动发现 IP 摄像头可用的流媒体 URL，并生成开箱即用的 Frigate 和 go2rtc 配置。
- [Viseron](https://viseron.netlify.app/) - 仅在本地运行的 NVR 和 AI 计算机视觉软件。具备目标检测、移动侦测、人脸识别等功能，让你轻松看护家庭、办公室或任何想监控的场所。 ([Source Code](https://github.com/roflcoopter/viseron)) `MIT` `Docker`
- [Zoneminder](https://www.zoneminder.com/) - 支持 IP、USB 和模拟摄像头的闭路电视（CCTV）软件应用。 ([Source Code](https://github.com/ZoneMinder/ZoneMinder)) `GPL-2.0` `PHP/deb`


### VPN

**[`^        back to top        ^`](#awesome-selfhosted)**

A [virtual private network (VPN)](https://en.wikipedia.org/wiki/Virtual_private_network) extends a private network across a public network and enables users to send and receive data across shared or public networks as if their computing devices were directly connected to the private network.

**Please visit [awesome-sysadmin/VPN](https://github.com/awesome-foss/awesome-sysadmin#vpn)**

_See also: [Awesome-Tunneling](https://github.com/anderspitman/awesome-tunneling)_



### Web 服务器

**[`^        back to top        ^`](#awesome-selfhosted)**

Web Servers and Reverse Proxies. A [web server](https://en.wikipedia.org/wiki/Web_server) is a piece of software and underlying hardware that accepts requests via [HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) (the network protocol created to distribute web content) or its secure variant [HTTPS](https://en.wikipedia.org/wiki/HTTPS). A [Reverse Proxy](https://en.wikipedia.org/wiki/Reverse_proxy) is a proxy server that appears to any client to be an ordinary web server, but in reality merely acts as an intermediary that forwards requests to one or more ordinary web servers.

_Related: [Proxy](#proxy)_

- [Algernon](https://algernon.roboticoverlords.org/) - 小巧自包含的纯 Go Web 服务器，支持 Lua、Markdown、HTTP/2、QUIC、Redis 和 PostgreSQL。 ([Source Code](https://github.com/xyproto/algernon)) `BSD-3-Clause` `Go/Docker`
- [Apache HTTP Server](https://httpd.apache.org/) - 安全、高效且可扩展的服务器，提供符合当前 HTTP 标准的 HTTP 服务。 ([Source Code](https://svn.apache.org/repos/asf/httpd/httpd/trunk/)) `Apache-2.0` `C/deb/Docker`
- [BunkerWeb](https://www.bunkerweb.io) - 保护你的 Web 服务的新一代 Web 应用防火墙（WAF）。 ([Demo](https://demo.bunkerweb.io), [Source Code](https://github.com/bunkerity/bunkerweb), [Clients](https://docs.bunkerweb.io/latest/plugins/)) `AGPL-3.0` `deb/Docker/K8S/Python`
- [Caddy](https://caddyserver.com/) - 强大、企业可用且支持自动 HTTPS 的 Web 服务器。 ([Source Code](https://github.com/caddyserver/caddy)) `Apache-2.0` `Go/deb/Docker`
- [Ferron](https://ferron.sh/) - 用 Rust 编写的快速、内存安全的 Web 服务器。 ([Source Code](https://github.com/ferronweb/ferron)) `MIT` `Rust/Docker/deb`
- [go-doxy](https://github.com/yusing/godoxy) - 轻量、简单且高性能的反向代理，具有 WebUI 和 Docker 集成，可根据流量自动关停/启动容器。
- [HAProxy](https://www.haproxy.org/) - 非常快速可靠的反向代理，为 TCP 和基于 HTTP 的应用程序提供高可用性、负载均衡和代理服务。 ([Source Code](https://git.haproxy.org/?p=haproxy.git;a=tree)) `GPL-2.0` `C/deb/Docker`
- [Lighttpd](https://www.lighttpd.net/) - 安全、快速、合规且非常灵活的 Web 服务器，针对高性能环境优化。 ([Source Code](https://git.lighttpd.net/lighttpd/lighttpd1.4)) `BSD-3-Clause` `C/deb/Docker`
- [Nginx Proxy Manager](https://nginxproxymanager.com/) - 用于管理 Nginx 代理主机的 Docker 容器，界面简单而强大。 ([Source Code](https://github.com/NginxProxyManager/nginx-proxy-manager)) `MIT` `Docker`
- [NGINX](https://nginx.org/en/) - HTTP 和反向代理服务器、邮件代理服务器以及通用 TCP/UDP 代理服务器。 ([Source Code](https://github.com/nginx/nginx)) `BSD-2-Clause` `C/deb/Docker`
- [Pangolin](https://digpangolin.com/) - 具有身份感知的隧道反向代理，配有仪表盘界面、访问控制和基于 WireGuard 的隧道（Cloudflare Tunnel、Tailscale 的替代品）。 ([Source Code](https://github.com/fosrl/pangolin)) `AGPL-3.0` `Docker`
- [Pomerium](https://www.pomerium.io) - 具有身份感知的反向代理，是现已过时的 oauth_proxy 的继任者。它在将请求代理到后端之前插入 OAuth 步骤，从而让你能安全地将自己的网站暴露在公共互联网上。 ([Source Code](https://github.com/pomerium/pomerium)) `Apache-2.0` `Go/Docker`
- [SafeLine](https://waf.chaitin.com/) - 保护你的 Web 应用免受攻击和漏洞利用的 Web 应用防火墙/反向代理。 ([Demo](https://demo.waf.chaitin.com/), [Source Code](https://github.com/chaitin/SafeLine)) `GPL-3.0` `Docker`
- [Static Web Server](https://static-web-server.net/) - 用于静态文件服务的跨平台、高性能异步 Web 服务器。 ([Source Code](https://github.com/static-web-server/static-web-server)) `Apache-2.0/MIT` `Rust/Docker`
- [SWAG (Secure Web Application Gateway)](https://github.com/linuxserver/docker-swag) - 支持 PHP 的 Nginx Web 服务器和反向代理，内置 Certbot（Let's Encrypt）客户端和 fail2ban 集成。
- [Traefik](https://traefik.io/) - 让微服务部署变得简单的 HTTP 反向代理和负载均衡器。 ([Source Code](https://github.com/traefik/traefik)) `MIT` `Go/Docker`
- [UUSEC WAF](https://waf.uusec.com/) - 业界领先的高性能 Web 应用防火墙和 API 安全网关，采用 AI 与语义技术（nginx 的分支）。 ([Source Code](https://github.com/Safe3/uusec-waf)) `GPL-3.0` `C/Lua/Docker`
- [Vinyl Cache](https://vinyl-cache.org/) - Web 应用加速器/缓存型 HTTP 反向代理（前身为 Varnish）。 ([Source Code](https://code.vinyl-cache.org/vinyl-cache/vinyl-cache)) `BSD-2-Clause` `Go/deb/Docker`
- [Zoraxy](https://zoraxy.aroz.org/) - 通用 HTTP 反向代理和转发工具。 ([Source Code](https://github.com/tobychui/zoraxy)) `AGPL-3.0` `Go/Docker`


### Wiki

**[`^        back to top        ^`](#awesome-selfhosted)**

A [wiki](https://en.wikipedia.org/wiki/Wiki) is a publication collaboratively edited and managed by its own audience directly using a web browser.

_Related: [Note-taking & Editors](#note-taking--editors), [Static Site Generators](#static-site-generators), [Knowledge Management Tools](#knowledge-management-tools)_

_See also: [Wikimatrix](https://www.wikimatrix.org/), [List of wiki software - Wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software - Wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software)_

- [AmuseWiki](https://amusewiki.org/) - Amusewiki 基于 Emacs Muse 标记语言构建，与原始实现基本保持兼容。它可以用作只读站点、受审核的 wiki、完全开放的 wiki，甚至私有站点。 ([Source Code](https://github.com/melmothx/amusewiki)) `GPL-1.0` `Perl/Docker`
- [BookStack](https://www.bookstackapp.com/) - 组织并存储信息，以类似书籍的方式存放文档。 ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://codeberg.org/bookstack/bookstack)) `MIT` `PHP/Docker`
- [django-wiki](https://github.com/django-wiki/django-wiki) - 功能丰富、易于集成且界面出众的 wiki 系统。优雅地存储你的知识：使用 django 模型。 ([Demo](https://demo.django-wiki.org/)) `GPL-3.0` `Python`
- [docmost Community Edition](https://docmost.com/) - 协作式 wiki 和文档软件（Confluence 和 Notion 的替代品）。 ([Source Code](https://github.com/docmost/docmost)) `AGPL-3.0` `Docker/Nodejs`
- [Documize](https://documize.com) - 现代的文档 + wiki 软件，内置工作流，单一二进制可执行文件，只需自备 MySQL/Percona。 ([Source Code](https://github.com/documize/community)) `AGPL-3.0` `Go`
- [Dokuwiki](https://www.dokuwiki.org/DokuWiki) - 易用、轻量且符合标准的 wiki 引擎，语法简单，允许在 wiki 之外读取数据。所有数据存储在纯文本文件中，因此无需数据库。 ([Source Code](https://github.com/dokuwiki/dokuwiki)) `GPL-2.0` `PHP`
- [Feather Wiki](https://feather.wiki) - 闪电般快速、可无限扩展的工具，用于创建个人非线性笔记本、数据库和 wiki；完全自包含，在浏览器中运行，大小仅 58 KB。 ([Demo](https://feather.wiki/?page=gallery#wikis), [Source Code](https://codeberg.org/Alamantus/FeatherWiki), [Clients](https://feather.wiki/?page=gallery#extensions)) `AGPL-3.0` `Javascript`
- [Gitit](https://github.com/jgm/gitit) - 将页面和上传文件存储在 git 仓库中的 wiki 程序，之后可以使用 VCS 命令行工具或 wiki 的 Web 界面进行修改。
- [LeafWiki](https://github.com/perber/leafwiki) - 为习惯以文件夹而非信息流方式思考的人打造的快速 wiki。快速编辑，树状导航，Markdown 存于磁盘。 ([Demo](https://demo.leafwiki.com)) `MIT` `Docker/Go`
- [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) - 驱动 Wikipedia 及所有其他 Wikimedia 项目的 wiki 软件包，每月服务数亿用户。 ([Demo](https://en.wikipedia.org/wiki/Main_Page), [Source Code](https://phabricator.wikimedia.org/source/mediawiki/)) `GPL-2.0` `PHP`
- [Otter Wiki](https://otterwiki.com/) - 使用 Markdown 的简单易用的 wiki 软件。 ([Source Code](https://github.com/redimp/otterwiki)) `MIT` `Docker`
- [PmWiki](https://www.pmwiki.org) - 用于协作创建和维护网站的基于 wiki 的系统。
- [Raneto](https://raneto.com/) - 使用静态 Markdown 文件的知识库平台。 ([Source Code](https://github.com/ryanlelek/Raneto)) `MIT` `Nodejs`
- [TiddlyWiki](https://tiddlywiki.com/) - 可复用的非线性个人 Web 笔记本。 ([Source Code](https://github.com/TiddlyWiki/TiddlyWiki5)) `BSD-3-Clause` `Nodejs`
- [Tiki](https://tiki.org/HomePage) - 内置功能最多的 wiki CMS 群件。 ([Demo](https://tiki.org/Try-Tiki), [Source Code](https://gitlab.com/tikiwiki/tiki)) `LGPL-2.1` `PHP`
- [W](https://w.club1.fr) - 轻量级多用户平面文件数据库 wiki 引擎。可快速创建页面，并在 Web 浏览器中使用 Markdown/HTML/CSS/JS 进行编辑。与其他 wiki 的主要区别在于，它鼓励你为每个页面单独定制样式。 ([Source Code](https://github.com/vincent-peugnet/wcms)) `AGPL-3.0` `PHP`
- [WackoWiki](https://wackowiki.org/) - 轻量且易于安装的多语言 wiki 引擎。 ([Source Code](https://github.com/WackoWiki/wackowiki)) `BSD-3-Clause` `PHP`
- [Wiki-Go](https://leomoon.com/downloads/web-apps/wiki-go/) - 现代、功能丰富的无数据库平面文件 wiki 平台。 ([Demo](https://wikigo.leomoon.com), [Source Code](https://github.com/leomoon-studios/wiki-go)) `GPL-3.0` `Go/Docker`
- [Wiki.js](https://js.wiki/) - 使用 Git 和 Markdown 的现代、轻量且强大的 wiki 应用。 ([Demo](https://docs.requarks.io), [Source Code](https://github.com/Requarks/wiki)) `AGPL-3.0` `Nodejs/Docker/K8S`
- [WikiDocs](https://www.wikidocs.app/) - 无数据库的 Markdown 平面文件 wiki 引擎。 ([Source Code](https://github.com/Zavy86/WikiDocs)) `MIT` `PHP/Docker`
- [WiKiss](https://wikiss.tuxfamily.org/) - 易于使用和安装的简单 wiki。 ([Source Code](https://svnweb.tuxfamily.org/listing.php?repname=wikiss/svn&path=%2F&sc=0)) `GPL-2.0` `PHP`
- [XWiki](https://www.xwiki.org) - 第二代 wiki，允许用户通过强大的基于扩展的架构来扩展其功能。 ([Demo](https://www.xwikiplayground.org/xwiki/bin/view/Main/), [Source Code](https://github.com/xwiki/xwiki-platform)) `LGPL-2.1` `Java/Docker/deb`
- [Zim](https://zim-wiki.org/) - 用于维护 wiki 页面集合的图形化文本编辑器。每个页面可以包含指向其他页面的链接、简单的格式和图片。 ([Source Code](https://github.com/zim-desktop-wiki/zim-desktop-wiki)) `GPL-2.0` `Python/deb`


--------------------

## 许可证列表

**[`^        back to top        ^`](#awesome-selfhosted)**

- `0BSD` - [BSD Zero-Clause Licence](https://spdx.org/licenses/0BSD.html)
- `AAL` - [Attribution Assurance License](https://spdx.org/licenses/AAL.html)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache, Version 2.0](https://spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - [Artistic License Version 2.0](https://spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - [BSD 4-clause "Original"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CAL-1.0` - [Cryptographic Autonomy License 1.0](https://spdx.org/licenses/CAL-1.0.html)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 License](https://spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 License](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - [Public Domain/Creative Common Zero 1.0](https://spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - [Common Development and Distribution License](https://spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](https://spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - [Educational Community License, Version 2.0](https://spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - [Eclipse Public License, Version 2.0](https://spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - [European Union Public License 1.2](https://spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - [GNU General Public License 1.0](https://spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - [GNU General Public License 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - [IBM Public License](https://spdx.org/licenses/IPL-1.0.html)
- `ISC` - [Internet Systems Consortium License](https://spdx.org/licenses/ISC.html)
- `LGPL-2.1` - [Lesser General Public License 2.1](https://spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - [Lesser General Public License 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT License](https://spdx.org/licenses/MIT.html)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - [Mozilla Public License](https://spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - [Open Software License 3.0](https://spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - [Sendmail License](https://spdx.org/licenses/Sendmail.html)
- `Ruby` - [Ruby License](https://spdx.org/licenses/Ruby.html)
- `Unlicense` - [The Unlicense](https://spdx.org/licenses/Unlicense.html)
- `WTFPL` - [Do What the Fuck You Want to Public License](https://spdx.org/licenses/WTFPL.html)
- `Zlib` - [Zlib/libpng License](https://spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - [Zope Public License 2.0](https://spdx.org/licenses/ZPL-2.0.html)


--------------------

## 反特性

- `⚠ ` - Depends on a proprietary service outside the user's control

--------------------

## External Links

**[`^        back to top        ^`](#awesome-selfhosted)**

- Alternative frontends/portals to discover/filter awesome-selfhosted apps: [awweso.me](https://awweso.me/), [awesome-web.theravenhub](https://awesome-web.theravenhub.com/browse.html)
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - 精选的极为出色的开源系统管理资源列表。
- Lists of software aimed at privacy and decentralization in some form: [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](https://libreprojects.net/), [Easy Indie App](https://easyindie.app)
- Other Awesome lists: [Awesome Big Data](https://github.com/0xnr/awesome-bigdata), [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- Communities/forums: [/c/selfhosted on lemmy.world](https://lemmy.world/c/selfhosted), [/c/selfhost on lemmy.ml](https://lemmy.ml/c/selfhost), [/r/selfhosted on reddit](https://old.reddit.com/r/selfhosted/), [/r/selfhosted Matrix Channel](https://matrix.to/#/#selfhosted:selfhosted.chat), [/r/homelab on reddit](https://old.reddit.com/r/homelab/), [IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 为 50 个自托管应用提供的主题/皮肤集合。 ([Source Code](https://github.com/GilbN/theme.park/)) `MIT` `CSS`

--------------------

## 贡献

Contributing guidelines can be found [here](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md).

## 许可证

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) License.
Terms of the license are summarized [here](https://creativecommons.org/licenses/by-sa/3.0/).  
The list of authors can be found in the [AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS) file.


## 贡献

贡献指南见上游 [Contributing](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/CONTRIBUTING.md)。本中文版的条目翻译问题请到本仓库提 issue；新增/修正条目请先向上游 PR，再同步到本仓库。

## 署名与许可

- 原清单：[awesome-selfhosted/awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)（CC-BY-SA-3.0，© Awesome-Selfhosted 贡献者）
- 本中文版基于上述清单翻译，按 **CC-BY-SA-3.0** 相同方式共享，© 2026 [@bayshier](https://github.com/bayshier)（翻译）
- 翻译如有出入，以上游英文原版为准

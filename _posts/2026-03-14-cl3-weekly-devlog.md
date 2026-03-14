---
layout: post
title: "CL3 開發週記｜從功能堆疊，走向可維護的平台工程"
date: 2026-03-14 10:00:00 +0800
categories: [weekly, devlog]
---

這一週，CL3 的開發重點，不只是新增功能，而是持續把系統從「能運作」往「可維護、可治理、可交付」推進。

本週完成了 Dashboard Telemetry 卡片顯示開關與狀態持久化，優化了 Header 中的 Build、Time Zone 與模組資訊顯示，也開始推進 `/explain` 與 Dashboard 的版型一致化，讓整體產品介面更完整。

在架構層面，多語系 / i18n 開始正式落地，CL3 不再只是內部工具思維，而是逐步朝可展示、可協作的平台前進。Admin 方面則持續強化資產維護流程，補強 Driver / Source 資訊透明度，並修補 ALLIANZ 建立流程的一致性問題。

本週另一個重要收穫，是更清楚確認未來資產輸入流程必須依 driver 特性治理：ALLIANZ 將朝 catalog picker 方向發展，YFINANCE 則朝 ticker search + validate picker 收斂，讓系統從自由輸入走向受控輸入。

這一週，CL3 又更接近一個真正可持續演進的平台。

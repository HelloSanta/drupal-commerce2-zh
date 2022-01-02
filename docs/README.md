# Drupal Commerce 2 中文版 說明文件

<aside>
💡 此開源文件，是為了推廣Drupal Commerce 於中文社群的運用而生，請有意貢獻者發送PR到Github，一起推廣Drupal多元的使用！

</aside>

> 閱讀此文件之前，是假設您已經熟悉、理解Drupal 8/9 的基礎運用。關於Drupal的基礎使用，請見[官網介紹](https://www.drupal.org/documentation)
>

## 前情提要

Drupal向來以其作為富有延展性的Open source 內容管理系統(Content Management System)著稱。

[Drupal Commerce](https://www.drupal.org/project/commerce) 精深於電商核心基礎，例如客戶(customer)、訂單(order)、支付(payment)、checkout(付款流程)等多個電商要件做拆分，使得此模組得以因應不同的商業需求進行客製的調整與開發，非常具有彈性；相較於其他整合型電商模組，如[Drupal Ubercart](https://www.drupal.org/project/ubercart)，就以一次到位的形式，讓具備簡易需求的客戶能夠在最短的時間內設定好電商系統與paypal的支付方式。相當然爾，這樣的設計哲學同時也限縮了電商系統具備的自由度跟做法 。

<aside>
⚠️ 建議評估好客戶/自身的需求，並評估電商系統的優劣之後，再進行規劃與電商系統的開發。

</aside>

### 基本使用分析

| Drupal Commerce | 其他Drupal電商模組 |
| --- | --- |
| 開發上 |  |
| 富有彈性、使用層面廣泛、適合客製調整 | 針對單一需求、介面使用上相較單純 |
| 介面需花費時間客製化 | 不易調整與客製 |
| 適合的專案 |  |
| 電商邏輯「單純」至「複雜」：需要促銷、訂單計算、串接不同金流商、訂單資料計算呈現等特殊需求 | 適合單一商品直接結帳的商家 |

## 常用額外模組

以下模組為Drupal Commerce模組所自有的相關子模組與功能之外，可與之搭配的模組。

| 模組名稱 | 說明 |
| --- | --- |
| Commerce Cart API | 提供一個簡易的cart REST API |
| Commerce Square Connect | 提供Commerce跟Square金流商API的整合 |
| Commerce Variation Cart Form | 提供直接由產品種類結帳的按鈕介面 |
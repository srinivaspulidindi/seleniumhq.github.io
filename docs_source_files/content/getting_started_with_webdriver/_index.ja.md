---
title: "WebDriverをはじめよう"
chapter: true
weight: 4
---


# WebDriverをはじめよう

Seleniumは市場で主要なブラウザの全てを _WebDriver_ を使うことでサポートしています。
WebDriverとはAPI群とプロトコルです。これらはウェブブラウザの動作をコントロールするための言語中立なインターフェイスを定義しています。
それぞれのブラウザは特定のWebDriverの実装を持っており、これらは *driver* と呼ばれます。
driverはブラウザに委譲する責務を持つコンポーネントであり、Seleniumとブラウザ間の通信を処理します。

この分離は、ブラウザベンダーに自分たちのブラウザでの実装の責任を持たせるための意図的な努力のひとつです。
Seleniumは可能な場合これらのサードパーティ製のdriverを使いますが、それが現実的でない場合のためにプロジェクトでメンテナンスしているdriverも提供しています。

Seleniumフレームワークはこれら全ての要素をユーザ向けのインターフェイスを通して結びつけます。このインターフェイスは異なるブラウザバックエンドを透過的に使えるようにし、クロスブラウザ・クロスプラットフォームの自動化を可能にします。

driverのより詳しい資料は[Driver Idiosyncrasies]({{< ref "/driver_idiosyncrasies/_index.md" >}})にあります。
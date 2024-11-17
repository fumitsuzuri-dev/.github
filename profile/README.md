![バナー](/images/banner.png)

Fumitsuzuriはファイルをアップロードすることで簡単に小説をプレビューできる小説執筆・プレビューサービスです。小説家・執筆者にぴったりのサービスです。まだまだ機能不足ではありますが、今後も継続的に開発を行っていき、必要な機能を充実させていきます。

## 主な機能
Fumitsuzuriの主な機能は以下の通りです。
### ファイルのアップロード
Markdownファイルのみファイルを選択・ドラッグアンドドロップを行えます。(2024/11/6現在)

その他のファイルを選択した場合、エラー文が表示されます。Markdownファイル内のYaml Headerには以下のような記述を行うことができます

```md
---
title: "" // 小説のタイトル
author: "" // 著者名
summary: "" // あらすじ
price: 0 // 価格
edition: 0 // 更新回数
---
小説のコンテンツ
```

![ドラッグアンドドロップ](/images/draganddrop.png)

### 小説の表紙・裏表紙の編集
編集できるのは以下のつ
- 小説のタイトル
- 著者名
- あらすじ
- 価格
- JANコード
- 編集回数

![編集](/images/edit.gif)

### 執筆した小説の読書
▶️ボタンをクリックすると小説の生成が開始されて、終了後実際に読めるUIが表示されます。
![読書](/images/read.gif)

### コンタクト
XのDMにメッセージしてください<br />
[@TsuzuriF68323](https://x.com/TsuzuriF68323)
# WorkTimer

作業時間を記録・管理するWindowsアプリケーションです。  
SQLiteによるローカル保存に対応し、オフライン環境でも利用可能です。

---

## 🚀 主な機能

- タスクの追加・削除
- 作業開始・終了時間の記録
- 選択履歴の表示
- SQLiteによるローカル保存
- 作業時間のAES暗号化による秘匿性確保
- 難読化済みの実行ファイルによるセキュリティ強化

![WorkTimer画面](https://github.com/kazuhiroyamamoto4-maker/task-timer-appl/blob/main/スクリーンショット%202025-09-15%20203519.png?raw=true)

---

## 📌 バージョン情報

- 現在のバージョン：v0.4.0（プレリリース）
- 作業時間の履歴表示機能は現在非公開です
- 今後のバージョンで段階的に公開予定です

---

## 🛠 動作環境

- Windows 10 / 11（.NET Framework 4.8 以上）
- SQLite データベースファイル（WorkTimerDB.db）を同梱

---

## 🔐 セキュリティと暗号化

- 作業開始・終了時間は AES 方式で暗号化して保存  
- 暗号化キーはアプリ内に安全に埋め込み済み  
- Dotfuscator Community Edition による難読化処理を適用済み

---

## 📄 ライセンス情報

本アプリは `System.Data.SQLite.dll` を使用しています。  
この DLL はパブリックドメインとして公開されており、商用・非商用問わず自由に使用可能です。  
Ms-PL ライセンスが適用される LINQ / EF6 コンポーネントは使用していません。

詳細：[System.Data.SQLite ライセンス情報](https://system.data.sqlite.org/home/doc/trunk/www/copyright.wiki)

---

## 👤 開発者情報

- 開発者：Kazuhiro Yamamoto（個人開発）
- GitHub：[kazuhiroyamamoto4-maker](https://github.com/kazuhiro

---

## 📬 お問い合わせ

- GitHub の [Issues](https://github.com/kazuhiroyamamoto4-maker/task-timer-appl/issues) にてご連絡ください  
- 使い方の共有やアイデア交換は [Discussions](https://github.com/kazuhiroyamamoto4-maker/task-timer-appl/discussions) へ

---

## ⚠️ 免責事項

本アプリは個人開発によるものであり、利用は自己責任でお願いします。  
データの損失や不具合に関して、開発者は一切の責任を負いません。

---

## 📦 配布ファイル構成

```plaintext
WorkTimer_v0.2.0.zip
├── WorkTimer.exe
├── WorkTimer.exe.config
├── System.Data.SQLite.dll
├── System.Data.SQLite.dll.config
├── WorkTimerDB.db
└── ReadMe.txt
```

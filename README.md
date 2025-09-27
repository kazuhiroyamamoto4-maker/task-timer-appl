# JobTimeLogger(旧WorkTimer)

作業時間を記録・管理するWindowsアプリケーションです。  
履歴はローカルに保存されるので、オフライン環境でも利用可能です。

---

## 🚀 主な機能

- タスクの追加・削除
- 作業開始・終了時間の記録、編集
- 作業履歴の表示
- れ行履歴はローカル保存
- 作業時間のAES暗号化による秘匿性確保
- 難読化済みの実行ファイルによるセキュリティ強化

---

## スクリーンショット

以下は「タスク時間計測」画面の例です。  
作業開始・終了時間、作業内容が秒単位で記録され、履歴として表示されます。

<img width="781" height="386" alt="メイン画面（記録中）" src="https://github.com/user-attachments/assets/c569fd1b-73c7-4ebe-96aa-5c48c52453d9" />

---

## 使い方の流れ

1. アプリを起動すると、作業未確定状態になります  
2. 「ACT」列のチェックを入れて開始ボタンクリックで記録か開始されて、履歴が自動記録されます
3. 作業時間は編集タブで編集可能です
4. 履歴ボタンクリックで履歴画面が表示され、過去のタスクの作業時間を閲覧することができます

---

## インストール方法
1. JobTimeLogger_vx.x.x.zip をダウンロード
2. zipを展開し、`JobTimeLogger.exe` を実行

---

## 📌 バージョン情報

- 現在のバージョン：v0.5.4（プレリリース）
- 作業時間の履歴のCSV出力機能は現在非公開です
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
- GitHub：[kazuhiroyamamoto4-maker](https://github.com/kazuhiroyamamoto4-maker)

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
JobTimeLogger_vx.x.x.zip
├── JobTimeLogger.exe
├── JobTimeLogger.exe.config
├── System.Data.SQLite.dll
├── System.Data.SQLite.dll.config
├── WorkTimerDB.db
└── ReadMe.txt
```

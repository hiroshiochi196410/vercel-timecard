# タイムカード管理システム

双葉三共株式会社の就業規則に準拠したタイムカード管理システム

## 機能

- ✅ 勤怠記録の入力・編集
- ✅ 有休管理
- ✅ 残業計算（管理職・一般従業員）
- ✅ 給与計算
- ✅ 会社カレンダー管理
- ✅ 統計・集計機能
- ✅ CSV入出力

## デプロイ方法

### Vercelでデプロイ

1. このリポジトリをGitHubにプッシュ
2. [Vercel](https://vercel.com)にログイン
3. "Import Project"をクリック
4. GitHubリポジトリを選択
5. "Deploy"をクリック

または、Vercel CLIを使用：

```bash
# Vercel CLIをインストール
npm i -g vercel

# デプロイ
vercel
```

## ローカルで実行

```bash
# このディレクトリで
python -m http.server 8000

# ブラウザで開く
http://localhost:8000
```

## 注意事項

- データはブラウザのLocalStorageに保存されます
- バックアップは定期的にCSVエクスポートしてください

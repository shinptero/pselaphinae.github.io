# Pselaphinae of Japan — アリヅカムシ亜科

日本産アリヅカムシ亜科（Pselaphinae）の分類・形態・生態に関する学術情報サイト。

## サイトの構造

```
pselaphinae-site/
├── index.html        ← トップページ
├── taxonomy.html     ← 分類体系（6上族の概要）
├── morphology.html   ← 形態的特徴
├── ecology.html      ← 生態と生物間相互作用
├── japan.html        ← 日本産種（代表属一覧）
├── methods.html      ← 採集・調査法
├── literature.html   ← 主要文献
├── css/
│   └── style.css     ← デザイン（全ページ共通）
└── README.md         ← この説明書
```

## 公開手順（GitHub Pages）

### ステップ1：リポジトリを作る
1. GitHubにログイン → 右上の「+」→「New repository」
2. リポジトリ名: 任意（例: `pselaphinae`）
3. Public を選択
4. 「Create repository」をクリック

### ステップ2：ファイルをアップロードする
1. 作成されたリポジトリのページで「アップロードする既存のファイル」をクリック
2. このフォルダの中身すべてをドラッグ＆ドロップ
   - index.html、taxonomy.html、morphology.html、ecology.html、japan.html、methods.html、literature.html
   - css フォルダ（中の style.css ごと）
3. 「Commit changes」をクリック

### ステップ3：GitHub Pages を有効化する
1. リポジトリの「Settings」タブ → 左メニューの「Pages」
2. Source が「Deploy from a branch」、Branch が「main」になっていることを確認
3. 「Save」をクリック
4. 数分後に `https://ユーザー名.github.io/リポジトリ名/` で公開される

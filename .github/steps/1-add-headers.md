<!--
<<< 著者注: ステップ 1 >>>
コースのステップを3～5つ選択してください。
最初のステップは常に最も難しいので、簡単なものを選びましょう。
詳しい説明については、docs.github.com へのリンクを参照してください。
ステップを確認するには、新しいタブを開くようにユーザーに促してください。
-->

## ステップ 1: ヘッダーを追加する

_「Markdown を使ったコミュニケーション」へようこそ！ :wave:_

**Markdown とは_？** Markdown は、GitHub 上でコミュニケーションを行うための [軽量構文](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) です。テキストに書式を設定して、見出し、リスト、**太字**、_斜体_、表など、さまざまなスタイルを追加できます。 GitHub のほとんどの場所で Markdown を使用できます。

- [イシュー](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues)、[プルリクエスト](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)、[ディスカッション](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions) へのコメント
- 拡張子が `.md` または `.markdown` のファイル
- [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)内のテキストスニペットの共有

**_ヘッダー_とは？** ヘッダーとは、セクションの先頭に表示される大きめのテキストのことです。サイズは6種類あります。

### 例

```md
# これは `<h1>` ヘッダーで、最も大きいです。

## これは `<h2>` ヘッダーです。

##### これは `<h6>` ヘッダーで、最も小さいです。
```

#### 表示例

# これは `<h1>` ヘッダーで、最も大きいです。

## これは `<h2>` ヘッダーです。

##### これは `<h6>` ヘッダーで、最も小さいです。

### :keyboard: アクティビティ: ヘッダーを含むファイルを編集する

1. 新しいブラウザタブを開き、このタブの指示を読みながら、2つ目のタブの手順を実行します。
1. **pull requests** タブを開きます。
1. **New pull request** をクリックし、比較するブランチとして `base: main` と `compare: start-markdown` を選択します。
1. **[Create pull request]** をクリックします。
1. このプルリクエストで、[**Files Changed**] タブに移動します。空のファイル `index.md` が作成されています。
1. `index.md` のファイルビューの右上隅にある 3 つの点が並んだ **...** メニューから [**Edit file**] を選択します。
1. [**Edit file**] タブで、任意のコンテンツの前に `#` とそれに続く **スペース** を追加して、H1 ヘッダーにします。1～6 個の `#` 文字とそれに続く **スペース** を使用して、さらにヘッダーを追加できます。
1. 新しいコンテンツの上にある [**Preview**] をクリックします。
1. ページの下部に、ファイルに加えた変更を説明する、短くてわかりやすいコミットメッセージを入力します。
1. [**Commit changes**] をクリックします。
1. 約 20 秒待ってから、このページ（手順に従っているページ）を更新します。 [GitHub Actions](https://docs.github.com/en/actions) は次のステップに自動的に更新されます。
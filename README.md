# Welcome to TowColumnsSlide

## Feature
- You can creat TowColumnsSlide with markdown, HTML/CSS and Marp.

With markdown, you can usually only create articles in one column,
Using the sample HTML and Marp, you can create a two-columns slide.

You can arrange program code and its execution results side by side, or images side by side.
Use the PDF output for programming training and documentation.

markdownでは通常1カラムでしか記事を作ることが出来ませんが、
サンプルのHTMLとMarpを使うことで2カラムのスライドを作ることが出来ます。

プログラムコードとその実行結果を横に並べたり、画像を横に並べたりすることができます。
PDF出力してプログラミングの研修や資料作成にお使いください。

## How to use
1. Open the VScode
1. Install "Marp for VS Code"  
[https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

1. Open and Edit the TwoColumnsSlide.md file in VScode
1. To add two columns, write the following HTML

---

1. VScodeを開きます
1. 拡張機能である"Marp for VS Code"をインストールします  
[https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

1. TwoColumnsSlide.md ファイルを開いて編集します。
1. 2カラムの表示には、以下のHTMLを記述します。

---

```md
<div class="column-one">
<div class="column-left">

### LeftHeadLine

 <!-- Content -->

</div>

<div class="column-right">

### RightHeadLine

<!-- Content -->

</div>
</div>
```

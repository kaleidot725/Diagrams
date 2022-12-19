# diagrams.net 管理ルール

本リポジトリでは以下の特徴を持つ[diagrams.net](https://www.diagrams.net)と呼ばれる、  
グラフ描画ソフトウェアの成果物をGitHub上で管理するルールをまとめます。

- diagrams.netはHTML5とJavaScriptで開発されたグラフ描画ソフトウェアです。
- diagrams.netではフローチャート、ワイヤーフレーム、UML、ネットワークなどの図形を作成できます。
- diagrams.netはWebアプリとしてオンラインで、Linux・macOS・Windowsはデスクトップアプリとしてオフラインで利用できます。

![image](https://user-images.githubusercontent.com/23740796/197519607-ea756bd1-ac27-4719-8ae8-4990a258f01f.png)

## 編集環境

以下に記載するソフトウェア＆プラグインでdiagrams.netのファイルを編集します。なのでソフトウェア＆プラグインを各自でインストールしてください。
※ローカル環境の編集環境を構築したくない場合、GitHubで'.'キーで起動できるVSCodeを利用して構築しても問題ありません。

| 名称 | 説明 |
| --- | ---- |
| [VSCode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/) | diagrams.netのファイルをVSCode編集するエディタ |
| [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) | VSCodeでdiagrams.netのファイルを編集するために必要な拡張プラグイン |

## 編集ルール

### svgファイルで保存すること

#### 理由

- GitHubでsvgファイルの差分を表示して、変更点を追いやすくするため

#### 手順

### 用紙サイズを設定すること

#### 理由

- GitHubのsvgファイルの差分を表示する際に、画像サイズを揃えて変更点を追いやすくするため

#### 手順

### 背景を設定すること

#### 理由

- GitHubやVSCodeではライトテーマとダークテーマの切り替えが可能です。背景が透明のままだと特定のテーマでの可視性を損ねるので背景を設定する。

#### 手順

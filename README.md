# privacy-policy

スマホアプリ・Webアプリ向けの **プライバシーポリシー置き場** です。
各アプリのプライバシーポリシーを HTML で公開し、[GitHub Pages](https://mshige1979.github.io/privacy-policy/) でホスティングしています。

App Store / Google Play やアプリ内のリンク先として、ここで公開している URL を利用できます。

## 公開ポリシー一覧

| アプリ | 説明 | 公開ページ | ソース |
| --- | --- | --- | --- |
| 血圧管理アプリ | 血圧記録・服薬リマインダーアプリ向け。端末内保存／HealthKit 連携について記載。 | https://mshige1979.github.io/privacy-policy/bp-manager-policy/ | [bp-manager-policy/index.html](bp-manager-policy/index.html) |
| WarikanApp（割り勘アプリ） | 割り勘計算アプリ向け。データは端末内のみに保存し、外部送信・第三者提供なし。 | https://mshige1979.github.io/privacy-policy/warikan-app-policy/ | [warikan-app-policy/index.html](warikan-app-policy/index.html) |
| ステージホッパー | ゲームアプリ向け。情報収集なし・広告識別子の取得なし・第三者提供なし。<br>[サポートページ](https://mshige1979.github.io/privacy-policy/stage-hopper-policy/support/)あり。 | https://mshige1979.github.io/privacy-policy/stage-hopper-policy/ | [stage-hopper-policy/index.html](stage-hopper-policy/index.html)<br>[support/index.html](stage-hopper-policy/support/index.html) |

## 仕組み

- `main` ブランチのルート (`/`) を GitHub Pages で公開しています。
- 各アプリごとにディレクトリを作り、その中に `index.html` を置きます。
- ディレクトリ名がそのまま公開 URL のパスになります。
  - 例: `bp-manager-policy/index.html` → `https://mshige1979.github.io/privacy-policy/bp-manager-policy/`

## 新しいポリシーを追加する手順

1. アプリ用のディレクトリを作成する（例: `my-app-policy/`）。
2. その中に `index.html` を作成し、プライバシーポリシーを記述する。
3. `main` ブランチに push する。数分後に GitHub Pages へ反映されます。
4. この README の「公開ポリシー一覧」に行を追加する。

## お問い合わせ

メール: mshige1979@ryuouen.net

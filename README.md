# docker-react-yarn-javascript
## 概要
- `javascript`を使用して`yarn`で`react`を起動する`dockerfile`と手順を記したリポジトリ。
- 詳細な使用方法は、以下のQiitaか個人ブログを参照。
	1. [【環境構築】DockerでReactをyarnを使用して作成&起動する方法（JavaScript編）](https://qiita.com/takuma-1234/items/02d5683ea54c3c16b38c)
	2. [【環境構築】DockerでReactをyarnを使用して作成&起動する方法（JavaScript編）](https://takuma-tech.com/2023/04/21/574/)
    
### Docker起動コマンド
```bash:
$docker-compose up -d --build
```
### react起動までの基本手順コマンド
- `vscode`でコンテナ内部に入る。
- `vscode`でターミナルを起動し作業ディレクトリに移動する。
```bash:
$cd ../react_yarn_javascript_workdir/
```
- `react`アプリの雛形を作成
```bash:
$yarn create react-app react_yarn_javascript
```
- 作成されたディレクトリへ移動
```bash:
$cd react_yarn_javascript/
```
- `react`を起動する。
```bash:
$yarn start
```
#### 参考資料

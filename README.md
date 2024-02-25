# Chainlink-Prediction-Sample
ChainlinkAutomationとChainlink Functionを利用したバスケットボールの試合結果を取得するサンプルプログラム用リポジトリです。

## デプロイしたコントラクト

[]()

## 初期設定

- nba-api

  `.env`ファイルを作成し、[https://api-sports.io/](https://api-sports.io/)にログインする。  
  そこでAPI KEYを取得する。

  ```txt
  RAPID_API_KEY=
  ```

## 動かし方

- インストール

  ```bash
  yarn
  ```

- NBAの試合の結果を取得するAPI

  ```bash
  yarn getGameData
  ```

  実行結果例

  ```bash
  yarn run v1.22.19
  $ ts-node ./src/index.ts
  =================================== [Start] =================================== 
  vistors win
  vistors win
  home win
  home win
  home win
  home win
  vistors win
  home win
  home win
  home win
  =================================== [End] =================================== 
  ✨  Done in 2.34s.
  ```


### 参考文献
1. [API Sports document](https://api-sports.io/documentation/nba/v2)
2. [API Sports](https://api-sports.io/)
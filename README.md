# atcoder_sample

# 準備

## atCoder のアカウント作成

    こちらから

    https://atcoder.jp/?lang=ja

## online-judge-tools のインストール

インストール
```
    pip install online-judge-tools
```
ログイン
```
    oj login -u ${USERNAME} -p ${PASSWORD} "https://atcoder.jp/"
```
確認
```
    oj login --check "https://atcoder.jp/"
```

## atcoder-cli のインストール

インストール
```
    npm install -g atcoder-cli
```
ログイン
```
    acc login
```
確認
```
    acc session
```

## 使い方

問題取得
```
    acc new ${probrem_id}
```
フォルダに移動
```
    cd ${probrem_id}/a
```
テンプレートコピー（事前にエイリアス設定必要、任意の名称で）
```
    kcp
```
カレントフォルダでテスト実行（事前にエイリアス設定必要、任意の名称で）
```
    ktest
```
カレントフォルダで提出（事前にエイリアス設定必要、任意の名称で）
```
    ksub
```
次の問題取得
```
    cd .. && acc add b（問題を表すアルファベット）
```

# python_app
test

## コード説明

### main.py
- Flaskを使ったWebアプリケーション本体です。
- `/` にアクセスすると `templates/index.html` を返します。

### templates/index.html
- HTML5のCanvasとJavaScriptで、矢印キーで四角形を移動できるインタラクティブなページです。
- キーボードイベントで上下左右にオブジェクトを移動します。

### test_main.py
- Flaskアプリのテストコードです。
- `/` へのアクセスが200 OKであること、HTMLにCanvas要素が含まれることを確認します。

## テストの実行方法

```bash
python -m unittest test_main.py
```

テストが成功すれば、アプリケーションが正しく動作していることが確認できます。

## プログラムの実行方法

1. 依存パッケージのインストール

```bash
pip install flask
```

2. アプリケーションの起動

```bash
python main.py
```

3. ブラウザで `http://localhost:5000` にアクセスしてください。

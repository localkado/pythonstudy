# Python学習
## PC環境
* macOS mojave
* Python version 3.7.1
## 環境構築
### Pythonをインストール → 仮想環境構築
* 参考サイト
    * https://basicincome30.com/python-install-mac
    * エラー解決参考サイト
        * https://qiita.com/kasama123/items/ab9eea7a9c42e3941a14

## 仮想環境の有効化・Pythonファイル作成(Hello World)・無効化

~~~
# 仮想環境py3envを有効化する
$ cd /Users/(ユーザ名)/python_env; pwd
$ source py3env/bin/activate

# Pythonを使う
## Hello Worldファイル作成
* http://www.tohoho-web.com/python/syntax.html
## Hello World実行
$ cd ~/python_env/py3env/include/
$ python helloworld.py

# 仮想環境py3envを無効化する
(py3env) $ deactivate 
~~~

## Pythonでwebアプリ
* 参考サイト
    * https://web-camp.io/magazine/archives/12998
        * https://qiita.com/okhrn/items/4d3c74563154f191ba16

### Pythonでローカルwebサーバ起動

~~~
$ python -m http.server 8000
~~~

* 起動できたら以下URLにアクセスし、ディレクトリ構成が確認できること
    * http://localhost:8000
* WEBサーバでHTMLを表示する
    * pythonstudy ディレクトリにindex.htmlを配置し、以下にアクセスできwebページが表示されること
    * http://localhost:8000/pythonstudy/index.html

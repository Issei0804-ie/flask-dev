# 使い方

## ダウンロード方法

```
$ git clone https://github.com/Issei0804-ie/flask-dev.git
$ cd flask-dev 
```

## docker の立ち上げ方

```
$ docker-copomse up 
```

## docker の落とし方

```
$ docker-compose down
```

## example

```
$ docker-compose up
Recreating pyt ... done
Attaching to pyt
pyt   | Collecting click==7.1.1
pyt   |   Downloading click-7.1.1-py2.py3-none-any.whl (82 kB)
     |████████████████████████████████| 82 kB 85 kB/s
pyt   | Collecting Flask==1.1.2
pyt   |   Downloading Flask-1.1.2-py2.py3-none-any.whl (94 kB)
     |████████████████████████████████| 94 kB 105 kB/s
pyt   | Collecting itsdangerous==1.1.0
pyt   |   Downloading itsdangerous-1.1.0-py2.py3-none-any.whl (16 kB)
pyt   | Collecting Jinja2==2.11.1
pyt   |   Downloading Jinja2-2.11.1-py2.py3-none-any.whl (126 kB)
     |████████████████████████████████| 126 kB 84 kB/s
pyt   | Collecting MarkupSafe==1.1.1
pyt   |   Downloading MarkupSafe-1.1.1-cp37-cp37m-manylinux1_x86_64.whl (27 kB)
pyt   | Collecting Werkzeug==1.0.1
pyt   |   Downloading Werkzeug-1.0.1-py2.py3-none-any.whl (298 kB)
     |████████████████████████████████| 298 kB 101 kB/s
pyt   | Installing collected packages: click, Werkzeug, MarkupSafe, Jinja2, itsdangerous, Flask
pyt   | Successfully installed Flask-1.1.2 Jinja2-2.11.1 MarkupSafe-1.1.1 Werkzeug-1.0.1 click-7.1.1 itsdangerous-1.1.0
pyt   |  * Serving Flask app "main" (lazy loading)
pyt   |  * Environment: production
pyt   |    WARNING: This is a development server. Do not use it in a production deployment.
pyt   |    Use a production WSGI server instead.
pyt   |  * Debug mode: on
pyt   |  * Running on http://0.0.0.0:80/ (Press CTRL+C to quit)
pyt   |  * Restarting with stat
pyt   |  * Debugger is active!
pyt   |  * Debugger PIN: 644-017-621

------------------------------------
(別のターミナルから下記のコマンドを入力)
$ curl localhost:80
Hello, World!%
------------------------------------
```

基本的に docker を立ち上げて動作確認、ソースを書き加えたら docker を落とす。　動かしたい時はまた立ち上げる...の繰り返しです。

example では curl コマンドを使っているが、safari等でも動くはず（未確認)



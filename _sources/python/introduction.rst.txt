Python導入手順書
====================

Pythonをインストールし、Pythonのコードを実行できるようにするまでの手順を示します。

.. contents:: 目次
   :depth: 2

----

1. インストーラを取得する
----------------------------

Pythonの実行環境を得るため、公式ページからインストーラを取得します。

**1. Pythonの公式ページにアクセスする。**

    https://www.python.org/

    .. image:: img/introduction_web1.png
       :align: center

**2-1. (32bit版をインストールする場合) Downloads > Windows > Python 3.x.x ボタンをクリックする。**

    .. image:: img/introduction_web2_1.png
       :align: center

    →32bit版のインストーラがダウンロードされます。

**2-2. (64bit版をインストールする場合)**

    **1. Downloads > Windows をクリックする。**

    .. image:: img/introduction_web2_2_1.png
       :align: center

    **2. Latest Python 3 Release - Python 3.x.x をクリックする。**

    .. image:: img/introduction_web2_2_2.png
       :align: center

    **3. Windows x86-64 web-based installer をクリックする。※**

    .. image:: img/introduction_web2_2_3.png
       :align: center

    →64bit版のインストーラがダウンロードされます。

    ※Windows x86-64 executable installer を選択しても問題ありません。

----

2. インストールを実行する
----------------------------

インストーラを起動し、Pythonのインストールを実行してください。

**1. インストーラを起動する。**

    .. image:: img/introduction_install1.png
       :align: center
       :width: 400

**2. Add Python 3.x to PATH にチェックを入れ、Install Now をクリックする。**

    .. image:: img/introduction_install2.png
       :align: center

    →インストールが開始されます。インストールが完了すると、Closeボタンのある画面に遷移します。

**3. Closeボタンをクリックする。**

    .. image:: img/introduction_install3.png
       :align: center

    →インストーラが終了します。

----

3. インストールが成功しているか確認する
----------------------------------------

Pythonのインストールが成功しているか確認します。

**1. コマンドプロンプトを起動する。**

**2. 以下のコマンドを入力する。**

    ::

        $ python --version

    →Python 3.x.x と表示されればインストール成功です。

    .. image:: img/introduction_check.png
       :align: center
       :width: 400

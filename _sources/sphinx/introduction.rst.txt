Sphinx導入手順書
====================

Sphinxをインストールし、ドキュメントを作成できるようにするまでの手順を示します。

.. contents:: 目次
   :depth: 2

----

1. Pythonをインストールする
----------------------------

Sphinxのインストールおよび実行には、Pythonが必要です。

:doc:`../python/introduction` を参考にPythonを導入してください。

----

2. Sphinxをインストールする
----------------------------

Pythonを導入すると、pipコマンド(Pythonのパッケージ管理ツール)が実行できるようになります。

コマンドプロンプトを起動し、以下のコマンドを入力してください。

::

    $ pip install -U sphinx

→Sphinxのインストールが開始されます。

----

3. インストールが成功しているか確認する
----------------------------------------

コマンドプロンプトに以下のコマンドを入力してください。

::

    $ sphinx-build --version

→sphinx-build x.x.x と表示されたら成功です。

.. image:: img/introduction_check.png
   :align: center
   :width: 400

----

参考資料：Sphinxのインストールマニュアル
https://www.sphinx-doc.org/ja/master/usage/installation.html

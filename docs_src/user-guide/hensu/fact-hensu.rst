.. _fact-hensu:

##################################################
ファクト変数
##################################################
- 各管理対象ノードのシステム情報を格納した変数
- プレイの実行の最初に管理対象ノードごとシステム情報を収集し格納する
- ファクト変数の定義は不要

.. _fact-hensu-timing:

**************************************************
収集するタイミング
**************************************************
プレイの最初に次のタスクを実行したときにファクト変数を収集する。

.. code-block:: none

   TASK [Gathering Facts] *******************************************************************************************************************************
   ok: [lithium]
   ok: [helium]

targets セクションで ``gather_facts: no`` を指定したとき、ファクト変数は収集しない。

.. _fact-hensu-kakunin:

**************************************************
ファクト変数の確認
**************************************************
アドホックコマンドで ``ansible.builtin.setup`` モジュールを実行するとファクト変数が確認できます。以下は管理対象ノード hydrogen のファクト変数です。

.. literalinclude:: ./log/setup.log
   :language: none

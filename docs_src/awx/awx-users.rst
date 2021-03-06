.. _awx-users:

##################################################
ユーザー : Users
##################################################
AWX サーバーに管理者（ admin アカウント）だけが登録されているので作業用のユーザーを登録します。システム管理者権限を持つユーザーが未登録の場合、 admin アカウントで実施します。

#. :guilabel:`ユーザー` をクリック

   .. image:: img/2021-07-23_19h01_45.png

#. :guilabel:`追加` をクリック

   .. image:: img/2021-07-23_19h01_55.png
      :scale: 65%

#. 次の値を入力

   .. list-table:: 
      :header-rows: 1
      :widths: 1, 4

      * - 項目
        - 入力する値
      * - ユーザー名
        - ユーザーアカウント名
      * - メール
        - ユーザーのメールアドレス
      * - パスワード
        - ユーザーアカウントのパスワード
      * - パスワードの確認
        - 「パスワード」と同じ値
      * - 名
        - ユーザーの姓名の「名」
      * - 姓
        - ユーザーの姓名の「姓」
      * - 組織
        - 「 :ref:`awx-organizations` 」で登録した組織を選択
      * - ユーザータイプ
        - 「標準ユーザー」、「システム監査者」、「システム管理者」から選択

   .. list-table:: ユーザータイプ
      :header-rows: 1
      :widths: 1, 4

      * - ユーザータイプ
        - 説明
      * - 標準ユーザー
        - 適切な役割や権限が与えられたリソース（インベントリ、プロジェクト、ジョブテンプレートなど）に限定したアクセス権を持つ
      * - システム監査者
        - AWX 内のすべてのオブジェクトに対する読み取り権限を持つ
      * - システム管理者
        - AWX の管理者であり、すべての権限を持つ

   .. image:: img/2021-07-23_19h02_42.png
      :scale: 65%

#. :guilabel:`保存`

   .. image:: img/2021-07-23_19h02_52.png
      :scale: 65%

#. :guilabel:`ユーザーに戻る` をクリック

   .. image:: img/2021-07-23_19h03_33.png
      :scale: 65%

#. 登録したユーザーを確認

   .. image:: img/2021-07-23_19h03_49.png
      :scale: 65%

#. もう 1 件、ユーザーを登録した状態

   .. image:: img/2021-07-23_19h05_00.png
      :scale: 65%

.. _awx-deploy:

##################################################
AWX をデプロイ
##################################################
CentOS 8.4 に AWX 19.2.2 をインストールします。

.. note::

   - AWX をデプロイするにあたり、下記のサイトを参考にしました。ありがとうございました。

      - `Install AWX on K3S <https://www.bitbull.ch/wiki/index.php/Install_AWX_on_K3S>`_
      - `ansible/awx-operator - GitHub <https://github.com/ansible/awx-operator>`_

   - インストール前に（内部）DNS サーバーや :file:`hosts` ファイルなどで **awx.example.jp** の名前解決ができるようにしてください。

.. include:: ./awx-deploy-command.txt
.. include:: ./awx-deploy-log.txt
.. include:: ./awx-deploy-login.txt

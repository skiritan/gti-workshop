# 3. 探索結果の確認

## Technologies の確認

続いて、ASMが発見したTechnologies (=Entitiesで利用されているアプリケーションやサービス）を確認します。

１．画面上部の`Technologies` タブをクリックすると、下記画面が表示されます。

![image-20250311190749773](images/image-20250311190749773.png)



２．左ペインのFiltersを選択することで、表示するTechnologies をフィルタすることができます。**web_server** を選択して、Webアプリケーションに関連するテクノロジーを確認します。デモ環境では、Apache HTTP Server や Nginx などのソフトウェアとそのバージョンが確認できます。

![image-20250311190831189](images/image-20250311190831189.png)



３．Technologyを１つクリックすると、そのテクノロジーが利用さているEntities が確認できます。

![image-20250311190928344](images/image-20250311190928344.png)

４．Technologies 画面にもどり、他にどのようなテクノロジーがあるかを確認します。 Webサーバのアプリケーションだけではなく、プラグインも識別できています。

![image-20250311191434771](images/image-20250311191434771.png)



５．左ペインのFiltersの下にある、Vendors の項目ではベンダー視点での確認ができます。各項目の数字を確認し、SaaSサービスやロードバランサーのベンダーなどの内容を確認してみてください。



![image-20250311191453551](images/image-20250311191453551.png)

６．最後に、先ほどダッシュボードで確認した「古い Openssh アプリケーション」を確認します。画面右上の検索ウィンドウに Openssl と入力すると、バージョン情報とともにアプリケーションが表示されます。このアプリケーションをクリックすると該当する Entity が表示されます。このように、古いモジュールやライブラリを利用しているIT資産を調査することができます。

![image-20250311191529501](images/image-20250311191529501.png)

Technologies の確認は以上です。[次のステップ](../034-check-issues) で Issues について確認していきます。

  


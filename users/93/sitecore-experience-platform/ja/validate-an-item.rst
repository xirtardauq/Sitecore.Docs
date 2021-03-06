#######################################
アイテムを検証する
#######################################

アイテムをパブリッシュする前に、アイテムのチェックをいくつか実行して、パブリッシュできるようにしておきましょう。

**************************************
ウェブページのマークアップをチェック
**************************************

すべての HTML フィールドを W3C HTML Validator に送ることで、ウェブページのマークアップをチェックすることができます。

すべての HTML フィールドを W3C HTML Validator に送信するには、以下の手順に従います。

1. コンテンツエディタまたはエクスペリエンスエディタで、該当するアイテムまたはページに移動します。
2. ウェブページのマークアップをチェックするには。
   
   * コンテンツ エディタの [レビュー] タブの [プルーフィング] グループで [マークアップ] をクリックします。
   * エクスペリエンス エディタの [ホーム] タブの [検証] グループで [マークアップ] をクリックします。

チェックの結果がウェブページ上に表示され、詳細な注意事項や潜在的な問題が表示されます。

**********************
アイテムを検証する
**********************

Sitecoreのフィールドバリデータは、アイテム、特定のフィールドタイプ、またはアイテムの特定のフィールドに適用することができるユーザー入力バリデータのセットです。

コンテンツエディタは、フィールドを自動的にバリデーションします。検証エラーや警告が含まれるフィールドがある場合、該当するフィールドの左側に赤いバーが表示され、バリデータバーのアイコンはエラーの種類に応じて赤または黄色に変わります。エラーの詳細を見るには、バリデータバーの個々のアイコンの上にマウスを移動してください。

.. image:: images/15ed64a1e515ac.png
   :align: center
   :width: 400px
   :alt: アイテムを検証する

Experience Editorでは、Saveをクリックするたびにページのバリデーションチェックを実行するようにSitecoreを設定することができます。

* エクスペリエンス エディタ リボンの [表示] タブの [有効化] グループで [フィールドの検証] をクリックします。

このようにして、ページに変更を加えて保存をクリックすると、ページ上のすべてのフィールドに対してバリデーションチェックが実行されます。検証の警告やエラーを含むフィールドがある場合は、警告やエラーの種類に応じて色分けされた点線でフィールドが強調表示され、詳細を示す通知が表示されます。

.. image:: images/15ed64a1e558f1.png
   :align: center
   :width: 400px
   :alt: アイテムを検証する

コンテンツ エディタとエクスペリエンス エディタでは、検証テストを手動で実行し、検証結果ダイアログ ボックスに検証テストの詳細を表示できます。

アイテムで検証テストを手動で実行するには

1. コンテンツ エディタまたはエクスペリエンス エディタで、該当するアイテムまたはページに移動します。
2. アイテムまたはページで検証テストを実行するには

   * [コンテンツ エディタ] の [レビュー] タブの [検証] グループで、[検証] をクリックします。
   * エクスペリエンス エディタの [ホーム] タブの [検証] グループで [検証] をクリックします。

[検証結果] ダイアログ ボックスには、検証結果の概要と変更の提案が表示されます。可能な値は次のとおりです。

* 有効 (緑) - アクションは必要ありません。
* 提案 (黄色) - 問題を調べて、アクションが必要かどうかを判断します。
* 警告(オレンジ) - 問題に対処します。
* エラー (赤) - これはエラーです。
* クリティカルエラー (赤) - 変更を保存する前に警告が表示されます。
* 致命的なエラー (赤) - エラーが修正される前にアイテムを保存することはできません。


.. image:: images/15ed64a1e5aa39.png
   :align: center
   :width: 400px
   :alt: アイテムを検証する


.. tip:: 英語版 https://doc.sitecore.com/users/93/sitecore-experience-platform/en/preview-a-webpage.html




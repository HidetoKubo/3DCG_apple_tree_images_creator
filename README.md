# リンゴ樹木3DCG画像 自動生成システム
# 概要
これは、深層学習(Mask R-CNN)によって、葉に隠れたリンゴの形状を検出するため、3DCGのリンゴ樹木の学習データ画像を自動生成するシステムです。
BlenderとPythonを用いて、リンゴの3DCG樹木画像と葉に隠れたリンゴの教師データを生成することができます。

具体的には、以下のような手順で学習データが生成できます。
1. Blender (2.93) 内でスクリプトを実行し、リンゴの3DCG樹木画像とリンゴ・樹木の深度マップを生成
2. Pythonファイルを実行し、リンゴ・樹木の深度マップを基に、葉に隠れた果実の教師データを生成

「Apple_images_creator.Blender」というBlenderファイルのスクリプトを実行することで、リンゴの3DCG樹木画像、樹木のデプスマップ、果実のデプスマップが生成されます。
また、「mask_images_creator.py」というPythonファイルを実行することで、「seisei.json」というマスクデータの出力ファイルが生成されます。


# デモ動画

# 生成できる画像
![Cycles](https://user-images.githubusercontent.com/98790632/154609642-a3ea4864-92b6-466e-af3c-151c2f581357.png)

![Appleimage](https://user-images.githubusercontent.com/98790632/155022781-73bf5893-a1ea-49f1-9b4a-0880e1da95bb.png)

# 使い方 動画

# テスト環境
Windows10

# 使用技術、サービス
Blender(2.93), Python

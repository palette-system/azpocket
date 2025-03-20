# ビルドガイド

## １．用意が必要な物

| 名前 | 詳細 | 個数 |
| --- | --- | --- |
| XIAO ESP32C6 | <a href="https://akizukidenshi.com/catalog/g/g129481/" target="_blank">秋月電子リンク</a> | 1 |
| バッテリー | DTP401525(PHR) 110mAh<br>リチウムイオンポリマー電池 3.7V 110mAh<br> <a href="https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-53KN" target="_blank">千石電商リンク</a> | 1 |
| 木工用ボンド | コクヨ KOKUYO ボンド 木工用速乾<br><a href="https://www.yodobashi.com/product/100000001001555306/" target="_blank">ヨドバシカメラリンク</a> | 1 |

<br><br>

## ２．入っている物
![in_parts1](/docs/img/make_01.jpg)
![in_parts2](/docs/img/make_02.jpg)

| 名前 | 詳細 | 個数 |
| --- | --- | --- |
| PCB | 　 | 1 |
| トッププレート | アルミ 0.8mm厚 | 1 |
| ミドルプレート | 透明アクリル 1.5mm厚 | 1 |
| ボトムプレート | 透明アクリル 1.5mm厚 | 1 |
| リードフレーム | <a href="https://akizukidenshi.com/catalog/g/g114809/" target="_blank">秋月電子リンク</a> | 1 |
| タクトスイッチ | <a href="https://akizukidenshi.com/catalog/g/g114887/" target="_blank">秋月電子リンク</a> | 2 |
| スライドスイッチ | <a href="https://akizukidenshi.com/catalog/g/g113989/" target="_blank">秋月電子リンク</a> | 1 |
| キースイッチ | Kailh PG1316M<br><a href="https://holykeebs.com/products/kailh-pg1316m-ultra-thin-butterfly-switch">holykeebsリンク</a> | 4 |
| キーキャップ | Kailh PG1316 Keycaps<br><a href="https://holykeebs.com/products/kailh-pg1316s-keycaps">holykeebsリンク</a> | 4 |
| 黒ネジ | M2 3mm | 6 |
| スペーサー | MAC8 TH-0.8-1.5-M2-B M2 1.5mm | 4 |

<br><br>

## ３．タクトスイッチのはんだ付け
位置をなるだけマークの通りになるようにはんだ付けして下さい。<br>
![pic](/docs/img/make_03.jpg)
<br><br>

## ４．スライドスイッチ のはんだ付け
細かいのではんだがブリッジしないよう気を付けて下さい。<br>
![pic](/docs/img/make_04.jpg)
<br><br>

## ５．スペーサー のはんだ付け
![pic](/docs/img/make_05.jpg)
<br><br>

## ６．キースイッチのはんだ付け
<br>
スイッチをPCBに差し込んでPCBとの隙間が無いように4つ角をはんだ付けして下さい。<br>
裏面ははんだの量を少なめにはんだ付けして下さい。量が多いとスイッチの接触不良につながります。<br>

![pic](/docs/img/make_06.jpg)
![pic](/docs/img/make_09.jpg)
![pic](/docs/img/make_16.jpg)
<br><br>

## ７．XIAO ESP32C6 のはんだ付け
裏面からピンをはんだ付けして下さい。<br>
リードフレームを使用して、B+B-にバッテリーピンをPCBに繋げて下さい。<br>
※PCBに書いてあるB+とB-が逆ですが写真の通りにはんだ付けしてください。<br>
![pic](/docs/img/make_08.jpg)
<br><br>

## ８．バッテリーのはんだ付け
写真の通りにバッテリーをPCBにはんだ付けして下さい。<br>
※PCBに書いてあるB+とB-が逆ですが写真の通りにはんだ付けしてください。<br>
![pic](/docs/img/make_07.jpg)
<br><br>

## ９．ファームウェアの書き込み
下記のサイトをChromeで開いてESP32C6にファームウェアを書き込んでください。<br><br>
<a href="https://palette-system.github.io/az-core/azpocket.html" target="_blank">ファームウェア書き込みサイト</a><br>
<br><br>

## １０．ボンドで裏面にボトムプレートを
ボトムプレートにボンドを塗り、薄く伸ばしてPCBに張り付けてください。<br>
※ボンドを塗りすぎるとスイッチの接触不良につながるので少なめに塗って下さい。<br>
![pic](/docs/img/make_08.jpg)
<br><br>

## １１．ミドルプレートとトッププレートを付けてねじ止め
表面にミドルプレートを挟んでトッププレートを重ねてねじ止めして下さい。
![pic](/docs/img/top.jpg)
<br><br>


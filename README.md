<html lang="ja">
    <head>
        <meta charset="utf-8" />
    </head>
    <body>
        <h1><center>Exposure Fusion</center></h1>
        <h2>なにものか？</h2>
        <p>
            多段階露出(Exposure Bracketing)された画像群を融合した画像を生成します。<br>
            <a href="https://www.researchgate.net/profile/Tom-Mertens/publication/4295602_Exposure_Fusion/links/53f716940cf2888a7497691d/Exposure-Fusion.pdf
">Exposure Fusion (2007)</a><br>
            <img src="images/ExposureFusion.svg">
            <br>
            色々なパラメータで補正した画像群から "いいとこ取り" 画像を作るのにも使えます。<br>
            <br>
            <img src="images/ExposureFusion2.svg"><br>
            <img src="images/ExposureFusion3.svg">
        </p>
        <h2>環境構築方法</h2>
        <p>
            pip install opencv-python 
        </p>
        <h2>使い方</h2>
        <p>
            python  exposure_fusion.py  (画像ファイル１)  (画像ファイル２) ･･･<br>
            例) python exposure_fusion.py A.jpg B.jpg C.jpg D.jpg<br>
            <br>
            または<br>
            <br>
            python  exposure_fusion.py (画像群に対するワイルドカード)<br>
            例) python exposure_fusion.py *.jpg<br>
            <br>
            実行すると融合画像が表示され、ESCキーを押下すると終了し、融合画像が fusion.png に保存されます。<br>
        </p>
    </body>
</html>

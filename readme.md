# makemosaic
cifar10の学習データ50000枚を使って自動でモザイクアートを作ります。

## getmean.ipynb
cifar10の学習データの全てで色平均を計算し、mean.csvに出力します。

## makemosaic.ipynb
入力した画像を指定サイズに分割し、上で取り出した色平均情報から一番色が近い画像を貼り付けていきます。(分割を細かくすればするほど出来上がりは綺麗ですが、実行時間は長くなります。)

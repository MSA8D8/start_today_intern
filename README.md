
Matrix Factrizationを用いて、ml-100kのデータセットから、映画のレコメンドを表示させるプログラム。  
latent factorとしてはUesr IDとItem IDの2つに分解している。  

データはローカルにダウンロードして使用して下さい。  

プログラムを動かすディレクトリと同じ所に、名前を変えず、置いて下さい。  

使用方法としては以下のようになります。但し、User IDはリストで入力する必要があります。　　

from ml_100k import main  


m = main.MatrixFactorization()    
m.recommend([1,20])  

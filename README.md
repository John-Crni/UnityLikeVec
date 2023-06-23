# UnityLikeVec
マインクラフトでUnity風に方向ベクトルを取得するクラス
Unityのtransform.upやtransform.right、transform.forwardの様に方向ベクトルを取得するクラスです。
使う為には、import MCH_RotateMatrix をし、getRotationMat関数にピッチ、ヨー、ロール(任意です),xyz(x=forward,y=up,z=rightで、指定するときはx=0,y=1,z=2この数字のどれかを入れる)を入力すればVec3型で返ってきます
どんな用途で使ってもいいです。ほんじゃ

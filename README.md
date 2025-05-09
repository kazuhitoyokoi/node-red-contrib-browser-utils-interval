cameraノードを用いて継続的に物体検出を行うフロー
=======================================

1. node-red-contrib-browser-utils、node-red-contrib-image-output、node-red-contrib-tensorflowをインストール
1. [node-red-contrib-browser-utilsのcamera.html](https://github.com/ibm-early-programs/node-red-contrib-browser-utils/blob/98317d16db6df984b066814639d9ebc638e720aa/camera/camera.html#L57)をコードエディタで開く
1. 57行目のsetTimeoutをsetIntervalに変更
1. Node-REDを再起動

-> cameraノードのボタンをクリックすると、継続的に物体検出が行われる

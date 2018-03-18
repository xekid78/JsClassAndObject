# JsClassAndObject
クラスとオブジェクト

## 処理
HelloクラスのHelloWorldメソッドを使う。

## コード
```
(function () {
    'use strict';

    class Hello {
        helloworld() {
            console.log("Hello World");
        }
    }

    var hw = new Hello();
    hw.helloworld();
    
})();
```

## 出力結果  
```
Hello World
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Java Script |
| Js環境 | Node.js 8.10.0 |

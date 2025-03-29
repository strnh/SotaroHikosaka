## [powerdns](https://www.powerdns.com/) への移行
* djbdns は堅牢ではあったが、メンテナンスがなされていないとの理由でFreeBSDの公式サポートが外された
* 現行のOSで動作が保証されなくなったこともあり、djbdns以外のDNSシステムが必要となった
* powerdns では djbdns のバックエンドDBのファイル形式を読み込めるとあるため、移行した。

## 主な業績
* 取り扱っているシステムすべてを powerdns のサービスに移行(10サーバ程度）
* バックエンドを postgresql に切り替えることで、GUI対応を追加。


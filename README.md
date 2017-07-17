##使い方
haproxy.cfg内の下記部分にある`use_backend`と`backend`を付け足していくだけ。
if文でhostによって分岐しているだけです。backendは動かしているportを書いて下さい。
docker for mac用で動作確認済み。


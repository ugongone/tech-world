## スマホのGPSってどういう仕組みで受信してるの？

皆さん普段普通に地図アプリとかでGPS普通に使ってると思うんでけど、
あれどうやって自分の位置割り出してるかご存知ですか？

基本的にGPS、Global Positioning Systemとは地球上どこにいても正確に自分の位置を特定するために使用される仕組みで、

地球の周りに飛んでいる約三十個のGPS衛星から発信された電波をスマホに内蔵されたGPSチップで受け取り、位置情報は特定しています。
スマホは少なくとも4つの異なるGPS衛星からの信号を使って「三角測量」という技術を用いて、各衛星からの距離を元に自分の位置を計算します。
各衛星からの距離は、衛星から送られてくる信号が到達するまでの時間を元に計算され、衛星ごとの距離データを組み合わせてスマホの位置情報を割り出すといった仕組みです。

ただ、この仕組みだけだと、都市部や屋内など、GPS信号の受信が難しい場所もあったりとか、
そもそもデバイスが最初にGPS情報を取得するまで結構時間がかかるなどの問題点があるので、補助GPSという携帯回線やWi-Fiネットワークを使用して、
GPSの位置情報取得を補助する仕組みが併用されており、近くの携帯基地局やWiーFiポイントの位置情報を目安に計測することで、
計測速度を飛躍的に上げたり、地下などのGPS信号が弱い場所でも位置を安定して取得できるといった仕組みになっています。

なので都市部とかにいると、この補助GPSが使われている場合が多いですね。
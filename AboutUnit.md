# 単位の約分と単位の換算について

単位の約分と単位の換算について気づいたことをメモします。

## 単位の約分について

例えば、気体の状態方程式$pV=nRT$で、体積$V$が$1.00\times 10^{-3}\ \mathrm{m}^3$、温度$T$が$288\ \mathrm{K}$、分子量$n$が$1.00\ \mathrm{mol}$のとき、圧力は次のようになります。
$$
p=\frac{nRT}{V}=\frac{1.00\ \mathrm{mol}*8.31\ \mathrm{J\cdot K^{-1}\cdot mol^{-1}}*288\ \mathrm{K}}{1.00\times 10^{-3}\ \mathrm{m}^3}=2.39\times 10^6\ \mathrm{Pa}
$$

このとき、$\mathrm{J=N\cdot m}$、$\mathrm{Pa=N\cdot m^{-2}}$ですから、単位部分だけ見れば
$$
\begin{aligned}
\frac{\cancel\mathrm{mol}*\mathrm{J\cdot \cancel{K^{-1}}\cdot \cancel {mol^{-1}}}*\cancel\mathrm{K}}{\mathrm{m^3}}&=\frac{\mathrm{N\cdot m}}{\mathrm{m^3}}\\
&=\mathrm{Pa}
\end{aligned}
$$
と単位の約分ができて、単位部分も含め辻褄が合っています。このように、文字式に単位も含め数値を代入することや、単位は約分できることは中学の物理や化学で最初で教えられることだと思います。

## 単位の換算について

一方圧力は$\mathrm{Pa}$の他に、水銀柱ミリメートル$\mathrm{mmHg}$で表すこともできます。$1\ \mathrm{Pa}=7.52\times 10^{-3}\ \mathrm{mmHg}$です。この式が単位も含め成り立つとすると、$\mathrm{Pa}$で全体を割って、
$$
1=7.52\times 10^{-3}\ \mathrm{mmHg\cdot Pa^{-1}}
$$
とできるはずです。このとき左辺の$1$には単位はありません。先程の、$p=2.39\times 10^6\ \mathrm{Pa}$という式の両辺にこの式をかければ、
$$
\begin{aligned}
p&=2.39\times 10^6\ \mathrm{Pa}*7.52\times 10^{-3}\ \mathrm{mmHg\cdot Pa^{-1}}\\
&=1.80\times10^{4}\ \mathrm{mmHg}
\end{aligned}
$$
と$\mathrm{mmHg}$に換算できます。このように、「1=数字 ［換算後の単位/換算前の単位］」という式を両辺に掛け、単位の約分をすることで単位の換算ができるようになりいます。

## 3つの単位に関する換算

標準気圧を単位とした$\mathrm{atm}$では$1\ \mathrm{atm}=760\ \mathrm{mmHg}$です。この式を変形して、
$$
\frac{\mathrm{atm}}{\mathrm{mmHg}}=760
$$
という式を作ります。このときも右辺には単位はありません。これを$1\ \mathrm{mmHg}=1.33\times10^2\ \mathrm{Pa}$の両辺に掛けると
$$
\begin{aligned}
1\ \cancel\mathrm{mmHg}*\frac{\mathrm{atm}}{\cancel\mathrm{mmHg}} &= 1\ \mathrm{atm}\\
&=1.33\times10^2\ \mathrm{Pa}*760\\
&= 1.01\times10^5\ \mathrm{Pa}
\end{aligned}
$$
と$\mathrm{atm}$と$\mathrm{Pa}$の関係式が得られます。このように3つの単位に関する換算でも単位の約分をうまく使うと、見通しよく換算できると思います。


## まとめ

「1=数字 ［換算後の単位/換算前の単位］」という関係式をいろいろ変形して使うと、見通しよく換算できることが分かりました。ここで挙げた例は単純なので、このような計算をしなくてもすぐに換算できると思いますが、複雑な単位の換算をしなければいけないときは役に立つと思います。

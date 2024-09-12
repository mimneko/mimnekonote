---
title: 高校数学用MathJaxサンプル
date: 2024-04-29
tags: [latex]
---

<style>
  /* -----------------------------------------
    増減表
  ----------------------------------------- */
  .derivative-test-chart {
    border-collapse: collapse;
    margin: 0 auto;
  }

  .derivative-test-chart td {
    border: 1px solid black;
    padding: 5px;
    text-align: center;
    min-width: 30px;
  }
</style>


<h1 id="article-title">高校数学用MathJax例</h1>
<div id="article-information">
  <div id="renewal-date" datetime="2024-04-29">2024-04-29</div>
  <div id="author">みむねこ</div>
</div>

<div id="toc">
  <p id="toc-title">目次</p>
  <ol id="toc-content">
      <li><a href="#h2-1">数式</a></li>
  </ol>
</div>

<h2>準備</h2>
<p>headタグ内に、以下のように書く。</p>
<pre><code data-copy>&lt;script&gt;
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  }
};
&lt;/script&gt;
&lt;script id="MathJax-script" async 
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"&gt;
&lt;/script&gt;
</code></pre>

<p>ドルマーク2つだと、 $$ 3 + 4 = 7 $$ ディスプレイ形式に。</p>
<pre><code>&lt;p&gt;ドルマーク2つだと、 $$ 3 + 4 = 7 $$ ディスプレイ形式に。&lt;/p&gt;</code></pre>
<p>ドルマーク1つだと、 $ 3 + 4 = 7 $ インライン形式に。</p>
<pre><code>&lt;p&gt;ドルマーク1つだと、 $ 3 + 4 = 7 $ インライン形式に。&lt;/p&gt;</code></pre>

<h2>数</h2>
<h3>分数</h3>
<h4>分数(小)</h4>
<p>$\frac{1}{2}$</p>
<pre><code>\frac{1}{2}</code></pre>
<h4>分数(大)</h4>
<p>$\dfrac{1}{2}$</p>
<pre><code>\dfrac{1}{2}</code></pre>
<pre><code>\displaystylefrac{1}{2}</code></pre>
<h4>分数と括弧</h4>
<p>$\left( -\frac{1}{2} \right)^2$</p>
<pre><code>\left( -\frac{1}{2} \right)^2</code></pre>
<h4>連分数</h4>
<p>$\frac{a+b}{c+\frac{d}{e}}$</p>
<pre><code>\frac{a+b}{c+\frac{d}{e}}</code></pre>
<p>$\cfrac{a+b}{c+\cfrac{d}{e}}$</p>
<pre><code>\cfrac{a+b}{c+\cfrac{d}{e}}</code></pre>
<h4>無限連分数</h4>
<p>$\begin{eqnarray}
  1+\frac{1}{1+\frac{1}{1+\frac{1}{1+\ddots}}}
  = \frac{1}{2} \left( 1+\sqrt{5} \right)
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  1+\frac{1}{1+\frac{1}{1+\frac{1}{1+\ddots}}}
  = \frac{1}{2} \left( 1+\sqrt{5} \right)
\end{eqnarray}</code></pre>
<h3>小数</h3>
<h4>小数</h4>
<p>$0.123$</p>
<pre><code>0.123</code></pre>
<h4>循環小数</h4>
<p>$\frac{1}{11} = 0.\dot{0}\dot{9}$</p>
<pre><code>\frac{1}{11} = 0.\dot{0}\dot{9}</code></pre>
<h4>無限小数</h4>
<p>$\sqrt{2} = 1.4142 \cdots$</p>
<pre><code>\sqrt{2} = 1.4142 \cdots</code></pre>
<h3>無限大</h3>
<p>$\infty$</p>
<pre><code>\infty</code></pre>
<h3>絶対値</h3>
<p>$|x|$</p>
<pre><code>|x|</code></pre>
<pre><code>\vert x \vert</code></pre>
<h3>分数と絶対値</h3>
<p>$\left| \dfrac{x}{2} \right|$</p>
<pre><code>\left| \dfrac{x}{2} \right|</code></pre>
<h3>ガウス記号</h3>
<p>$[x]$</p>
<pre><code>[x]</code></pre>
<pre><code>\lbrack x \rbrack</code></pre>

<h2>四則演算</h2>
<h3>足す</h3>
<p>$1 + 2$</p>
<pre><code>1 + 2</code></pre>
<h3>引く</h3>
<p>$3 - 1$</p>
<pre><code>3 - 1</code></pre>
<h3>掛ける</h3>
<p>$2 \times 3$</p>
<pre><code>2 \times 3</code></pre>
<p>$a \cdot b = ab$</p>
<pre><code>a \cdot b = ab</code></pre>
<h3>割る</h3>
<p>$6 \div 3$</p>
<pre><code>6 \div 3</code></pre>
<h3>プラスマイナス</h3>
<p>$\pm 1$</p>
<pre><code>\pm 1</code></pre>
<h3>マイナスプラス</h3>
<p>$\mp 1$</p>
<pre><code>\mp 1</code></pre>
<h3>筆算</h3>
<h4>掛け算</h4>
<p>$\begin{array}{r}
  67 \\[-3pt]
  \underline{\times\phantom{0}63}\\[-3pt]
  201 \\[-3pt]
  \underline{\phantom{0}402\phantom{0}} \\[-3pt]
  4221
  \end{array}$</p>
<pre><code>\begin{array}{r}
67 \\[-3pt]
\underline{\times\phantom{0}63}\\[-3pt]
201 \\[-3pt]
\underline{\phantom{0}402\phantom{0}} \\[-3pt]
4221
\end{array}</code></pre>
<h4>割り算</h4>
<p>$\begin{array}{r}
  7.6 \\[-3pt]
25\enclose{longdiv}{190\phantom{0}} \\[-3pt]
  \underline{175\phantom{.0}} \\[-3pt]
  15\phantom{.}0 \\[-3pt]
  \underline{15\phantom{.}0} \\[-3pt]
  \phantom{000}0
\end{array}$</p>
<pre><code>\begin{array}{r}
  7.6 \\[-3pt]
25\enclose{longdiv}{190\phantom{0}} \\[-3pt]
  \underline{175\phantom{.0}} \\[-3pt]
  15\phantom{.}0 \\[-3pt]
  \underline{15\phantom{.}0} \\[-3pt]
  \phantom{000}0
\end{array}</code></pre>
<h3>合同式</h3>
<p>$a \equiv b \mod n$</p>
<pre><code>a \equiv b \mod n</code></pre>
<p>$a \equiv b \pmod n$</p>
<pre><code>a \equiv b \pmod n</code></pre>
<h3>比例</h3>
<p>$x \propto y$</p>
<pre><code>x \propto y</code></pre>

<h2>大小</h2>
<h3>大なり</h3>
<p>$a \gt b$</p>
<pre><code>a \gt b</code></pre>
<h3>大なりイコール</h3>
<p>$a \geqq b$</p>
<pre><code>a \geqq b</code></pre>
<h3>小なり</h3>
<p>$a \lt b$</p>
<pre><code>a \lt b</code></pre>
<h3>小なりイコール</h3>
<p>$a \leqq b$</p>
<pre><code>a \leqq b</code></pre>
<h3>イコール</h3>
<p>$a = b$</p>
<pre><code>a = b</code></pre>
<h3>ノットイコール</h3>
<p>$a \neq b$</p>
<pre><code>a \neq b</code></pre>
<h3>ニアリーイコール</h3>
<p>$a \fallingdotseq b$</p>
<pre><code>a \fallingdotseq b</code></pre>
<h3>十分大きい</h3>
<p>$a \gg b$</p>
<pre><code>a \gg b</code></pre>
<h3>十分小さい</h3>
<p>$a \ll b$</p>
<pre><code>a \ll b</code></pre>

<h2>複数行数式</h2>
<h3>イコールで縦に揃える</h3>
<p>$\begin{eqnarray}
  x + 2x &=& 3 \\
  x &=& 1
\end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  x + 2x &=& 3 \\
  x &=& 1
\end{eqnarray}</code></pre>
<h3>連立方程式</h3>
<p>$\begin{eqnarray}
  \left\{
    \begin{array}{l}
      x + y = 10 \\
      2x + 4y = 32
    \end{array}
  \right.
\end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  \left\{
    \begin{array}{l}
      x + y = 10 \\
      2x + 4y = 32
    \end{array}
  \right.
\end{eqnarray}</code></pre>
<h3>場合分け</h3>
<p>$\begin{eqnarray}
  |x|
    =
    \begin{cases}
      x & ( x \geqq 0 ) \\
      -x & ( x \lt 0 )
    \end{cases}
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
|x|
  =
  \begin{cases}
    x & ( x \geqq 0 ) \\
    -x & ( x \lt 0 )
  \end{cases}
\end{eqnarray}</code></pre>

<h2>集合</h2>
<h3>属する</h3>
<p>$x \in A$</p>
<pre><code>x \in A</code></pre>
<p>$A \ni x$</p>
<pre><code>A \ni x</code></pre>
<h3>属していない</h3>
<p>$x \notin A$</p>
<pre><code>x \notin A</code></pre>
<h3>部分集合</h3>
<p>$A \subset B$</p>
<pre><code>A \subset B</code></pre>
<p>$A \supset B$</p>
<pre><code>A \supset B</code></pre>
<h3>部分集合でない</h3>
<p>$A \not \subset B$</p>
<pre><code>A \not \subset B</code></pre>
<h3>共通部分</h3>
<p>$A \cap B$</p>
<pre><code>A \cap B</code></pre>
<h3>和集合</h3>
<p>$A \cup B$</p>
<pre><code>A \cup B</code></pre>
<h3>空集合</h3>
<p>$\varnothing$</p>
<pre><code>\varnothing</code></pre>
<p>$\emptyset$</p>
<pre><code>\emptyset</code></pre>
<h3>補集合</h3>
<p>$\overline{ A }$</p>
<pre><code>\overline{ A }</code></pre>
<h3>ド・モルガンの法則</h3>
<p>$\overline{ (A\cap B) } = \overline{ A } \cup \overline{ B }$</p>
<pre><code>\overline{ (A\cap B) } = \overline{ A } \cup \overline{ B }</code></pre>
<h3>自然数全体の集合</h3>
<p>$\mathbb{ N }$</p>
<pre><code>\mathbb{ N }</code></pre>
<h3>整数全体の集合</h3>
<p>$\mathbb{ Z }$</p>
<pre><code>\mathbb{ Z }</code></pre>
<h3>有理数全体の集合</h3>
<p>$\mathbb{ Q }$</p>
<pre><code>\mathbb{ Q }</code></pre>
<h3>実数全体の集合</h3>
<p>$\mathbb{ R }$</p>
<pre><code>\mathbb{ R }</code></pre>

<h2>論理</h2>
<h3>ならば</h3>
<p>$P \Rightarrow Q$</p>
<pre><code>P \Rightarrow Q</code></pre>
<p>$P \Leftarrow  Q$</p>
<pre><code>P \Leftarrow  Q</code></pre>
<h3>同値</h3>
<p>$P \iff Q$</p>
<pre><code>P \iff Q</code></pre>
<p>$P \Leftrightarrow Q$</p>
<pre><code>P \Leftrightarrow Q</code></pre>
<h3>よって、ゆえに</h3>
<p>$\therefore$</p>
<pre><code>\therefore</code></pre>
<h3>なぜならば</h3>
<p>$\because$</p>
<pre><code>\because</code></pre>
<h3>否定</h3>
<p>$\overline{ P }$</p>
<pre><code>\overline{ P }</code></pre>

<h2>順列と組み合わせ</h2>
<h3>順列</h3>
<p>${}_n \mathrm{ P }_k$</p>
<pre><code>{}_n \mathrm{ P }_k</code></pre>
<h3>組み合わせ</h3>
<p>${}_n \mathrm{ C }_k$</p>
<pre><code>{}_n \mathrm{ C }_k</code></pre>
<h3>階乗</h3>
<p>$n!$</p>
<pre><code>n!</code></pre>
<h3>組み合わせの公式</h3>
<p>$\begin{eqnarray}
  {}_n \mathrm{ C }_k
    = \frac{ n! }{ k! ( n - k )! }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
{}_n \mathrm{ C }_k
  = \frac{ n! }{ k! ( n - k )! }
\end{eqnarray}</code></pre>
<h3>順列の公式</h3>
<p>$\begin{eqnarray}
  {}_n \mathrm{ P }_k
    = n \cdot ( n - 1 ) \cdots ( n - k + 1 )
    = \frac{ n! }{ ( n - k )! }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
{}_n \mathrm{ P }_k
  = n \cdot ( n - 1 ) \cdots ( n - k + 1 )
  = \frac{ n! }{ ( n - k )! }
\end{eqnarray}</code></pre>

<h2>総和・総乗</h2>
<h3>総和</h3>
<p>$\sum_{i=1}^{n} a_i$</p>
<pre><code>\sum_{i=1}^{n} a_i</code></pre>
<p>$\displaystyle \sum_{i=1}^n a_i$</p>
<pre><code>\displaystyle \sum_{i=1}^n a_i</code></pre>
<h3>総和のイメージ</h3>
<p>$\begin{eqnarray}
  \sum_{ k = 1 }^{ n } k^2
    = \overbrace{ 1^2 + 2^2 + \cdots + n^2 }^{ n }
    = \frac{ 1 }{ 6 } n ( n + 1 ) ( 2n + 1 )
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
\sum_{ k = 1 }^{ n } k^2
  = \overbrace{ 1^2 + 2^2 + \cdots + n^2 }^{ n }
  = \frac{ 1 }{ 6 } n ( n + 1 ) ( 2n + 1 )
\end{eqnarray}</code></pre>

<h2>指数・対数</h2>
<h3>べき乗</h3>
<p>$2^3$</p>
<pre><code>2^3</code></pre>
<p>$e^{ i \pi }$</p>
<pre><code>e^{ i \pi }</code></pre>
<h3>平方根</h3>
<p>$\sqrt{ 2 }$</p>
<pre><code>\sqrt{ 2 }</code></pre>
<p>$\sqrt{ \mathstrut a } + \sqrt{ \mathstrut b }$</p>
<pre><code>\sqrt{ \mathstrut a } + \sqrt{ \mathstrut b }</code></pre>
<h3>3乗根</h3>
<p>$\sqrt[ 3 ]{ x }$</p>
<pre><code>\sqrt[ 3 ]{ x }</code></pre>
<h3>対数</h3>
<h4>自然対数</h4>
<p>$\log x$</p>
<pre><code>\log x</code></pre>
<h4>常用対数</h4>
<p>$\log_{ 10 } x$</p>
<pre><code>\log_{ 10 } x</code></pre>

<h2>図形</h2>
<h3>角度</h3>
<p>$90^{ \circ }$</p>
<pre><code>90^{ \circ }</code></pre>
<p>$\frac{ \pi }{ 2 }$</p>
<pre><code>\frac{ \pi }{ 2 }</code></pre>
<h3>角記号</h3>
<p>$\angle A$</p>
<pre><code>\angle A</code></pre>
<h3>平行</h3>
<p>$AB /\!/ CD$</p>
<pre><code>AB /\!/ CD</code></pre>
<h3>垂直</h3>
<p>$AB \perp CD$</p>
<pre><code>AB \perp CD</code></pre>
<h3>三角形</h3>
<p>$\triangle ABC$</p>
<pre><code>\triangle ABC</code></pre>
<h3>弧</h3>
<p>$\stackrel{\huge\frown}{AB}$</p>
<pre><code>\stackrel{\huge\frown}{AB}</code></pre>
<p>$\overparen{AB}$</p>
<pre><code>\overparen{AB}</code></pre>
<h3>合同</h3>
<p>$\triangle ABC \equiv \triangle DEF$</p>
<pre><code>\triangle ABC \equiv \triangle DEF</code></pre>
<h3>相似</h3>
<p>$\triangle ABC \backsim \triangle DEF$</p>
<pre><code>\triangle ABC \backsim \triangle DEF</code></pre>

<h2>三角関数</h2>
<h3>サイン</h3>
<p>$\sin x$</p>
<pre><code>\sin x</code></pre>
<h3>コサイン</h3>
<p>$\cos x$</p>
<pre><code>\cos x</code></pre>
<h3>タンジェント</h3>
<p>$\tan x$</p>
<pre><code>\tan x</code></pre>
<h3>サイン変換</h3>
<p>$\begin{eqnarray}
  \sin 45^\circ
    = \frac{ \sqrt{2} }{ 2 }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
\sin 45^\circ
  = \frac{ \sqrt{2} }{ 2 }
\end{eqnarray}</code></pre>
<h3>コサイン変換</h3>
<p>$\begin{eqnarray}
  \cos \frac{ \pi }{ 3 }
    = \frac{ 1 }{ 2 }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
\cos \frac{ \pi }{ 3 }
  = \frac{ 1 }{ 2 }
\end{eqnarray}</code></pre>
<h3>タンジェント変換</h3>
<p>$\begin{eqnarray}
  \tan \theta
    = \frac{ \sin \theta }{ \cos \theta }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
\tan \theta
  = \frac{ \sin \theta }{ \cos \theta }
\end{eqnarray}</code></pre>

<h2>複素数</h2>
<h3>複素数</h3>
<p>$a+bi$</p>
<pre><code>a+bi</code></pre>
<h3>共役複素数</h3>
<p>$\bar{z}$</p>
<pre><code>\bar{z}</code></pre>
<h3>偏角</h3>
<p>$\arg (z)$</p>
<pre><code>\arg (z)</code></pre>
<h3>1の3乗根</h3>
<p>$\omega$</p>
<pre><code>\omega</code></pre>
<h3>複素数の絶対値</h3>
<p>$\begin{eqnarray}
  z\bar{z} = |z|^2
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
z\bar{z} = |z|^2
\end{eqnarray}</code></pre>

<h2>極限</h2>
<h3>極限</h3>
<p>$\lim_{ x \to +0 } \frac{1}{x} = \infty$</p>
<pre><code>\lim_{ x \to +0 } \frac{1}{x} = \infty</code></pre>
<p>$\displaystyle \lim_{ n \to \infty } f_n(x) = f(x)$</p>
<pre><code>\displaystyle \lim_{ n \to \infty } f_n(x) = f(x)</code></pre>

<h2>微分・積分</h2>
<h3>微分</h3>
<p>$\frac{ dy }{ dx }$</p>
<pre><code>\frac{ dy }{ dx }</code></pre>
<p>$\frac{ \mathrm{ d } y }{ \mathrm{ d } x }$</p>
<pre><code>\frac{ \mathrm{ d } y }{ \mathrm{ d } x }</code></pre>
<p>$f'$</p>
<pre><code>f'</code></pre>
<h3>2階微分</h3>
<p>$\frac{ d^2 y }{ dx^2 }$</p>
<pre><code>\frac{ d^2 y }{ dx^2 }</code></pre>
<p>$f^{\prime\prime}$</p>
<pre><code>f^{\prime\prime}</code></pre>
<p>$f^{ ( 2 ) }$</p>
<pre><code>f^{ ( 2 ) }</code></pre>
<h3>導関数の定義</h3>
<p>$\begin{eqnarray}
  f'(x)
    = \frac{ df }{ dx }
    = \lim_{ \Delta x \to 0 } \frac{ f(x + \Delta x) - f(x) }{ \Delta x }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
f'(x)
  = \frac{ df }{ dx }
  = \lim_{ \Delta x \to 0 } \frac{ f(x + \Delta x) - f(x) }{ \Delta x }
\end{eqnarray}</code></pre>
<h3>増減表</h3>
<p>$\begin{array}{c|ccccc}
  x     & \cdots & -1 & \cdots & 1 & \cdots \\ 
  \hline
  f’(x) & + & 0 & – & 0 & + \\ 
  \hline
  f(x)  & \nearrow & e & \searrow & -e & \nearrow
\end{array}$</p>
<pre><code>\begin{array}{c|ccccc}
  x     & \cdots & -1 & \cdots & 1 & \cdots \\ 
  \hline
  f’(x) & + & 0 & – & 0 & + \\ 
  \hline
  f(x)  & \nearrow & e & \searrow & -e & \nearrow
\end{array}</code></pre>
<h3>積分</h3>
<p>$\int_0^1 f(x) dx$</p>
<pre><code>\int_0^1 f(x) dx</code></pre>
<p>$\displaystyle \int_{-\infty}^{ \infty } f(x) dx$</p>
<pre><code>\displaystyle \int_{-\infty}^{ \infty } f(x) dx</code></pre>
<h3>サンプル</h3>
<p>$\begin{eqnarray}
  \int_0^1 x dx
  = \left[ \frac{x^2}{2} \right]_0^1
  = \frac{1}{2}
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
\int_0^1 x dx
= \left[ \frac{x^2}{2} \right]_0^1
= \frac{1}{2}
\end{eqnarray}</code></pre>

<h2>ベクトル</h2>
<h3>ベクトル</h3>
<p>$\vec{ a }$</p>
<pre><code>\vec{ a }</code></pre>
<p>$\overrightarrow{ AB }$</p>
<pre><code>\overrightarrow{ AB }</code></pre>
<h3>横ベクトル</h3>
<p>$( a_1, a_2, \ldots, a_n )$</p>
<pre><code>( a_1, a_2, \ldots, a_n )</code></pre>
<h3>縦ベクトル</h3>
<p>$\left(
  \begin{array}{c}
    a_1 \\
    a_2 \\
    \vdots \\
    a_n
  \end{array}
\right)$</p>
<pre><code>\left(
  \begin{array}{c}
    a_1 \\
    a_2 \\
    \vdots \\
    a_n
  \end{array}
\right)</code></pre>
<h3>内積</h3>
<p>$\vec{ a } \cdot \vec{ b }$</p>
<pre><code>\vec{ a } \cdot \vec{ b }</code></pre>

<h2>表</h2>
<h3>表</h3>
<p>$\begin{array}{ccc}
  xxx & yyy & zzz \\
  1   & 2   & 3
\end{array}$</p>
<pre><code>\begin{array}{ccc}
  xxx & yyy & zzz \\
  1   & 2   & 3
\end{array}</code></pre>
<h3>表（縦線付）</h3>
<p>$\begin{array}{|c|c|c|}
  xxx & yyy & zzz \\
  1   & 2   & 3 \\
\end{array}$</p>
<pre><code>\begin{array}{|c|c|c|}
  xxx & yyy & zzz \\
  1   & 2   & 3 \\
\end{array}</code></pre>
<h3>表（横線付）</h3>
<p>$\begin{array}{ccc}
  \hline
  xxx & yyy & zzz \\
  \hline
  1   & 2   & 3 \\
  \hline
\end{array}$</p>
<pre><code>\begin{array}{ccc}
  \hline
  xxx & yyy & zzz \\
  \hline
  1   & 2   & 3 \\
  \hline
\end{array}</code></pre>
<h3>増減表</h3>
<p>$\begin{array}{c|ccccc}
  x     & \cdots & -1 & \cdots & 1 & \cdots \\ 
  \hline
  f’(x) & + & 0 & – & 0 & + \\ 
  \hline
  f(x)  & \nearrow & e & \searrow & -e & \nearrow
\end{array}$</p>
<pre><code>\begin{array}{c|ccccc}
  x     & \cdots & -1 & \cdots & 1 & \cdots \\ 
  \hline
  f’(x) & + & 0 & – & 0 & + \\ 
  \hline
  f(x)  & \nearrow & e & \searrow & -e & \nearrow
\end{array}</code></pre>

<h2>線</h2>
<h3>縦線</h3>
<p>$| x |$</p>
<pre><code>| x |</code></pre>
<p>$\vert x \vert$</p>
<pre><code>\vert x \vert</code></pre>
<p>$\{ x \mid x \in A \}$</p>
<pre><code>\{ x \mid x \in A \}</code></pre>
<h3>上線</h3>
<p>$\overline{ A }$</p>
<pre><code>\overline{ A }</code></pre>
<p>$\bar{ A }$</p>
<pre><code>\bar{ A }</code></pre>
<h3>スラッシュ</h3>
<p>$/$</p>
<pre><code>/</code></pre>
<h3>バックスラッシュ</h3>
<p>$\backslash$</p>
<pre><code>\backslash</code></pre>
<h3>斜線(下)</h3>
<p>$\diagdown$</p>
<pre><code>\diagdown</code></pre>
<h3>斜線（上）</h3>
<p>$\diagup$</p>
<pre><code>\diagup</code></pre>
<h3>キャンセル</h3>
<p>$\cancel{a}$</p>
<pre><code>\cancel{a}</code></pre>
<p>$\bcancel{a}$</p>
<pre><code>\bcancel{a}</code></pre>
<p>$\xcancel{a}$</p>
<pre><code>\xcancel{a}</code></pre>
<h3>キャンセルと矢印</h3>
<p>$\cancelto{A}{a}$</p>
<pre><code>\cancelto{A}{a}</code></pre>
<h3>サンプル</h3>
<p>$\begin{eqnarray}
    \frac{\cancel{2}}{\cancel{6}}=\frac{1}{3}
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  \frac{\cancel{2}}{\cancel{6}}=\frac{1}{3}
\end{eqnarray}</code></pre>
<p>$\begin{eqnarray}
    \frac{1}{\cancel{3}} \times \frac{\cancelto{2}{6}}{5}
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  \frac{1}{\cancel{3}} \times \frac{\cancelto{2}{6}}{5}
\end{eqnarray}</code></pre>

<h2>矢印</h2>
<h3>左矢印</h3>
<p>$\leftarrow$</p>
<pre><code>\leftarrow</code></pre>
<p>$\longleftarrow$</p>
<pre><code>\longleftarrow</code></pre>
<h3>右矢印</h3>
<p>$\rightarrow$</p>
<pre><code>\rightarrow</code></pre>
<p>$\longrightarrow$</p>
<pre><code>\longrightarrow</code></pre>
<h3>上矢印</h3>
<p>$\uparrow$</p>
<pre><code>\uparrow</code></pre>
<h3>下矢印</h3>
<p>$\downarrow$</p>
<pre><code>\downarrow</code></pre>
<h3>左右矢印</h3>
<p>$\leftrightarrow$</p>
<pre><code>\leftrightarrow</code></pre>
<p>$\longleftrightarrow$</p>
<pre><code>\longleftrightarrow</code></pre>
<h3>上下矢印</h3>
<p>$\updownarrow$</p>
<pre><code>\updownarrow</code></pre>
<h3>2重左矢印</h3>
<p>$\Leftarrow$</p>
<pre><code>\Leftarrow</code></pre>
<p>$\Longleftarrow$</p>
<pre><code>\Longleftarrow</code></pre>
<h3>2重右矢印</h3>
<p>$\Rightarrow$</p>
<pre><code>\Rightarrow</code></pre>
<p>$\Longrightarrow$</p>
<pre><code>\Longrightarrow</code></pre>
<h3>2重上矢印</h3>
<p>$\Uparrow$</p>
<pre><code>\Uparrow</code></pre>
<h3>2重下矢印</h3>
<p>$\Downarrow$</p>
<pre><code>\Downarrow</code></pre>
<h3>2重左右矢印</h3>
<p>$\Leftrightarrow$</p>
<pre><code>\Leftrightarrow</code></pre>
<p>$\Longleftrightarrow$</p>
<pre><code>\Longleftrightarrow</code></pre>
<h3>2重上下矢印</h3>
<p>$\Updownarrow$</p>
<pre><code>\Updownarrow</code></pre>
<h3>右上矢印</h3>
<p>$\nearrow$</p>
<pre><code>\nearrow</code></pre>
<h3>右下矢印</h3>
<p>$\searrow$</p>
<pre><code>\searrow</code></pre>
<h3>左上矢印</h3>
<p>$\nwarrow$</p>
<pre><code>\nwarrow</code></pre>
<h3>左下矢印</h3>
<p>$\swarrow$</p>
<pre><code>\swarrow</code></pre>
<h3>頭に矢印</h3>
<p>$\vec{ a }$</p>
<pre><code>\vec{ a }</code></pre>
<p>$\overrightarrow{ AB }$</p>
<pre><code>\overrightarrow{ AB }</code></pre>
<p>$\overleftarrow{ AB }$</p>
<pre><code>\overleftarrow{ AB }</code></pre>

<h2>括弧</h2>
<h3>丸括弧</h3>
<p>$( x )$</p>
<pre><code>( x )</code></pre>
<h3>角括弧</h3>
<p>$[ x ]$</p>
<pre><code>[ x ]</code></pre>
<p>$\lbrack x \rbrack$</p>
<pre><code>\lbrack x \rbrack</code></pre>
<h3>波括弧</h3>
<p>$\{ x \}$</p>
<pre><code>\{ x \}</code></pre>
<p>$\lbrace x \rbrace$</p>
<pre><code>\lbrace x \rbrace</code></pre>
<h3>大きい括弧</h3>
<p>$\left[ \dfrac{ 1 }{ 2 } \right]$</p>
<pre><code>\left[ \dfrac{ 1 }{ 2 } \right]</code></pre>
<h3>上括弧</h3>
<p>$\overbrace{ x + y + z }$</p>
<pre><code>\overbrace{ x + y + z }</code></pre>
<p>$\overbrace{ a_1 + \cdots + a_n }^{ n }$</p>
<pre><code>\overbrace{ a_1 + \cdots + a_n }^{ n }</code></pre>
<h3>下括弧</h3>
<p>$\underbrace{ x + y + z }$</p>
<pre><code>\underbrace{ x + y + z }</code></pre>
<p>$\underbrace{ a_1 + \cdots + a_n }_{ n }$</p>
<pre><code>\underbrace{ a_1 + \cdots + a_n }_{ n }</code></pre>

<h2>点</h2>
<h3>点（中央）</h3>
<p>$\cdot$</p>
<pre><code>\cdot</code></pre>
<h3>複数の点（中央横向き）</h3>
<p>$\cdots$</p>
<pre><code>\cdots</code></pre>
<h3>複数の点（下側横向き）</h3>
<p>$\ldots$</p>
<pre><code>\ldots</code></pre>
<h3>頭に点</h3>
<p>$\dot{ a }$</p>
<pre><code>\dot{ a }</code></pre>

<h2>三角形</h2>
<h3>三角形</h3>
<p>$\triangle$</p>
<pre><code>\triangle</code></pre>

<h2>空白</h2>
<h3>空白</h3>
<p>$aaa \ bbb$</p>
<pre><code>aaa \ bbb</code></pre>
<p>$aaa \quad bbb$</p>
<pre><code>aaa \quad bbb</code></pre>
<p>$aaa \qquad bbb$</p>
<pre><code>aaa \qquad bbb</code></pre>
<p>$aaa \hspace{ 10pt } bbb$</p>
<pre><code>aaa \hspace{ 10pt } bbb</code></pre>
<h3>空白をなくす</h3>
<p>$aaa \! bbb$</p>
<pre><code>aaa \! bbb</code></pre>
<h3>改行</h3>
<p>$\begin{eqnarray} 
  aaa \\ bbb
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray} 
  aaa \\ bbb
\end{eqnarray}</code></pre>
<p>$\begin{eqnarray} 
  aaa \\[5pt] bbb
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray} 
  aaa \\[5pt] bbb
\end{eqnarray}</code></pre>
<h3>サンプル</h3>
<p>$\begin{eqnarray}
  & & \frac{1}{2} +\frac{1}{3} +\frac{1}{6} \\[ 5pt ]
  &=& \frac{3}{6} +\frac{2}{6} +\frac{1}{6} \\
  &=& 1
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  & & \frac{1}{2} +\frac{1}{3} +\frac{1}{6} \\[ 5pt ]
  &=& \frac{3}{6} +\frac{2}{6} +\frac{1}{6} \\
  &=& 1
\end{eqnarray}</code></pre>

<h2>文字サイズ</h2>
<h3>極小サイズ</h3>
<p>$\tiny{ abc ABC }$</p>
<pre><code>\tiny{ abc ABC }</code></pre>
<h3>小さいサイズ</h3>
<p>$\scriptsize{ abc ABC }$</p>
<pre><code>\scriptsize{ abc ABC }</code></pre>
<h3>少し小さいサイズ</h3>
<p>$\small{ abc ABC }$</p>
<pre><code>\small{ abc ABC }</code></pre>
<h3>ノーマルサイズ</h3>
<p>$\normalsize{ abc ABC }$</p>
<pre><code>\normalsize{ abc ABC }</code></pre>
<h3>大きいサイズ</h3>
<p>$\large{ abc ABC }$</p>
<pre><code>\large{ abc ABC }</code></pre>
<h3>さらに大きいサイズ</h3>
<p>$\Large{ abc ABC }$</p>
<pre><code>\Large{ abc ABC }</code></pre>
<h3>もっと大きいサイズ</h3>
<p>$\LARGE{ abc ABC }$</p>
<pre><code>\LARGE{ abc ABC }</code></pre>
<h3>特大サイズ</h3>
<p>$\huge{ abc ABC }$</p>
<pre><code>\huge{ abc ABC }</code></pre>
<h3>極大サイズ</h3>
<p>$\Huge{ abc ABC }$</p>
<pre><code>\Huge{ abc ABC }</code></pre>

<h2>フォント</h2>
<h3>ローマン体</h3>
<p>$\mathrm{ ABC }$</p>
<pre><code>\mathrm{ ABC }</code></pre>
<h3>タイプライターフォント</h3>
<p>$\mathtt{ ABC }$</p>
<pre><code>\mathtt{ ABC }</code></pre>
<h3>サンセリフ</h3>
<p>$\mathsf{ ABC }$</p>
<pre><code>\mathsf{ ABC }</code></pre>
<h3>カリグラフィーフォント</h3>
<p>$\mathcal{ ABC }$</p>
<pre><code>\mathcal{ ABC }</code></pre>
<h3>太文字</h3>
<p>$\mathbf{ ABC }$</p>
<pre><code>\mathbf{ ABC }</code></pre>
<h3>イタリック</h3>
<p>$\mathit{ ABC }$</p>
<pre><code>\mathit{ ABC }</code></pre>
<h3>中抜き文字</h3>
<p>$\mathbb{ ABC }$</p>
<pre><code>\mathbb{ ABC }</code></pre>
<h3>スクリプトフォント</h3>
<p>$\mathscr{ ABC }$</p>
<pre><code>\mathscr{ ABC }</code></pre>
<h3>フラクトゥール</h3>
<p>$\mathfrak{ ABC }$</p>
<pre><code>\mathfrak{ ABC }</code></pre>

<h2>上付き・下付き</h2>
<h3>上付き文字</h3>
<p>$a^{ xy }$</p>
<pre><code>a^{ xy }</code></pre>
<h3>上付き文字（左）</h3>
<p>${}^{ xy } a$</p>
<pre><code>{}^{ xy } a</code></pre>
<h3>下付き文字</h3>
<p>$a_{ xy }$</p>
<pre><code>a_{ xy }</code></pre>
<h3>下付き文字（左）</h3>
<p>${}_{ xy } a$</p>
<pre><code>{}_{ xy } a</code></pre>
<h3>下付きサンプル</h3>
<p>$\begin{eqnarray}
    a_n^2 + a_{ n + 1 }^2 = a_{ 2n + 1 }
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  a_n^2 + a_{ n + 1 }^2 = a_{ 2n + 1 }
\end{eqnarray}</code></pre>

<h2>ギリシャ文字</h2>
<h3>アルファ</h3>
<p>$\alpha$</p>
<pre><code>\alpha</code></pre>
<h3>ベータ</h3>
<p>$\beta$</p>
<pre><code>\beta</code></pre>
<h3>ガンマ</h3>
<p>$\gamma$</p>
<pre><code>\gamma</code></pre>
<h3>デルタ</h3>
<p>$\delta$</p>
<pre><code>\delta</code></pre>
<h3>パイ</h3>
<p>$\pi$</p>
<pre><code>\pi</code></pre>

<h2>特殊文字</h2>
<h3>ユニコード</h3>
<p>$\unicode{x5F45}$</p>
<pre><code>\unicode{x5F45}</code></pre>
<p>$\begin{eqnarray}
    \unicode{x5F45}\text{は、弓へんに剪。}
  \end{eqnarray}$</p>
<pre><code>\begin{eqnarray}
  \unicode{x5F45}\text{は、弓へんに剪。}
\end{eqnarray}</code></pre>
<h3>セクション</h3>
<p>$\S$</p>
<pre><code>\S</code></pre>
<h3>$\TeX$ロゴ</h3>
<p>$\TeX$</p>
<pre><code>\TeX</code></pre>
<p>$\LaTeX$</p>
<pre><code>\LaTeX</code></pre>

<h2>使用例</h2>
<h3>2次方程式の解の公式</h3>
<div class="koushiki-box">
  <div class="box-title">2次方程式の解の公式</div>
  <p>
    2次方程式 $ ax^2+bx+c=0 $ の解は、 $ b^2-4ac\geqq0 $ のとき<br>
    \begin{equation*}
      x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
    \end{equation*}
  </p>
</div>

<h3>増減表</h3>
<h4>htmlのtable + MathJax</h4>
<table class="derivative-test-chart">
  <tr>
      <td>\(x\)</td>
      <td>\(\cdots\)</td>
      <td>\(-1\)</td>
      <td>\(\cdots\)</td>
      <td>\(1\)</td>
      <td>\(\cdots\)</td>
  </tr>
  <tr>
      <td>\(f'(x)\)</td>
      <td>\(+\)</td>
      <td>\(0\)</td>
      <td>\(-\)</td>
      <td>\(0\)</td>
      <td>\(+\)</td>
  </tr>
  <tr>
      <td>\(f(x)\)</td>
      <td>\(\nearrow\)</td>
      <td>\(e\)</td>
      <td>\(\searrow\)</td>
      <td>\(e\)</td>
      <td>\(\nearrow\)</td>
  </tr>
</table>
<h4>MathJaxのarrayだけ</h4>
<p>
\begin{array}{|c|c|c|c|c|c|}
  \hline
  x     & \cdots & -1 & \cdots & 1 & \cdots \\ 
  \hline
  f’(x) & + & 0 & – & 0 & + \\ 
  \hline
  f(x)  & \nearrow & e & \searrow & -e & \nearrow \\
  \hline
\end{array}
</p>

<h3>他</h3>
<p><mark>アインシュタイン</mark>は $ E=mc^2 $ の公式を導きました。</p>
<p>
  \begin{eqnarray}
    i\hbar\frac{\partial}{\partial t}\psi(x,t)=
    \left(-\frac{\hbar^2}{2m}+V(x)\right)\psi(x,t)
  \end{eqnarray}
</p>

<h2>参考</h2>
<h3>MathJax</h3>
<h4>一例</h4>
<p>使用例も載っているのでおすすめ。</p>
<ul class="reference-list">
  <li><a href="https://www.tohoho-web.com/ex/mathjax.html" target="_blank">とほほのMathJax入門 - とほほのWWW入門</a>, 参照<time datetime="2024-04-27">2024-04-27</time></li>
  <li><a href="https://easy-copy-mathjax.nakaken88.com/table/" target="_blank">表 | Easy Copy Mathjax</a>, 参照<time datetime="2024-04-28">2024-04-28</time></li>
</ul>

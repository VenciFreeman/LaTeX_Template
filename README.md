# LaTeX_Template
Some LaTeX files as template. Always improving.

## Some Font and Symbol
### Font
```latex
 \texttt{"normal"}      &\texttt{}         & ABCDEFGHIJKLMNOPQRSTUVWXYZ\\
 \texttt{"blackboard"}  &\texttt{\mathbb}  &\mathbb{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"boldface"}    &\texttt{\mathbf}  &\mathbf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"typewriter"}  &\texttt{\mathtt}  &\mathtt{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"roman"}       &\texttt{\mathrm}  &\mathrm{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"sans-serif"}  &\texttt{\mathsf}  &\mathsf{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"calligraphic"}&\texttt{\mathcal} &\mathcal{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"script"}      &\texttt{\mathscr} &\mathscr{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
 \texttt{"fraktur"}     &\texttt{\mathfrak}&\mathfrak{ABCDEFGHIJKLMNOPQRSTUVWXYZ}\\
```

### Color
```latex
 \verb+\color{black}{黑色}+    & \color{black}{黑色}   \\
 \verb+\color{darkgray}{深灰}+ & \color{darkgray}{深灰}\\
 \verb+\color{gray}{灰色}+     & \color{gray}{灰色}    \\
 \verb+\color{silver}{银色}+   & \color{silver}{银色}  \\
 \verb+\color{lightgray}{浅灰}+&\color{lightgray}{浅灰}\\
 \verb+\color{white}{白色}+    & \color{white}{白色}   \\
 \verb+\color{brown}{棕色}+    & \color{brown}{棕色}   \\
 \verb+\color{maroon}{栗色}+   & \color{maroon}{栗色}  \\
 \verb+\color{red}{红色}+      & \color{red}{红色}     \\
 \verb+\color{fuchsia}{桃红}+  & \color{fuchsia}{桃红} \\
 \verb+\color{magenta}{品红}+  & \color{magenta}{品红} \\
 \verb+\color{pink}{粉红}+     & \color{pink}{粉红}    \\
 \verb+\color{orange}{橙色}+   & \color{orange}{橙色}  \\
 \verb+\color{yellow}{黄色}+   & \color{yellow}{黄色}  \\
 \verb+\color{lime}{青柠}+     & \color{lime}{青柠}    \\
 \verb+\color{olive}{橄榄}+    & \color{olive}{橄榄}   \\
 \verb+\color{green}{绿色}+    & \color{green}{绿色}   \\
 \verb+\color{aqua}{水绿}+     & \color{aqua}{水绿}    \\
 \verb+\color{cyan}{青色}+     & \color{cyan}{青色}    \\
 \verb+\color{teal}{靛青}+     & \color{teal}{靛青}    \\
 \verb+\color{blue}{蓝色}+     & \color{blue}{蓝色}    \\
 \verb+\color{navy}{海蓝}+     & \color{navy}{海蓝}    \\
 \verb+\color{violet}{罗兰}+   & \color{purple}{罗兰}  \\ 
 \verb+\color{purple}{紫色}+   & \color{purple}{紫色}  \\ 
```

```latex
\verb+#000+ & \color{#000}{text} & \verb+#005+ & \color{#005}{text} & \verb+#00A+ & \color{#00A}{text} & \verb+#00F+ & \color{#00F}{text}  \\
\verb+#500+ & \color{#500}{text} & \verb+#505+ & \color{#505}{text} & \verb+#50A+ & \color{#50A}{text} & \verb+#50F+ & \color{#50F}{text}  \\
\verb+#A00+ & \color{#A00}{text} & \verb+#A05+ & \color{#A05}{text} & \verb+#A0A+ & \color{#A0A}{text} & \verb+#A0F+ & \color{#A0F}{text}  \\
\verb+#F00+ & \color{#F00}{text} & \verb+#F05+ & \color{#F05}{text} & \verb+#F0A+ & \color{#F0A}{text} & \verb+#F0F+ & \color{#F0F}{text}  \\
\verb+#080+ & \color{#080}{text} & \verb+#085+ & \color{#085}{text} & \verb+#08A+ & \color{#08A}{text} & \verb+#08F+ & \color{#08F}{text}  \\
\verb+#580+ & \color{#580}{text} & \verb+#585+ & \color{#585}{text} & \verb+#58A+ & \color{#58A}{text} & \verb+#58F+ & \color{#58F}{text}  \\
\verb+#A80+ & \color{#A80}{text} & \verb+#A85+ & \color{#A85}{text} & \verb+#A8A+ & \color{#A8A}{text} & \verb+#A8F+ & \color{#A8F}{text}  \\
\verb+#F80+ & \color{#F80}{text} & \verb+#F85+ & \color{#F85}{text} & \verb+#F8A+ & \color{#F8A}{text} & \verb+#F8F+ & \color{#F8F}{text}  \\
\verb+#0F0+ & \color{#0F0}{text} & \verb+#0F5+ & \color{#0F5}{text} & \verb+#0FA+ & \color{#0FA}{text} & \verb+#0FF+ & \color{#0FF}{text}  \\
\verb+#5F0+ & \color{#5F0}{text} & \verb+#5F5+ & \color{#5F5}{text} & \verb+#5FA+ & \color{#5FA}{text} & \verb+#5FF+ & \color{#5FF}{text}  \\
\verb+#AF0+ & \color{#AF0}{text} & \verb+#AF5+ & \color{#AF5}{text} & \verb+#AFA+ & \color{#AFA}{text} & \verb+#AFF+ & \color{#AFF}{text}  \\
\verb+#FF0+ & \color{#FF0}{text} & \verb+#FF5+ & \color{#FF5}{text} & \verb+#FFA+ & \color{#FFA}{text} & \verb+#FFF+ & \color{#FFF}{text}  \\
```

### Continued Fraction
```latex
x = a_0 + \cfrac{1^2}{a_1
        + \cfrac{2^2}{a_2
        + \cfrac{3^2}{a_3 
        + \cfrac{4^4}{a_4 + \cdots}}}}
        


\underset{j=1}{\overset{\infty}{\LARGE\mathrm K}}\frac{a_j}{b_j}
=\cfrac{a_1}{b_1
+\cfrac{a_2}{b_2
+\cfrac{a_3}{b_3
+\ddots}}}

x = a_0 + \frac{1^2}{a_1+}
          \frac{2^2}{a_2+}
          \frac{3^2}{a_3 +} 
          \frac{4^4}{a_4 +} \cdots
```

### Linear Algebra
```latex
 \texttt{\overline}&\overline{AAA}\\
 \texttt{\underline}&\underline{BBB}\\
 \texttt{\widetilde}&\widetilde{CCC}\\
 \texttt{\widehat}&\widehat{DDD}\\
 \texttt{\fbox}&\fbox{EEE}\\
 \texttt{\vec}&\vec{x}\ \mathrm{or}\ \vec{AB}\\
 \texttt{\check}&\check{x}\\
 \texttt{\acute}&\acute{x}\\
 \texttt{\grave}&\grave{x}\\
 \texttt{\bar}&\bar{x}\\
 \texttt{\hat}&\hat{x}\\
 \texttt{\tilde}&\tilde{x}\\
 \texttt{\mathring}&\mathring{x}\\
 \texttt{\dot}&\dot{x}\\
 \texttt{\ddot}&\ddot{x}\\
 \texttt{\dddot}&\dddot{x}\\
```

```latex
\texttt{smallmatrix}&\bigl(\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}\bigr)\\
 \texttt{matrix} &\begin{matrix} 1&2\\3&4\\ \end{matrix} \\
 \texttt{pmatrix}&\begin{pmatrix}1&2\\3&4\\ \end{pmatrix}\\
 \texttt{bmatrix}&\begin{bmatrix}1&2\\3&4\\ \end{bmatrix}\\
 \texttt{Bmatrix}&\begin{Bmatrix}1&2\\3&4\\ \end{Bmatrix}\\
 \texttt{vmatrix}&\begin{vmatrix}1&2\\3&4\\ \end{vmatrix}\\
 \texttt{Vmatrix}&\begin{Vmatrix}1&2\\3&4\\ \end{Vmatrix}\\
```

```latex
\begin{pmatrix}
 1 & a_1 & a_1^2 & \cdots & a_1^n \\
 1 & a_2 & a_2^2 & \cdots & a_2^n \\
 \vdots  & \vdots& \vdots & \ddots & \vdots \\
 1 & a_m & a_m^2 & \cdots & a_m^n \\
\end{pmatrix}
```

```latex
\left[
\begin{array}{cc|c}
  1&2&3\\
  4&5&6\\
\end{array}
\right]

\begin{cases} %\\[2ex]
 a_1x+b_1y+c_1z=\frac{p_1}{q_1} \\[2ex] 
 a_2x+b_2y+c_2z=\frac{p_2}{q_2} \\[2ex] 
 a_3x+b_3y+c_3z=\frac{p_3}{q_3}
\end{cases}
```

```latex
\require{cancel}
\require{enclose}
\verb|y+\cancel{x}| & y+\cancel{x}\\
\verb|y+\bcancel{x}| & y+\bcancel{x}\\
\verb|y+\xcancel{x}| & y+\xcancel{x}\\
\verb|y+\cancelto{0}{x}| & y+\cancelto{0}{x}\\
\verb+\frac{1\cancel9}{\cancel95} = \frac15+& \frac{1\cancel9}{\cancel95} = \frac15 \\
\verb|\enclose{horizontalstrike}{x+y}| & \enclose{horizontalstrike}{x+y}\\
\verb|\enclose{verticalstrike}{\frac xy}| & \enclose{verticalstrike}{\frac xy}\\
\verb|\enclose{updiagonalstrike}{x+y}| & \enclose{updiagonalstrike}{x+y}\\
\verb|\enclose{downdiagonalstrike}{x+y}| & \enclose{downdiagonalstrike}{x+y}\\
```

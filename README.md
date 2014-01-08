latex
=====
\documentclass{article}
\usepackage[cp1252]{inputenc}
\usepackage[polski]{babel}
\usepackage{amssymb}
\usepackage{amsmath}
\usepackage{wasysym} 
\usepackage[pdftex]{graphicx}

\begin{document}

\selectlanguage{polski} 

\noindent \textbf{3. Wyznaczniki Grama.}

 Przedstawiamy teraz wyniki tego paragrafu dla przypadku, gdy jako form/e kwadratow/a wybrano iloczyn skalarny w przestrzeni euklidesowej, tj.
\[A(x;;x)\equiv (x,x).\] 
Wiemy, /ze iloczyn skalarny wektora ze sob/a jest dodatnio okre/slon/a form/a kwadratow/a i na odwr/ot, ka/zd/a symetryczn/a form/e dwuliniow/a, kt/orej odpowiada dodatnio okre/slona forma kwadratowa, mo/zna przyj/a/c za iloczyn skalarny. A zatem ka/zde twierdzenie o dodatnio okre/slonych formach kwadratowych jest jednocześnie pewnym twierdzeniem o wektorach w przestrzeni euklidesowej.

 Niech $e_1,{\ e}_{2\ },\cdots ,\ e_k$  b/ed/a wektorami w przestrzeni Euklidesa. Wyznacznik$\left| \begin{array}{cccc}
(e_1,e_1) & (e_1,e_2) & \cdots  & (e_1,e_k) \\ 
(e_2,e_1) & (e_2,e_2) & \cdots  & (e_2,e_k) \\ 
\cdots  & \cdots  & \cdots  & \cdots  \\ 
(e_k,e_1) & (e_k,e_2) & \cdots  & (e_k,e_k) \end{array}
\right|$

\noindent nazywamy wyznacznikiem Grama tego uk/ladu wektor/ow.

 TWIERDZENIE 4. \textit{Wyznacznik Grama dowolnego uk/ladu wektor/ow jest zawsze wi/ekszy lub r/owny zeru. Jest równy zeru wtedy i tylko wtedy, gdy wektory }$e_1,{\ e}_{2\ },\ \cdots \ ,\ e_k$\textit{ s/a liniowo niezale/zne. }DOW/OD. Przypu/s/cmy, /ze wektory $e_1,{\ e}_{2\ },\ \cdots \ ,\ e_k$ są liniowo niezale/zne. Rozpatrzmy form/e dwuliniow/a.\textit{}
\[A(x;;y)\equiv (x,y).\] 
gdzie $(x,y)$ jest iloczynem skalarnym wektor/ow $x$ i $y$. W/owczas wyznacznik Grama jest wyznacznikiem  ${\triangle }_k$ rozpatrzonym w tym paragrafie (patrz wz/or(7)). Poniewa/z $A(x;;y)$ jest dodatnio okre/slon/a form/a kwadratow/a, wi/ec na mocy twierdzenia 3, ${\triangle }_k>0$. Wyka/zemy, /ze w przypadku wektor/ow liniowo zale/znych wyznacznik Grama jest r/owny zeru. Rzeczywi/scie, je/zeli wektory $e_1,{\ e}_{2\ },\ \cdots \ ,\ e_k$ s/a liniowo zale/zne, to co najmniej jeden z nich, np. $e_k$, jest kombinacj/a liniow/a wektor/ow pozosta/lych
\[e_k=\ {\lambda }_1e_1+{\lambda }_2e_2+\dots +{\lambda }_{k-1}e_{k-1}.\] 
A zatem ostatni wiersz w wyznaczniku Grama jest kombinacj/a liniow/a wierszy pozosta/lych. Wyznacznik ten jest wi/ec r/owny zeru. Tym samym twierdzenie zosta/lo dowiedzione.  Dla przyk/ladu rozpatrzmy wyznacznik Grama dw/och wektor/ow $x$ i $y$
\[{\triangle }_2=\left| \begin{array}{cc}
(x,x) & (x,y) \\ 
(y,x) & (y,y) \end{array}
\right|.\] 
Stwierdzenie, /ze ${\triangle }_2>0$, staje si/e w tym przypadku nier/owno/sci/a Cauchy-Buniakowskiego.

\noindent P${}_{RZYK/LADY}$. 1. W dwumiarowej przestrzeni euklidesowej (na p/laszczy/xnie) wyznacznik
\[{\triangle }_2=\left| \begin{array}{cc}
(x,x) & (x,y) \\ 
(y,x) & (y,y) \end{array}
\right|\] 
ma nast/epuj/acy sens geometryczny: ${\triangle }_2$ jest r/owne kwadratowi pola r/ownoleg/loboku zbudowanego na wektorach $x$ i $y$. Rzeczywi/scie, zgodnie z okre/sleniem iloczynu skalarnego,
\[\left(x,y\right)=\left(y,x\right)=\left|x\right|\left|y\right|{\cos  \varphi \ },\] 
gdzie $\varphi $ jest k/atem mi/edzy wektorami $x$ i $y$.  A zatem
\[{\triangle }_2={\left|x\right|}^2{\left|y\right|}^2-{\left|x\right|}^2{\left|y\right|}^2{{\cos }^2 \varphi \ }={\left|x\right|}^2{\left|y\right|}^2\left(1-{{\cos }^2 \varphi \ }\right)={\left|x\right|}^2{\left|y\right|}^2{{\sin }^2 \varphi \ },\] 
tj. ${\triangle }_2$ jest r/owne kwadratowi pola r/ownoleg/loboku zbudowanego na wektorach $x$ i $y$. 2. W przestrzeni tr/ojmiarowej obj/eto/s/c r/ownoleg/lo/scianu zbudowanego na wektorach $x$, $y$, $z$, jak pokazuje si/e w geometrii analitycznej, jest r/owna warto/sci bezwzgl/ednej wyznacznika
\[\upsilon =\left| \begin{array}{ccc}
x_1 & x_2 & x_3 \\ 
y_1 & y_2 & y_3 \\ 
z_1 & z_2 & z_3 \end{array}
\right|,\] 
gdzie $x_i,y_i,z_i$ s/a wsp/o/lrz/ednymi  wektor/ow $x,\ y,\ z$ w bazie ortogonalnej. Obliczamy kwadrat tego wyznacznika mno/z/ac wiersze. Otrzymamy
\[v^2=\left| \begin{array}{ccc}
x^2_1+x^2_2+x^2_3 & x_1y_1+x_2y_2+x_3y_3 & x_1z_1+x_2z_2+x_3z_3 \\ 
y_1x_1+y_2x_2+y_3x_3 & y^2_1+y^2_2+y^2_3 & y_1z_1+y_2z_2+y_3z_3 \\ 
z_1x_1+z_2x_2+z_3x_3 & z_1y_1+z_2y_2+z_3y_3 & z^2_1+z^2_2+z^2_3 \end{array}
\right|=\left| \begin{array}{ccc}
(x,x) & (x,y) & (x,z) \\ 
(y,x) & (y,y) & (y,z) \\ 
(z,x) & (z,y) & (z,z) \end{array}
\right|.\] 
A zatem wyznacznik Grama wektor/ow $x,\ y,\ z$ jest r/owny kwadratowi obj/eto/sci r/ownoleg/lo/scianu zbudowanego na tych wektorach.

\noindent 


\end{document}



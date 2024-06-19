# Deducoes

## P14) O elemento neutro da soma é único

Se $e \isin \reals$ tal que $a + e = a^{(*)},\hspace{3em} \forall a \isin \reals $ 
então $e = 0$

Tomando a = 0 em * temos

$$a + e = 0 \hspace{3em} (1)$$

Tomando $a = e$ em P2 temos:

$$e + 0 = e$$

Por P4

$$0 + e = e \hspace{3em} (2)$$

De 1 e 2, resulta

$$0 = e$$

## P15) Unicidade do inverso da soma

Dado $a \isin \reals$, se $X \isin \reals$, tem a propriedade de que

$$a + x = 0 \hspace{3em}(*)$$

entao

$$x = -a$$

Iniciando

$$ x = x$$
Por P1

$$x = x+0$$

Por P3

$$x+0 = x + a + (-a)$$

Por P4

Por P3

$$x+0 = x + a + (-a)$$

$$x+0 = a + x + (-a)$$

Pela hipotese *

$$x+0 = 0 + (-a)$$

Por P2

$$x= -a$$

## P16) $-(-a) = a \hspace{1em} \forall \space a \isin \reals$

Para mostrar que $-(-a)$ e $a$ sao iguais, veremos P15, ou seja, provaremos que $-(-a)$ e $a$ sao inversoso de um mesmo numero.
Mas $-a$ e o mesmo de $a$ por P3, basta mostrar que $-(-a)$ é o inverso de $-a$, e isso ocorre por P3.

## P17) $0.a = 0 \hspace{1em} \forall \space a \isin \reals$

$$0a = 0a$$

Por P2

$$0a = 0a + 0$$

Por P3

$$0a = (a + (-a))0$$

Por P9

$$0a = 0a + (-0a)$$

Por P3

$$0a = 0$$


## P18) $(-x).y =-(x.y)$

Mostramos que $(-x).y$ e $-(x.y)$ sao o mesmo aditivo de um mesmo numero

Mas $ -(x.y)$ é o aditivo de $x.y$

Basta mostrar que $-(x).y$ e o mesmo aditivo de $xy$

$$(-x).y = -(xy)$$

Por P9

$$(-x).y + xy = ((-x)+ x).y$$

Por P3

$$((-x)+ x).y = 0y$$

Por P17

$$(-x).y + xy = 0$$

## P19) $(-x).(-y) = (x.y)$

$$(-x)(-y) = (-x)(-y)$$

Por P2

$$(-x)(-y) = (-x)(-y) + 0$$

Por P17

$$(-x)(-y) = (-x)(-y) + 0y$$

Por P3

$$(-x)(-y) = (-x)(-y) + y(x + (-x))$$

Por P9

$$(-x)(-y) = (−x)((−y)+y)+xy$$

Por P3

$$(-x)(-y) = (−x)(0)+xy$$

Por P17

$$(-x)(-y) =0 + xy$$

Por P2

$$(-x)(-y) = xy$$


## P20) $(a.b) = 0$

Supondo $a = 0$

Supondo que $a \neq 0$, mostremos que $b = 0$

Multiplicando por $a^{-1}$

$$a^{-1}(a.b) = a^{-1}.0$$

por P17

$$^{-1}.0 = 0$$

por P1

$$a^{-1}(a.b) = b$$

Logo

$$b = 0$$


## P21) Unicidade do elemento neutro do produto

Se $e \isin \reals$ tal que $a . e = a,\hspace{3em} \forall a \isin \reals$ 
entao e = 1

$$ e.a = a$$

temos a = 1

$$ e.1 = 1$$

$$ e = 1$$

## P22) Unicidade do elemento inverso do produto

Se $e \isin \reals$ tal que $a . x = 1,\hspace{3em} \forall a \isin \reals$ 
entao $x = a^{-1}$


$$x = x$$

Por P6

$$x = x.1$$

Por P7

$$x = x.(a.a^{-1})$$

Pela hipótese

$$x = 1.a^{-1}$$

Por P6

$$x = a^{-1}$$


## P23) $\frac{1}{\frac{1}{a}} = a$ se $a \neq 0$

$$(a^{-1})^{-1} = a$$

Provemos que a e $(a^{-1})^{-1}$ sao o iverso de um mesmo elemento, de $(a)^{-1}$

Como por P7 a é o inverso de $(a)^{-1}$, resta provar que $(a^{-1})^{-1}$ tambem é o inverso de $(a)^{-1}$

Mas por P7 temos que $(a^{-1})^{-1}$ é o inverso de $(a)^{-1}$

## P24) $\frac{1}{ab} = \frac{1}{a}.\frac{1}{b}$ se $a \neq 0$ e $b \neq 0$

Queremos provar que:

$$(ab)^{-1} = (a)^{-1}.(b)^{-1}$$

Podemos afirmar por P7

$$(ab)^{-1} ab = 1$$

Multiplicando dos dos lados por $(b)^{-1}$

$$(ab)^{-1} ab(b)^{-1}= (b)^{-1}$$

Por P5

$$(ab)^{-1} a(b.(b)^{-1})= (b)^{-1}$$

Por P7

$$(ab)^{-1} a = (b)^{-1}$$

Multiplicando dos dos lados por $(a)^{-1}$

$$(ab)^{-1} a(a)^{-1} = (b)^{-1}(a)^{-1}$$

Por P5

$$(ab)^{-1} (a.(a)^{-1}) = (b)^{-1}(a)^{-1}$$

Por P7 temos que

$$(ab)^{-1} = (b)^{-1}(a)^{-1}$$

## P25) $\frac{ac}{bd} = \frac{a}{b}.\frac{c}{d}$ se $b \neq 0$ e $d \neq 0$

Iremos provar:

$$(ac.(bd)^{-1}) = (a.(b)^{-1}).(c.(d)^{-1})$$ 

Tomando a igualdade

$$(a.(b)^{-1}).(c.(d)^{-1}) = (a.(b)^{-1}).(c.(d)^{-1})$$ 

Por P8

$$(a.(b)^{-1}).(c.(d)^{-1}) = (a.c)(b)^{-1}(d)^{-1}$$ 

Por P24

$$(a.(b)^{-1}).(c.(d)^{-1}) = ac.(bd)^{-1}$$ 

Logo

(ac.(bd)^{-1}) = (a.(b)^{-1}).(c.(d)^{-1})

## P26) $\frac{\frac{a}{b}}{\frac{c}{d}} = \frac{a}{b}.\frac{d}{c}$ se $a \neq 0$ $b \neq 0$ e $d \neq 0$

Queremos provar que:

$$(a.(b)^{-1}).(d.(c)^{-1}) = a.((b)^{-1}) (c.(d)^{-1})^{-1}$$ 

Tomando a igualdade

$$a.((b)^{-1}) c.((d)^{-1})^{-1} = a.((b)^{-1}) (c.(d)^{-1})^{-1}$$  

Por P22

$$a.((b)^{-1}) c.((d)^{-1})^{-1} = a.((b)^{-1}) c^{-1}.(d)$$

## P27) $\frac{ad+bc}{bd} = \frac{a}{b}.\frac{d}{c}$ se $b \neq 0$ e $d \neq 0$

Queremos provar que:

$$(a.(b)^{-1})+(c.(d)^{-1}) = (ad + bc).(bd)^{-1}$$

Tomando a igualdade

$$ (ad + bc).(bd)^{-1} = (ad + bc).(bd)^{-1}$$

Por P9

$$ (ad + bc).(bd)^{-1} = (ad)(bd)^{-1} + (bc)(bd)^{-1}$$

Por P8

$$ (ad + bc).(bd)^{-1} = (ab^{-1})(dd)^{-1} + (cd^{-1})(bb)^{-1}$$

Por P7

$$ (ad + bc).(bd)^{-1} = (ab^{-1})1 + (cd^{-1})1$$

Por P6

$$ (ad + bc).(bd)^{-1} = (ab^{-1}) + (cd^{-1})$$



Logo

$$(a.(b)^{-1})+(c.(d)^{-1}) = (ad + bc).(bd)^{-1}$$




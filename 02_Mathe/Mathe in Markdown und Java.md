# Mathe in Markdown

## Formeln darstellen
1. Die Formel in einem `$..$` Zeichen $f(x)=3x^2+7x-15 = 0$ steht im Text.
2. Die Formel in zwei `$$..$$` Zeichen ist abgesetzt vom Text.
    $$a^2+b^2 = c^2$$


## Wurzeln
Mit `$\sqrt{}$` kann eine Wurzel dargestellt werden. Die ecken Klammern `[3]` sind optionale Parameter.

> Bsp: `$\sqrt[3]{5x^2-7}$` zeigt $\sqrt[3]{5x^2-7}$ 

> Bsp: `\sqrt{2}` stellt $\sqrt{2}$ dar


## Brüche darstellen
Mit dem Befehl `$\frac{}{}$`  oder `$\dfrac{}{}$` können Brüche dargsestellt werden.

1. kompakter Bruch im Text $\frac{3x^2-5x+7}{\sqrt{5}}$
2. abgesetzte Formel mit Bruch: $$\dfrac{3x^2-5x+7}{\sqrt{5}}$$


## Indizes verwenden
| Beispiel | Markdown Befehl | Beschreibung |
|---------|-----------------|--------------|
| $U_{eff}$        | `$U_{eff}$`      |tiefgestellter Index|
| $e^{j\omega t}$  | `$e^{j\omega t}$`|hochgestellter Index|

## Formelbuchstaben
| Zeichen | Markdown Befehl | Beschreibung |
|---------|-----------------|--------------|
| $\Omega$  | `$\Omega$`    | große griechische Buchstaben|
| $\alpha$  |` $\alpha$`    | kleine griechische Buchstaben |
| $5\mu m$  | `$5\mu m$ `   | Einheiten|
| $\cdot$   |`$\cdot`       | multiplikation |



## Integrale darstellen
Der Befehl `$\int \limits_{a}^{b} \sin(x) dx$` zeigt die Formel:
$$\int \limits_{a}^{b} \sin(x) dx$$




## Vektoren
Mit dem Befehl `$\vec{x}$` kann ein Vektor $\vec{x}$ dargestellt werden.

### Klammern
Die Befehle `\left(` und `\right)` erzeugen Klammern mit dynamischer Höhe.


### Mathematische Tabellen
Die Umgebung `\begin{array}{c}...\end{array}` erzeugt eine Tabelle mit einer zentrierten Spalte `c`. Ein Array mit 3 Spalten könnte so aussehen.
````latex
$
\begin{array}{lcr}
    Name    & Vorname   & Email \\
    Hammer  & Niko      & hn@webmail.de \\
\end{array}
$
````

>Beispiel:
>$$
>\begin{array}{lcr}
>    Name    & Vorname   & Email \\
>    Hammer  & Niko      & hn@webmail.de \\
>\end{array}
>$$


### Einen ganzen Vektor darstellen
Für einen Verktor werden die dynamischen Klammern, sowie die Arrays benötigt.
````latex
$$\vec{x}=
\left(
\begin{array}{c}
    1  \\
    1  \\
    1
\end{array}
\right)
+
p \cdot
\left(
\begin{array}{c}
    2   \\
    3  \\
    5
\end{array}
\right)
$$
````
$$\vec{x}=
\left(
\begin{array}{c}
    1  \\
    1  \\
    1
\end{array}
\right)
+
p \cdot
\left(
\begin{array}{c}
    2   \\
    3  \\
    5
\end{array}
\right)
$$

## Beträge
>Beispiel: `$|{3x^2}|$` ergibt $|{3x^2}|$


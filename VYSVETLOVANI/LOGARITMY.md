# Použití přirozeného logaritmu (\(\ln\)):

Začneme přepsáním rovnice \(e^x = a\) pomocí přirozeného logaritmu:
\[
\ln(e^x) = \ln(a)
\]
Využijeme vlastnosti logaritmu, že \(\ln(e^x) = x\):
\[
x = \ln(a)
\]
Takto získáme přesný výraz pro \(x\), který vyhovuje původní rovnici.

## Numerické řešení:

Pokud není možné řešit rovnici pomocí přirozeného logaritmu, můžeme použít numerické metody.
Jednou z možností je Newtonova metoda. Začneme s počátečním odhadem \(x_0\) a iterativně upravujeme hodnotu \(x\) podle vztahu:
\[
x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}
\]
Kde \(f(x) = e^x - a\) je funkce, kterou potřebujeme najít kořen, a \(f'(x)\) je její derivace.
Iterujeme, dokud není dosaženo požadované přesnosti.

## Grafické řešení:

Pro jednoduché rovnice, jako je \(e^x = a\), můžeme rovnici vyřešit graficky.
Nakreslíme graf funkce \(y = e^x\) a horizontální přímku \(y = a\).
Průsečík těchto dvou grafů nám dá hodnotu \(x\), která splňuje rovnici.

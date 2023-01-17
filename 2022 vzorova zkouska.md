## úloha 1

Navrhněte efektivní algoritmus, který v zadané posloupnosti celých čísel najde maximální hodnotu, která se neopakuje, a na výstupu vrátí tuto hodnotu i její pozici v posloupnosti (pokud existuje, jinak vrátí výsledek None).

(a) Popište algoritmus (včetně datových struktur, které případně budete používat). Programový kód v Pythonu není povinný, slovní vysvětlení zvoleného postupu řešení naopak povinné je.

(b) Zdůvodněte správnost algoritmu.

(c) Odvoďte asymptotickou časovou a prostorovou složitost (v nejhorším případě).

Příklad: 

vstup: 2 2 6 1 1 7 9 2 5 7 9 

výstup: 6 2 (pozice v posloupnosti číslujeme od 0) 

## úloha 2

Je zadán binární strom, v jehož vrcholech jsou uložena přirozená čísla. Navrhněte efektivní algoritmus, který vypíše čísla uložená ve všech listech stromu, ležících na poslední hladině (tj. listech v maximální vzdálenosti od kořene).

(a) Svoje řešení zapište jako funkci v Pythonu, využijte definici třídy pro vrchol binárního stromu níže,

(b) zdůvodněte správnost,

(c) odvoďte časovou složitost.

```
class VrcholBinStromu:
    """třída pro reprezentaci vrcholu binárního stromu""" 
    def __init__(self, x = None, levy = None, pravy = None)
        self.info = x # data 
        self.levy = levy # levé dítě 
        self.pravy = pravy # pravé dítě
```

## úloha 3

(a) Dokažte nebo vyvraťte. Pro každou dvojici funkcí f,g: N→R+ platí:

Pokud f(n)=O(g(n)), pak 2^f(n)=O(2^g(n)).

(b) Dokažte nebo vyvraťte.

Zadaný prvek lze z binární haldy o n prvcích odstranit v čase O(log n).

Můžete předpokládat, že halda je uložena v poli a prvek je zadán svojí pozicí (tj. indexem) v tomto poli. 

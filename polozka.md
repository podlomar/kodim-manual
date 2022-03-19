# Obecná struktura položky

Každá položka je buď soubor nebo složka s určitou vnitřní strukturou. Pokud je položka složkou, musí v ní být přítomen soubor `entry.yml`, který popisuje uspořádání paložky.

## Název a link

Každá položka musí nějakým způsobem definovat svůj název a takzvaný _link_. Link slouží k identifikaci položky v rámci její nadřazené položky a URL. Adresa položky sestávající s jednotlivých linků pak může vypadat například takto

```
/kurzy/python-1/promenne
```

Pokud je položka složkou, automaticky se jako link bere název složky. V případě souboru je to název souboru bez přípony. 

Název položky musí specifikovat autor podle pravidel dané položky. Pokud název chybí, automaticky se za název dosadí link, který je vždy daný.
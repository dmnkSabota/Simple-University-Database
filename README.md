# Simple-University-Database
Jednoduchá terminálová aplikácia spravujúca databázu univerzity v jazyku JAVA.

## Programy
* **JAVA 18**

## ZADANIE
Předpokládejme osoby v rámci univerzity, kde každá osoba má svoje identifikační číslo, jméno,
příjmení a datum narození. Každá osoba může dostat měsíční finanční ohodnocení. Existují dvě
skupiny osob:

* Studenti, kteří dostávají v rámci studia známky. Pokud je jejich studijní průměr na základě
získaných známek nižší než definovaná hodnota, mohou získat finanční ohodnocení formou
stipendia (tj. nepodléhá dani).
* Učitelé, kterým jsou na výuku přiřazováni studenti. Výše měsíčních finančních prostředků
vynaložených na jednoho zaměstnance se odvíjí od aktuálního počtu studentů vyučovaných
daným zaměstnancem. Za každého studenta se stipendiem, pak získává bonusovou odměnu.
Mzda i odměny jsou realizovány prostřednictvím hrubé mzdy.

Osoba může být na univerzitu přijata buď jako student nebo jako zaměstnanec (tj. není možné, aby
stejná osoba figurovala v roli studenta i zaměstnance). Každý student musí být přiřazen k alespoň
jednomu vyučujícímu. Vyučující mohou mít 0 až neomezený počet studentů.
Vytvořte v programovacím jazyce JAVA ve vývojovém prostředí Eclipse databázový program, který
umožní uživateli následující:

* a) Přidávat nové osoby - uživatel vždy provede výběr osoby (student/učitel) zadá jeho jméno a
příjmení a rok narození. Následně je osobě přiděleno unikátní identifikační číslo. V případě
studenta je nutno jej přidělit některému vyučujícímu/vyučujícím.
* b) Zadat studentovi novou známku – uživatel vybere studenta podle jeho ID a zadá požadovanou
známku.
* c) Propuštění osoby z univerzity – uživatel zadá ID osoby, která je odstraněn z databáze.
* d) Výpis všech učitelů daného studenta.
* e) Přiřazení a odebrání studenta danému vyučujícímu.
* f) Nalezení jednotlivých osob dle jejich ID a výpis ostatních informací (jméno, příjmení, rok
narození, náležející finanční ohodnocení - ve formě čisté mzdy v případě učitelů).
* g) Výpis všech učitelů řazených podle aktuálního počtu studentů.
* h) Pro vybraného učitele výpis všech jeho studentů řazený dle studijního průměru.
* i) Abecedně řazený výpis všech osob (dle příjmení) v jednotlivých kategoriích (student a učitel)
s jejich parametry (ID, jméno, příjmení, rok narození, finanční ohodnocení - ve formě čisté mzdy
v případě učitelů).
* j) Celkové finanční prostředky potřebné k pokrytí jednoho měsíce rozdělené na stipendia a hrubou
mzdu.
* k) Připojení k SQL databázi, přičemž přihlašovací údaje (název databázového souboru) budou
načteny z lokálního souboru.
* l) Načtení všech údajů z SQL databáze.
* m) Uložení všech údajů do SQL databáze.
* n) Vymazání vybrané osoby z SQL databáze.
* o) Načtení vybrané osoby SQL databáze.
 
Program musí dále obsahovat následující:
* Efektivní využití základních vlastností OOP.
* Alespoň jednu abstraktní třídu nebo rozhraní
* Alespoň jednu dynamickou datovou strukturu
* Jednotkový test pro alespoň jednu metodu s tázanou funkcionalitou. 

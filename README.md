# Fashion_Track
# Informační systém pro obchod s oblečením „FashionTrack“

## Krátký popis
Webový informační systém pro maloobchodní prodejnu s oblečením, který umožňuje sledovat prodeje, správu zásob, statistiku návštěvnosti a vyhodnocení výkonnosti prodejů v reálném čase.


## Cíl systému a cílová skupina

### Cíl systému
Zjednodušit a zefektivnit řízení obchodu s oblečením – automatizovat evidenci prodejů, sledovat zásoby, analyzovat návštěvnost a pomoci vedení obchodu dělat informovaná rozhodnutí o objednávkách a marketingu.

### Cílová skupina
- **Majitel / vedoucí prodejny** – správa zásob, přehled prodejů, sledování zisku a výkonnosti zaměstnanců.  
- **Prodavači** – zadávání uskutečněných prodejů, správa pokladny a dostupnosti zboží.  
- **Marketingový manažer** – přístup ke statistikám návštěvnosti a oblíbenosti produktů.

### Řešený problém
Obchod doposud používal ruční evidenci prodejů a skladových zásob v Excelu, což vedlo k chybám, ztrátě přehledu o prodejích a neefektivnímu plánování objednávek.  
„FashionTrack“ nabízí moderní online systém, který tato data automaticky zpracovává a poskytuje přehledné reporty.


## Základní funkce (Role a oprávnění)

### Administrátor / Majitel
- Přidávat, upravovat a mazat produkty (název, velikost, barva, cena, množství).  
- Prohlížet přehled všech uskutečněných prodejů.  
- Generovat reporty o denních, týdenních a měsíčních tržbách.  
- Sledovat, které produkty se nejlépe prodávají.  
- Analyzovat počet zákazníků a průměrnou hodnotu nákupu.  

### Prodavač
- Zadávat nové prodeje do systému (produkt, počet kusů, cena).  
- Označit zboží jako vyprodané.  
- Vytvářet účtenky pro zákazníky.  
- Hlásit stav zásob (když je třeba doobjednat zboží).  

### Marketingový manažer
- Zobrazovat statistiky návštěvnosti obchodu .  
- Analyzovat prodejní trendy.  
- Využívat export dat pro marketingové kampaně.  

## Spravovaná data (příklady)
- **Produkty:** název, kód, kategorie (tričko, kalhoty, bunda…), velikost, barva, nákupní cena, prodejní cena, množství na skladě.  
- **Prodeje:** datum, prodavač, prodané položky, celková částka, způsob platby.  
- **Zákazníci:** anonymní záznamy o počtech návštěv a nákupech (pro analýzu návštěvnosti).  
- **Dodavatelé:** jméno firmy, kontaktní údaje, seznam dodávaných produktů.  
- **Zaměstnanci:** jméno, pozice, přihlašovací údaje, pracovní směny.  
- **Statistiky:** denní tržby, počet zákazníků, průměrná hodnota nákupu, nejprodávanější položky.  

## Možné rozšíření systému
- Integrace s e-shopem (synchronizace online a offline prodejů).  
- Modul pro sledování slev a akcí.  
- Mobilní aplikace pro kontrolu zásob na prodejně.  
- Automatické upozornění při nízkém stavu zásob.  
- Dashboard s grafy a statistikami pro vedení obchodu.  


## Technické poznámky
- Data budou uložena v relační databázi (např. MySQL / PostgreSQL).  
- Systém bude přístupný přes webové rozhraní s přihlášením.  
- Osobní údaje a prodejní data budou zabezpečena dle GDPR.  

# Scientometrie &ndash; kalkulace publikačního výkonu a dělení rozpočtu VaV 2021 (After action review)

>Taky budu ráda, když už to uzavřeme.
Data jsou v globálu správně – drobné nuance se snad vejdou do statistické odchylky.
Příští rok se nám snad již bude pracovat lépe.
Až bude kolo definitivně uzavřeno, radši bych ale znovu prošla metodiku dělení rozpočtu – myslím, že bychom ji v některých místech měli upřesnit, aby bylo jasné jak pro nás, s jakými daty a jak s nimi máme pracovat, tak pro cílové uživatele, aby věděli, co mají vyplňovat v OBD a co má smysl reklamovat k opravě.
Bylo to fakt náročné. Další emoce si ale nechám skutečně až za cílovou pásku. 😊
Díky všem.




## Potřebná vstupní data

* Ohodnocení časopisů podle citačních databází
    * Dataset časopisů WOS (metrika AIS)
    * Dataset časopisů Scopus (metrika SJR)
* Seznam publikací, autorů a jejich afiliací (kvantifikováno prostřednictvím FP)
    * Extrakce dat z databáze OBD


## Metodika výpočtu

* [Odkaz na metodiku](https://vsb-my.sharepoint.com/:w:/g/personal/ryg22_vsb_cz/EaCUfNO7czFMtPMzuadSxjUBpT7F7DIDfgW0Mr-Cp4lhbg?e=sFNdLN)


## Transformace a modelování dat

Vstupní data jsou importována do datového skladu a pomocí Python skriptu podle metodiky transformována do výsledné podoby.


## Sdílení výstupu

Je stanoven termí pro sdílení výstupů.

Výstupy jsou sdíleny na webu univerzity s řízeným přístupem ve formě reportu (s možností stažení data ve formátu CSV nebo XLS). Výstupy jsou:

1. výsledky výpočtů (finální tabulka s dělením financí)
2. vstupní data a mezivýpočty


## Kontrola

Je stanovan termín pro podání připomínek ke vstupním datům a výsledkům a termín pro jejich vypořádání. 

Připomínky se podávají prostřednictvím HelpDesku a jsou řazeny do kategorií:

* vstupní data, metriky časopisů
* afiliace, MP, FP
* metodika/transformace
* ostatní


<hr>
<hr>

## Co se musí stát

* definovat FP ve směrnici OBD
* ujistit se, že institut FP všichni pochopili a doplní ho u záznamů 2020
* stanovit zodpovědné osoby pro vypořádání  


## Co se nesmí opakovat

* přeposílání emailů s dotazy a reklamacemi na různé adresy
* nevědět, v jaké fázi připomínkování a jejich vypořádávání se nacházíme

## Doladit v procesu

* párovat publikace a časopisy podle eISSN pokud nedojde ke shodě s ISSN


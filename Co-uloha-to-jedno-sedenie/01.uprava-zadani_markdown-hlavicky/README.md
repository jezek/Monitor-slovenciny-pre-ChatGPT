# Monitor zo slovenského jazyka a literatúry pre ChatGPT [🔗](../../README.md)

## Co uloha to jedno sedenie

### Uprava zadani a markdown hlavicky

#### Vysledky

| Beh | Datum | Opakovania | Body - vyber | Body - Pis | Body - Celkom | Body - Max | Uspesnost [%] |
| ------------ | ----- | ---------- | ------------ | ---------- | ------------- | ---------- | ------------- |
| [1](./chat.1.md) | 2023-02-{14,17,18,19} | 5 | 68 | 20 | [88](./chat.1.md#celkove-vyhodnotenie) | 150 | 58,666 [*](#poznamka)|

#### Hodnotenie

ChatGPT dosiahol v teste zo slovenského jazyka a literatúry priemernú úspešnosť 58,666%[*](#poznamka).

Porovnie s [vysledkami na ziakoch](https://www.minedu.sk/vysledky-monitoringu-nucem-2021-distancne-vzdelavanie-z-pohladu-deviatakov/).
> Žiaci dosiahli v teste zo slovenského jazyka a literatúry priemernú úspešnosť 61,6 %. Žiaci osemročných gymnázií boli významne úspešnejší (74,1 %) v porovnaní so žiakmi základných škôl (60,5 %). …
>
> Žiaci zo sociálne znevýhodneného prostredia (2,0 % testovaných) dosiahli v slovenskom jazyku a literatúre priemernú úspešnosť 36,3 %. …

#### Postup

1. Overenie, ci ChatGPT [spravne pochopi ulohu s markdown hlavickami](./test-markup-otazky-a-ulohy-s-navodom.chat.md) a vytvorena [sablona](./chat.template.md) s vstupmi pre ulohy a miestami pre vlozenie vystupov.
2. Pre kazdu ulohu vytvorene nove sedenie s ChatGPT na chat.openai.com a zapisanie udajov do hlavicky kopie sablony (Datum, Verzia).
3. Vlozenie vstupu zo sablony a zapisovanie odpovedi do kopie sablony. Viacere odpovede dosiahneme regeneraciou odpovede, alebo regeneraciou otazky.
4. Vyhodnotenie do predpripravenej tabulky v kopii sablony.

#### Poznamka
Uloha cislo [23](./chat.template.md#uloha-23b) bola upravena do omnoho citatelnejsej podoby, keby sme ju ponechali v povodnom zneni, dosiahli by sme o 4 body menej a vysledok by bol 56%.

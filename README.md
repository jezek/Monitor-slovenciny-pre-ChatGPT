# Monitor zo slovenského jazyka a literatúry pre ChatGPT

Bol som zvedavy na akej urovni vie ChatGPT komunikovat po slovensky. Rozhodol som sa ho preto otestovat nejakym testom v slovencine. Na tuto ulohu som si vybral celoslovensky monitor test zo slovenskeho jazyka a literatury pre 9. rocnik zakladnych skol a 4. rocnik 8-rocnych gymnazii.

Test som zadal ChatGPT dvoma sposobmi. Raz cely test v jednom sedeni, s minimalnymi upravami a druhy krat som sa ho na kazdu otazku pytal zvlast a otazky boli upravene tak, aby sa im dalo lahsie rozumiet.

## Vysledky

- Cely test v ramci jednoho sedenia
  1. [Skrty v uvode a miesto pre odpoved pod ulohami](./Cely-test-v-jednom-sedeni/01.skrty-v-uvode-a-miesto-pre-odpoved-pod-ulohami/README.md) - 40%

- Kazda otazka (s relevantnou) ukazkou vo vlastnom sedeni.
  1. [Uprava zadani a markdown hlavicky](./Co-uloha-to-jedno-sedenie/01.uprava-zadani_markdown-hlavicky/README.md) - 58,666% [*](./Co-uloha-to-jedno-sedenie/01.uprava-zadani_markdown-hlavicky/README.md#poznamka)

Porovnie s [vysledkami na ziakoch](https://www.minedu.sk/vysledky-monitoringu-nucem-2021-distancne-vzdelavanie-z-pohladu-deviatakov/).
> Žiaci dosiahli v teste zo slovenského jazyka a literatúry priemernú úspešnosť 61,6 %. Žiaci osemročných gymnázií boli významne úspešnejší (74,1 %) v porovnaní so žiakmi základných škôl (60,5 %). …
>
> Žiaci zo sociálne znevýhodneného prostredia (2,0 % testovaných) dosiahli v slovenskom jazyku a literatúre priemernú úspešnosť 36,3 %. …

## Postup

1. Stiahnutie pdf [testu](./T9-2022_SJL.pdf) a [odpovedi](./kluc_T9-2022_SJL.pdf) z [https://monitor9.zones.sk/testy-testovanie9/](https://monitor9.zones.sk/testy-testovanie9/)

2. Prepisanie testu do [textovej podoby](./T9-2022_SJL.txt).

   Poznamky k prepisu:
   - V otazke 05. Sa pytaju na podciarknute slova. Tie som zapisal ako slovo s _ na oboch stranach a [usitil sa, ze ChatGPT chape, ze to znamena podciarknutie](./Podciarknute-slova.chat.md).
   - V v otazke 06. pytaju na oramovanu cast ukazky. Tu som vyznacil textom v zatvorkach a [uistil sa, ze ChatGPT spravne rozpozna oramovanu cast](./Oznacenie-oramovaneho-textu.chat.md).
   - V otazke 23. som vyznacene chybajuce pismena nahradil podciarnikom _ a [vezera to, ze vie o ktore slova ide](./Chybajuce-pismena.chat.md).

3. Priprava vstupno-vystupnych sablon pre test zo slovenciny.
   - Cely test v ramci jednoho sedenia
     1. [Skrty v uvode a miesto pre odpoved pod ulohami](./Cely-test-v-jednom-sedeni/01.skrty-v-uvode-a-miesto-pre-odpoved-pod-ulohami/chat.template.md)
   - Kazda otazka (s relevantnou) ukazkou vo vlastnom sedeni.
     1. [Uprava zadani a markdown hlavicky](./Co-uloha-to-jedno-sedenie/01.uprava-zadani_markdown-hlavicky/chat.template.md)

4. Zber odpovedi do sablon a vyhodnotenie.
   - Cely test v ramci jednoho sedenia
     1. Skrty v uvode a miesto pre odpoved pod ulohami - Sedenie [1](./Cely-test-v-jednom-sedeni/01.skrty-v-uvode-a-miesto-pre-odpoved-pod-ulohami/chat.1.md), [2](./Cely-test-v-jednom-sedeni/01.skrty-v-uvode-a-miesto-pre-odpoved-pod-ulohami/chat.2.md), [3](./Cely-test-v-jednom-sedeni/01.skrty-v-uvode-a-miesto-pre-odpoved-pod-ulohami/chat.3.md)
   - Kazda otazka (s relevantnou) ukazkou vo vlastnom sedeni.
     1. Uprava zadani a markdown hlavicky - Beh [1](./Co-uloha-to-jedno-sedenie/01.uprava-zadani_markdown-hlavicky/chat.1.md)
5. Vyhodnotenie.
   - Cely test v ramci jednoho sedenia
     1. [Skrty v uvode a miesto pre odpoved pod ulohami](./Cely-test-v-jednom-sedeni/01.skrty-v-uvode-a-miesto-pre-odpoved-pod-ulohami/README.md)
   - Kazda otazka (s relevantnou) ukazkou vo vlastnom sedeni.
     1. [Uprava zadani a markdown hlavicky](./Co-uloha-to-jedno-sedenie/01.uprava-zadani_markdown-hlavicky/README.md)

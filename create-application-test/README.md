# Postup pro vytvoření validního requestu
1. Zkopírujte vzorový dotaz ze souboru `create_application_request.json`
2. Do jednotlivých položek dosaďte data z vybraného řádku souboru `create_application_test_data.xlsx`
>  Řiďte se mapováním **název sloupce ==> název atributu v JSON**
3. Vyplníte-li request všemi daty z daného řádku souboru, získali jste požadovaný request, který lze na testovacím prostředí použít

# Postup pro jednoduché vygenerování nových dat nad rámec přiložených příkladů v Excelu
1. Zkopírujte libovolný řádek souboru `create_application_test_data.xlsx` jako nový a upravte alespoň atribut `order.number` (stačí inkrementace +1) a `customer.phone` (stačí inkrementace +1)
2. Chcete-li změnit i ostatní atributy, můžete, doporučujeme zachovat vzorovou podobu requestu (délku stringů a číselných hodnot, platné formáty tel. čísla, e-mailu a všech URL)

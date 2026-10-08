Steg 1:
![Inställningssidan för ruleset](m5-step1-1.png)
![Sidan för ruleset](m5-step1-2.png)
Skapade en ny regel "lint and test backend" och verifierade att Enforcement status är Active och att bypass-listan är tom.

Steg 2:
![PR med röd check (nekad)](m5-step2.png)
Skapade en pull request där poängen var att blockera merging genom att inkludera en oanvänd import.

Steg 4:
![Actions flik med manuell trigger](m5-step4.png)
Lade till en ett sätt att manuellt starta workflow och verifierade att triggern fungerar.
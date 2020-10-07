---
title: Czech Local Functionality | Microsoft Docs
description: The following topics describe the local functionality in the Czech version of Business Central.
author: v-makune

ms-service: dynamics365-business-central
ms.topic: conceptual
ms.search.keywords: CZ, Czech, Advance payment, Advance invoices, Payables, Finance,  Cash, EET, Cash Desk
ms.date: 12/30/2019
ms.reviewer: v-makune
ms.author: v-makune
---


# Přepočet pohledávek a závazků (Úprava směnných kurzů)

Většina firem v České republice požaduje následující vylepšení, která mají být realizována v oblasti úpravy směnných kurzů při přepočtu pohledávek a závazků:

- Možnost řídit úpravu směnných kurzů samostatně pro bank. účty, zákazníky a dodavatele
- Možnost účtovat úpravu směnného kurzu v detailu nebo souhrnně dle měny
- Možnost spustit úpravu směnných kurzů jako simulaci (bez účtování) v testovacím režimu

Ve standardní sestavě Úprava směnných kurzů je nyní možné:

- Nastavit bankovní účet, zákazníka nebo dodavatele jako filtr
- Vybrat úpravu jen pro zákazníky nebo dodavatele nebo bankovní účty
- Zvolit testovací režim
- Vybrat sumarizaci položek
- Vybrat způsob přenosu dimenzí

Úprava směnných kurzů rovněž obsahuje změněný princip výpočtu pro realizované zisky a ztráty na základě Zákona o daních z příjmů. Tato funkce vypočítá realizovaný zisk nebo ztrátu proti naposledy upraveným částkám.
Tato funkce ve standardní verzi Microsoft[!INCLUDE[d365fin](../../includes/d365fin_md.md)] nejdříve odúčtuje nerealizovaný zisk nebo ztrátu a pak vypočítá realizovaný zisk nebo ztrátu. Výpočet je proveden proti částce v původním kurzu při zpracování platby a faktury.
Nový princip výpočtu zpracovává odchylky oproti aktuálně upravenému směnnému kurzu.
Úprava směnných kurzů byla rozšířena i o český modul zálohy.

## Aktualizace směnného kurzu

Společnosti je umožněno automaticky aktualizovat směnné kurzy měn pomocí funkcí Služby směnného kurzu.
Ty byly vylepšeny o možnost automaticky aktualizovat směnné kurzy měn z ČNB (České Národní Banky).
Uživatel si může v nastavení služby směnného kurzu definovat http adresu služby a další parametry aktualizace směnných kurzů.

## Směnný kurz pro DPH  

Směnný kurz se již v dokladech nachází, ale v České republice musí existovat možnost nastavit v prodejních a nákupních dokladech jiný směnný kurz pro účtování a jiný pro výpočet DPH. Tato funkce přidává pole Kód měny DPH a Směnný kurz DPH na dokladech.  Uživatelé mohou změnit směnný kurz pro DPH před zaúčtováním dokladů.

## Viz Také

[České lokální funkcionality](czech-local-functionality.md)  
[Finance](../../finance.md)
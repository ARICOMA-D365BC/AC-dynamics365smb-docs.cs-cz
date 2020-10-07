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


# Elektronická evidence tržeb (EET)

Elektronická Evidence Tržeb (EET) je evidence tržeb z obchodních činností vyplácených v hotovosti. Informace o těchto transakcích jsou zasílány finančnímu úřadu. V okamžiku platby je vytvořena datová zpráva a odeslána online na portál finanční správy. Odpověď ze serveru je zpráva s jedinečným FIK kódem, který musí být vytištěn na účtence pro zákazníka.

Platební metody obsažené v EET:

- V hotovosti
- Kartou
- Šek
- Cizí směnka
- Jiné podobné typy jako dárkové poukazy, kupóny, bitcoiny atd.

Pro více informací navštivte oficiální portál [ www.etrzby.cz ](http://www.etrzby.cz).

## Použití v [!INCLUDE[d365fin](../../includes/d365fin_md.md)]

Následující prodejní doklady jsou zahrnuty v aplikaci [!INCLUDE[d365fin](../../includes/d365fin_md.md)]:

- Platba prodejní faktury
- Platba zálohové faktury
- Refundace prodejního dobropisu
- Refundace zálohové faktury
- Příjmový pokladní doklad na Finanční účet (bez prodejního dokladu původu)

Při zaúčtování definovaných dokladů (a s definovanou platební metodou) se vytvoří položka EET a na základě funkčního režimu se zpracuje:

- On-line – položka EET je vytvořena a uložena v aplikaci [!INCLUDE[d365fin](../../includes/d365fin_md.md)], je generována zpráva finančnímu úřadu a odeslána na server. Odpověď ze serveru je zpracována, uložena a na účtence zákazníka je vytištěno jedinečné ID transakce generované daňovými úřady.
- Off-line – záznam EET je vytvořen a uložen v [!INCLUDE[d365fin](../../includes/d365fin_md.md)]. Na účtence zákazníka je vytištěno jedinečné ID generované v [!INCLUDE[d365fin](../../includes/d365fin_md.md)] (Identifikace společnosti a dokladu). Záznamy EET jsou zpracovány později pomocí dávkové úlohy.

## Hlavní funkčnosti

- Položky knihy EET - tabulka, kde jsou uloženy a zpracovány registrované dokumenty. Každý záznam obsahuje údaje o prodeji vyžadované daňovými úřady, potřebné pro tisk účtenky a data z elektronické komunikace. Nové záznamy jsou vytvářeny automaticky zaúčtováním dokladů původu.
- Nastavení služby EET
- Nastavení certifikátu
- Terminály EET POS – identifikace registrovaných míst

## Viz také

[České lokální funkcionality](czech-local-functionality.md)  
[Finance](../../finance.md)
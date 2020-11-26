---
title: Czech Local Functionality - Statutory Statements | Microsoft Docs
description: This feature provides the reports - Balance Sheet, Income Statement
author: v-makune

ms-service: dynamics365-business-central
ms.topic: conceptual
ms.search.keywords: CZ, Czech, Advance payment, Advance invoices, Payables, Finance,  Cash, EET, Cash Desk
ms.date: 10/01/2020
ms.reviewer: v-makune
ms.author: v-makune
---


# Statutární výkazy

Společnosti musí vytvořit účetní závěrku v souladu se zákonem o účetnictví č. 563/1991.  Musí vytvořit rozvahu a výkaz zisků a ztrát.
Tato funkce poskytuje následující výkazy:

- Rozvaha
- Výkaz zisku a ztráty

Tyto výkazy používají účetní schémata s definovanou strukturou statutárních výkazů.

V tabulce Název účetního schématu je v české verzi přidáno nové pole:
- Typ účetního schématu – Rozvaha nebo Výkaz zisku a ztrát

V řádku účetních schémat jsou v české verzi přidána nová pole:
- Korekce řady – odkaz na jiný řádek pro sestavení Rozvahy
- Typ Aktivní/Pasivní – Aktiva nebo pasiva pro sestavení Rozvahy
- Vypočti – Vždy, Nikdy, Při kladné, Při záporné

Rozvaha a Výkaz zisků a ztrát jsou často připravovány v šablonách souborů aplikace Excel s potřebným vzhledem pro vytištění výkazu. Uživatelé chtějí mít možnost mapovat definované účetní schémata do připravených šablon aplikace Excel.

Z výše uvedených důvodů tato funkce poskytuje nové nastavení šablon aplikace Excel a mapování položek výkazů. Na základě tohoto nastavení mohou uživatelé exportovat data účetních schémat do souboru aplikace Excel.

## Viz Také

[České lokální funkcionality](czech-local-functionality.md)  
[Statutární informace o společnosti](statutory-company-information.md)
[Finance](../../finance.md)
---
title: Czech Local Functionality - Create VAT control report | Microsoft Docs
description: This section describes local functionality - VAT control report
author: v-makune

ms-service: dynamics365-business-central
ms.topic: conceptual
ms.search.keywords: CZ, Czech, Advance payment, Advance invoices, Payables, Finance,  Cash, EET, Cash Desk
ms.date: 10/01/2020
ms.reviewer: v-makune
ms.author: v-makune
---


# Kontrolní hlášení DPH

Funkcionalita [!INCLUDE[d365fin](../../includes/d365fin_md.md)] byla rozšířena o **Kontrolní hlášení DPH**. Základním formulářem je **Karta kontrolní hlášení DPH**. Položky DPH jsou pro zvolené datum DPH a datum zaúčtování (podle nastavení hlavní knihy) načítány do formuláře podle zvoleného období.  Základní nastavení, tj. Rozdělení kombinací DPH účto skupin do jednotlivých sekcí kontrolní sestavy, je stanoveno ve výkazu DPH. Ke zpracování kontrolního hlášení je nutné nastavit sekce kontrolního hlášení DPH, čísla sazebníku, výkaz DPH, nastavení  stat. vykazování a rozšířené nastavení účtování DPH. Funkcionalita obsahuje:

- **Kartu kontrolní hlášení DPH** - umožňuje vybrat období hlášení.
- **Návrh řádků kontrolního hlášení** - načte řádky kontrolního hlášení pro zvolené období.
- Provedení kontrol - sestava **Kontrolní hlášení DPH - test** - tiskne přehled odpovídající jednotlivým oddílům.
- Možnost exportu hlášení - funkce **Export** exportuje hlášení do souboru.
- Uzavření řádků - funkčnost **Uzavření řádků**  vyplní pole **Uzavřeno dokladem číslo** v řádcích kontrolního hlášení.

## Viz také  
 
[České lokální funkcionality](czech-local-functionality.md)  
[Datum DPH](how-to-setup-vat-date.md)
[Výkaz DPH](vat-statement.md)
[Finance](../../finance.md)
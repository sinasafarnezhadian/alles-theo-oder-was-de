# Marken der Unternehmensgruppe Theo Müller

> Stand: 14.09.2026\
> Zweck: Grundlage für eine Web-App, die prüft, ob eine
> Lebensmittelmarke zur Unternehmensgruppe Theo Müller gehört.

## Verbraucher-Marken der Unternehmensgruppe

Die folgende Liste umfasst die aktuell recherchierten Lebensmittel- und
Verbrauchermarken, die der Unternehmensgruppe Theo Müller bzw. ihren
Tochtergesellschaften zugeordnet werden.

  --------------------------------------------------------------------------
  Marke                   Bereich                 Hinweis
  ----------------------- ----------------------- --------------------------
  Müller / Müllermilch    Molkereiprodukte        Kernmarke der
                                                  Unternehmensgruppe

  Weihenstephan           Molkereiprodukte        Teil der
                                                  Unternehmensgruppe

  Sachsenmilch            Molkereiprodukte        Teil der
                                                  Unternehmensgruppe

  Landliebe               Molkereiprodukte        Seit 2023 Teil der
                                                  Unternehmensgruppe

  Käserei Loose / Loose   Käse                    Teil der
                                                  Unternehmensgruppe

  Bönsel                  Käse                    Marke im Umfeld der
                                                  Käserei Loose

  Harzbube                Käse                    Teil des Käsegeschäfts

  Rusack                  Käse                    Teil des Käsegeschäfts

  Almhof                  Molkereiprodukte        Niederländische Marke

  Elinas                  Joghurt /               Marke der
                          Molkereiprodukte        Unternehmensgruppe

  Lünebest                Molkereiprodukte        Marke der
                                                  Unternehmensgruppe

  Biotiful Gut Health     Fermentierte Produkte / Marke der
                          Drinks                  Unternehmensgruppe

  Homann / HOMANN         Feinkost                Seit 2011 Teil der
                                                  Unternehmensgruppe

  Nadler                  Feinkost / Fisch        Teil der HOMANN-Gruppe

  Hamker                  Feinkost / Saucen /     Teil der HOMANN-Gruppe
                          Dressings               

  NORDSEE                 Fisch / Handelsprodukte Im
                                                  Lebensmitteleinzelhandel
                                                  über die HOMANN-Gruppe

  Weser-Feinkost          Feinkost                Teil der HOMANN-Gruppe

  Lisner                  Feinkost / Fisch        Polnische Marke der
                                                  HOMANN-Gruppe

  Nordfish                Fisch / Feinkost        Polnische Marke der
                                                  HOMANN-Gruppe

  Polarica                Fisch                   Polnische Marke der
                                                  HOMANN-Gruppe

  Graal                   Fisch / Feinkost        Marke der HOMANN-Gruppe

  Berief                  Pflanzliche Produkte    2026 von der
                                                  Unternehmensgruppe Theo
                                                  Müller übernommen;
                                                  Übernahme sollte für die
                                                  App als aktueller
                                                  Konzernstatus geführt
                                                  werden
  --------------------------------------------------------------------------

## Unternehmen und Geschäftsbereiche, die keine klassischen Endverbraucher-Marken sind

Diese Namen können für die Web-App ebenfalls relevant sein, sollten aber
nicht automatisch als „Marke im Supermarktregal" behandelt werden:

-   Culina Group -- Logistik
-   Milk & More -- Milchlieferdienst / Direct-to-Consumer, insbesondere
    UK
-   Naturfarm -- Fruchtverarbeitung
-   Optipack -- Verpackungslösungen
-   Fahrzeugtechnik Aretsried
-   eigene Energieerzeugung / Energiegesellschaften der Gruppe

## Wichtig für die Datenbank

Für die Prüfung einer Marke sollte nicht nur nach dem Markennamen
gesucht werden. Sinnvoll sind mindestens diese Felder:

``` text
brand
parent_company
relationship
category
country
status
valid_from
valid_to
source
source_date
notes
```

### Empfohlene Statuswerte

-   `direct_brand` -- direkte Marke der Unternehmensgruppe
-   `subsidiary_brand` -- Marke einer Tochtergesellschaft
-   `acquired_brand` -- erworbene Marke
-   `regional_brand` -- regional bzw. länderspezifisch
-   `retail_product` -- Handels-/Einzelhandelsprodukt
-   `company_not_brand` -- Unternehmen bzw. Dienstleister, keine
    klassische Konsumentenmarke
-   `historical` -- früher zugehörig, aktuell nicht mehr

## Abgrenzung: Müller Drogeriemarkt

**Nicht mit der Unternehmensgruppe Theo Müller verwechseln:** Die
Drogeriekette **Müller** (Müller Handels GmbH & Co. KG) ist ein
eigenständiges Unternehmen. Deren Eigenmarken wie Aveo, Body&Soul, Terra
Naturi, Beauty Baby usw. gehören **nicht** zur Unternehmensgruppe Theo
Müller.

## Quellen

1.  Unternehmensgruppe Theo Müller -- Karriere-/Unternehmensseite: Die
    Gruppe nennt unter anderem Müller, Milk&More, Weihenstephan,
    Sachsenmilch, Loose und HOMANN als Marken bzw. Geschäftsbereiche.
2.  Unternehmensgruppe Theo Müller / HOMANN: HOMANN gehört seit 2011 zur
    Unternehmensgruppe; zum Portfolio werden HOMANN, Nadler, NORDSEE,
    Hamker, Weser-Feinkost sowie die polnischen Marken Lisner, Nordfish
    und Polarica gezählt.
3.  Aktuelle Berichterstattung 2026 zur Markenwelt der
    Unternehmensgruppe: nennt unter anderem Weihenstephan, Sachsenmilch,
    Landliebe, Elinas, Lünebest, Biotiful Gut Health, Almhof, Loose,
    Harzbube, Bönsel, HOMANN, Nadler, Hamker, Graal und Lisner.
4.  Die Zuordnung sollte vor einem produktiven Einsatz der App
    regelmäßig aktualisiert werden, insbesondere bei Übernahmen und
    Verkäufen.

## Hinweis zur Vollständigkeit

„Alle Müller-Marken" ist keine vollständig eindeutige Kategorie. Die
Unternehmensgruppe besitzt neben bekannten Verbraucher-Marken auch
Tochterunternehmen, regionale Marken, Produktionsunternehmen,
Logistikunternehmen und Dienstleistungen. Für eine Markenprüf-App sollte
deshalb zwischen **Marke**, **Tochterunternehmen**, **Dienstleister**
und **historischer Beteiligung** unterschieden werden.

Diese Datei ist als Ausgangsdatenbestand gedacht und nicht als
abschließendes rechtliches Konzernregister.

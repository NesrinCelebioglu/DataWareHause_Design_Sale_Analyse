# Global Superstore – Data Warehouse & Vertriebsdashboard (Power BI)

## Projektübersicht
In diesem Projekt wurde ein Data-Warehouse-Modell im Star-Schema entwickelt und ein interaktives Vertriebsdashboard in Power BI erstellt – basierend auf dem Global Superstore Datensatz.

Schwerpunkte:
Dimensionale Datenmodellierung (Fakt- & Dimensionstabellen)  
Incremental Refresh  
DAX-Berechnungen & Zeitintelligenz  
KPI-basierte Vertriebsanalyse  

## Datenmodell

### Faktentabelle
Sales  
Profit  
Quantity  
Shipping Cost  
Return Flag  

### Dimensionstabellen
Kunde  
Produkt  
Region  
Order Date  
Ship Date  

✔ One-to-Many-Beziehungen  
✔ Single-Direction-Filterung (Dim → Fact)  
✔ Performance-optimiertes Modell  

## Performance-Optimierung

Incremental Refresh  
Aktualisierung nur der letzten 12 Monate  
Historische Daten bleiben im Cache  
Schnellere Ladezeiten & skalierbare Architektur  

## DAX-Highlights

Berechnete Spalten  
Prep Days  
Profitability Category  

Zentrale Measures  
Total Sales  
Total Profit  
Average Profit  
Profitable Sales  
Return Rate  

Zeitintelligenz  
Sales YTD  
Sales QTD  
Sales Last Year (LY)  

## Dashboard-Funktionen

KPI-Karten (Sales, Profit, Kunden, Bestellungen)  
Umsatz nach Markt  
Umsatz nach Kategorie  
Quartalsvergleich inkl. Vorjahr  
Filter: Country, State, City  

## Technologien

Power BI | Power Query | DAX | Star Schema | Incremental Refresh  

## Demonstrierte Kompetenzen

Data-Warehouse-Design  
Business-Intelligence-Entwicklung  
DAX & Zeitintelligenz  
Performance-Optimierung  
Datengetriebene Entscheidungsunterstützung  

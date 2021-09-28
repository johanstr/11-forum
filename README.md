# MODULE 11 - Web Applicaties 1
  
## Inleiding
Deze git-repository is bedoeld voor de instructiemomenten voor module 11. Hier vind je dus de bestanden waarmee samen tijdens de instructiemomenten een forum bouwen in vanilla PHP.  

### Code binnenhalen om te experimenteren  

1. STAP 1  
   Open een terminal venster  
2. STAP 2  
   Tik in de terminal de onderstaande opdracht in:  
```bash
git clone https://github.com/johanstr/forum-klas1 forum
```
---
## De mappen in deze repository
* design  
Bevat alle HTML, CSS en JavaScript bestanden die nodig zijn om ons forum vorm te geven in een browser. Maar de bestanden hier zijn niet bedoeld om hier met PHP je forum te gaan programmeren. De bestanden zijn het resultaat van voorwerk (namelijk je user interface klaar hebben staan voordat we gaan programmeren).  
  
* dev  
Alleen in deze map gaan we programmeren. Ook deze map heeft weer submappen, ieder met hun eigen doel/nut. In de map **dev** gaan we alle zichtbare pagina's in PHP bouwen. We maken hier geen **.html** bestanden meer, maar uitsluitend **.php** bestanden. Ook al zal een **.php** bestand uitsluitend HTML code bevatten.  
  
---
## De database
In de repository (repo) vind je ook het bestand forum_klas1.sql. Met dit bestand kun je een database vullen met dummy data, zodat we tijdens het ontwikkelen van onze applicatie ook 
resultaten op het scherm zien.  
  
Start XAMPP, en dus start Apache en MySQL in XAMPP. Open daarna in de browser phpMyAdmin (dit is een beheerpaneel van de databaseserver) en maak hier een database aan met de naam **forum**.  
  
Importeer nu het bestand forum_klas1.sql.
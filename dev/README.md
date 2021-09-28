# De root van ons project

## De map dev
De map __dev__ is de root van onze applicatie. In deze map plaatsen we uitsluitend de PHP-bestanden die verantwoordelijk zijn voor de weergave van een pagina in onze applicatie.  
  
<br />  

### Wat plaatsen we in deze map?
Je vindt dus in deze map bijvoorbeeld de volgende bestanden:  
* index.php  
De startpagina van onze applicatie. Hierin willen we een overzicht van alle threads in de database.  
  
* login.php  
Dit bestand doet niks anders dan het tonen van een login-formulier. Het afhandelen van een login laten we over aan een ander PHP-bestand in de map __app__, zoals bijvoorbeeld het bestand __login_afhandelen.php__.  
  
* register.php  
Dit bestand doet niets anders dan het weergeven van een registratie formulier. Ook hier geldt weer dat we de afhandeling van een registratie (opslaan van de nieuwe gebruiker) aan een ander bestand in de map __app__ overlaten, bijvoorbeeld: __register_afhandelen.php__.  
  
* thread.php  
Dit bestand laat een pagina zien met alle topics van 1 thread.  
  
* rules.php  
Dit bestand laat een static pagina zien met onze forum-regels.  

---
## De map app
Dit is een map waarin we alle PHP code plaatsen die niet direct verantwoordelijk zijn voor het produceren en laten zien van een pagina of delen van UI. Deze map is een sub map van de map __dev__.  

We richten deze map ook weer in met sub mappen. Het hoe en waarom wordt tijdens de instructiemomenten uitgelegd.  

---
## Andere sub mappen
In de map __dev__ maken we ook nog een aantal sub mappen, namelijk:  
* __css__  
  De map waarin we onze stylesheet(s) plaatsen.  
* __img__  
  In deze map plaatsen we alle media bestanden, zoals afbeeldingen, die we in onze applicatie willen gaan gebruiken.  
* __fonts__  
  In deze map plaatsen we alle font bestanden die we in onze applicatie willen gaan gebruiken.  
* __js__  
  In deze map plaatsen we alle ondersteunde JavaScript bestanden.
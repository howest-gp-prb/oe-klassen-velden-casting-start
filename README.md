# Oefening Casting : klassen en velden

Bekijk onderstaand filmpje aandachtig zodat je weet wat er van je verwacht wordt.  
  
In deze oefening maak je 3 klassen aan :   
  * Actor
    * id : string  
    * lastname : string  
    * firstname : string  

    Je voorziet een constructor die zowel lastname als firstname ontvangt.  
    In de constructor zorg je er voor dat het veld id automatisch gevuld wordt met een unieke waarde.  
    Je kan hiervoor volgende instructie gebruiken :  id = Guid.NewGuid().ToString()  
    Je overschrijft de ToString methode en toont in de plaats de naam en de voornaam.  

  * Movie
    * id : string
    * name : string
    * year : int
    
    Je voorziet een constructor die zowel de name als year ontvangt.
    In de constructor zorg je er voor dat het veld id automatisch gevuld wordt met een unieke waarde.  
    Je kan hiervoor volgende instructie gebruiken :  id = Guid.NewGuid().ToString()  
    Je overschrijft de ToString methode en toont in de plaats de naam en het jaar.  

  


![afbeelding](assets/oe-klassen-casting.gif)

  
  

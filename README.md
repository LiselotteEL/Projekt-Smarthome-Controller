##Øvelse - Smarthome Controller
Du skal udvikle en IOT-smarthome styresystem til din makkers hjem i Java. Du skal besvare skriftligt i en .md fil på din GitHub i projektet Smarthome 1.

1. 	Identify the problem domain - Interview din makker om hans hjem, og find ud af, hvad der kunne styres i hjemmet og hvordan. 
    Beskriv kort opgaven med minimum 5 connected 	appliances.
2. 	Use case - Beskriv 1-2  use-cases, som viser, hvordan systemet vil blive brugt af din makker i virkeligheden.  
3. 	Design your classes  - Beskriv nu de klasser, som er nødvendige for applikationen.
4.	Abstraction  and interfaces - Find muligheder for abstraktioner, interfaces og reusable design patterns blandt klasserne. 
    Vis løsningen til din makker, og få hans accept.
5. 	UML - Tegn UML’en eller opret klasserne i koden, og træk UML’en automatisk.
6. 	S.O.L.I.D. - Beskriv, hvordan dit design lever op til SOLID principperne. 
7. 	Ekstra - Find allerede eksisterende klasser, som kan indgå i løsningen.



**1.** 	Lys, varme, ovn, kaffemaskine, TV
	Alle ovenstående appliances skal kunne betjenes via app remotely;
	Lys skal kunne tændes og slukkes. Lys skal kunne tidsindstilles. Lys skal kunne justeres i 	lysstyrke.
	Radiatorer skal kunne tændes og slukkes. Radiatorer skal kunne indstilles på specifik grad 	celcius.
	Ovn skal kunne tændes og slukkes. Ovn skal kunne indstilles på grader. Ovn skal kunne 	indstilles på varmetype (alm. ovn, varmluft mm.)
	Kaffemaskine skal kunne tændes/slukkes.
	TV skal kunne tændes/slukkes.

**2.** Use case - Beskriv 1-2  use-cases, som viser, hvordan systemet vil blive brugt af din makker i virkeligheden. 	
Bruger har mulighed for at kunne betjene sit lys uden at være fysisk tilstede i huset. Hvis bruger kommer hjem efter mørkets         frembrud, kan lyset tændes med app til bruger kommer hjem; bruger kan også anvende fjernbetjent lys ved ønsket om, at det skal ligne, at der er nogen hjemme i huset.
Bruger kan anvende appen til at styre sit lys - både om det skal være slukket/tændt og 	hvilken lysstyrke i hele huset, men ved         nemheden fra én samlet app.
	
  
  Bruger har mulighed for at kunne betjene varmen uden at være fysisk tilstede i huset. 	Bruger har mulighed for at kunne skrue ned for   varmen ved fravær og skrue op for varmen	igen til ønsket temperatur inden bruger kommer hjem.
	Bruger kan anvende appen til at slukke/tænde for radiator(er) samt indstille til en specifik grad celcius.

  Bruger har mulighed for at tænde/slukke for sin ovn uden at være fysisk tilstede i huset, fx med ønsket om at forvarme ovnen til         bruger kommer hjem.
  Bruger kan indstille grader celciius og indstille varmetypen.
    
    
    
**3.** Design your classes  - Beskriv nu de klasser, som er nødvendige for applikationen.

Lys:
Superclass: Light.java 
supclass: KitchenLight.java , DinningroomLight.java , LivingroomLight.java , HallLight.java , BedroomLight.java

Varme:
Superclass: Radiator.java
supclass: RadiatorStudy.java , RadiatorBathroom.java , RadiatorBedroom.java





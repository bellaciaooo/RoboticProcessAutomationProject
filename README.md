# RoboticProcessAutomationProject
AUTOMATIZAREA GESTIONARII TIMPULUI SI A ACTIVITATILOR ZILNICE

Robotul rulează de luni până vineri la ora 18 și cere utilizatorului să introducă următoarele informații:
1. Numele utilizatorului.
2. Data inregistrarii.
3. Numărul de ore lucrate în ziua respectivă.
4. O scurtă descriere a activităților desfășurate în ziua respectivă.
  
Robotul efectueaza următoarele acțiuni:
- Verifica dacă data curentă este în intervalul de luni până vineri și ora este după ora 18. Dacă nu este, să afișeze un mesaj de eroare și să încheie programul.
- Verifica dacă utilizatorul a introdus un număr valid de ore lucrate (un număr pozitiv și mai mic sau egal cu 24) sau daca data introdusa este in format valid (dd/mm/yyyy). Dacă nu este valid, să afișeze un mesaj de eroare și să solicite reintroducerea informațiilor.
- Inregistreaza datele introduse într-un fișier Excel cu următoarea structură:
     - Pe prima coloană, data curentă.
     - Pe a doua coloană, numărul de ore lucrate.
     - Pe a treia coloană, descrierea activităților.
- Fișierul este salvat cu numele de formă: "NUME_UTILIZATOR_LUNA_ANUL.xlsx".
După înregistrarea datelor, robotul poate oferi utilizatorului opțiunea de a introduce informații pentru o altă zi sau de a încheia programul.

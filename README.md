//Romana 
Proiectul este conceput pentru a facilita organizarea spațiului de lucru pe fiecare etaj, în ceea ce privește birourile și sălile destinate angajaților. Fiecare angajat poate efectua o singură rezervare activă, având posibilitatea de a o anula din tabloul de bord al profilului. În situația în care un utilizator are deja o rezervare activă, platforma îi restricționează posibilitatea de a selecta un nou loc (butoanele de pe hartă devin inactive). În cazul în care nu există nicio rezervare activă, utilizatorii sunt liberi să aleagă oricare dintre locurile disponibile.

Interfața meniului este simplă, oferind o hartă interactivă cu butoane reprezentative pentru fiecare loc de pe etaj. Prin intermediul inteligenței artificiale, se furnizează o predicție referitoare la probabilitatea de a găsi un loc liber la o anumită dată.

Proiectul se dovedește util, contribuind la o organizare eficientă a spațiului și a angajaților, care nu mai trebuie să caute un loc disponibil în întreaga sală. Pe hartă, locurile disponibile sunt marcate vizual cu culoarea verde, în timp ce cele ocupate sunt marcate cu culoarea roșie.

Pentru a accesa aplicația, utilizatorii trebuie să dețină un cont, pe care îl pot crea direct pe site-ul aplicației. După crearea contului, ei pot vizualiza harta și pot aloca/dezaloca un loc.

Proiectul funcționează pe partea de backend cu Python (utilizând biblioteca Flask), iar baza de date este gestionată cu SQLite. Interfața de utilizator este realizată cu ajutorul HTML5, CSS și folosește framework-ul Bootstrap. Partea de inteligență artificială este integrată tot în Python, folosind algoritmul Logistic Regression, fiind antrenată cu datele primite.

//Engleza
The project is designed to aid in the organization of workspace on each floor, encompassing desks and employee rooms. Each individual can have only one active reservation, which they can cancel through their Profile dashboard. If a user already has an active reservation, the platform does not allow them to select a new spot (the buttons on the map become unresponsive). Conversely, if no reservation is active, they are free to choose any available spot. The menu interface is straightforward, featuring an interactive map with representative buttons for each spot on the floor. With the assistance of AI, a prediction regarding the probability of finding an available seat on a given date is provided.

The project proves beneficial by promoting efficient space organization and aiding employees in avoiding the hassle of searching for an available spot throughout the room. Available spots are visually indicated on the map in green, while occupied spots are marked in red.

To access the application, users need to create an account, which they can do directly on the application's website. After creating an account, they can view the map and allocate/deallocate a spot.

The project operates on the backend using Python (utilizing the Flask library), with the database created using SQLite. The frontend is developed using HTML5 and CSS, with the Bootstrap framework also utilized. The AI component is integrated into Python, employing the Logistic Regression algorithm, and trained with the provided data.

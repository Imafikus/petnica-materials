Linearna algebra 101
==
Aleksa Tešić, 5.7.2018.

IS Petnica

---
Šta će nama linearna?
==
---
Šta će nama linearna?
==
* Lep način da se definiše nekakav prostor
* Lako se implementira u računarskom sistemu
* I hardverski i softverski
---
Osnovne komponente
==
* Vektori
* Matrice
---
Tačka u 2D
===
* Vektor položaja
---
Tačka u 3D
===
* Vektor položaja
---
Možemo generalizovati na N dimenzija!!!
===
---
Šta je zapravo vektor?
===
---
Vektor je osnovna gradivna komponenta vektorskog prostora
===
---
Čime je određen vektor?
===
---
Čime je određen vektor?
===
* intenzitetom
* pravcem
* smerom
---
Intenzitet vektora
===
* možemo da kažemo da je to dužina vektora
---
Pravac vektora
===
* Prava sa kojom se poklapa
---
Smer vektora
===
* Na koju ,,stranu" ide
---
Operacije sa vektorima
===
* Sabiranje vektora
	* pravilo trougla
	* pravilo paralelograma 	
---
Operacije sa vektorima
===
* Skalarni proizvod
* Množenje vektora skalarom
* Vektorski proizvod
* Norma vektora
---
Skalarni proizvod
===
  $x\cdot y=|x||y|\cos w$ - 2D
  
  $x\cdot y=x_1y_1+x_2y_2+x_3y_3w$

---

Kolinearni vektori
===
* imaju isti pravac
---
Ortogonalni (normalni) vektori
===
* ugao između njih je 90 stepeni
---
A šta je sad to vektorski prostor?
===	
---
A šta je sad to vektorski prostor?
===
* prostor u kome su "lepo" definisani množenje skalarom i sabiranje vektora
* 2D, 3D su vektorski prostori
* Koliko dimenzija, toliko vektora(ortovi)
---
Baza vektorskog prostora?
===
---
Baza vektorskog prostora?
===
* Minimalni skup vektora potreban da pozicioniramo tačku u tom prostoru 
---
Linearni Operatori (Transformacije)
===
---
Linearni Operatori (Transformacije)
===
* Preslikava jedan vektorski prostor u drugi
* tj. Transformiše vektorski prostor
* Gledajte na njih kao na funkcije
---
Šta važi za linearne transformacije?
===
* $A(x + y)=A(x)+A(y)$
* $A(\alpha x)=\alpha A(x)$
* $x ,y$ pripadaju vektorskom prostoru 
* $\alpha$ je skalar  
---
Šta sve može da bude linearni operator?
===
---
Šta sve može da bude linearni operator?
===
* Sve što možemo da predstavimo kao vektorski prostor
---
Generalizacija *svega* na vektorske prostore! 
===
---

A šta će nama sad ovo?
===
---
Uzmemo bilo koju bazu prostora
===
---
Možemo dobiti bilo koju drugu bazu tog istog prostora 
===
---
Šta sam ja upravo rekao?
===
* Primenom konačnog broja linearnih operatora(transformacija) ćemo jedno bazu transformisati u drugu
* Imamo zapravo kompozicije funkcija
* Iste su dimenzije, pa je regulator regularan
---
Regularni operatori
===
* Imaju inverz, tj. postoji $A^{-1}$
* Rade nad vektorskim prostorima koji imaju istu dimenziju
---
Regularni operatori nam omogućuju da manipulišemo prostorom
===
---
Regularni operatori nam omogućuju da manipulišemo prostorom
===
* Translacije, rotacije, skaliranje, refleksija...
---
Matrice (Kvadratne)
===
---
Matrice su izomorfizmi regulularnih operatora
===
---
WTF is izomorfizam!?
===
---
WTF is izomorfizam!?
===
* Dve (ili više) stvari koje se ponašaju potpuno isto
* Npr. neki grafovi
* Matrice i regularni operatori
---
Matrice vs. Regularni operatori
===
* Primena operatora se svodi na množenje matrice matricom tog operatora
* $M^{-1}=A^{-1}$
* Jedinična matrica je neutral za množenje
* Nula matrica neutral za sabiranje
* Kompozicija operatora je zapravo samo množenje
 više matrica 
---
Množenje matrica
===
---
Determinanta matrice
===
---
Determinanta matrice
===
* Pokazuje da li transformacija čuva odnos ili ne
* Sarusovo Pravilo
* La Granž
---
Što ovo mnogo dobro radi na kompu?
===
---
Paralelizacija!
===
---
Pitanja?
===
---




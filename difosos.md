##1.5 Característiques dels llenguatges més difosos
  
1- Característiques de la programació estructurada
  
**- Claredat:** Tot el codi ha de estar lo suficientment informat per a que sigui fàcil d'entendre i verificar (comentaris, variables amb noms comprensibles, procediments entenedors...).
  
**- Teorema de l'estructura:** Qualsevol programa es pot escriure utilitzant les tres estructures bàsiques de control:

* **Seqüencia:** Instruccions executades successivament, una darrere l’altra.

* **Selecció:** Instrucció condicional amb doble alternativa, de la forma "si condició, llavors SentènciaA, sinó SentènciaB".

* **Iteració:** El bucle condicional "mentre condició, fes SentènciaA", que executa les instruccions repetidament mentre la condició es compleixi.

**- Disseny descendent:** Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall. En altres paraules, es la partició d'un problema gran en molts de petits, fent així que sigui més fàcil de resoldre cadascun per separat.

**- Programació modular:** Ens referim a la divisió d’un programa en parts més manejables i independents.

Hi han dos maneres de dividir un programa:

* **Procediments:** El bucle condicional "mentre condició, fes SentènciaA", que executa les instruccions repetidament mentre la condició es compleixi.

* **Funcions:** El bucle condicional "mentre condició, fes SentènciaA", que executa les instruccions repetidament mentre la condició es compleixi.

**- Tipus abstractes de dades (TAD):** Son un nou tipus de dades creades per el programador per facilitar la complexitat de les dades a l'hora de definir-les i poder fer-ne les seves operacions.

2- Característiques de la programació orientada a objectes

L’**orientació a objectes** (en endavant, OO) és un paradigma de construcció de programes basat en una abstracció del món real.

Un **objecte** és una combinació de dades (anomenades **atributs**) i mètodes (**funcions i procediments**) que ens permeten interactuar amb ell. En OO, doncs, els **programes són conjunts d’objectes que interactuen entre ells** a través de missatges (crides a mètodes).

La programació orientada a objectes es basa en la integració de 5 conceptes:

**Abstracció:** Es defineixen les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari.
* **Exemple**: classe.

**Encapsulació:** Es la capacitat que tenen els objectes per permetre o no ser accesibles des d'afora.
* public, protect, private.

**Modularitat:** Estant el programa separat en mòduls, quan es modifica un d'ells, no afecta als altres.

**Jerarquia:** Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són l’herència i l’agregació:

* **Herència**: Es permet que una classe tingui els mateixos mètodes/variables que una altre, i a més, que pugui tenir les seves propies.

**Exemple**: Treballador **es** una persona i pot **heredar** perfectament de persona.

* **Agregació**: Es quan un objecte està format per la combinació d'altres objectes o components. 

**Exemple**: Un ordinador es **composa** de una CPU, una pantalla, un teclat, etc... aquests components **no tenen sentit** sense l'ordinador.

**Poliformisme:**  Es la capacitat que tenen els mètodes per fer-ne sobrecàrrrega (overload). L'overload es quan un mètode es pot implementar varies vegades, però amb paràmetres diferents.

**Exemple**: Mètode DemanarDades(), pot ser **DemanarDades(String nom, String cognom, String cognom2)** i a la vegada es pot fer **sobrecàrrega** del mateix mètode d'aquesta manera: **DemanarDades(String nom, String cognom)**.

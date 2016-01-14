
##1.4. Paradigmes de programació.
  
1- Paradigma Estructurat

  * **Seqüencia:** Instruccions s'executen una darrera l'altre.
  * **Decisió/Selecció:** El programa pot tenir diferents decisions (if).
  * **Repetició:** El programa es capaç de produir repeticions (while,for).

  Exemples de llenguatge estructurat: C, ALGOL, Pascal.

  * Tipus d'estructures de control:
	  * Seqüencia.
	  * Selecció.
	  * Iteració.

* **Disseny Descendent**: es tracta de modular el programa mitjançant funcions o procediments fent aixi que cada part del programa tingui un únic objectiu o tasca.

  * Problemes de la programació estructurada:
    * Funció <-- dades per paràmetre (Dades compartides en tot el programa)
    * Disseny : es mes difícil pre-definir un disseny abans de començar a programar.
    * Reutilització de codi: si repeteixes en molts llocs  un mateix bloc de codi, i has de canviar un valor o variable,           hauries d’arreglar-ho en tots els llocs on l’has copiat.
    
2- Paradigma de objectes (Programacio orientada a objectes)

* Abstracció del món real: intentar traslladar a un programa orientat a objectes, coses, objectes del món real.
  
* També compleixen el llenguatge estructurat.
  
La programació orientada a objectes te les següents caracteristiques:

  * **Encapsulació**: Es la capacitat d'ocultar atributs o mètodes d'una classe a una altra. 
  * **Modularitat**:  El programa ha d'estar separat en mòduls (funcions o procediments), un per a cada objectiu.
  * **Jerarquia**: Tot s'ha d'executar en un ordre que sigui correcte (funció a, després funció b).
  * **Polimorfisme**: Permeten la sobrecarrèga d'un mètode (mètode persona(String nom), mètode persona(String nom, int edat))

Exemples llenguatges: C++, Java, C# 

3- Paradigma funcional

  El **paradigma funcional** està basat en un **model matemàtic**. La idea és que el **resultat d’un càlcul és l’entrada del     següent**, i així successivament fins que una composició produeixi el resultat desitjat.
  
  Exemple: **Recursivitat**.

4- Paradigma lògic

  El **paradigma lògic** té com a característica principal **l’aplicació de les regles de la lògica** per inferir conclusions a   partir de dades.
  
  Es basa en comprovar la situació i depenent d'aquesta, farà una opció o en farà d'un altra.
  
  Exemples:
  
  * Backtracking
  
  * I.A (Exemples: 4 en ratlla, escacs)


##1.2 Codi font, codi objecte i codi excutable: màquines virtuals

**Codi font:** fitxers de text on está el codi que ha fet el programador, pero que encara no pot entendre el processador.

  Per a que aquest codi el pugui entendre, es necessitarà fer una **compilació**.

**Codi objecte:** es la traducció que es fa amb el codi font, per convertir-lo a codi màquina, però falta un pas més per a que es pugui executar, fer-ne un **enllaç**.

**Codi executable:** aquest codi finalment esta preparat per **executar-se en la màquina**. Quan s'agafen els fitxers amb codi objecte i els enllaçem tots amb **l'enllaçador** (o **linker**). Això fa que estigui completament traduït i es pugui executar.

**Enllaçador:** es l'encarregat de incloure les **funcions de les llibreries** i d'ajuntar tots els fitxers per crear el **fitxer executable.**

Els programes es separen en dos grups:

* **Compilats:** S'agafa el codi font i es compila, aconseguint el codi objecte. Una vegada tenim tots els fitxers compilats, l'enllaçador crea el fitxer executable.

  * Avantatges: Si s'ha de compilar algun fitxer, no es necessari compilar tot el programa, només farà falta compilar aquest i   després tornar a enllaçar.
  
  * Desventatges: S'han de crear per a cada processador, un programa d'un no funcionarà en un altre.
  

* **Interpretats:** Agafen el codi font i fan una **pre-compilació**, en la qual es tradueix a un llenguatge que pot entendre   l'intèrpret, que serà l'encarregat de executar el programa (**Màquina Virtual de Java**).

  * Avantatges: Són **multi-plataforma**, es poden executar en qualsevol sistema gràcies a l'intèrpret. 
  
  * Desventatges: Són mes lents, ja que sempre fan el procés d'interpretar, es necessari tenir instal·lat l'intèrpret.



##1.2 Codi font, codi objecte i codi excutable: màquines virtuals

**Codi font:** fitxers de text on está el codi que ha fet el programador, pero que encara no pot entendre el processador.

  Per a que aquest codi el pugui entendre, es necessitarà fer una **compilació**.

**Codi objecte:** es la traducció que es fa amb el codi font, per convertir-lo a codi màquina, però falta un pas més per a que es pugui executar, fer-ne un **enllaç**.

**Codi executable:** aquest codi finalment esta preparat per **executar-se en la màquina**. Quan s'agafen els fitxers amb codi objecte i els enllaçem tots amb **l'enllaçador** (o **linker**). Això fa que estigui completament traduït i es pugui executar.

**Màquines Virtuals:** El concepte de màquina virtual sorgeix amb l’objectiu de **facilitar el desenvolupament de compiladors** que generen codi per a diferents processadors.

La **compilació** consta de dues fases:

* La primera parteix del codi font a un llenguatge intermedi **obtenint un programa equivalent amb un menor nivell d’abstracció** que l’original i que no pot ser directament executat. 

* La segona fase **tradueix el llenguatge intermedi** a un llenguatge comprensible per la màquina.

Exemple de màquina virtual: JVM (**Java Virtual Machine**).

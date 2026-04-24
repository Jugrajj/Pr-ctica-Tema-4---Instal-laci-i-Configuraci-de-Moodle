## 1. Configuració inicial de Moodle

Per fer aquest apartat de la pràctica, he iniciat la sessió com a administrador i havia canviat el meu correu electrònic i la contrasenya seguint aquests passos:

Per començar he fet click en el **Logo** del meu perfil del *Moodle*, i després en l’opció de **"Perfil/Profile"**  ![Text alternatiu](imagen1.png "Títol opcional")
 - Una vegada dins de l’apartat de perfil, hem de fer clic a **"Edit Profile"**
  ![Text alternatiu](Imagen2.png "Títol opcional")
- En aquest apartat ja ens sortirà l’opció de configurar les nostres dades com: "correu electrònic, nom, contrasenya..."
  ![Text alternatiu](Imagen3.png "Títol opcional")

## 2. Configuració del lloc
En el punt *2* he canviat el nom del lloc i també he fet que la pàgina principal no mostri contingut per als usuaris no autenticats amb aquests passos: # - Primer de tot iniciem la sessio com **Administrador** en *Moodle*.
 ![Text alternatiu](Imagen4.png "Títol opcional")
 - Ara anem a **Administració del lloc > Primera plana > Paràmetres.**
 - Després configurem la franja horaria correcta:  Ubicació > Paràmetres.
 ![Text alternatiu](Imagen5.png "Títol opcional")
 - Jo, per exemple he escollit ***Europe/Madrid***
 ![Text alternatiu](Imagen6.png "Títol opcional")
- Ara ens falta canviar l'idioma del lloc:
 - Instal·lem paquets d'idioma si cal des de Administració del lloc > Idioma > Paquets d'idioma.
 ![Text alternatiu](Imagen8.png "Títol opcional")
 - Aquí escollim l'idioma que nosaltres volem; jo he escollit "Espanyol". Després fem un clic en "Install selected language pack(s)"
  ![Text alternatiu](Imagen9.png "Títol opcional")

- Anem a Administració del lloc > Idioma > Paràmetres.
 ![Text alternatiu](Imagen7.png "Títol opcional")
- Aqui escollim l'idioma que hem descarregat. Despres de escollir ho baixem i fem click en ***Save changes***
 ![Text alternatiu](Imagen10.png "Títol opcional")
## Establim una política de contrasenyes robusta:
- Anem a Administració del lloc > Seguretat > Normatives del lloc.
  ![Text alternatiu](Imagen11.png "Títol opcional")
- Despres baixem un poc i pusem un **1** en els opcions que volem per a que siguin **certs** y **0** en els que no volem:
    ![Text alternatiu](12.png "Títol opcional")
  Despres baixem un altre vegada per guardar els canvis.

# 3. Creació de cursos
En aquest punt tenim que crear ***Cursos*** seguint els pasos següents:
### ***Accediu a quadre de navegació: Cursos > Afegeix curs.***

- Creem un curs anomenat A amb 3 temes.
  ![Text alternatiu](13.png "Títol opcional")
  Aqui fem click en **Crear un curso**
  Despres de aixo tenim que fer click en ***Añadir seccion*** i posem el nom que volem. ex: Tema1,2,3...
  ![Text alternatiu](15.png "Títol opcional")


- Despres creem un curs anomenat B amb 5 temes.
fem aquesta part de la activitat de la mateixa manera que el pasat
  ![Text alternatiu](16.png "Títol opcional")

# 3.1 Exploreu les opcions de personalització dels cursos:

- Activeu el mode edició (Botó Activar Edició).
- Afegiu material (per exemple, un document PDF) a algun tema.
  ![Text alternatiu](17.png "Títol opcional")
- Canvieu el títol d'algun tema.
  ![Text alternatiu](18.png "Títol opcional")

4.1. Creació manual d'usuaris
Creeu manualment un usuari anomenat Bob amb autenticació manual:
Anar a Administració del lloc > Usuaris > Comptes > Afegeix un usuari.
  ![Text alternatiu](bob.png "Títol opcional")

# 4. Creació i gestió d'usuaris

4.2. Creació massiva d'alumnes
- Genereu 10 alumnes utilitzant un arxiu CSV:
- Anar a Administració del lloc > Usuaris > Carrega usuaris.
- Consulteu l'exemple de fitxer CSV a la secció Usuaris.
- Elimineu dos dels alumnes creats mitjançant Accions amb usuaris en bloc.
  ![Text alternatiu](10ç.png "Títol opcional")

# 5. Matriculació d'usuaris als cursos

5.1. Configuració de mètodes d'inscripció
- Curs A:
Desactiveu qualsevol mètode d'inscripció per fer-lo públic.
El curs ha de ser accessible sense iniciar sessió.
![Text alternatiu](ases.png "Títol opcional")

- Curs B:
Activeu el registre manual d'usuaris.
Matriculeu l'usuari Bob com a professor i els alumnes restants com a estudiants.
![Text alternatiu](enrol.png "Títol opcional")

5.2. Verificació
Comproveu que:
El contingut del curs A està disponible públicament.
![Text alternatiu](nose.png "Títol opcional")

Per accedir al curs B, cal iniciar sessió.
![Text alternatiu](tmpc.png "Títol opcional")

# 6. Personalització del lloc
![Text alternatiu](22.png "Títol opcional")
Per a cambiar de Tema de ***Moodle*** anem a Site Administration --> Appereance --> Themes
![Text alternatiu](23.png "Títol opcional")
Una vegada aqui escollim un de aquestes.
![Text alternatiu](24.png "Títol opcional")

Logotip:

Afegiu un logotip al vostre Moodle:
Jo he escollit aquest logo que diu ***"Joodle"*** que es un nom personalitzat per a mi.
![Text alternatiu](logt.png "Títol opcional")

### Look Final: 
![Text alternatiu](26.png "Títol opcional")

# 7.1. Curs A
Assigneu un professor i matriculeu alumnes.
![Text alternatiu](prof.png "Títol opcional")

Afegiu continguts:
Diferents tipus d'activitats i recursos.
Una tasca amb data d'entrega oberta que demani la càrrega d'un fitxer PDF.
![Text alternatiu](Tasca.png "Títol opcional")

7.2. Curs B
Cloneu el contingut del curs A al curs B:
Anar a Administració del curs > Importar.
Per a importar del Curs A --> Curs B tenim que anar al curs on volem importar y despres fer click en ***Mas*** y escollir ***"Course reuse"*** despres escullim el curs (Curs A en aquest cas) y fem click en import
![Text alternatiu](imp.png "Títol opcional")

# 8. Qualificacions i insígnies
Qualificacions:

Completeu totes les tasques evaluables amb un usuari alumne.
![Text alternatiu](tasccc.png "Títol opcional")

Configureu el calificador per obtenir una nota automàtica:
![Text alternatiu](cal.png "Títol opcional")

Anar a Administració del curs > Configuració de qualificacions.
Insígnies:

Creeu una insignia i atorgueu-la a un alumne:
Anar a Administració del lloc > Insígnies.
En aquest apartat de la activitat he creat una insignia anomenat ***Top*** per als estudiants que tinguin bona nota.
Per fer aquest apartat he anat a ***Curs A*** y despres he fet click en mas, una vegada alli he fet click en ***Insignias*** i he creat aquesta.
![Text alternatiu](insg.png "Títol opcional")

# 9. Qüestionaris
Creeu un qüestionari amb preguntes del banc de preguntes:
Per fer aixo he tingut que anar al Curs A
![Text alternatiu](curss.png "Títol opcional")
Despres he fet click en ***Mas*** y en el menuhe fet click en **Banco de preguntas**
![Text alternatiu](banc.png "Títol opcional")
Una vegada aqui he fet clck en ***Añadir*** y he afegit les preguntes.

Organitzeu preguntes en categories diferents.
Respongueu les preguntes amb un usuari estudiant i verifiqueu les qualificacions amb l'usuari professor.


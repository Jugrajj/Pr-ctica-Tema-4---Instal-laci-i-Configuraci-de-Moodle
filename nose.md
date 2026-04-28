## 1. Configuració inicial de Moodle
### Objectius de la pràctica

- Instal·lar i posar en funcionament un sistema de gestió de continguts, en aquest cas Moodle.  
- Familiaritzar-se amb l’ús de Moodle des del rol d’administrador per organitzar cursos, usuaris, materials i avaluacions.  
- Comprendre les funcionalitats d’una plataforma LMS (Learning Management System) i aplicar-les dins d’un context educatiu.

Per fer aquest apartat de la pràctica, he iniciat la sessió com a administrador i he canviat el meu correu electrònic i la contrasenya seguint aquests passos:

Per començar he fet click en el **Logo** del meu perfil del *Moodle*, i després en l’opció de **"Perfil/Profile"**  
![Text alternatiu](imagen1.png "Títol opcional")

- Una vegada dins de l’apartat de perfil, hem de fer clic a **"Edit Profile"**  
  ![Text alternatiu](Imagen2.png "Títol opcional")

- En aquest apartat ja ens sortirà l’opció de configurar les nostres dades com: correu electrònic, nom, contrasenya...  
  ![Text alternatiu](Imagen3.png "Títol opcional")

Si fem clic en ***Edit Profile*** i baixem, ens sortirà un apartat on podem canviar la nostra foto de perfil: ***jo no ho he volgut canviar, per tant no ho he fet***.  
![Text alternatiu](perff.png "Títol opcional")


## 2. Configuració del lloc
En aquest punt he realitzat la configuració inicial del lloc Moodle com a administrador, modificant aspectes generals del sistema.

En el punt 2 he canviat el nom del lloc i també he fet que la pàgina principal no mostri contingut per als usuaris no autenticats amb aquests passos:

### - Primer de tot iniciem la sessió com **Administrador** en *Moodle*.
![Text alternatiu](Imagen4.png "Títol opcional")

- Ara anem a **Administració del lloc > Primera plana > Paràmetres.**

- Després configurem la franja horària correcta: Ubicació > Paràmetres.  
![Text alternatiu](Imagen5.png "Títol opcional")

- Jo, per exemple, he escollit ***Europe/Madrid***  
![Text alternatiu](Imagen6.png "Títol opcional")

- Ara ens falta canviar l’idioma del lloc:
  - Instal·lem paquets d’idioma si cal des de Administració del lloc > Idioma > Paquets d’idioma.  
  ![Text alternatiu](Imagen8.png "Títol opcional")

  - Aquí escollim l’idioma que nosaltres volem; jo he escollit "Espanyol". Després fem clic en "Install selected language pack(s)"  
  ![Text alternatiu](Imagen9.png "Títol opcional")

- Anem a Administració del lloc > Idioma > Paràmetres.  
![Text alternatiu](Imagen7.png "Títol opcional")

- Aquí escollim l’idioma que hem descarregat. Després de seleccionar-lo baixem i fem clic en ***Save changes***  
![Text alternatiu](Imagen10.png "Títol opcional")


### Establim una política de contrasenyes robusta:
- Anem a Administració del lloc > Seguretat > Normatives del lloc.  
![Text alternatiu](Imagen11.png "Títol opcional")

- Després baixem una mica i posem un **1** en les opcions que volem perquè siguin certes i un **0** en les que no volem.  
![Text alternatiu](12.png "Títol opcional")

Després baixem un altre cop per guardar els canvis.


## 3. Creació de cursos
En aquest punt hem de crear ***Cursos*** seguint els passos següents:

### Accediu a quadre de navegació: Cursos > Afegeix curs.

- Creem un curs anomenat A amb 3 temes.  
![Text alternatiu](13.png "Títol opcional")

Aquí fem clic en **Crear un curso**.

Després hem de fer clic en ***Añadir seccion*** i posem el nom que volem, per exemple: Tema 1, 2 i 3.  
![Text alternatiu](15.png "Títol opcional")

- Després creem un curs anomenat B amb 5 temes.  
Aquesta part la fem de la mateixa manera que l’anterior.  
![Text alternatiu](16.png "Títol opcional")


## 3.1 Exploreu les opcions de personalització dels cursos:

- Activeu el mode edició (botó Activar Edició).
- Afegiu material (per exemple un document PDF) a algun tema.  
![Text alternatiu](17.png "Títol opcional")

- Canvieu el títol d’algun tema.  
![Text alternatiu](18.png "Títol opcional")


## 4. Creació i gestió d'usuaris

### 4.1 Creació manual d'usuaris
Creeu manualment un usuari anomenat Bob amb autenticació manual:

Anar a Administració del lloc > Usuaris > Comptes > Afegeix un usuari.  
![Text alternatiu](bob.png "Títol opcional")


### 4.2 Creació massiva d'alumnes
- Genereu 10 alumnes utilitzant un arxiu CSV:
- Anar a Administració del lloc > Usuaris > Carrega usuaris.
- Consulteu l’exemple de fitxer CSV a la secció Usuaris.
- Elimineu dos dels alumnes creats mitjançant Accions amb usuaris en bloc.  
![Text alternatiu](10ç.png "Títol opcional")


## 5. Matriculació d'usuaris als cursos

### 5.1 Configuració de mètodes d'inscripció

- **Curs A:**  
Desactiveu qualsevol mètode d’inscripció per fer-lo públic i accessible sense iniciar sessió.  
![Text alternatiu](ases.png "Títol opcional")

- **Curs B:**  
Activeu el registre manual d’usuaris. En aquest cas he matriculat a **Bob** com a professor i la resta d’alumnes com a estudiants.  
![Text alternatiu](enrol.png "Títol opcional")


### 5.2 Verificació
Comproveu que:
- El curs A és accessible sense iniciar sessió.  
![Text alternatiu](nose.png "Títol opcional")

- El curs B requereix iniciar sessió per accedir-hi.  
![Text alternatiu](tmpc.png "Títol opcional")


## 6. Personalització del lloc
En aquest apartat hem modificat l’aparença general de Moodle.

- Per canviar el tema anem a: Site Administration → Appearance → Themes  
![Text alternatiu](23.png "Títol opcional")

- Seleccionem un dels temes disponibles.  
![Text alternatiu](24.png "Títol opcional")

### Logotip:
Afegim un logotip personalitzat al lloc Moodle.  
En el meu cas he utilitzat un logotip anomenat ***"Joodle"***.  
![Text alternatiu](logt.png "Títol opcional")

### Look final:
![Text alternatiu](26.png "Títol opcional")


## 7.1 Curs A
Assignem un professor i matriculem els alumnes.  
![Text alternatiu](prof.png "Títol opcional")

Afegim continguts:
- Diferents tipus d’activitats i recursos.
- Una tasca amb data d’entrega oberta que demana la càrrega d’un fitxer PDF.  
![Text alternatiu](Tasca.png "Títol opcional")


## 7.2 Curs B
Clonem el contingut del curs A al curs B:

Per fer això he entrat al curs on vull importar i després he fet clic en ***Mas*** i he seleccionat ***Course reuse***. Després he escollit el curs A i he fet clic en import.  
![Text alternatiu](imp.png "Títol opcional")


## 8. Qualificacions i insígnies

### Qualificacions:
Completo totes les tasques avaluables amb un usuari alumne.  
![Text alternatiu](tasccc.png "Títol opcional")

Configuro el qualificador per obtenir una nota automàtica:  
![Text alternatiu](cal.png "Títol opcional")

Anar a Administració del curs > Configuració de qualificacions.


### Insígnies:
Cree una insígnia i la vaig atorgar a un alumne:

Anar a Administració del lloc > Insígnies.

En aquest apartat he creat una insígnia anomenada ***Top*** per als estudiants amb bona nota.

Per fer-ho he entrat al **Curs A** i després he fet clic en ***Mas*** i he seleccionat ***Insignias*** i l’he creat.  
![Text alternatiu](insg.png "Títol opcional")


## 9. Qüestionaris
Cree un qüestionari amb preguntes del banc de preguntes:

Per fer això he entrat al **Curs A**.  
![Text alternatiu](curss.png "Títol opcional")

Després he fet clic en ***Mas*** i en el menú he seleccionat **Banco de preguntas**.  
![Text alternatiu](banc.png "Títol opcional")

Un cop aquí he fet clic en ***Añadir*** i he afegit les preguntes.

Organitzo les preguntes en categories diferents.

Responc les preguntes amb un usuari estudiant i verifico les qualificacions amb l’usuari professor.

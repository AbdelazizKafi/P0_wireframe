# P0_wireframe

# Part de DAW
La primera pagina que he fet ha sigut la pàgina principal , en la qual apareix el logo a la part central superior i a la seva dreta hi han varis apartats com el del buscador de la pàgina, l'apartat de l'usuari i la cistella de compres.
A la pàgina hi han dues seccions com el catàle i els blogs i notícies.
Com a imatge principal surt una guitarra en grant en una casa de fusta i amb un quadre darrere.
![1](https://github.com/user-attachments/assets/f1fda561-6657-46bf-a5df-408b7ee7cced)

La segona pàgina que es la del catàleg de productes, hi ha un filtre a la part superior dreta que permet filtrar per marca, per preu i per tipus
Al cos de la pàgina hi surten 8 productes diferents amb la imatge, el nom i el preu. També he implementat un botó per afegir a la cistella.
![2](https://github.com/user-attachments/assets/d4e9209e-167e-4e18-b447-d509c0462276)

A la tercera pàgina que es la del producte i els seus detalls, hi ha una guitarra en gran amb uns quadres que representen les diferents fotos del producte. Mostro el seu nom, les valoracions i el preu. També es veu el color i la descripció.
Per l'altra banda surt el porcentatje de valoracions dels clients i un exemple d'una valoració d'un client aleatori.
![3](https://github.com/user-attachments/assets/ef6b8b5f-37e0-45dd-b498-2d53ba0b575a)

La quarta pàgina tracta de l'apartat de la cistella i el checkout. A la esquerra mostro la cistella on surt el producte i opcions per modificar la quantitat desitjada o eliminar el producte directament.
En quant al checkout hi han 3 apartats, el primer es el de la direcció d'enviament on es pot modificar la direcció i les dades del recipient. Després al mètode de pagament hi ha una varietat com tarjeta, un xec regal, financiació i PayPal.
Als mètodes d'enviament hi han 3 opcions que son entrega a domicili, punt de recollida i la recollida a la botiga.
![4](https://github.com/user-attachments/assets/57b659a6-6d45-46cf-9dea-b1923d2bcade)

A la penultima pagina he fet el procés d'inici de sessió i també el de registració per nous usuaris. A l'inici de sessió es pot utilitzar el nom d'usuari o el correu i la contrasenya. També hi ha un botó per recordad les dades per a la pròxima vegada. I lògicament el boto per fer l'inici de sessió.
També hi ha un apartat per reiniciar la contrasenya en cas de pèrdua. Es demana el correu electrònic per enviar un correo i reiniciar-la. Al registre es demana el correu, l'usuari i la contrasenya. Hi ha un botó per unir-se a la newsletter si l'usuari ho desitja.
![5](https://github.com/user-attachments/assets/73b22589-5f55-4394-b9e2-d139b171f7da)

L'ultima pàgina es el bloc de noticies. Aqui es basicament utilitzar l'imaginació per inventar algunes noticies. Jo he fet una noticia principal on surt un guitarrista i a la dreta una noticia real d'un guitarrista professional. 
Ha quedat com si fos una noticia d'un diari.
![6](https://github.com/user-attachments/assets/2fcf891f-1d78-4427-8bc2-b5abec9818c4)


# Part de DAM

22/10/2024 He començat a plantejar els dibuixos per a la wireframe de l'app per al mòvil, mirant les webs que s'han proporcionat i basant-me en un exercici d'una altra assignatura que era bastant similar.

23/10/2024 He fet els esbossos bruts de totes les pantalles de l'aplicació móvil en un full. És una mica caòtic, però penso que s'entén la idea general de què és i fa cada cosa. Aquí la imatge:
![alt text](image.png)

24/10/2024 
He aconseguit fer totes les pantalles que se'm demanaven. Aquí hi són:

1) Pantalla d'inici i pantalla de catàleg de productes:
![alt text](image-1.png)
Pantalla d'inici: Com es pot veure a l'imatge, la pàgina d'inici té la secció de presentació de la botiga i secció de destacats. 
Pantalla de catàleg: Mostra els articles, amb una opció per fer filtratge per marca, preu i tipus, i els articles amb la seva imatge, descripció, preu i extres.

2) Pantalla de detall del producte i pantalla de formulari de producte (ADMIN):
![alt text](image-2.png)

Pantalla de detall: Mostra la imatge del producte i a sota les seves especificacions i preu. Just a sota hi ha l'opció de comprar o afegir al cistell, i a sota d'això les valoracions dels clients sobre el producte. Pantalla de formulari: L'administrador té aquesta pantalla per a poder afegir un producte, on hi ha la informació que ha de tenir un producte per posar-lo a la venta, és a dir, seccions per a que l'admin introdueïxi la foto, la descripció, el preu, ...

3) Pantalla de compra i pantalla d'autenticació i registre d'usuaris:
![alt text](image-3.png)
Pantalla de compra: Es mostra els articles que s'han afegit a la cistella, on cada article té una icona de paperera per si el client vol descartar l'article, i a sota, mostra el preu total i les opcions de pagament (PayPal, Apple Pay o Bizum). Pantalla d'autenticació: Mostra l'icona de l'aplicació i a sota els requadres per a que l'usuari introdueïxi el seu correu i contrassenya, i quan ho ha introduït li clica al botó d'iniciar sessió. Si l'usuari no té compte, l'ha de clicar al botó de registrar-se, i si a l'usuari se l'hi ha oblidat la contrassenya, li ha de clicar al botó de canviar contrassenya.

4) Pantalla de registre i pantalla de blog i notícies:
![alt text](image-4.png)
Pantalla de registe: És la pantalla que apareix quan l'usuari clica al botó de registrar-se en la pantalla anterior. Apareix el logo de l'app i els camps que ha d'omplir i clicar al botó d'acceptar les condicions, i llavors clica al botó de registrar-se i ja està registrat. Pantalla de blog i notícies: Mostra notícies i un blog per als usuaris, on a la part superior hi ha una opció per filtrar per diferents tipus de publicacions o notícies.

NOTA: Quasi totes les pantalles tenen a la part superior la barra de buscar, el menú (el menú son les tres línies amb punts) i a la part inferior les icones per anar als diferents llocs, només els hi falta a la pantalla d'autenticació i a la pantalla de registre d'usuaris.
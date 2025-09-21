# Teorie HTML

- Toate elementele ("< p > buna < /p >") au opening/closing tags => < p > - opening < /p > - closing.

### h - tag

Tagurile h1-h6 sunt folosite pentru a arata importanta content-ului. Cu cat e mai mic numarul cu atat e mai mare importanta (h1 > h2).

#### Se foloseste doar 1 h1/pagina

### p - tag

Pentru a crea un paragraf.

### main - tag

HTML-ul are cateva elemente prin care se identifica anumite parti din content. Ele fac ca html-ul sa fie mai usor de citit si ajuta cu Search Engine Optimization (SEO).

Tot ce se afla in tag-ul de main (doar unul/document) ar trebui sa fie unic.

## Nesting elements

Sunt elemente in cadrul altor elemente <i>'< main >< p >< /p >< /main >'</i>.
Spatierea ar trebui sa fie facuta la 2 spatii. Asta se numeste <b>Identare</b>

## Void elements

Sunt elemente <b>fara closing tag</b> e.g. : <i>< img >-tag</i>.

## Attributes

Cuvinte speciale folosite in opening tag pentru a controla actiunile elementului.

### src - attribute

<b>src</b> in interiorul tag-ului img specifica URL-ul (Uniform Resource Locator) imaginii.

#### URL-ul indica o locatie unica si specifica pentru o resursa online.

### img - tag

Toate tag-urile img trebuie sa aibe un <b>src</b> si un <b>alt</b>.

### a - tag

<b>a</b> tag vine de la anchor si este folosit pentru a pune un link catre o alta pagina,documentatie,imagine etc... .

### target - attribute

Pentru a deschide link-ul intr-un nou tab putem folosi <b>"target="\_blank""</b> dupa <b>"href"</b>.

### Mai multe elemente fot fi transformate in link-uri e.g. < img >.

### section element

Este folosit pentru a descrie sectiuni intr-un document cum ar fi: chapters, headers, footers etc... . Este al doilea tag folosit pentru SEO.

### Adaugarea unui nou "h2" implica incepera unei noi sectiuni.

### ul - element

Folosit pentru a crea o lista neordonata adica cu simboluri.

### li - element

Folosit pentru a enumera itemele din lista li = list item.

## Cele doua (ul, li) sunt dependete una de cealalta.

### figure & figcaption - elements

Sunt folosite pentru a dauga un titlu imaginii <b>figure->img->figcaption->figure</b> sau <b>figure->figcaption->img->figure</b>.

### em - element.

Folosit pentru a sublinia un cuvant.

#### "em" este diferit de "i" deoarece "i" doar face cuvantul/paragraful italic dar "em" este folosit pentru a scoate ceva in evidenta.

i se foloseste spre e.g. la un nume de autor iar em la un text precum "Call for help".

### ol - element

Se foloseste pentru a crea o lista ordonata (adica cu elemente numerotate).

### strong - element

Folosit pentru a arata ca un cuvant are un impact puternic.

### form - elemet

Este folosit pentru a prelua informatii de la user e.g.: name, email... .

### action - attribute

Spune form-ului unde ar trebui sa fie trimise datele, adica path-ul
E.g.: Daca main path-ul meu este "http://127.0.0.1:5500/FreeCodeCamp-HTML-CSS/HTML/index.html" si la <b> action </b> adaug <b>/submit-url</b> datele imi vor fi transmise catre endpoint-ul:<b>"http://127.0.0.1:5500/FreeCodeCamp-HTML-CSS/HTML/index.html/submit-url"</b>

### input - void element

Cu ele colecatam datele de la user.

### type - attribute

Sunt multe tipuri de inputuri si acestea sunt create prin atributul type care poate fi password field, reset button, control pentru a selecta fisiere/imagini... .

### name - attribute

Pentru ca data inputului sa fie trimisa catre endpoint-ul precizat in action inputul trebuie sa aibe un ume.

### placeholder - attribute

Pentru a oferi user-ului un indiciu despre ce tip de informatie ar trebui sa adauge.

### required - attribute

Pentru ca user-ul sa fie obligat sa adauge acel tip de informatie.

### button - elemet

Creeaza un buton.
Si butonul are atribut type cu valori cum ar fi: submit/ reset/ button(default).

### lable - element

Sunt folosite pentru a asocia text unui input (deoarece input e void element e.g.: lable input Indoor /lable) cu insusi input-ul.

#### Daca apasam pe lable untr-un radiou va fi selectat acel radio. Nu e necesar sa apasam pe buton daca avem un lable.

### id - attribute

Folosit pentru a identifica diferite elemente HTML.Fiecare valoare pentru atributul id trebuie sa fie unica pentru <b>intreaga pagina</b>.

### name - attribute

Daca atributul name este inexistent sau diferit atunci putem observa ca ambele butoane radio pot fi selectate dar daca avem acelasi nume pentru amandoua atunci ori primul ori al doilea poate fi selectat(doar la radio).

### value - attribute

Fiecare control dintr-un formular (ex. < input >, < select >, < textarea >) este trimis catre server sub forma perechei name=valoare.

Daca un element nu are atributul name, nu va fi inclus în request.

Valorile sunt trimise ca siruri de caractere (stringuri), nu ca numere sau boolean nativ. Conversia în number, boolean etc. se face abia pe backend.

< input type="number" name="x" > → la fel, se trimite x= (șir gol). Nu se trimite 0 automat. Serverul poate interpreta șirul gol ca null sau ca eroare, depinde de implementare.

< input type="checkbox" name="x">

Daca e bifat, se trimite x=on (sau x=altceva pentru value="altceva").

Daca nu e bifat, nu se trimite deloc perechea name=valoare.

### fieldset - element

Este folosit pentru a grupa inputurile si label-urile intr-un webform. Ele singure sunt <b>inline</b> insemnand ca sunt pe aceeasi linie dar daca le facem nest intr-un fieldset vor fi pe randuri diferite. Elementele fieldset sunt block-level elements(adica apar pe linie noua.)

### legend - element

Este un titlu pentru intreg fieldset-ul

### Doua varinate in care putem asocia numele inputului cu inputul

- 1. facem inputul nested cu lable
- 2. avem inputul si dupa input punem doar textul nested cu lable iar in lable folosim atributul "for" la care <b>folosim acelasi nume cu numele id-ului din input</b>.

## La inputuri folosim tot timpul atributul name. Ajuta serverul sa procese mai usor web form-ul.

### checked - attribute

Folosit pentru a face inputul de tip radio sau checkbox selectat by default.

### footer - element

Este al 3 lea element folosit pentru SEO si contine informatii despre autor, copyright dat, links pentru terms of use, contact information ... . Este la finalul paginii.

### head - elemet

Este folosit pentru medatada adica date despre document care nu sunt afisate user-ului cum ar fi titlu,link catre stylesheet si script-uri. Metadata = date despre date.

### title - head element

Determina ce va afisa browser-ul in bara ca si titlu

### meta - void head element

Spune browser-ului cum sa se comporte

### html - element

Este root elemen-ul oricariu fisier html si contine intreg content-ul paginii

### lang - html attribute

Pentru a specifica linba folosita in pagina

## Toate paginile HTML trebuie sa inceapa cu < !DOCTYPE html >

### Spune browser-ului ca documentul este un document HTML5 (ultima versiune)

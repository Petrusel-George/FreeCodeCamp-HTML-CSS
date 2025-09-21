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

Pentru a deschide link-ul intr-un nou tab putem folosi <b>"target="_blank""</b> dupa <b>"href"</b>.

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

### strong - elements

Folosit pentru a arata ca un cuvant are un impact puternic.
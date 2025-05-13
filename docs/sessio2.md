# Sessió 2: Introducció a CSS

## Objectius de la sessió

- Entendre què és el CSS i per a què serveix.
- Aplicar estils bàsics a etiquetes HTML.
- Diferenciar contingut (HTML) i aparença (CSS).
- Personalitzar colors, fonts, mides, fons i alineacions.

## Eines recomanades per a la sessió

- CodePen: [https://codepen.io/](https://codepen.io/)

## Contingut

### Què és CSS?

CSS (Cascading Style Sheets) és un llenguatge de fulls d'estil utilitzat per a descriure l'aparença i el format d'un document escrit en HTML. CSS permet separar el contingut de la presentació, facilitant així la creació de pàgines web atractives i ben dissenyades.

CSS són les "instruccions d’estil" de la web: permet canviar colors, mides, disposicions...

### Exemple senzill

```html
<!DOCTYPE html>
<html lang="ca">
<head>
    <title>Exemple de CSS</title>
</head>
<body>
    <h1>Benvingut a la meua pàgina web</h1>
    <p>Aquesta és una pàgina d'exemple per a mostrar l'ús de CSS.</p>
</body>
</html>
```

```css
h1 {
  color: darkblue;
  font-family: Arial;
}

p {
  color: #444;
  font-size: 18px;
}
```

### Estils CSS bàsics

- **Color**: `color: blue;`
- **Fons**: `background-color: lightgray;`
- **Tipus de lletra**: `font-family: Arial, sans-serif;`
- **Mida de lletra**: `font-size: 16px;`
- **Marge**: `margin: 10px;`
- **Ompliment**: `padding: 10px;`
- **Alineació**: `text-align: center;`
- **Bordes**: `border: 1px solid black;`
- **Imatges**: `width: 100px; height: auto;`
- **Enllaços**: `text-decoration: none;` (per eliminar el subratllat)
- **Estils de text**: `font-weight: bold;`, `font-style: italic;`

## Activitat

Anem a modificar la pàgina creada a la sessió anterior per a aplicar-li estils CSS.

- A CodePen, obre el teu "Pen" creat a la sessió anterior.
- A la secció de CSS, afegeix els següents estils:

```css
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}
```

Fixeu-vos que el color de fons de la pàgina canvia a un gris clar i la font del text a Arial.

- Afig estils per a l'encapçalament `<h1>`:

```css
h1 {
  color: darkblue;
  text-align: center;
}
```

- Afig estils per al paràgraf `<p>`:

```css
p {
  color: #444;
  font-size: 18px;
  text-align: justify;
}
```

- Afig estils per a les capçaleres `<h2>`:

```css
h2 {
  color: darkgreen;
  text-align: center;
}
```

- Afig estils per a les imatges `<img>`:

```css
img {
  width: 300px;
  height: auto;
  display: block;
  margin: 0 auto;
}
```

Les propietats `display: block;` i `margin: 0 auto;` centren la imatge a la pàgina.

- Afig estils per als enllaços `<a>`:

```css
a {
  color: blue;
  text-decoration: none;
}
```

## Reptes adicionals

- Experimenta amb diferents colors i mides de lletra.
- Afig més estils CSS per a millorar l'aparença de la teua pàgina.
- Prova a crear classes CSS per a aplicar estils específics a diferents elements de la teua pàgina.

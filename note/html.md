# Exercice HTML5/CSS
## Premier jour :
La stucture d'une page html
```
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8"/>
		<title> Titre </title>	
	</head>
	<body>
	</body>
</html>
```
De maniere generale il faudra mettre dans le html uniquement les information de structuration de la page et garder les informations estetique pour le css.

### Balises :

`<meta charset="utf-8" />` sert a forcer le codage de la page avec le utf-8

`<title> </title>` balise importante pour les moteursde recherche doit englober les themes couvert dans la page

`<link rel="stylesheet" href="css/style.css" />` creer le lien vers la feuille de style css

`<p></p>` balise entourant un paragraphe de texte

`<div></div>` balise minimaliste definissant un conteneur

`<span></span>` balise minimaliste inline deffissant un conteneur inline

`<img src="path/image" alt="text image of what">` balise inserant une image dans la page l'image doit avoir un interet informatif en rapport avec l'article sinon il faudra inserer l'image en css. l'attribut `src` doit contenir le chemin relatif ou absolu de l'image. L'attribut `atl` contient une description de l'image important pour obtenir la validation par le w3c

`<a href="cible" target="option" > </a>` lien cliquable menant vers la cible `href`. Target defini le comportement de l'ouverture du lien ex:`_blank` pour ouvrir un nouvelle page. La cible peut etre une URL, un chemin relatif ou absolu vers un fichier ou un `id` avec `#idname`.
 
Liste non ordonnee : 
```
<ul>
	<li> </li>
	<li> </li>
</ul>
```

Liste ordonnee :
```
<ol>
	<li> </li>
	<li> </li>
</ol>
```

### Attribut commun a toutes les balises
- `id="name"` : *selecteur* defini un identifiant qui doit etre unique dans la page. name est senssible a la casse
- `classe="name"` : *selecteur* affecte la classe name a une balise 


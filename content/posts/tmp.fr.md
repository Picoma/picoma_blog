---
author: "Hugo Authors"
title: "Guide de syntaxe Markdown pour L2"
date: "2019-03-11"
description: "Exemple d'article montrant la syntaxe de base Markdown et le formatage des éléments HTML.."
tags: ["markdown", "css", "html", "themes"]
categories: ["themes", "syntax"]
series: ["Themes Guide"]
ShowToc: true
TocOpen: false
weight: 2
draft: false
---

Cet article propose un exemple de syntaxe Markdown de base qui peut être utilisée dans les fichiers de contenu Hugo. Il montre également si les éléments HTML de base sont décorés avec CSS dans un thème Hugo.

<!--plus-->

## Titres

Les éléments HTML `<h1>`—`<h6>` suivants représentent six niveaux de titres de section. `<h1>` est le niveau de section le plus élevé tandis que `<h6>` est le niveau le plus bas.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraphe

Xerum, quo qui aut unt explam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin replis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur ? Quianimin porecu evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Citations

L'élément blockquote représente le contenu qui est cité à partir d'une autre source, éventuellement avec une citation qui doit être dans un élément « footer » ou « cite », et éventuellement avec des modifications en ligne telles que des annotations et des abréviations.

#### Blockquote sans attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Notez** que vous pouvez utiliser la _syntaxe Markdown_ dans un blockquote.

#### Blockquote avec attribution

> Ne communiquez pas en partageant la mémoire, partagez la mémoire en communiquant.
>
> — <cite>Rob Pike[^1]</cite>

[^1]: la citation ci-dessus est extraite de la [discours](https://www.youtube.com/watch?v=PAAkCSZUG1c) de Rob Pike lors du Gopherfest, le 18 novembre 2015.

## Les tables

Les tableaux ne font pas partie de la spécification principale de Markdown, mais Hugo les prend en charge dès le départ.

| Nom | Âge |
| ----- | --- |
| Bob | 27 |
| Alice | 23 |

#### Inline Markdown dans les tableaux

| Italique | Audacieux | Codes |
| --------- | -------- | ------ |
| _italique_ | **gras** | `code` |

## Blocs de code

#### Code en ligne

« Ceci est du code en ligne »

#### Uniquement `pré`

<pre>
Ceci est un prétexte
</pre>

#### Bloc de code avec backticks

```
<!DOCTYPEhtml>
<html lang="fr">
 <tête>
 <meta charset="utf-8" />
 <title>Exemple de document HTML5</title>
 </tête>
 <corps>
 <p>Tester</p>
 </corps>
</html>
```

#### Bloc de code avec backticks et langue spécifiée

```html {linenos=true}
<!DOCTYPEhtml>
<html lang="fr">
 <tête>
 <meta charset="utf-8" />
 <title>Exemple de document HTML5</title>
 <meta name="description" content="Exemple d'article montrant la syntaxe Markdown de base et le formatage des éléments HTML.">
 </tête>
 <corps>
 <p>Tester</p>
 </corps>
</html>
```

#### Bloc de code indenté de quatre espaces

	<!doctypehtml>
	<html lang="fr">
	<tête>
	<méta charset="utf-8">
	<title>Exemple de document HTML5</title>
	</tête>
	<corps>
	<p>Tester</p>
	</corps>
	</html>

#### Bloc de code avec le shortcode de surbrillance interne de Hugo

{{< highlight html >}}

<!doctypehtml>
<html lang="fr">
<head>
 <meta charset="utf-8">
 <title>Exemple de document HTML5</title>
</head>
<body>
 <p>Tester</p>
</body>
</html>
{{< /highlight >}}

#### Essentiel

{{< gist spf13 7896402 >}}

## Types de liste

#### Liste commandée

1. Premier élément
2. Deuxième élément
3. Troisième élément

#### Liste non ordonnée

- Liste des éléments
- Un autre article
-Et un autre objet

#### Liste imbriquée

-   Fruit
 - Pomme
 -   Orange
 - Banane
- Laitier
 - Lait
 - Fromage

## Autres éléments — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> est un format d'image bitmap.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Appuyez sur <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Suppr</kbd></kbd> pour mettre fin à la session.

La plupart des <mark>salamandres</mark> sont nocturnes et chassent les insectes, les vers et d'autres petites créatures.
Envoyer des commentaires
Résultats de traduction disponibles 

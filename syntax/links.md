# Links

Le markdown est compatible avec deux styles de liens : en-ligne et référence.

Dans ces deux styles, le lien texte est délimité par des [crochets].

Pour créer un lien en-ligne, utilisez un couple de parenthèses régulière immédiatement après le crochet fermant du lien texte. A l'intérieur des parenthèses, placez l'URL vers lequel vous voulez que le lien dirige, avec un titre optionnel pour le lien, entouré par des guillemets. Par exemple :
```markdown
[Je suis un lien de style en-ligne](https://www.google.com)

[Je suis un lien de style en-ligne avec un titre](https://www.google.com "Page d'accueil de Google")

[Je suis un lien de style référence][Texte de référence arbitraire indifférent à la casse]

[Je suis une référence relative à un fichier de dépôt](../blob/master/LICENSE)
```

Les liens de style référence utilisent un second couple de crochets, à l'intérieur desquels vous placez l'étiquette de votre choix pour identifier le lien:
```markdown
Ceci est [un exemple][id] de lien de style référence.
```

Vous pouvez de manière optionnelle utilisez un espace pour séparer les couples de crochets:
```markdown
Ceci est [un exemple] [id] de lien de style référence.
```

Alors, n'importe où dans le document, vous définissez votre étiquette de lien comme cela, seul sur une ligne :
```markdown
[id]: http://example.com/  "Titre optionnel ici"
```

**GitHub** et **GitBook** sont compatibles avec une mise en lien automatique des URL. Ils lieront automatiquement les URL standards, donc si vous voulez lier un URL (au lieu de mettre en place un lien texte), vous pouvez simplement entrer l'URL et il sera transformé en un lien vers cet URL.


---

Voici un quiz à propos des liens en markdown.

Sélectionnez les liens valide:
- [x] `[un lien](http://google.fr)`
- [ ] `(un lien)[http://google.fr]`

> Le lien texte est délimité par [des crochets].

Quelles sont les informations correctes à propos de ce lien: ```[un lien](http://google.fr "google")```
- [ ] le lien est https://google.fr
- [x] le titre du lien est "google"
- [ ] il montrera le texte "google"
- [x] il montrera le texte "un lien"

> Les liens peuvent avoir 3 prties : le texte, l'URL et un titre.

---

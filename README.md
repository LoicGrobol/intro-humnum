[comment]: <> "LTeX: language=fr"
<!-- markdownlint-disable MD003 MD025 MD033 -->

Humanités Numériques
====================

[![Licence : CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/)

Contenus pour le cours « Humanités Numériques » des licences SDL, InfoCom et Humanités de
l'Université Paris Nanterre

- [Site du cours](https://loicgrobol.github.io/intro-humnum/)
- [Dépôt GitHub](https://github.com/LoicGrobol/intro-humnum)

Contact : [<loic.grobol@parisnanterre.fr>](mailto:loic.grobol@parisnanterre.fr)

## Ressources

- Les slides sont dans [slides/](slides) et faites en
  [RMarkdown](https://bookdown.org/yihui/rmarkdown). Pour les compiler on peut utiliser la commande
  suivante (en adaptant les noms de fichiers) :

  ```sh
   R -e rmarkdown::render"('slides/lecture-01/lecture-01.Rmd',output_file='lecture-01.html')"
   ```

  Cela nécessite que R et les packages `rmarkdown` et `revealjs` soient installés, voir [la
  doc](https://bookdown.org/yihui/rmarkdown/compile.html) pour plus d'informations. À défaut, on
  peut également les lire comme des fichiers markdown standards.

## Licences

[![CC BY Licence badge](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

Copyright © 2021 Loïc Grobol [\<loic.grobol@gmail.com\>](mailto:loic.grobol@gmail.com)

Sauf indication contraire, les fichiers présents dans ce dépôt sont distribués selon les termes de
la licence [Creative Commons Attribution 4.0
International](https://creativecommons.org/licenses/by/4.0/).

Un résumé simplifié de cette licence est disponible à <https://creativecommons.org/licenses/by/4.0/>.

Le texte intégral de cette licence est disponible à
<https://creativecommons.org/licenses/by/4.0/legalcode>

### Exceptions à la licence

Les fichiers suivants ne sont pas distribués selon les termes de la licence Creative Commons
Attribution 4.0 International

#### CC BY-NC-ND

[![CC BY NC ND Licence badge](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

- [`affiche_manifeste.png`](slides/lecture-01/pics/affiche_manifeste.png) est issu [du site du
  ThatCamp Paris](https://tcp.hypotheses.org/443) et est soumis à la licence [CC-BY-NC-ND
  2.0](https://creativecommons.org/licenses/by-nc-nd/2.0/).
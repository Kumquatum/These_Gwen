# Checklist des trucs à ne pas oublier / faire avant le rendu

## Compilation LaTeX
- [x] Les numéros de chapitre/section sont ok (l'intro et la conclusion n'ont pas de n° de chapitre mais bien de section qui doit suivre la suite des sections de chapitre)
- [x] Mettre en forme le .bib avec https://flamingtempura.github.io/bibtex-tidy/ en virant les sections "file abstract keywords mendeley-groups mendeley-tags annote"
- [x] Voir pour le souci des labels définis plusieurs fois
    - Soit garder la suppression de warning comme là et osef (\WarningFilter{latex}{Label})
    - Soit essayer de redéfinir des alias différents pour les articles dans les chapitres. Ex : Ritchie2016 → Ritchie2016Chap1

## Rédaction
- [x] Refaire les titres de table et figure pour qu'ils soient plus courts dans la liste à base de \caption[Titre résumé]{Titre classique : description}
- [x] Rajouter l'intro de chapitre 1 et notamment mentionner que l'article est CC-BY
- [ ] Acronymes à rajouter, reprendre comme a fait Regis avec \acrfull et \acrshort

## Admninistratif
- ~~[x] Faire signer par tous les auteurs de l'article GWENA une autorisation d'insertion dans la thèse~~
    -  Pas besoin, article en CC-BY
    -  Le marquer dans l'intro chapitre 1
- [x] Remplir l'autorisation d'insertion d'article en anglais dans la thèse
- [x] Relancer Francine sur le mail d'autorisation de rédaction en anglais
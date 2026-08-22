# .github

Formulaires d+issue par défaut pour les dépôts de l+organisation
Sam-Outillage.

Ce dépôt ne contient **aucun code**. GitHub y lit les fichiers communautaires
par défaut : tout dépôt de l'organisation qui n'a pas les siens hérite de
ceux-ci.

| Fichier | Effet |
|---|---|
| `.github/ISSUE_TEMPLATE/*.yml` | Les formulaires proposés à l'ouverture d'une issue |
| `.github/ISSUE_TEMPLATE/config.yml` | Autorise ou non l'issue libre, sans formulaire |

**Un dépôt qui pose ses propres gabarits reprend la main.** S'il existe le
moindre fichier dans son `.github/ISSUE_TEMPLATE/`, aucun de ceux d'ici ne
s'applique - c'est tout ou rien, pas une fusion.

## Pourquoi ce dépôt est public

C'est une contrainte de GitHub, pas un choix : les gabarits par défaut ne
s'appliquent à l'échelle d'une organisation que depuis un dépôt `.github`
public. Un dépôt privé ou interne ne fonctionne pas.

Les gabarits sont donc écrits pour être lisibles par n'importe qui : ils
décrivent une méthode de travail, jamais un produit, un client ni un système
interne.

## Les quatre formulaires

| Formulaire | Sert à |
|---|---|
| **Épique** | Un chantier qui traverse plusieurs dépôts et porte une échéance |
| **Décision** | Un arbitrage qui bloque du travail en aval tant qu'il n'est pas rendu |
| **Conformité** | Une obligation qui vient d'un texte, d'une norme ou d'une politique de sécurité |
| **Anomalie terrain** | Un défaut constaté sur un équipement en service, pas en développement |

L'issue libre reste ouverte : imposer un formulaire pour tout ajoute de la
friction là où elle ne sert à rien.

Deux champs méritent d'être renseignés honnêtement plutôt que favorablement.
**Confiance dans la date**, sur une épique, sépare ce qui est un mur de ce qui
est un souhait. **Réversibilité**, sur une décision, dit le soin à mettre dans
l'instruction - et le droit qu'on a de se tromper.

## Ce que ce dépôt ne contient pas encore

`SECURITY.md`, `CONTRIBUTING.md` et `CODE_OF_CONDUCT.md` s'ajouteraient ici et
vaudraient pour toute l'organisation. Ils engagent - une politique de sécurité
annonce un contact et un délai de réponse - et n'ont pas encore été arbitrés.

# ABZ Project — promotion immobilière

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `abzproject.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/abzproject.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs abzproject` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@abzproject.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (Prix annoncé / Prix annoncé / Précisé €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
We are ABZ Project, a residential property developer based in Estinnes, in the province of Hainaut. We develop residential building projects and we buy and sell property we own ourselves. The company was formed in March 2025, so we claim no track record we do not have; what we can be judged on is how we handle an acquisition. In Wallonia a buyer is entitled to receive specific documents before committing: a conforming extract from the soil status database, a valid energy performance certificate, and the electrical installation inspection report for a dwelling. Those are routinely produced at the notary's office at the last moment, when it is too late to change your mind calmly. We hand them over before anyone signs. New homes are built to the near-zero-energy standard, and we are the owner-seller rather than an agent. Site: abzproject.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |

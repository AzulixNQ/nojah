# Noweiz HUB

Le site de Noweiz HUB, avec Nojah (order flow) et Weizix (ICT) : https://noweiz.com/ (l'ancien lien https://azulixnq.github.io/nojah/ y renvoie).

- `index.html` : la page (le style et le script sont dedans, aucun service extérieur).
- `img/certificats/` : les 14 preuves de payout de Nojah (13 certificats Lucid Trading et 1 preuve Topstep), recadrées depuis ses captures (aucune n'est refaite) ; sur celles d'octobre et de novembre, le QR code et le code du certificat sont masqués.
- `video/` : l'épisode 1 de la série « 1 week-end = 2 setups » (l'absorption, par Nojah, nouveau style) et son affiche.
- `fonts/` : la police du site (licence SIL Open Font License 1.1, voir `fonts/OFL.txt`).
- `og.jpg` : l'image qui s'affiche quand on partage le lien. `favicon.svg` et `apple-touch-icon.png` : les icônes.
- `apercu/` : l'ancien lien de l'aperçu, qui renvoie vers la page.
- `academy/` : **un autre site**, la version de test de Noweiz Academy (les comptes), servie sous `test.noweiz.com`. Il est rangé ici parce que l'offre OVH Perso n'accepte qu'un seul site relié à GitHub. Son code source est dans le dépôt `AzulixNQ/noweiz-academy` ; voir `academy/LISEZMOI.md`.

Mise en ligne : hébergement OVH (offre Perso), site « Noweiz HUB », dossier `hub`, relié par Git à ce dépôt, branche `main`. Après un envoi sur GitHub : console OVH > Hébergements web > Mes sites > ⋮ du site > Git > Déployer. `.htaccess` renvoie `www`, `noweiz.fr` et `noweiz.eu` vers `https://noweiz.com/`. GitHub Pages reste actif seulement pour renvoyer l'ancien lien.

## Les rubans de lumière (22/11)
`rubans.js` dessine les rubans blancs et argentés derrière la page (WebGL). C'est une copie de `academy/assets/rubans.js` (le même fichier que Noweiz Academy, réglé ici avec `data-teinte="argent"` sur la toile) : en cas de changement, recopier l'un dans l'autre.

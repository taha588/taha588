## État actuel
- Fait : T1 complet, T2.1, T2.2, puis refonte visuelle (T3.3) et vérification du rendu réel (T3.2).
- Mise en page : « À propos » et « Engagement » en 2 colonnes (table HTML), projets avec citation
  « Résultat », cartes de statistiques adaptées au thème via <picture> + prefers-color-scheme.
- Bugs réels trouvés et corrigés pendant la vérification :
  1. Bannière cassée depuis le début — capsule-render injectait un « & » brut dans le SVG (XML invalide) ;
     corrigé en encodant %26amp%3B dans le paramètre desc.
  2. Compteur de vues komarev.com refusé par le proxy camo de GitHub (« Cannot proxy the given URL ») ;
     remplacé par hits.sh, testé à travers camo.
  3. Cartes github-readme-stats parfois vides (animation d opacité) : disable_animations=true.
  4. height="165em" invalide en HTML : remplacé par height="170" pour aligner les 2 cartes.
- En cours : —
- Problème : il reste les modules du Master (T2.3), les certifications (T2.4) et la relecture
  de la Stack (T3.1) — en attente d informations de l utilisateur.
- Prochaine étape : merger la PR #1 pour que le profil soit visible, puis T2.3/T2.4/T3.1.

## Décisions
- Username GitHub : `taha588` ; email : `mohamedtahakchmar@gmail.com`.
- Lien LinkedIn nettoyé (paramètres `utm_*` retirés) : `kachmar-mohamed-taha-30b8502a1`.
- Pas de badge Portfolio (choix de l utilisateur).
- Projets décrits uniquement à partir du contenu réel des dépôts, aucune invention.
  Forks et projet « Sanabil » (non publié) exclus.
- Vérification : le rendu local via l API markdown (mode gfm) force des retours à la ligne et ne
  reflète pas un README ; la référence est la page du dépôt sur github.com.
- Langue du profil : français. Langue des échanges : darija.

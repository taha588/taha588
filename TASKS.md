# TASKS — Profil GitHub (README)

## T1 : Nettoyage technique
- [x] T1.1 : Remplacer les placeholders username/email — Critère : `grep -c VOTRE_ README.md` = 0 ✅
- [x] T1.2 : Retirer images cassées (snake sans workflow, trophies, streak heroku mort) — Critère : `grep -cE 'snake|trophy|herokuapp'` = 0 ✅
- [x] T1.3 : LinkedIn réel inséré (`kachmar-mohamed-taha-30b8502a1`), 2 endroits — Critère : `grep -c TODO-LINKEDIN README.md` = 0 ✅
- [x] T1.4 : Bloc Portfolio commenté supprimé (aucune URL) — Critère : `grep -c Portfolio README.md` = 0 ✅

## T2 : Contenu Data Science
- [x] T2.1 : Section **Formation** + Stack enrichie (ML, NoSQL, BI, « en apprentissage ») ✅
- [x] T2.2 : 3 projets réels publiés (quantization INT8, géospatial MongoDB, Assistant Handicap) ✅
- [ ] T2.3 : Modules du Master (bloc commenté dans « Formation ») — Critère : liste réelle affichée
- [ ] T2.4 : Certifications (bloc commenté) — Critère : liste réelle, ou bloc supprimé si aucune

## T3 : Vérification
- [ ] T3.1 : Relire la Stack et retirer toute techno non réellement pratiquée
- [ ] T3.2 : Ouvrir le profil sur github.com/taha588 et vérifier qu'aucune image n'est cassée

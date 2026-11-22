# Page de vente : Formation Motion Design avec l’IA

Site statique (HTML, images, vidéos). Aucune installation ni compilation nécessaire.

## Contenu
- `index.html` : la page de vente complète
- `images/` : logo et photos
- `videos/` : vidéos des apprenants et réalisations
- `vercel.json` : réglages pour Vercel (facultatif)

## Modifier le lien de paiement
Dans `index.html`, cherche la ligne `const CHARIOW_URL = "..."` (tout en bas)
et remplace l’adresse entre guillemets par ton lien Chariow.

## Remplacer une photo ou une vidéo
Garde exactement le même nom de fichier (par exemple `videos/issa.mp4`)
et remplace-le dans le dossier. La page se met à jour toute seule après le commit.

## Déploiement sur Vercel
Framework Preset : **Other**. Build Command et Output Directory : laisser vides.

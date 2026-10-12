# Martinet Light

Thème clair pour Home Assistant, inspiré de la palette Martinet Dark. Il reprend ses couleurs sémantiques et ses variables de surface dans une palette claire.

## Contenu

- `martinet_light.yaml` : définition du thème **Martinet Light**.

Le fichier définit les couleurs Home Assistant et les variables `martinet-*` utilisées par les cartes Martinet compatibles. Il ne modifie pas les tableaux de bord. Une carte qui fixe ses couleurs directement dans son YAML ou son CSS ne changera pas automatiquement avec le thème.

## Installation

1. Copiez `martinet_light.yaml` dans le dossier `themes/` de votre configuration Home Assistant.
2. Vérifiez que les thèmes sont chargés dans `configuration.yaml` :

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

3. Rechargez les thèmes depuis **Outils de développement → YAML → Recharger les thèmes**, ou redémarrez Home Assistant.
4. Choisissez **Martinet Light** dans votre profil utilisateur.

## Personnalisation

Modifiez les valeurs de couleur dans `martinet_light.yaml`, puis rechargez les thèmes. Les variables `martinet-*` peuvent aussi être utilisées par les cartes personnalisées qui les prennent en charge.

## Licence

Aucune licence de réutilisation n’est encore définie pour ce dépôt.

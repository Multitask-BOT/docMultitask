# 🎧 Vocaux privés

Système permettant aux membres de créer **automatiquement** leur salon vocal personnel.

## Configuration

### `/config vocaux-prives etat:<activer|desactiver> salon_creation:#salon categorie:Categorie?`

* **Activer** crée (ou vérifie) un _salon de création_ et une _catégorie vocaux privés_.
* **Désactiver** supprime proprement la configuration (salon/catégorie dédiés).

## Utilisation

1. Un membre rejoint le **salon de création**.
2. Multitask crée un vocal privé à son nom et le déplace dedans.
3. À la sortie de tous les membres, le salon est supprimé.

> Permissions nécessaires pour le bot : _Gérer les salons_, _Déplacer des membres_.

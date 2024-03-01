# Classes

### Utilisateur
- Attributs
    - Identifiant
    - Nom d'utilisateur (mail)
    - Mot de passe (hashé)
- Méthodes
    - Authentification
    - Désauthentification
    - Création de compte
    - Suppression de compte

### Personnage
- Attributs
    - Identifiant
    - Nom du personnage (facultatif)
    - Niveau
    - Attributs
    - Points champion
    - Compétences
- Méthodes
    - Créer personnage
    - Sauvegarder personnage (pour utilisateur)
    - Modifier personnage (pour utilisateur)
    - Supprimer personnage

### Equipement
- Attributs
    - Identifiant
    - Nom
    - Type
    - Catégorie
    - bonus unique
- Méthodes
    - CRUD

### Ensemble d'équipement
- Attributs
    - Identifiant
    - Nom de l'ensemble
    - Bonus
    - nb pièces
    - équipement
- Méthodes
    - CRUD

# Relations
- Un utilisateur peut avoir plusieurs personnage
- Un personnage appartient à un seul utilisateur
- Un ensemble d'équipement peut être attribué à plusieurs personnages
- Un personnage peut utiliser plusieurs ensemble d'équipements.

# Modèle de données (à réfléchir)



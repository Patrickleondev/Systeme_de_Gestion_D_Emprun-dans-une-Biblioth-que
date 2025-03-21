# Système de Gestion de Bibliothèque (Version Flask)

## Installation

1. Créez un environnement virtuel Python :
bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/MacOS
source venv/bin/activate


2. Installez les dépendances :
bash
pip install -r requirements.txt


3. Initialisez la base de données :
bash
# Créez la base de données et les tables
mysql -u root < database/schema.sql

# Ajoutez les données de test
mysql -u root < database/sample_data.sql


4. Démarrez l'application :
bash
flask run



5. Accédez à l'application :
- Ouvrez http://localhost:5000
- Connectez-vous avec :
  - Utilisateur : admin
  - Mot de passe : admin

## Fonctionnalités

1. Gestion des livres
   - Liste des livres
   - Ajout de nouveaux livres
   - Modification et suppression

2. Gestion des membres
   - Liste des membres
   - Ajout de nouveaux membres
   - Modification des informations

3. Gestion des emprunts
   - Historique des emprunts
   - Nouvel emprunt
   - Retour de livre
   - Renouvellement

4. Support technique
   - Bouton d'assistance WhatsApp
   - Contact direct avec le développeur

## Dépannage

Si vous ne voyez pas les données :
1. Vérifiez que MySQL est en cours d'exécution
2. Vérifiez que les scripts SQL ont été exécutés
3. Vérifiez les logs Flask pour les erreurs
#   S y s t e m e _ d e _ G e s t i o n _ D _ E m p r u n - d a n s - u n e - B i b l i o t h - q u e 
 
 

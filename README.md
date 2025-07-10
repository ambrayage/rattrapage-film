# 🎬 Film Manager - Mini-app Symfony

Cette application permet d'enregistrer les films vus ou à voir. Elle propose un CRUD complet avec un filtre pour n’afficher que les films non vus.

## 🚀 Installation

Cloner ce dépôt :
git clone https://github.com/votre-utilisateur/film-manager.git
cd film-manager

Installer les dépendances :
composer install

Configurer la base de données dans le .env :
DATABASE_URL="mysql://user:password@127.0.0.1:3306/film_manager"

Créer la base et lancer les migrations :
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate

Lancer le serveur :
symfony server:start

🔧 Fonctionnalités
Ajouter, modifier, supprimer un film

Afficher tous les films

Filtrer pour n’afficher que ceux à voir

📁 Dossier CRUD
Généré automatiquement avec Symfony Maker Bundle.

🧪 Exemple
"Interstellar" — vu ✅

"Les Évadés" — à voir 🔜

👤 Auteur : Ambre RAMOS
Développé dans le cadre d'une épreuve Symfony.

# E-serasera
Ce projet est une application web permettant aux utilisateurs de publier des articles et d’interagir autour de ces publications.

### ✨ Fonctionnalités principales

- Création d’articles avec catégories
- Like et Dislike
- Commentaires
- Barre de recherche en temps réel
- Chat intégré pour la communication

---

### 🧰 Technologies utilisées

- **Backend :** Symfony (PHP)
- **Authentification :** JWT (JSON Web Token)
- **Base de données :** sqLite
- **ORM :** Doctrine
- **Frontend :** React + Vite
- **Chat en Temps réel :** Mercure
- **Recherche temps réel :** JavaScript + AJAX
- **Sécurité :** Vérification des rôles, encodage des mots de passe

### 🚀 Installation

#### 1. Cloner le projet
git clone git@github.com:NyFitiaErnestini/E-serasera.git

cd ton-projet

2. Installation du backend (Symfony)
   
cd backend

composer install

Configurer le fichier .env.

Créer la base de données et exécuter les migrations :

php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
symfony server:start

3. Installation du frontend (React)
cd ../frontend
npm install
npm run dev
⚠️ Assure-toi que ton backend accepte les requêtes CORS depuis le frontend (nelmio/cors-bundle conseillé).

✅ Accès local
Frontend : http://localhost:5173
Backend : http://localhost:8000

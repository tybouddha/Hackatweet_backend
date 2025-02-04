# Hackatweet Backend

## 🚀 Prérequis
### Environnement
- [Node.js](https://nodejs.org/) (version 14.x ou supérieure)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/)

## 📥 Clonage du Projet
```bash
git clone https://github.com/tybouddha/Hackatweet_backend.git
cd Hackatweet_backend
```

## 📦 Installation des Dépendances
```bash
npm install  # ou yarn install
```

## 🔧 Configuration
### Variables d'Environnement
Créez un fichier `.env` à la racine du projet avec les variables suivantes :
```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/hackatweet
JWT_SECRET=votre_clé_secrète_jwt
CORS_ORIGIN=http://localhost:3001
```

### Configuration MongoDB
- Assurez-vous que MongoDB est installé et en cours d'exécution.
- Créez une base de données nommée `hackatweet`.

## ▶️ Démarrage du Serveur
### Développement
```bash
npm run dev  # ou yarn dev
```

### Production
```bash
npm run build
npm start  # ou yarn build && yarn start
```

## 📂 Structure du Projet
```
Hackatweet_backend/
│
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   └── config/
│
├── .env
├── package.json
└── README.md
```

## 🚀 Déploiement
### Plateformes Recommandées
#### **Heroku**
```bash
heroku create votre-nom-app
heroku config:set MONGODB_URI=votre_uri_mongodb
git push heroku main
```

#### **Railway**
- Connectez votre dépôt GitHub.
- Configurez les variables d'environnement.

#### **Render**
- Créez un nouveau service web.
- Pointez vers votre dépôt GitHub.
- Configurez les variables d'environnement.

#### **Docker**
```bash
# Construire l'image
docker build -t hackatweet-backend .

# Exécuter le conteneur
docker run -p 3000:3000 -e MONGODB_URI=votre_uri hackatweet-backend
```

## 🧪 Tests
```bash
npm test  # ou yarn test
```

## 🤝 Contribution
1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Commitez vos modifications (`git commit -m 'Add some AmazingFeature'`).
4. Poussez votre branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

## 📞 Contact
- **Brunée** - bruneecedric@gmail.com
- **Projet GitHub** : [Hackatweet Backend](https://github.com/tybouddha/Hackatweet_backend)

## 🚨 Problèmes Courants
- Assurez-vous que MongoDB est correctement installé et configuré.
- Vérifiez que toutes les variables d'environnement sont définies.
- Consultez les logs en cas d'erreurs de déploiement.

## 📚 Ressources Supplémentaires
- [📖 Documentation Node.js](https://nodejs.org/)
- [📘 Guide MongoDB](https://docs.mongodb.com/)
- [📙 Documentation Express.js](https://expressjs.com/)

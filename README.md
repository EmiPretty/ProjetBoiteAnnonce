# Projet Next.js

## Auteurs
**Nassim Bentifraouine**  
**Imene Bentifraouine**

---

## Prérequis
Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version recommandée : 16.x ou plus récente)
- [npm](https://www.npmjs.com/)

---

## Configuration du projet

### 1. Récupérer le fichier `.env`

⚠️ **Attention importante** ⚠️ : Le fichier `.env` est essentiel pour le bon fonctionnement de l'application, car il contient les variables d'environnement nécessaires (clés API, informations de connexion à la base de données, etc.). **Ne partagez jamais ce fichier publiquement**.

Pour obtenir ce fichier, veuillez me contacter directement.  
Sans ce fichier, l'application ne pourra pas fonctionner correctement.

---

### 2. Installation des dépendances

Dans le répertoire du projet, exécutez la commande suivante pour installer toutes les dépendances listées dans le fichier `package.json` :

```bash
npm install
```

---

### 3. Configuration Prisma

Ce projet utilise Prisma comme ORM pour interagir avec la base de données.

Assurez-vous que votre base de données est bien configurée et accessible.

Modifiez le fichier `.env` pour inclure l'URL de connexion à votre base de données.

Générez le client Prisma en exécutant la commande suivante :

```bash
npx prisma generate
```

---

### 4. Lancer le serveur de développement

Une fois toutes les étapes précédentes terminées, vous pouvez démarrer le serveur de développement avec la commande :

```bash
npm run dev
```

L'application sera accessible à l'adresse suivante : [http://localhost:3000](http://localhost:3000)
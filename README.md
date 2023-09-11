# BitChest - Résumé de l'Application

BitChest est une application de gestion de portefeuille de crypto-monnaies avec une interface d'administration développée en React.js et Vite.js. L'application vise à offrir une expérience utilisateur conviviale pour deux types de profils : les Administrateurs et les Clients.

## Fonctionnalités Principales

### Pour les Administrateurs

- Gestion des données personnelles.
- Gestion des clients, y compris la création, l'affichage, la modification et la suppression des données utilisateur.
- Gestion des droits utilisateur (Administrateur ou Client).
- Consultation des cours des crypto-monnaies.
- Affichage de la liste des crypto-monnaies et de leurs cours.

### Pour les Clients

- Gestion des données personnelles.
- Gestion du portefeuille, y compris l'affichage du contenu, du solde en euro, et la possibilité de vendre une crypto-monnaie.
- Consultation des cours des crypto-monnaies.
- Affichage de la liste des crypto-monnaies et de leurs cours.
- Consultation de la courbe de progression de chaque crypto-monnaie.
- Achat de crypto-monnaies au cours actuel.

## Le Portefeuille

- Chaque client possède un portefeuille privé contenant ses achats en crypto-monnaies.
- Les clients peuvent voir la liste des crypto-monnaies qu'ils possèdent, les détails des achats (date, quantité, cours), et la plus-value actuelle.

## L'installation:

Pour récupérer le code source du projet, utilisez la commande suivante :

```bash
git clone https://github.com/kohai-fred/bitchest-front.git
cd bitchest-front
```

2. Copiez le fichier `.env.example` et renommez-le en `.env`.

3. Installez les dépendances en utilisant yarn :

```bash
yarn install
```

4. Compilez les ressources du frontend :

```bash
yarn dev
```

5. Vous pouvez maintenant accéder à l'interface d'administration en visitant l'URL suivante dans votre navigateur :

```
https://127.0.0.1:5173
```

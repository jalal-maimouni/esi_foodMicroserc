## Fucntions

### First Microservice

```bash
# link
https://esi-foods-auth-api.vercel.app/api

```

- **register**: créer nouveau compte
- **login**: se connecter à compte existant
- **logout**: se déconnectet du compte existant
- **update username**: modifier username

### Second Microservice

```bash
# link
https://esi-foods-storage-api.vercel.app/api

```

- **upload file**: stocker les photos de profils sur firebase pour les utilisateurs ayant un compte

### Third Microservice

```bash
# link
https://esi-foods-products.vercel.app/api

```

- **get products**: Afficher tout les produits
- **get product by id**: Afficher un seul produit par son ID

On peut aussi : _(seulement l'admins)_

- **add product**: ajouter un produit dans la base de données
- **update product**: modifiier produit dans base de données 
- **delete product**: supprimer produit de la base de données

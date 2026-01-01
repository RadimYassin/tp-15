# API GraphQL Bancaire

Application Spring Boot exposant une API GraphQL pour la gestion de comptes bancaires et transactions.

## Technologies

- Spring Boot
- Spring GraphQL
- Spring Data JPA
- H2 Database

## Démarrage

```bash
mvn spring-boot:run
```

## Endpoints

- GraphQL: `http://localhost:8080/graphql`
- GraphiQL: `http://localhost:8080/graphiql`

## Requêtes disponibles

- `allComptes` - Liste des comptes
- `compteById(id)` - Compte par ID
- `totalSolde` - Statistiques des soldes
- `allTransactions` - Liste des transactions
- `transactionStats` - Statistiques des transactions

## Mutations

- `saveCompte(compte)` - Création de compte
- `addTransaction(transaction)` - Ajout de transaction
# tp-15


## Author

- **Yassine Radim**

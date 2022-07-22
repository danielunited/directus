# Quick Directus Demo

A quick demo of Directus with a [sample PostgreSQL database](https://dataedo.com/samples/html/World_PostgreSQL/doc/World_(PostgreSQL_database)_11/home.html). 

Work in progress.
## Installation

```
yarn
```

```
docker run -d --name directus-db-container -p 5432:5432 danielalter/directus-db
```

```
npx directus bootstrap
```

```
npx directus start
```

Your app will now be live at [localhost:8055](http://localhost:8055)

Login with the following credentials:
```
Username: admin@example.com
Password: password
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
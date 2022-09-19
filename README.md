
### `About:`
This is the backend CMS that is powering the [blog](https://www.adamhunter.website/blog) of [adam-nextjs-site](https://github.com/Adamhunter108/adam-nextjs-site).  

### `Tech Stack:`
| JavaScript | Node.js | PostgreSQL | Strapi | Cloudinary | AWS
| :----: | :----: | :----: | :----: | :----: | :----: |
| <img src="https://cdn.worldvectorlogo.com/logos/logo-javascript.svg" width="50" height="50"/> | <img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" width="50" height="50"/> | <img src="https://cdn.worldvectorlogo.com/logos/postgresql.svg" width="50" height="50"/> | <img src="https://cdn.worldvectorlogo.com/logos/strapi-2.svg" width="50" height="50"/> | <img src="https://cdn.worldvectorlogo.com/logos/cloudinary-2.svg" width="50" height="50"/> | <img src="https://cdn.worldvectorlogo.com/logos/aws-2.svg" width="50" height="50"/>  

### `Specifics:`
The `main` branch of this git repository deploys automatically to `Railway` ([adam-blog-railway-strapi.up.railway.app](https://adam-blog-railway-strapi.up.railway.app)) for CI/CD.  The production environment uses a `PostgreSQL` database and uploads media to `Cloudinary`.  Changes made to the CMS ***must*** be made by developing locally.


### `Local Development:`
#### `Requirements:`

* Node.js <img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" width="25" height="25"/> (v12-16 only)
* `.env` for environment variables

```bash
$ # check node.js version
$ node -v
$ # if using older or newer version of node.js
$ nvm use node 16
$ # install dependencies
$ npm i
$ # start local development node.js server
$ npm run develop
$ # or
$ yarn develop
```

Or create your own Strapi CMS with PostgreSQL database on Railway:  
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/strapi)

<!-- ---
title: Strapi
description: A self-hosted version of Strapi using a Postgres database
tags:
  - strapi
  - postgresql
  - cms
  - javascript
---

# Strapi example

This example deploys self-hosted version of [Strapi](https://strapi.io/). Internally it uses a PostgreSQL database to store the data.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/strapi)

## ✨ Features

- Strapi
- Postgres

## 💁‍♀️ How to use

- Click the Railway button 👆
- Add the environment variables
  - If you do not add the Cloudinary related environment variables, your images/files will not be persisted between deploys.

## 📝 Notes

- After your app is deployed, visit the `/admin` endpoint to create your admin user.
- Railway's filesystem is ephemeral which is why any changes to the filesystem are not persisted between deploys. This is why, this example uses Cloudinary for storage. -->

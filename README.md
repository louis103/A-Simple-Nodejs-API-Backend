## A Simple Nodejs CRUD API Backend

### Install project on localhost(make sure you have nodejs installed)
```javascript
git clone github.com/louis103/A-Simple-Nodejs-API-Backend.git
cd A-Simple-Nodejs-API-Backend
run npm i
run npm run dev
```

### Instructions on setting up mongodb atlas: for backend database

#### Head over to [mongodb atlas](https://cloud.mongodb.com/) and create an account and a project.

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/init_atlas.png"/>

#### Next create a mongodb database...

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/create_database.png" />

#### Next create a mongodb collection, in this case a Products collection just as the database model

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/create_collection.png"/>

#### CRUD API; CREATING products using Postman software.

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/create_product1.png" />
<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/create_product2.png" />

#### READ; fetch all products from the mongodb database

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/get_all_products.png"/>

#### UPDATE; update a product in mongodb database using product ID

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/update_by_id.png"/>

#### DELETE; delete a product in mongodb database using product ID

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/delete_by_id.png"/>

#### View data in [mongodb atlas ui](https://cloud.mongodb.com/)

<img align="center" src="https://github.com/louis103/A-Simple-Nodejs-API-Backend/blob/main/scrshots/view_in_atlas.png"/>

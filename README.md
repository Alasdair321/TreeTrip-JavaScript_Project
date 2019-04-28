# CodeClan Week 9 Group Project
**[Alasdair Carstairs](https://github.com/Alasdair321), [Eric Cross](https://github.com/ericxcross), [Myriam Boran](https://github.com/MyriamBoran)**

## TreeTrip Javascript Project

Find out the number of trees required to absorb the released CO2 from your trip by selecting from the transport categories and providing the distance travelled.

![Screenshot landing page](client/public/images/screenshot1.png)
![Screenshot first category](client/public/images/screenshot2.png)
![Screenshot second category](client/public/images/screenshot3.png)
![Screenshot distance category](client/public/images/screenshot4.png)
![Screenshot results](client/public/images/screenshot5.png)
![Screenshot alternative options](client/public/images/screenshot6.png)

## Running the website locally:

Install dependencies:

```
npm install
```

Run a mongoDB server:

```
mongod
```

Seed the database:

```
mongo < server/db/seeds.js
```

Run webpack:

```
npm run build
```

Run express:

```
npm run server:dev
```

### Using

The application is running on port 300 so visit http://localhost:3000.

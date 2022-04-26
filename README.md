# Szakdolgozat
Egy érdekes és szemkápráztató webáruház, ami Vue.js-ben készült. Ehhez a projekthez a [Vue CLI](https://github.com/vuejs/vue-cli) 3.x verziója került felhasználásra.

## Tulajdonságok
1. A felhasználó képes fiókot létrehozni, abba bejelentkezni, illetve új jelszót kérni email cím segítségével.
2. CRUD műveletek
    * A felhasználó hozzá tud adni termékeket és azokat törölni.
    * Az adminisztrátor hozzá tud adni termékeket a kínálathoz.
    * Az adminisztrátor törölheti vagy szerkesztheti a hozzáadott termékeket.
3. Biztonság
    * A felhasználó jelszava titkosításra kerül a fiók létrehozása során.

## Felhasznált eszközök
A felhasználáshoz a következők kerültek felhasználásra: Vue.js, Node.js, MongoDB, Bootstrap, Express

## Telepítés
1. VueCLI [telepítése](https://cli.vuejs.org/guide/installation.html)
2. NodeJS [telepítése](https://nodejs.org/en/download/)
3. Csomagkezelő használata (NPM/Yarn)
4. Git clone esetén érdemes a frontend és a backend mappában lefuttatni az `npm install` vagy a `yarn install` parancsot.
5. A MongoDB adatbázis beállítása a `backend/app.js` elérési úton.
### Példa:
```
    const MONGODB_URI = 'mongodb://127.0.0.1:27017/spacey';
```
6. A szerverek elindítása: `npm start`(backend) és `npm run serve`(frontend)

## Képernyőképek

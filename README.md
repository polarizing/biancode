# biancode

### Biancode is an outcomes-driven online learning platform and is used to power the BianCode coding bootcamp.

You need postgres running locally. You can install postgres on a Mac through the command-line ```brew install postgres```.

To install and run the application on a local server **for the first time**:

1. Install node modules and packages. ```npm install```
2. Start a local postgres server (easiest through GUI interface). 
3. Create a database through the command-line. ```CREATEDB biancode```
4. Seed the database. ```node seed```
5. Start the server. ```npm start```
6. Visit ```localhost:1337```.

To run the application **from a pre-existing build**:

1. Seed the database. ```node seed```
2. Start the server. ```npm start```
3. Run ```gulp``` (auto-refreshing) or ```gulp build``` (build once).
4. Visit ```localhost:1337```.

##### For Developers
- Never push to master.

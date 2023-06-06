# sellzify-server

1. git clone https://github.com/ganeshnayanajith/sellzify-server.git
2. create a local mongo database called 'sellzify'
3. uncomment following code in the index.js for the first run
   ```
   // AffiliateStat.insertMany(dataAffiliateStat);
   // OverallStat.insertMany(dataOverallStat);
   // Product.insertMany(dataProduct);
   // ProductStat.insertMany(dataProductStat);
   // Transaction.insertMany(dataTransaction);
   // User.insertMany(dataUser);

   // console.log('data inserted');
   ```
4. npm install
5. npm run start
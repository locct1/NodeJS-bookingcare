npm install body-parser@1.19.0 dotenv@8.2.0 ejs@3.1.5 express@4.17.1

npm install --save-dev @babel/core@7.12.10 @babel/preset-env@7.12.10 @babel/node@7.12.10 nodemon@2.0.7

npm install --save-dev sequelize-cli@6.2.0
npm install --save mysql2@2.2.5
npm install --save sequelize@6.6.2

npm install --save-dev react-number-format@4.6.4

npx sequelize-cli init
node_modules/.bin/sequelize init

Tạo model: 
npx sequelize-cli model:generate --name User --attributes 'firstName:string,lastName:string,email:string'

 4: Tạo migrations:
npx sequelize-cli db:migrate

5. Tạo Seeder: npx sequelize-cli seed:generate --name demo-user

npx sequelize-cli db:seed:all

npm install @babel/node -g ('babel-node' is not recognized as an internal or external command, operable program or batch file.)


let deleteUser = (data) => {
    return new Promise(async (resolve, reject) => {
        try {

            
        } catch (e) {
            reject(e);
        }
    })
}
nho vid 52  41:01

npx sequelize-cli db:migrate --to migration-create-user.js

npx sequelize-cli db:migrate

raw:true covert obj (Markdown==null)
raw:false sequelize obj(Markdown{

})
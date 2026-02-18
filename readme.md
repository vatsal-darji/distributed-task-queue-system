node version = 20.17.0

few sequelize commands :

- generare models : npx sequelize-cli model:generate --name modelname --attributes title:string
- run migration : npx sequelize-cli db:migrate
- run all seeder : npx sequelize-cli db:seed:all
- run particular seed : npx sequelize-cli db:seed --seed seedname

env info:

- PORT=8000
- DATABASE_URL=postgres://username:password@host:port/dbname
- JWT_SECRET=''

run guide commands:

- match your node version
- npm i
- add .env
- edit migration (as per your requirnments)
- migration with sequelize
- npm run dev (for development)

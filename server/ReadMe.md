## Backend setup for local development

You can refer to the `.env.example` file to setup your local development.

To use production database, you should change the `MONGO_URL` to `<MONGO_URL>/?retryWrites=true&w=majority`.

If you want to setup your local database, you should update your standalone mongodb instance to support replica sets. (No need to update if your mongo instance already supports replica sets.)

Please refer to [this](https://adelachao.medium.com/create-a-mongodb-replica-set-in-windows-edeab1c85894) document for creating replica sets.

Local replica set mongo setup using docker-compose: [guide](https://stackoverflow.com/a/66016351)

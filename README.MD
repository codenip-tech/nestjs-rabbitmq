## How to run the project
- Run RabbitMQ instance with `docker-compose up -d`
- This will allow you to navigate to `http:localhost:15672` (user and password: `guest`) to see the instance
- Go to Producer folder, install dependencies with `yarn` and run the process with `yarn start:dev`
- Go to Consumer folder, install dependencies with `yarn` and run the process with `yarn start:dev`
- Now you can use Postman or a similar tool to call the POST endpoint with a cat name
```
POST /cats
{
  "name":"Brian"
}
```
# Starting the app via Docker

- Make sure you have docker installed - the app will run via docker-compose
- Add a .env file in the root directory
- Install project and submodules e.g. in folder `job-keywords`:
```
mkdir job-keywords
cd job-keywords
git clone --recurse-submodules git@github.com:lambley/job-keywords.git .
```

# Starting the app locally
## Starting the Client App
Use this command:
```
npm run dev
```

This launches the app on localhost 3001

## Starting the Server app
Use this command to start the server:
```
nest --watch
```

Also remember to start the redis server:
```
sudo service redis-server start
```

and end it using:
```
sudo service redis-server stop
```

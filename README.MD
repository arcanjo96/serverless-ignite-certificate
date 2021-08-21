### Install dependencies
```
npm i
```

### Run application
```
npm run dynamodb:install

npm run dynamodb:start && npm run dev
```

### Deploy application to your favorite provider (this application using aws)
```
serverless config credentials —provide aws —key=YOUR_KEY —secret=YOUR_SECRET -o 

npm run deploy:dev (dev)
npm run deploy:prod (production)
```
# Learn json-server

## Step By Step

1. Install  json-server in global
	```dash
	npm install json-server -g
	```

2. Create json file ('./data/db.json')

3. Run json-server
	```dash
	json-server --watch data/db.json
	```
4. Open [http://localhost:3000](http://localhost:3000) ( json-server default is listen 3000 port )

5. Create test file ('./test/index.html' & './src/index.js') 

6. Run Http Server
	```dash
	node ./src/index.js
	```

7. Open [http://localhost:8080](http://localhost:8080)

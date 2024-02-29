JSON -deployment Server Creation
---------------------------------

1.create a folder for json
2.using Command :'npm init -y' to create package.json file
3.add the 'start' command as 'node index.json' in script of package.json file
4.creqate .gitignore file
5.create db.json file
7.add resources in db.json like 'videos','categories' and 'history'
9.to install resources in json-server:'npx json-server db.json'/ npm i json-server@0.17.4
8.create index.js file
   - import json-server
   - create server using json-server
   - create a middleware
   - setup path for db.json
   - define port
   -  listen server in the given port


//host using node 
to run json file using json-server: using command 'npx json-server db.json'/node index.js
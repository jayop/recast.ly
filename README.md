npm install babel-watch
npm install -g lite-server

babel . --out-dir compiled --presets=es2015,react --ignore=node_modules,compiled --source-maps inline --watch

lite-server
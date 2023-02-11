# Module-Federation

```
npx degit https://github.com/jherr/wp5-starter-react-ts.git ts-remote
npx degit https://github.com/jherr/wp5-starter-react-ts.git ts-host

yarn start

// links ts-host with ts-remote to use the pokemon type
yarn workspace ts-host add ts-remote@1.0.0

// clone ts-remote porject and name it shared-types
cp -r ts-remote shared-types 

// Add shared-types to both ts-remote and ts-host
yarn workspace ts-remote add shared-types@1.0.0
yarn workspace ts-host add shared-types@1.0.0  

```

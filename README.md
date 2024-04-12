Install node modules:
```
npm install
```
Install nodemon:
```
npm install nodemon
```
Install typescript:
```
npm install -D typescript
```
Create the tsconfig.json file:
```
npx tsc --init
```
Install ts-node in order for nodemon to work with typescript:
```
npm i -g ts-node
```
In order to run nodemon you need to specify that the file is index.ts file now since by default it will look for index.js:
```
nodemon src/index.ts
```
Install type declarations for Node:
```
npm i --save-dev @types/node                    
```
Install type declarations for express:
```
npm i --save-dev @types/express
```

# NodeJS-API-Ethereum

## Prerequisites 

- Node.js
- Truffle 
- Ganache
- Web3.js
- Postman

## Setup

Install truffle and ganache with the following commands:

```bash
npm install -g truffle
```

```bash
npm install -g ganache
```

Install dependencies for the project

```bash
npm install
```

## Start API

#### Start Ethereum blockchain

```bash
ganache-cli
```

#### Compile and Migrate Smart Contract

Compile the contract

```bash
truffle compile
```

Deploy the contract

```bash
truffle migrate
```

![image](https://user-images.githubusercontent.com/34191864/227470630-59a9c65a-a3aa-4cae-83a7-a2e97f4bdcbc.png)


Copy the value of the `contract address` displayed in console after deploy the contract (as shown in image above) and update the value of the variable `contractAddress` in [line 5](https://github.com/danielcs2000/NodeJS-API-Ethereum/blob/cb84f78a761a8aee4a7f24cf88e337a3f6fbd6d7/app.js#L5) of app.js

#### Run express server

```bash
node app.js
```

## Test API


#### Get initial value of `myNumber` variable

![image](https://user-images.githubusercontent.com/34191864/227468207-70094ad8-3c8d-4594-87cf-e0adac09c700.png)

#### Set value of `myNumber` to 5

![image](https://user-images.githubusercontent.com/34191864/227468675-f49fe631-78cc-4ef9-8747-200a8cfc969b.png)

#### Get final value of `myNumber` variable

![image](https://user-images.githubusercontent.com/34191864/227469216-ef845440-96a5-428f-91da-3efd941d3307.png)




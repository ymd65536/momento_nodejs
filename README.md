# momento_nodejs

Node.js でMomentoを動かす

## SetUp

```sh
npm install @gomomento/sdk
npm install dotenv
```

```sh
export MOMENTO_AUTH_TOKEN=<your Momento token here>
export MOMENTO_TTL_SECONDS=300
```

## Run

```sh
cd ~/Desktop
git clone https://github.com/ymd65536/momento_nodejs.git
cd momento_nodejs
node test.js
```

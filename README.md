# Fabric V1 alpha based NodeSDK sample with TLS disabled 

### Steps to run the sample

#### STEP1: Clone the repo

```
git clone https://github.com/asararatnakar/fabric_v1_nodesample_nontls
```

#### STEP2: Install fabric-client fabric-ca-client node modules

```
cd fabric_v1_nodesample_nontls

npm install
```

#### STEP3: Launch the network

```
cd fabric_v1_nodesample_nontls/artifacts/

docker-compose up -d
```

### STEP4: execute the applications one after another

```
cd fabric_v1_nodesample_nontls/app
```

**CREATE CHANNEL**

`node create-channel.js`

**JOIN CHANNEL**

`node join-channel.js`

**INSTALL CHAINCODE**

`node install-chaincode.js`

**INSTANTIATE CHAINCODE**

`node instantiate-chaincode.js`

**INVOKE**

`node invoke-transaction.js`

**QUERY**

`node query.js`

## OR

##### Run the app with shell script


```
cd fabric_v1_nodesample_nontls/

./runApp.sh
```

# Swisstronik Tesnet Techinal Task 6 (Deploy Proxy)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0x3445c3aa2061d3989a5a9B159E31699C5C0d5D61
```

Tutorial Video : [Youtube](https://youtu.be/IucFidGBwo8?si=AfvMha-QyylsfUg6)

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/Mnuralim/swisstronik-deploy-proxy.git
```

```bash
cd swisstronik-deploy-proxy
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
touch .env
```

add this to your .env file

```bash
PRIVATE_KEY="your private key"
```

### 4. Compile Smart Contract

```bash
npm run compile
```

### 5. Deploy Smart Contract

```bash
npm run deploy
```

### 6. Initialize Owner

```bash
npm run initialize
```

### 7. Add Issuer

```bash
npm run add-issuers
```

### 8. Get Issuers list

```bash
npm run list-issuers
```

### 9. Upgrade Smart Contract

```bash
npm run upgrade
```

### 10. Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github

credit by :

github : [Mnuralim](https://github.com/Mnuralim)

twitter : @Izzycracker04

telegram : @fitriay19

youtube : https://www.youtube.com/@IzzyTSN

Ignore this!!!

```
SWTRProxy = '0x52228e79969e3e8969AaAB49e3071bB28E54304c'
ProxyAdmin = '0xA3d32182Afcbe8941e3976991e242a9F2a671613'
SWTRImplementation = '0xaf3D8bD3232833677b748fd36c3d77c865B2Ce00'
```

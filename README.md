# xRollup
xRollup is a layer 2 scaling solution leveraging zkSnarks.

## Projects
### Payment Channels (name?)

### Non-custodial centralized exchange. (name?)



### Deploying the xRollup Burner Wallet

```sh
git checkout gh-pages
cd burner-wallet
npm run build
git add build
git commit -m "Update burner wallet distribution"
cd ..
git subtree push --prefix burner-wallet/build origin gh-pages
```
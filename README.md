# Wukong Coin Android Wallet
Another Android Wukong lighting Wallet

### QUICKSTART
- Download the APK for the most current release [here](https://github.com/m2049r/xmrwallet/releases) and install it
- Run the App and select "Generate Wallet" to create a new wallet or recover a wallet
- Advanced users can copy over synced wallet files (all files) onto sdcard in directory Monerujo (created first time App is started)
- See the [FAQ](doc/FAQ.md)

### Disclaimer
Please write down the 25 seed

### Random Notes
- Based off Wukong v0.11.1.0
- currently only android32 (runs on 64-bit as well)
- works on the testnet & mainnet
- sync is slow due to 32-bit architecture
- use your own daemon - it's easy
- screen stays on until first sync is complete


### Issues / Pitfalls
- You should backup your wallet files in the "monerujo" folder periodically.
- Also note, that on some devices the backups will only be visible on a PC over USB after a reboot of the device (it's an Android bug/feature)
- Created wallets on a private testnet are unusable because the restore height is set to that
of the "real" testnet.  After creating a new wallet, make a **new** one by recovering from the seed.
The official monero client shows the same behaviour.

### HOW TO BUILD
No need to build. Binaries are included:

- openssl-1.0.2l
- Wukong-v0.11.1.0
- boost_1_64_0

If you want to build them yourself (recommended) check out [the instructions](doc/BUILDING-external-libs.md)

Then, fire up Android Studio and build the APK.

### Donations
- Address: 9yKxFHfe61QKLegJcPYzFDaGRXu24syM4QBMJoEN1wNggBStpTxM1iNE2HwZwHkesNUfr2tDp9zrx6LUVauzcnTUUnERUfB


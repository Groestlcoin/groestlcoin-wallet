# GROESTLCOIN WALLET

Welcome to _Groestlcoin Wallet_, a standalone Groestlcoin payment app for your Android device!

This project contains several sub-projects:

 * __wallet__:
     The Android app itself. This is probably what you're searching for.
 * __market__:
     App description and promo material for the Google Play app store.


### PREREQUISITES FOR BUILDING

You'll need git, a Java 11 SDK and Gradle between 4.4 and 6.9.x for this. We'll assume Ubuntu 22.04 LTS (Jammy Jellyfish)
for the package installs, which comes with OpenJDK 11 and Gradle 4.4.1 out of the box.

    # first time only
    sudo apt install git gradle openjdk-11-jdk

Create a directory for the Android SDK (e.g. `android-sdk`) and point the `ANDROID_HOME` variable to it.

Download the [Android SDK Tools](https://developer.android.com/studio/index.html#command-tools)
and unpack it to `$ANDROID_HOME/`.

Finally, the last preparative step is acquiring the source code. Again in your workspace, use:

    # first time only
    git clone -b master https://github.com/Groestlcoin/groestlcoin-wallet.git groestlcoin-wallet
    cd groestlcoin-wallet


### BUILDING

You can build all sub-projects in all flavors at once using Gradle:

    # each time
    gradle clean build

For details about building the wallet see the [specific README](wallet/README.md).

### Stores
 * __Testnet__:
   <a href="https://f-droid.org/app/hashengineering.groestlcoin.wallet_test">F-Droid</a> |
   <a href='https://play.google.com/store/apps/details?id=hashengineering.groestlcoin.wallet_test'>Google Play</a>
 * __Mainnet__:
   <a href="https://f-droid.org/app/hashengineering.groestlcoin.wallet">F-Droid</a> |
   <a href='https://play.google.com/store/apps/details?id=hashengineering.groestlcoin.wallet'>Google Play</a>

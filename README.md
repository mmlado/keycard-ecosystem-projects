# keycard-ecosystem-projects
A curated list of projects in the Keycard ecosystem

| :point_up:    | You are encouraged to contribute - please create a pull request and insert entry into suitable section **lexicographically**. Thank you! |
|---------------|:------------------------|


## Hardware products 

https://github.com/keycard-tech/status-keycard  
Keycard is an implementation of a BIP-32 HD wallet running on Javacard 3.0.4+.

https://github.com/keycard-tech/keycard-shell  
Keycard Shell transforms any Keycard into a standalone modular hardware wallet with built-in keypad, display, camera, and USB. Fully open-source and EAL6+ certified, it uses ERC-4527 and UR2.0 QR codes for secure signing. Can be used fully airgapped.

## Software wallets 

https://github.com/status-im/status-desktop  
Status desktop built with nim and Qt

https://github.com/status-im/status-mobile  
Status mobile built with go and Clojure 

https://github.com/walleth/walleth  
Android mobile wallet for Ethereum 

## Other applications 

[https://github.com/choppu/keycard-desktop](https://github.com/choppu/keycard-desktop "https://github.com/choppu/keycard-desktop")  
Keycard Desktop application to manage your Keycards (not a wallet). 

https://github.com/rkreutz/keycard-manager-help/  
Closed source tool to manage your keycard, load any applets (cap file), FIDO2 applet, and encrypt decrypt files. On apps store: https://apps.apple.com/iq/app/keycard-manager/id1610328465

## SDKs and CLIs

https://github.com/keycard-tech/keycard-go  
Go SDK for Keycard.

https://github.com/keycard-tech/status-keycard-java  
This SDK simplifies integration with Keycard in Android and Desktop applications. In this SDK you find both the classes needed for generic communication with SmartCards as well as classes specifically addressing Keycard.

https://github.com/keycard-tech/Keycard.swift  
Swift SDK to integrate Keycard with iOS13+.

https://github.com/choppu/keycard-sdk  
Typescript SDK for Keycard.

https://github.com/keycard-tech/keycard-cli  
Keycard-CLI is a command line tool to manage Keycards.

https://github.com/keycard-tech/react-native-status-keycard  
React Native library to interact with Keycard using [Java SDK](https://github.com/status-im/status-keycard-java)

https://github.com/choppu/kprojs  
Javascript API to communicate with Keycard Shell through USB with websites and through nodejs-based native applications.

https://github.com/nxm-rs/apdu  
Rust toolkit for smartcards. nexum-apdu is a comprehensive toolkit for smart card communication in Rust using the APDU (Application Protocol Data Unit) protocol. Whether you're building a payment terminal, identity verification system, or HSM integration, nexum-apdu provides the foundation for secure card communications. Can be used for other smartcards than Keycard.

https://github.com/nxm-rs/keycard  
Rust toolkit (SDK and CLI) for interacting with Keycards. Also includes an `alloy` signer for making use of Keycard in `alloy'

## Tools 

https://github.com/keycard-tech/keycard-certify  
A tool to create certificates for Keycard manufacturing.

[https://github.com/choppu/kpro-updater] (https://github.com/choppu/kpro-updater "https://github.com/choppu/kpro-updater"  
A desktop tool to upgrade Keycard Shell. Not complete yet because it can only download files from a server. Will add selecting local files also. Useful because only chrome-based browser support webhid, so firefox user can use this instead to upgrade keycard Shell. 

https://github.com/keycard-tech/keycard-exit  
Mobile application on Android and iOS to store operators on Keycard Multipass and login the operators dashboard when accessed through a web browser.

https://github.com/keycard-tech/keycard-certify  
To create certificates you should first fill in the form, specifying lot number, the quantity of cards for which you need to create a certificate, destination path for the certificates file and choose the output encryption PGP key. You also need a Keycard to sign the certificates. Path `m/43'/60'/1581'/2'/0` will be used to sign.

https://github.com/keycard-tech/payment-network-apps  
This repository contains the dApps and SmartContract used for the Keycard Payment Network. The goal of the project itself is to provide the means for using the Keycard as a payment method in retail stores or other non-remote scenarios (i.e: both merchant and buyer are in the same place). The aim is to make purchases using cryptocurrencies as easy and familiar as tapping your card to POS. Note that there is no crypto-to-fiat conversion involved so the scenario we are addressing is where all parties want to use crypto. Beside convenience, the network we are building will have several mitigation measures for unauthorized transactions. While some of these measures are already in place, more are in the works

https://github.com/keycard-tech/keycard-redeem  
This repository contains SmartContracts, dApps and tools to enable using the Keycard Cash applet as a asset redeeming tool. Usage scenario include gift cards, prepaid cards and general distribution of assets. Both ERC20 and NFT are supported. Beside redeeming the asset, in the NFT scenario, the way mappings are created between card and asset can also be useful for user authentication scenario in a context with lower security concerns, such as ticketing for events

https://github.com/keycard-tech/keycard-connect  
Keycard Connect's main function is to enable using the Keycard with dApps outside of a web3 browser using WalletConnect. The dApp must of course support WalletConnect for this to work. Additionally, this app is a little toolbox for Keycard, allowing things like changing PIN, initializing cards, changing seed etc.

https://github.com/keycard-tech/keycard-ledger  
Tentative Ledger application to run a emulated Keycard hardware wallet on Ledger, uses Keycard API over Ledger.

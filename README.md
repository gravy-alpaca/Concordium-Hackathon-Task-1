# Concordium Hackathon
## Task 1: Setup Development Environment
*Done By gravy-alpaca*
### Step 1: Installing Rust 
I installed rust using the following command:
``` curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh ```
![94fb9f7b-4f92-4b04-afb0-d1ab5fe96415](https://user-images.githubusercontent.com/125801855/220115784-2b137c1f-e219-433c-be2e-9fe47196b033.jpg)
### Step 2: install wasm32-unknown-unknown target by using this command
```rustup target add wasm32-unknown-unknown```
![4708fe38-4ebf-47f1-8a3d-d44329a74109](https://user-images.githubusercontent.com/125801855/220116122-ef0c5d37-d7f6-44ea-bd73-75088de4c524.jpg)
### Step: 3 Cargo-Concodium
-Download the latest release (2.7.0)
-move the download to ~/.cargo/bin
![56446d1a-1a65-4106-baf6-edfceb41a2a0](https://user-images.githubusercontent.com/125801855/220117883-bef302b7-1896-4938-aa90-12edfd537d93.jpg)
-check if everything was downloaded properly throught this command:
```cargo concordium --help```
![d841f4a3-8c67-4a1a-820a-0b2a878eecf3](https://user-images.githubusercontent.com/125801855/220118154-8cada423-adc2-4a18-a316-701f5c9e5efb.jpg)
### Step 4: Install the Concordium Client
-Download the latest release
-move the download to ~/.cargo/bin
check if everything was downloaded properly throught this command:
```cargo concordium-client --help```
![9c47044e-4065-4a8b-86aa-88b6aa202c27](https://user-images.githubusercontent.com/125801855/220119812-6834126f-6c8c-4508-a8f2-1440f82a9897.jpg)
### Step 5:Setup a Testnet Account and get testnet CCD
- First Download the COncordium walllet extension from google chrome webstore

![02217caa-ed4b-42ba-b19a-2f55eb5f4df1](https://user-images.githubusercontent.com/125801855/220121213-4022658d-b290-4f62-8646-358ec4856ab3.jpg)
-Create and claim CCD from the in-wallet faucet
![6ceff7b0-edb2-4a4a-9579-ca877013950a](https://user-images.githubusercontent.com/125801855/220121417-12a23bd4-194f-4539-80c0-343f51a8ebf1.jpg)
### Step 6: Export Wallet keys and import them into the Concordium Client
- ```home/amog/Downloads/amogshard/concordium-client config account import /home/amog/Downloads/amogshard/4PScWz3JrKp5naRZxax5xRHD5QxJPGb333ACiDaweApxn17aDR.export --name Gravy-Alpaca ```
![aff96ac8-112d-4dbc-9df1-1f8467f17e96](https://user-images.githubusercontent.com/125801855/220123331-832e6817-d9de-4d23-b18b-fa8c7a688b91.jpg)
# That's it!!!

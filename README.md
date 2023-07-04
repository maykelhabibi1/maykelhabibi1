### Hi there 👋

<!--
**maykelhabibi1/maykelhabibi1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->git clone https://github.com/AleoHQ/leo
cd leo
sudo apt install screen -y

git clone https://github.com/AleoHQ/snarkOS.git --depth 1

cd snarkOS

./build_ubuntu.sh

cargo install --path .

screen -S client

./run-client.sh

\\\\\\\\\\Press CTRL+A+D

snarkos account new

\\\\\\\\\\\\Private Key  APrivateKey1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   \\\\\\\\\\  View Key  AViewKey1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
 \\\\\\\\    Address  aleo1xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

screen -S prover

./run-prover.sh

\\\\\\Enter your private Key

\\\\ Press CTRL+A+D

go to site https://www.aleo.network/transactions




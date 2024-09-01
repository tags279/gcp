# gcp-mining-app

run the necessary updates first before running the script.
INSTALL NODEJS FIRST (use fnm)
# installs fnm (Fast Node Manager)
curl -fsSL https://fnm.vercel.app/install | bash

# activate fnm
source ~/.bashrc

# download and install Node.js
fnm use --install-if-missing 20

wget the release
tar -xvf gcp.tar.gz
# this installs the dependencies indicated on the package.json file
npm install

# run the index.js (for localhost)
node index.js



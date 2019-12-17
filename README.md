# APP_Criptomoedas
API https://www.mercadobitcoin.com.br/api-doc/
Bitcoins  https://www.mercadobitcoin.net/api/BTC/ticker/
ethereum  https://www.mercadobitcoin.net/api/ETH/ticker/
litecoin https://www.mercadobitcoin.net/api/LTC/ticker/

https://app-manifest.firebaseapp.com/

Gerando diretorio no cmd
npm install workbox-cli --global
Manually enter path
 ./
selecione todos os arquivos
sw.js
workbox-config.js
npm install http-server  -g
http-server


const API_KEY='cc9e5c8a661511c35e4ad418ac197b177b63f34933ad3dbdbe542f7b2a364250';
let url ='https://min-api.cryptocompare.com/data/pricemulti?fsyms=BTC,ETH,LTC&tsyms=USD&api_key=' + API_KEY;
axios.get(url).then((response)=>{


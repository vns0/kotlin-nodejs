# kotlin-node example

The project was created to demonstrate the possibility of hybrid use of two technologies. The idea is to write on what you know (javascript) and the ability to get multithreading (kotlin).
If you are interested in this topic - write to me, maybe I can help you)

# Kotlin [Inst]

Clone the repository and cd the working directory:

    git clone git@github.com:nikitavoryet/kotlin-nodejs.git
    cd kotlin-nodejs

Build and run the program:

    npm i
    npm run build
    npm run start


Curl Example:
```
curl 'http://localhost:3000/getCryptoFakeRate'

response: [{"name":"BTC","price":60768.63,"pair":"USD","sign":"$"},{"name":"ETH","price":4210.93,"pair":"USD","sign":"$"}]

curl 'http://localhost:3000/getCryptoFakeRate?code=BTC'

response: [{"name":"BTC","price":60768.63,"pair":"USD","sign":"$"}]

curl 'http://localhost:3000/getCryptoFakeRate?code=NotFound'

response: [{"name":"BTC","price":60768.63,"pair":"USD","sign":"$"},{"name":"ETH","price":4210.93,"pair":"USD","sign":"$"}]

```
    author: 
    
    Name:          Nikita
    Company:       SmartWorld
    Position:      TeamLead
    Mail:          n.vtorushin@inbox.ru
    TG:            @nikitavoryet
    Year of birth: 1999
    FullStack:     JS/GO

**AirAccount Product Design**

##### AirAccount is an Ethereum application account framework built on Account Abstraction.
#### Why build AirAccount?
Gap and Benefits: there are so many barriers for Normal Guys to the Blockchain:

Bad UX, Tech Difficulty, No Internet or Smartphone and more.

Account Abstraction is a feature on Ethereum Roadmap to **mass adoption**.

It need get rid of all this problems with decntralized and diversity components.

So we create AirAccount **components** for Account Abstraction:

A Decentralized Ethereum Account Solution with **Easy, Affordable and Security**.

#### What is Air Account?

**AirAccount is an Ethereum application account framework built on Account Abstraction(EIP4337).**

It is an Opensource framework to **Bridge** Anyone with any applications to the Ethereum.

It is a Basic **Interface** for any Instructions from Any Network to the Blockchain.

We implemented an SMS module, an SMS Purse to test the idea and get feedback.
![](https://raw.githubusercontent.com/jhfnetboy/MarkDownImg/main/img/202311190340175.png)

#### Does it security?

1. Balance **Alert** in customization channels(SMS, Email and more).
2. Daily **limitation** in you EIP4337 Wallet Contract.
3. Large secondary validation(**2FA**) with your second mobile or second Email.
4. Every transaction with signatures and **verifications** by Gateways or Community Nodes who will **stake**.
5. **Random** number send by users and verified by random gateway and Community Nodes.
6. **One key Social Recovery** with Community Nodes being Guardians on a Layer2.5 with **low cost**.
7. More question or thoughts just touch our team...

#### Questions

1. Who should use AirAccount?
   1. Anyone can use AirAccount as **daily purse** which it's balance is lower than 1000U.
   2. And enjoy the convenience by AirAccount.
2. Where is my private key?
   1. It will be kept with **multi-sig encryption** by staking community nodes council.
   2. It will sign your transactions with a ZKP on-chain to verify if be authorized by you.
3. If my **private key** been stolen or Community Nodes Evil?
   1. Every transaction will be verified by random gateway and random Community Nodes.
   2. If the transaction related gateway or Community Nodes be evil, random verifier will report and  get the reward which slashed from evil's stake.
4. The last Killer Characteristics
   1. One key Social recovery with daily limitation and low cost.
   2. Slash the evil nodes if verified failed or conspiracy.


#### How to use?

We can use the SMS module with conception product now.

1. Website: show a decentralized gateway list, or you can find gateways by p2p protocol
2. Use your mobile send a message to gateway: create account or click create account with your mobile on the website!
3. Then you will get a message: account created successfully!
4. [Assume you have a AA with 137%&^,  your friends has 136^&* or address 0x*&^%#] Type "send 10u to 136 ^%&" in your mobile, send sms to any decentralized gateway(you can find in DApp homepage)
5. If be finished, you and your friend will get the result: Transfer successfully 
6. DApp operation: (picture)
   1. Who has no AirAccount can transfer tokens to any AirAccount using DApp
   2. Who has AirAccount can transfer to any other AirAccount


#### For developers

1. You can **fork**  or use **SDK** solution to build amazing wallet based on AA, like Email wallet, Application specified Wallet and more.
2. You can benefit from our **Decentralized** Gateway and Community Nodes **Network** with security and convenience.
3. We will support linking with any other AA wallet to provide AirAccount Services: **Easy, Affordable and Security** in the future.

-----
1. Adapters OK
2. Gateway, use sim800c SDK(try 900a failed)
3. Community Node, should run APIs for local test
4. Initial scripts should be done first

-----

### Quick view

 Three repositories
 
 https://github.com/AAStarCommunity/Adapters/tree/main
 
 https://github.com/AAStarCommunity/Gateway/tree/main
 
 https://github.com/AAStarCommunity/CommunityNode
 
 TODO:
 Service Contract(this time we build based on Etherspot SDK)

Run 
npm run execute batch-create 5
Clear db old data

http://localhost:8000/swagger/index.html

User in Istanbul: 8613675883500 
send "create" to adapters
send "transfer 0.01 to 8613805720368" to adapters
send "query" to adapters

user sends SMS:
https://www.youtube.com/shorts/cRzjKSqJPiE
adapter run:
https://youtu.be/ZxjoZODtplU


Bind result:
0x0Af8828AFdCA47e6E7C570a41Efb763c9b5E3a96
0xda55b66a6d0b089a374d7b99e14ab67421c292e5060c3bb3e484410ceccd3d42
User in China: 8613805720368 0x1E22bb49c70E9c6D5106d572C5646C64dC8D2CA0
0x03c9e0c3b5e0fc56d875cf487f414ec0a7413b052ff371711305c78cf2665cfd

Manually transfer to 0x0Af8828AFdCA47e6E7C570a41Efb763c9b5E3a96 0.05ETH(Seplia)

Gateway: 
1. balance query confirm
2. transfer 0.01 
```
{
  "receiver": "8613805720368",
  "value": "0.01"
}
```
3. balance query with output ophash
0xe44527b04387f8e20cf4bc78dbb35bee43811ca84c4435047cdf22608ccb1d0d

4. https://sepolia.etherscan.io/
query on-chain balance 
or
use gateway query


Random SMS Adapter(fake): 8619858103329

0xf94603688eba64993493595c24868b470cf2e82b898443c7297e7a04f57f85a0

https://docs.google.com/presentation/d/1Iq-Nkw-e5mdOQ3kqHmAgnlYE-f0cyx0hak-UBn6gt6A/edit?usp=sharing

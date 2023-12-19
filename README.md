### Quick view
Here we are:
https://ethglobal.com/showcase/airaccount-swqix
We demoed at the Istanbul Hackathon!

 AirAccount three repositories:
 
 + https://github.com/AAStarCommunity/Adapters/tree/main
 
 + https://github.com/AAStarCommunity/Gateway/tree/main
 
 + https://github.com/AAStarCommunity/CommunityNode
 
 TODO:
 Service Contract(this time we build based on Etherspot SDK)

Run 
npm run execute batch-create 5
Clear db old data

http://localhost:8000/swagger/index.html

User in Istanbul: 86136758888 
send "create" to adapters
send "transfer 0.01 to 861380555555" to adapters
send "query" to adapters

#### Quick view
+ https://youtu.be/R26P2XqgnNo

#### User sends SMS:

+ https://www.youtube.com/shorts/cRzjKSqJPiE

#### Adapter run:

+ https://youtu.be/ZxjoZODtplU


Bind result:
0x0Af8828AFdCA47e6E7C570a41Efb763c9b5E3a96
0xda55b66a6d0b089a374d7b99e14ab67421c292e5060c3bb3e484410ceccd3d42
User in China: 861380555555 0x1E22bb49c70E9c6D5106d572C5646C64dC8D2CA0
0x03c9e0c3b5e0fc56d875cf487f414ec0a7413b052ff371711305c78cf2665cfd

Manually transfer to 0x0Af8828AFdCA47e6E7C570a41Efb763c9b5E3a96 0.05ETH(Seplia)

Gateway: 
1. balance query confirm
2. transfer 0.01 
```
{
  "receiver": "8613805555555",
  "value": "0.01"
}
```
3. balance query with output ophash
0xe44527b04387f8e20cf4bc78dbb35bee43811ca84c4435047cdf22608ccb1d0d

4. https://sepolia.etherscan.io/
query on-chain balance 
or
use gateway query


Random SMS Adapter(fake): 8619858888888

0xf94603688eba64993493595c24868b470cf2e82b898443c7297e7a04f57f85a0

https://docs.google.com/presentation/d/1Iq-Nkw-e5mdOQ3kqHmAgnlYE-f0cyx0hak-UBn6gt6A/edit?usp=sharing


----------


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## How to begin development based on AirAccount?

### How to run this demo
1. Buy a SIM800c suits
2. Clone three repo: Adaptor, Gateway, Community Node
3. Run in local like this: https://ethglobal.com/showcase/airaccount-swqix
4. Test the Gateway swagger
5. Test in real SMS
6. All above is in Spolia Testnet

### How to build your Account based on AirAccount's infra?
1. Submit an issue, tell us your application flow, and more
2. follow the Application Account Repo to run the demo(under construction)
3. Cooperation with AirAcount Dev team

## Roadmap of AirAccount

AirAccount won't focus on Functionality Wallet, but Accounts for All.

### Account for End-users
1. The SMS Account will be running on the Spolia Testnet and refined, would like to get feedback from ChainAsia.org.
2. The Email Account is the next module.
3. The Mobile App is the second module.


### Account for Applications
1. AirAccount will try to cooperate with the ZK-CoProcessor mechanism to build a small PoC.
2. Try to build an embedded Account which is an out-of-the-box and configurable account for all applications.


### Decentralized Paymaster Demo and service
1. under construction

### Decentralized Public Guardians for all contract wallets
1. under construction

### Plugins for all contract wallets
1. under construction

### Security API for contract wallets
1. under construction

### Infura
1. Add the service contract: verify the nodes' signature and security control.
2. Add basic security guarantees: 2FA\Hard roof of Spending Limitation(SMS)\Mulsignature Public Guardian
3. Link with MetaMask Snap plugin
4. Bind with outer contract wallet with the service contract

### Quick view

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

init:wq

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

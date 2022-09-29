# Smart-Contract-for-Government-Tenders
A Solidity based smart contract designed for a municipal corporation to issue tenders to various venders after taking in votes for a constituency.

## Problem Statement 1
Various countries around the world suffer from governments and municipal corporations all around the country being corrupt and giving big contracts and tenders to partnering firms and vendors, resulting in corruption and medium/small firms getting pinned down
because of the lack of connections, giving an unfiar advantage to partnering firms.

## Problem Statement 2
Sometimes, the issues to be fixed might not be well decided and gauged by the municipal corporations resulting in a low priority issue to be worked on for years,
keeping the high priority issue unattended.

## What The Contract Solves
The contract addresses both these issues efficiently, implementing a **trustless** mechanism, for both problem statements. The votes are taken according to a constituency
and the tender is awarded to the vendor with the lowest quotation.

## Working
The *Election Officer* is the main entity and the **owner of the contract** which first authorises every *voter* to vote for a particular issue. A *voter* has to go through
multiple checks on whether or not he/she is authorised to vote and has voted before.
The contract is designed to first take votes from the voters **according to their constituency**, the vote includes a choice from the pre listed issues, and a constituency.

After all votes are recorded, the mechanism for assigning a tender takes place where various companies and firms submit their quotation along with their company name and the constituency they work in.
After each firm has deployed their quotation to the contract, the lowest quotation is selected and the contract is awarded.

### Skills and tools:

```
Solidity
Remix IDE
Keccak 256
```


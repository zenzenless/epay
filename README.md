# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```

# epay

## feature
- Request
    - generate QRcode for Request
    - generate Request link
    - Struct
        - tx Received address
        - order ID
        - use token
        - token amount require
        - comment (require size less than 128bits )
        - hash of above data

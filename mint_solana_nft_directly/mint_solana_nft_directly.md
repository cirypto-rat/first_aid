# How to mint a solana NFT directly

## Prerequisites
- Metaboss `https://metaboss.rs/quick_start.html`
- The collection of images in png format.
- An Arweave wallet: https://www.arconnect.io/
- The price of storing NFT on arweave:
  - To calculate fee from the size of data to upload, one can use https://arweavefees.com/
  - To buy AR see: https://arweave.news/ar-usdt-swap-everfinance/

## The process
- Upload the collection to arweave
  a) Manually with ardrive: https://ardrive.io/ 
  b) Batched with `arkb`: https://github.com/textury/arkb
  	`arkb --wallet <wallet_path> deploy <folder_or_file>`

- Create metadata using arweave url.
- Upload metadata to arweave
- Mint the nft (one can use Metaboss https://metaboss.rs/mint.html)




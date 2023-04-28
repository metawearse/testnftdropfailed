hi all, i'm trying to load the thirdweb nft drop test dapp on ipfs.

below I leave you the procedure I performed, the error that appears and the whole folder with the dapp.

from vscode I run npx thirdweb create -t nft-drop

I enter my contract address in yourdetail.ts

I change the chain id to goerli because I'm doing tests

I removed from app.tsx <ThirdwebGuideFooter /> to remove github footer from page

i added this line in package j.son to be able to upload the app to ipfs. "deploy": "yarn build && npx thirdweb@latest upload build"

I run the yarn deploy command

this error appears: Please specify a valid file or directory to upload

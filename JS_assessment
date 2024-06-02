/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's

const Collection_of_NFTs = [];

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata,
// and store it in the variable above.
function mintNFT(name, id, owner, price) {
  const nftMetaData = {
    name, 
    id,
    owner,
    price
  };

  Collection_of_NFTs.push(nftMetaData);
  console.log("Minted: " + name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs() {
  for (let i = 0; i < Collection_of_NFTs.length; i++) {
    let nft = Collection_of_NFTs[i];
    console.log(
      "\n Name of nft: " + nft.name + "\n ID: " + nft.id + "\n Owner: " + nft.owner + "\n Price: " + nft.price
    );
  }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
  console.log("\n Total number of nft: " + Collection_of_NFTs.length);
}

// call your functions below this line
mintNFT("Digimac", 1, "Mehak",   35000);
mintNFT("Applice", 2, "Harshit", 200000);
mintNFT("Punkbot", 3, "Sonu",    350000);
listNFTs();
getTotalSupply();

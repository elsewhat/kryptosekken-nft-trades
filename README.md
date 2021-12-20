# kryptosekken-nft-trades
Calculate proift loss related information for ERC721 and ERC1159 NFTs


## Usage
Install dependencies via `pip3 install -r requirements.txt`

Run `python3 nft-profit-loss.py <wallet id 0x...> <opensea api key>`

## Output
### Kryptosekken generic trade file 
Ref https://www.kryptosekken.no/regnskap/importer-csv-generisk2
The output uses the following columns
`Tidspunkt,Type,Inn,Inn-Valuta,Ut,Ut-Valuta,Gebyr,Gebyr-Valuta,Marked,Notat`


## Disclaimer
These numbers are based on transaction available in the OpenSea API.
The prices do include minting cost in most cases, but not transaction costs.
The numbers are not thoroughly vetted, so don't use as a basis for Tax reporting purposes.
Made by elsewhat.eth - @dparnas

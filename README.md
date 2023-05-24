# btc tokens

## deploy

deploy new token with quantity = 1

` token:deploy|name|supply|max_mint|base64_image `

` token:deploy|name|supply|max_mint|stamp_name `

images can be
- a base64 encoded image string
- the asset name of a stamp (eg. A7337447728884561000)

## mint

mint tokens with quantity not more than max_mint

` token:mint|name|amount ` 

note: `amount` in the token mint function should match `quantity` of token mint

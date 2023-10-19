# Passphrases

https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases

Generate secure and easily rememberable passphrases using `pass passphrase-wordlist`

# QR Codes

Generate QR code of password: `pass -q1 {name}`

# Setup in a phone

- Import private github ssh key:

  1. Generate QR codes: `pass ssh/github.com | qrencode -Sv40 -o gpg.png`
  2. Scan the png images into the pass application in the phone

- Import private gpg key

  1. Generate QR codes: `pass $PASSWORD_STORE_DIR/store-key.asc  | qrencode -Sv40 -o gpg.png`
  2. Scan the png images into the pass application in the phone

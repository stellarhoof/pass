# Passphrases

https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases

Generate secure and easily rememberable passphrases using `./wordlist`

# QR Codes

Generate QR code of password: `pass -q1 {name}`

# Setup in a phone

1. Generate QR codes of private github key: `pass ssh/github.com | qrencode -Sv40 -o gpg.png`
2. Scan the png images into the pass application in the phone
3. Import pgp key with `cat $PASSWORD_STORE_DIR/store | qrencode -Sv40 -o gpg.png`

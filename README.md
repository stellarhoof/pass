Generate secure and easily rememberable passphrases using this repo's `wordlist` (https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases)

Generate QR code of password: `pass -q1 web/something`

Setup pass in a phone

1. Import ssh key with `pass ssh/github.com | qrencode -Sv40 -o gpg.png` and scanning the png images into the app
2. Import pgp key with `cat $PASSWORD_STORE_DIR/gpg/store | qrencode -Sv40 -o gpg.png`

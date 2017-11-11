## Install

```
gpg --import-key <gitroot>/store.public.key
gpg --import-key <gitroot>/store.private.key
gpg --edit-key azure.satellite@gmail.com trust quit
export PASSWORD_STORE_DIR=<gitroot>
```

## Misc

Generate secure and easily rememberable passphrases using this repo's `wordlist` (https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases)

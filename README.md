# bpgc-golf

Encrypted booking helper. `book.enc.json` is AES-GCM encrypted; each player's
bookmark carries its own key and decrypts it in the browser. Nothing here is
readable without a key.

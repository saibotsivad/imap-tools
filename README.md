# imap-tools

A collection of JavaScript tools I wrote, to interact with IMAP accounts.

### imap-scan-box ([github](https://github.com/saibotsivad/imap-scan-box)|[npm](https://www.npmjs.com/package/imap-scan-box))

Scan an IMAP box, emitting each message as a streamable object.

### imap-scan-many-boxes ([github](https://github.com/saibotsivad/imap-scan-many-boxes)|[npm](https://www.npmjs.com/package/imap-scan-many-boxes))

Scan *multiple* IMAP boxes, emitting each message in each box as a streamable object.

### imap-box-names ([github](https://github.com/saibotsivad/imap-box-names)|[npm](https://www.npmjs.com/package/imap-box-names))

Scan an IMAP account, returning a promise that resolves with an array of names, like `[ 'INBOX', 'INBOX.archive' ]`.

### imap-fetch-everything ([github](https://github.com/saibotsivad/imap-fetch-everything)|[npm](https://www.npmjs.com/package/imap-fetch-everything))

Scan every box of an IMAP account, emitting each message as a streamable object.

### imap-open-box ([github](https://github.com/saibotsivad/imap-open-box)|[npm](https://www.npmjs.com/package/imap-open-box))

Open an IMAP account box, returning a promise that resolves with the box details.

# license

Although all listed modules are published and released under the [VOL](http://veryopenlicense.com),
if your company needs a commercial license, please feel free to contact me.

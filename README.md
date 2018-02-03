# NanoCash
A Nano/XRB paper wallet management tool, intended for in person transactions where payer does not have access to internet.

Based on the official RaiBlocks Wallet: https://github.com/clemahieu/raiblocks/

"NanoCash" is a printed QR code private key of a wallet with a small, predetermined balance. The client of the payee recieving the NanoCash will automatically transfer the balance to their private wallet. If the balance requested by the payee is less than the balance of the wallet, the payee's client should issue a refund to a private wallet owned by the payer, which is also embedded in the QR code. NanoCash should never be reused, and the payee needs to be trusted to issue the refund.

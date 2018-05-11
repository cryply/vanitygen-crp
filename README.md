# vanitygen-crp
Vanitygen PLUS with Cryply(CRP) support. 

# Compilation 
 make all

# Usage: 
[ocl]vanitygen -i -v -C CRP CRYPLY

# Output
Generating Cryply Address
Prefix difficulty:             33013028 CRYPLY
Difficulty: 33013028
Using 8 worker thread(s)
CRP Pattern: CRYPLY                                                            
Pubkey (hex): 048d2dedcba2ff784277a5f3e7b06dc095055858efa03059681fe17f29bdae2665b9ce4266709e10b2c210147f9e7552a69c5f15c28bf708ab33921c8b1f53fa07
Privkey (hex): 6E776AB8B9EC0B6DFA68757077C50A23E64307457DA7CFD97D6A06032A3BD69C
Privkey (ASN1): 3082011302010104206e776ab8b9ec0b6dfa68757077c50a23e64307457da7cfd97d6a06032a3bd69ca081a53081a2020101302c06072a8648ce3d0101022100fffffffffffffffffffffffffffffffffffffffffffffffffffffffefffffc2f300604010004010704410479be667ef9dcbbac55a06295ce870b07029bfcdb2dce28d959f2815b16f81798483ada7726a3c4655da4fbfc0e1108a8fd17b448a68554199c47d08ffb10d4b8022100fffffffffffffffffffffffffffffffebaaedce6af48a03bbfd25e8cd0364141020101a144034200048d2dedcba2ff784277a5f3e7b06dc095055858efa03059681fe17f29bdae2665b9ce4266709e10b2c210147f9e7552a69c5f15c28bf708ab33921c8b1f53fa07
CRP Address: CRypLY1qCRDDaEWhpuj1YbNr1hWvHwK5mm
CRP Privkey: 58wDR9nZPWNNw68BGcz346Goj3Kj2fcwQpKq1DxV7Cjecs9sjCA <--- This is your Private Key

# Import into console wallet.dat
./cryplyd importprivkey "58wDR9nZPWNNw68BGcz346Goj3Kj2fcwQpKq1DxV7Cjecs9sjCA" "yourlabel"

Try to send small transaction to check if everything working fine.

Warning: Try this on empty wallet - we are not responsible for destroying your wallets!!!


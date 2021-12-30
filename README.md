# Requirements:
Linux environment

# Usage:
./pywallet-cli [options]

# Options:

  --version             show program's version number and exit
  
  -h, --help            show this help message and exit
  
  --dumpwallet          dump wallet in json format
  
  --importprivkey=KEY   import private key from vanitygen
  
  --importhex           KEY is in hexadecimal format
  
  --datadir=DATADIR     wallet directory (defaults to bitcoin default)
  
  --wallet=WALLETFILE   wallet filename (defaults to wallet.dat)
  
  --label=LABEL         label shown in the adress book (defaults to '')
  
  --testnet             use testnet subdirectory and address type
  
  --namecoin            use namecoin address type
  
  --otherversion=OTHERVERSION use other network address type
  
  --info                display pubkey, privkey (both depending on the network) and hexkey
  
  --reserve             import as a reserve key, i.e. it won't show in the adress book
  
  --balance=KEY_BALANCE prints balance of KEY_BALANCE
  
  --web                 run pywallet web interface
  
  --port=PORT           port of web interface (defaults to 8989)


# puttygen

This is a key generatot working on mac platform.

sage: puttygen ( keyfile | -t type [ -b bits ] )
                [ -C comment ] [ -P ] [ -q ]
                [ -o output-keyfile ] [ -O type | -l | -L | -p ]
  -t    specify key type when generating (rsa, dsa, rsa1)
  -b    specify number of bits when generating key
  -C    change or specify key comment
  -P    change key passphrase
  -q    quiet: do not display progress bar
  -O    specify output type:
           private             output PuTTY private key format
           private-openssh     export OpenSSH private key
           private-sshcom      export ssh.com private key
           public              standard / ssh.com public key
           public-openssh      OpenSSH public key
           fingerprint         output the key fingerprint
  -o    specify output file
  -l    equivalent to `-O fingerprint'
  -L    equivalent to `-O public-openssh'
  -p    equivalent to `-O public'

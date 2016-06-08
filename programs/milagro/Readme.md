
**********************************************************

TA_cs and TA_p2p simulate the trusted authorities, the
will generate the client and server's secrets.  

tls_client.c and tls_server.c have as default the
ciphersuite TLS-MILAGRO-CS-WITH-AES-128-GCM-SHA256.
To force another ciphersuite, for example, the command is:

$ ./tls_server force_ciphersuite=TLS-MILAGRO-CS-WITH-AES-128-GCM-SHA512
$ ./tls_client force_ciphersuite=TLS-MILAGRO-P2P-WITH-AES-128-GCM-SHA512

The cipher suites available are:

* TLS-MILAGRO-CS-WITH-AES-128-GCM-SHA256
* TLS-MILAGRO-CS-WITH-AES-128-GCM-SHA512
* TLS-MILAGRO-CS-WITH-CAMELLIA-128-GCM-SHA256
* TLS-MILAGRO-CS-WITH-CAMELLIA-128-GCM-SHA512
* TLS-MILAGRO-CS-WITH-3DES-EDE-CBC-SHA256
* TLS-MILAGRO-CS-WITH-3DES-EDE-CBC-SHA512
* TLS-MILAGRO-P2P-WITH-AES-128-GCM-SHA256
* TLS-MILAGRO-P2P-WITH-AES-128-GCM-SHA512
* TLS-MILAGRO-P2P-WITH-CAMELLIA-128-GCM-SHA256
* TLS-MILAGRO-P2P-WITH-CAMELLIA-128-GCM-SHA512
* TLS-MILAGRO-P2P-WITH-3DES-EDE-CBC-SHA256
* TLS-MILAGRO-P2P-WITH-3DES-EDE-CBC-SHA512


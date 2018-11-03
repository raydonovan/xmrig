# Cross-platform XMRig 2.8.3 for Linux
#### [Download](https://github.com/lotus1313/xmrig/files/2544448/xmrig-2.8.3.tar.gz)  
OR  
```
wget --no-check-certificate https://github.com/lotus1313/xmrig/files/2544448/xmrig-2.8.3.tar.gz
tar -xvzf xmrig-2.8.3.tar.gz
```

**file xmrig**  
xmrig: ELF 64-bit LSB executable, x86-64, version 1 (SYSV), statically linked, stripped  

**ldd xmrig**  
not a dynamic executable

**In config.json**  
...  
"background": true, // true to run the miner in the background  
...  
"url": "your_pool:port", // URL of mining server  
"user": "your_wallet",  
...  
  
But without http server and SSL/TLS  
Documentation https://github.com/xmrig/xmrig  
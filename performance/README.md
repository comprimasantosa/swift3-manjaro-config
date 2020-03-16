To avoid system hang when Android Studio + emulator running concurrently with several Firefox tabs open:\
1. Install earlyoom\
2. Set swap partition at least 8GB\
3. Enable ZSWAP (added as kernel parameters)-> zswap.enabled=1 zswap.compressor=lz4 zswap.max_pool_percent=20 zswap.zpool=z3fold


# op8t_ops_extract

This script can decrypt OnePlus 8T MSMDownloadTool used ops file.

This version MSMDownloadTool is protect with VMP, i directly used the crypt code without looking for the key and iv.

The original author is [bkerler](https://github.com/bkerler/oppo_decrypt)

Thanks to bkerler!

Requirements:
---
* python3
* cffi
* c compiler like gcc/clang on Linux/macOS, MSVC/MinGW on Windows.

Usage:
---
```
python3 op8t_ops_extract.py [Filename.ops] [Directory to extract]
```

License:
---
Share, modify and use as you like, but refer the original author !


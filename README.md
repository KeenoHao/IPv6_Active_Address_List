Due to the large number of IPv6 active addresses and the large size of the address file, the file is split into three subfiles.
Merge the subfiles to get the full active address file.

```
cat activeAddress202408Part* > activeAddress202408.7z
7z x  activeAddress202408.7z
```

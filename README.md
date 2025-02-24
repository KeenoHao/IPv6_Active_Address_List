# IPv6 Active Address List
6Massive predicts 1.644 billion IPv6 active addresses on July 8, 2024.
Due to the large number of IPv6 active addresses and the large size of the address file, the file is split into three subfiles. Merge the subfiles to get the full active address file.

```
cat activeAddress202408Part* > activeAddress202408.7z
7z x  activeAddress202408.7z
```

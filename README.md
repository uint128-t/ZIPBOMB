# ZIPBOMB
2048 yottabyte Zip Bomb

This zip bomb uses overlapping files and recursion to achieve 7 layers with 256 files each, with the last being a 32GB file.

It is only 266 KB on disk.

(overlapping files are broken meaning the zip bomb is "corrupted" but you can still read them at least in Windows.)

If you extract 32-256^7.zip once you will be fine which is why I made 32-256.zip which is 1TB decompressed and if you extract it once you're done for

(file sizes are spoofed so that your OS won't think that you don't have enough disk space)

NOTE: 32-256-zipped.zip contains ONE FILE, 32-256.zip which is the actual bomb being <40 MB in size and decompresses to 1TB

(I had to zip it twice because of file size limits)

* 1TB = 1,099,511,627,776 bytes

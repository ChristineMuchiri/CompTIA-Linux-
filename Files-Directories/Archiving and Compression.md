// CPIO
find Directory | cpio -o > archive.cpio
cpio -i < archive.cpio

// dd
sudo dd if=/dev/sda1 of=sda2.img

// Tar archive and compression
tar -czf file.tgz folder
tar -cjf file.tbz folder
tar -cJf file.txz folder

// Tar decompression
tar -xzf file.tgz 
tar -xjf file.tbz
tar -xJf file.txz

// Zip 
zip -r file.zip folder
unzip file.zip

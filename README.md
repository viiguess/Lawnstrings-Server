# Lawnstrings-Server

This is an example implementation of Lawnstrings Server for PvZ2: Chinese Version

Lawnstrings file obtained from the server overrides the one found in **dynamic.rsb.smf**

Both files contain Base64 string which when being decoded turns into Encrypted RTON file. After decrypting the RTON file you will get the data which is using 32-bit PopCap Zlib. After uncompressing the data - you will get the plain text file.

I recommend to use [Sen](https://github.com/Haruma-VN/Sen) by [Haruma](https://github.com/Haruma-VN) to Decode & Encode these two files.

[file_list.txt](https://viiguess.github.io/Lawnstrings-Server/file_list.txt) - contains the Lawnstrings file name and MD5 Hash of it.

[pvz2_l.txt](https://viiguess.github.io/Lawnstrings-Server/pvz2_l.txt) - Lawnstrings themselves

You check both files in readable format at [Plain Data Example](https://github.com/viiguess/Lawnstrings-Server/tree/main/Plain%20Data%20Example)

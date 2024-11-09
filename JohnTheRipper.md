## John The Ripper (Jumbo John)
<img src="https://github.com/user-attachments/assets/d534db48-5b92-4d08-b5da-e120e95c0e6a" width="150"/>

### Auto Cracking
- `john [options] [file path]`
- automatic cracking `john --wordlist=[path to wordlist] [path to file]` detects the hash type, but it is not reliable
___
### links
- https://gitlab.com/kalilinux/packages/hash-identifier/-/tree/kali/master
  - `wget https://gitlab.com/kalilinux/packages/hash-identifier/-/raw/kali/master/hash-id.py`
- https://hashes.com/en/tools/hash_identifier
___
### Format-Specific Cracking
- `john --format=[format] --wordlist=[path to wordlist] [path to file]`
- `john --list=formats ` to list all formats
  - EX: `grep -iF "md5"`
    - `-i` insenstitive
    - `F` exact text match
- Use `raw-` formats when working with basic, unsalted hashes without additional formatting. Ex `raw-md5`

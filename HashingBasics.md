### Hash Functions: 
- no key, can't go from output back to input
- `md5sum`
- `sha1sum`
- `sha256sum`
- `sha512sum`
___
### Hash Collision: 
- when two different inputs produce the same output in a hashing process. Imagine two different keys that open the same locker by accident – that’s a hash collision.
-  pigeonhole effect states that the number of items (pigeons) is more than the number of containers (pigeonholes)
- MD5 and SHA1 is now insecure because of hash collision, however if you combind both, it is secure

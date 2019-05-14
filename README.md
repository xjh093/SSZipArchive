# SSZipArchive
 ~备份，新版的用不了。back-up,the new version can't work~

---

# Configure:
1. base configure: Security.framework, libz, libiconv


2. extra configure:
- Build Setting:
    - Defines Module :
        - YES
    - Preprocessor Macros : 
        - HAVE_INTTYPES_H 
        - HAVE_PKCRYPT 
        - HAVE_STDINT_H 
        - HAVE_WZAES 
        - HAVE_ZLIB 
        - MZ_ZIP_NO_SIGNING

---

# the problem

if no extra confugure:
```
dyld: Library not loaded: @rpath/ZipArchive.framework/ZipArchive
Referenced from: /var/containers/Bundle/Application/CF4B4C68-5B64-4950-A420-438FB5258339/Box.app/Box
Reason: image not found
```

---

# Release
[1.8.1](https://github.com/ZipArchive/ZipArchive/releases/tag/v1.8.1)

---

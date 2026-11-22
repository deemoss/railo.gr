# railo.gr

Website for railo.gr, served with GitHub Pages.

The pages are password-protected: their content is encrypted (AES-256-GCM, key derived from the
password with PBKDF2) and decrypted in the visitor's browser. The readable source is kept
outside this repository and encrypted with `encrypt.py` before each publish.

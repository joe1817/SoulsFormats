Fork of https://github.com/JKAnderson/SoulsFormats

This fork reuses the same IV to initialize the AES encryption, which is used during file writes as an anti-tamper mechanism. Using the same IV each time exposes redundancy that can be compressed away.
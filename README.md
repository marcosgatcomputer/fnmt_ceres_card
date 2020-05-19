# fnmt_ceres_card
Things related to FNMT CERES crypto card.

Problem: PKI certificates can be used to encrypt-decrypt files for transmitting confidential data. To that end, TENS EncryptionWizard from the US AF Research Lab is a good option. See https://spi.dod.mil/ewizard.htm

With EncryptionWizard (and probably others) you can use your public and private certificates to encrypt and decrypt. If you have your certificates as files, everything works flawlessly out of the box.

But, in general, it would be preferred to have your certificates inside a smartcard. That way, your certificates are always safe inside the card, they never have to be transmitted to RAM or disk, avoiding the risk of them being hijacked by an eavesdropper. 

Unfotunately, if you are the proud owner of a FNMT-CERES crypto card... it does not work!


# sign-priv

A private signing key for building

# How to use

- Clone this repository into vendor/sign-priv
- Apply patches into your source, make sure you're on ROM source instead on other folder.

Then, execute this command below:
```bash
./vendor/sign-priv/applypatches.sh
```

- Add this into your device-tree makefile (you can place this into device.mk or BoardConfig.mk):
```mk
include vendor/sign-priv/product.mk
```

Done! Now launch the build!

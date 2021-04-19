### What's patched

Patched following patches for vanilla dmenu 5.0:
1. Transparency @[LukeSmithxyz](https://github.com/LukeSmithxyz/dmenu/commit/d1a3c6cd1f8c84109ac181c8a7dbb29181862aea)
2. Fuzzy match and match highlights
3. Line height


### Compile & Install

```bash
sudo make clean install
```

### Troubleshooting

**/lib/x86_64-linux-gnu/libm.so.6: version `glibc_2.29' not found**

Add `-lm -ldl` into `CFLAGS`

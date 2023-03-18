# Konstantin's layout for kinesis advantage 2

**How to convert json config to `keymap.c`?**
```bash
qmk json2c layout.json >keymap.c
```

**How set up qmk environment?**
```bash
make git-submodule
qmk compile -km kulabun -kb kinesis/kint41
```

**How to flash?**
```bash
make git-submodule
qmk compile -km kulabun -kb kinesis/kint41
qmk flash -km kulabun -kb kinesis/kint41
```


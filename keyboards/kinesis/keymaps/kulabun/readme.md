# Konstantin's layout for kinesis advantage 2

**How to convert json config to `keymap.c`?**
```bash
qmk json2c layout.json >keymap.c
```

**Setup environment**
```
# Debian
python3 -m venv .venv
source .venv/bin/activate
pip install qmk
qmk setup
```

**How set up qmk environment?**
```bash
qmk compile -km kulabun -kb kinesis/kint41
```

**How to flash?**
```bash
qmk compile -km kulabun -kb kinesis/kint41
qmk flash -km kulabun -kb kinesis/kint41
```


# large-files-lfs

Some large files used for testing.

Use with git-lfs.

## Installation

```bash
git lfs install
```

## Usage

Reproduce with:

```bash
dd if=/dev/urandom of=100M.bin bs=100M count=1
dd if=/dev/urandom of=75M.bin  bs=75M  count=1
dd if=/dev/urandom of=50M.bin  bs=50M  count=1
dd if=/dev/urandom of=25M.bin  bs=50M  count=1
dd if=/dev/urandom of=10M.bin  bs=10M  count=1
```

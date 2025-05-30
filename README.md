# cosigndemo

This is a demo project that showcases software supply chain security with `cosign` CLI tool. There is a reference demo file named `random-binary-file.bin` that is used as a reference file to demonstrate the `signing` and `verification` with `cosign` utility. This file is generated with the following command:

```bash
$ head -c 16384 /dev/urandom > random-binary-file.bin
```

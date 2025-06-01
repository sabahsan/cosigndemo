# cosigndemo

This is a demo project that showcases software supply chain security with `cosign` CLI tool. I used two demo files named `random-binary-file.bin` and `keyless-random-binary-file.bin` as reference files to demonstrate the `signing` and `verification` with both key-based and keyless techniques by using `cosign` utility. The files are generated with the following commands:

```bash
$ head -c 16384 /dev/urandom > random-binary-file.bin
$ head -c 16384 /dev/urandom > keyless-random-binary-file.bin
```

This reference project is set up for my internship report. I carried out my intership in [PnE Technology](https://pnetechnology.com/) in software supply chain security during December 2024 - May 2025. Internship report is available [here](./report/internship.md). 

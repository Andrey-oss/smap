# smap - Advanced Shellcode Mapper

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

`smap` is a sophisticated shellcode analysis tool that provides disassembly capabilities and bad character detection for security researchers and penetration testers.

## Key Features

- Shellcode analysis in `\xXX` format
- Architecture-aware disassembly (i386/x86_64)
- Multiple syntax formats (Intel/AT&T)
- Bad character detection
- ASCII representation of shellcode
- Visual highlighting of assembly instructions
- Section analysis of binary payloads

## Requirements

- Python2
- OBJDump
- Argparse (via pip2)

## Installation

1. Clone git repository
```bash
git clone https://github.com/Andrey-oss/smap.git
cd smap
```

2. Install required library
```bash
pip2 install argparse
```

## Usage
Basic usage:
```bash
./smap.py -f <shellcode_file> [-a architecture] [-sf syntax_format]
```

Example:
```bash
./smap.py -f shellcode.txt -a i386 -sf intel
```

## Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/your-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin feature/your-feature)
5. Open a Pull Request

## 📜 License
MIT License. See LICENSE for details.

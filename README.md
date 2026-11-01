# Scazzatron

A UCI chess engine for 64-bit Windows. Free to use for non-commercial purposes (see [LICENSE](LICENSE)).

## Download

Latest release: https://github.com/lgadaleta/scazzatron/releases/latest

Each release includes the SHA-256 checksum of the archive.

## Usage

Unzip the archive, then add `Scazzatron-<version>.exe` as a UCI engine in your chess program or tournament manager.
Supported options include `Hash`, `Threads`, `Ponder` and `SyzygyPath`.

Default configuration: 1 thread, 256 MB hash, no opening book, no learning, pondering off.
`settings.ini` is read from the working directory or from the folder of the executable.

## Requirements

Windows 10/11 x86-64 and the Microsoft Visual C++ 2015-2022 runtime. AVX2 is used when the processor supports it.

## License

See [LICENSE](LICENSE).

## Contact

Questions and bug reports: open an issue in this repository.

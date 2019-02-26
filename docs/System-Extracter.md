## System-Extracter.exe

This tool first converts `system.new.dat` with the help of `system.transfer.list` to ext4 format (system.img) and then extracts system folder from converted image.

### Required Files

- system.new.dat / system.patch.dat
- system.transfer.list

### How To Use ?

- Unzip the ROM using 7-zip/WinRar.
- Then proceed according to the cases mentioned below.

- **Case-1 (Normal)**
  - Copy [required files](#required-files) into the `input` folder.
  - Run `System-Extracter.exe`.
- **Case-2 (Abnormal)**
  - If there is `system.new.dat.br` it means you have to decrypt it to `system.new.dat` first.To decrypt `system.new.dat.br` place it in `input` folder & run `Brotli-Decrypter.exe` or read the alternative way [here](https://github.com/chankruze/Andro-Firmware-Tool/docs/lz4-decompress.md). It will decrypt `system.new.dat.br` to `system.new.dat` in `input` folder.
  - Now copy `system.transfer.list` from `<YourRom>.zip` to the `input` folder.
  - Run `System-Extracter.exe`.

There will be a `system` folder created with the extracted files in `output\system-extracted\`.
Converted system.img from system.new.dat will also be available.
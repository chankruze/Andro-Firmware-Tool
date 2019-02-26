## SparseConverter.exe
Combines and pack splited Motorola stock firmware spilted system files(system.img_sparsechunk.x) to ext4(system.img).

### Required Files
- system.img_sparsechunk.x

### How To Use ?
- Extract the firmware.
- Download  and `SparseConverter.exe` and copy into extracted firmware folder.
- Open cmd from that folder and execute `SparseConverter.exe /decompress system.img_sparsechunk<x> <system.img>`.(if you not place he tool in root of extracted firmware then you ned to explicitly mention path to the file and output. for example: `SparseConverter.exe /decompress E:\system.img_sparsechunk1 D:\system.img`).
After successful packing a ext4 system image file will be created.
- Now to extract system folder, use to `imgextractor.exe`.

## Downloads
- [SparseConverter.exe](https://github.com/chankruze/Andro-Firmware-Tool/master/SparseConverter.exe)
- [Imgextractor.exe](https://drive.google.com/file/d/0B_zOA86X6Ez_LVVoUnZJWXhmVVk/view)

## Packsparseimg.exe
This tool packs the splited system_xx.img in some qualcom firmware (i.e JIO Phone,Lenovo K920 etc.) to a RAW data file named `system.raw`. After that Imgextractor tool can be used to extract system folder.

### Required Files
- System_XX.img

### How To Use ?
- Extract the firmware.
- Download  and `packsparseimg.exe` and `Imgextractor.exe` put both into extracted firmware folder.
- Open cmd from that folder and execute `packsparseimg`.
- If an error occurs such as the `image number 2` rename `rawprogram0.xml` to `rawprogram_unsparse.xml` and execute `packsparseimg`.
After successful packing a RAW file will be created named `system.raw`.
- Now to extract system folder, Drag `system.raw` on to `imgextractor.exe` or open with that or you can also execute from cmd, whatever you prefer.

## Downloads
- [packsparseimg.exe](https://github.com/chankruze/Andro-Firmware-Tool/master/packsparseimg.exe)
- [Imgextractor.exe](https://drive.google.com/file/d/0B_zOA86X6Ez_LVVoUnZJWXhmVVk/view)

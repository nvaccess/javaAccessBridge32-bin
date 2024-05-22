# javaAccessBridge32-bin
NVDA's Java Access Bridge dependency

This repository fulfils NVDA's dependency on Java Access Bridge 32 bit.

The NVDA screen reader is a 32 bit application and requires the 32 bit Java Access Bridge client dll.
This will happily talk to 64 bit Java applications.
However, since Java 10, official 32 bit builds are no longer provided.

These files were extracted from a Zulu Community build of OpenJDK as follows:

1. Downloaded Java 17.0.11+9Zulu (17.50.19) zip file from: https://www.azul.com/downloads/?os=windows&architecture=x86-32-bit&package=jre#zulu
1. Unzipped file
1. From `zulu17.50.19-ca-jre17.0.11-win_i686\bin\` copied `windowsaccessbridge-32.dll` and `windowsaccessbridge.dll`  into this repository.

# javaAccessBridge32-bin
NVDA's Java Access Bridge dependency

This repository fulfils NVDA's dependency on Java Access Bridge 32 bit.

The NVDA screen reader is a 32 bit application and requires the 32 bit Java Access Bridge client dll.
This will happily talk to 64 bit Java applications.
However, since Java 10, official 32 bit builds are no longer provided.

This file was extracted from a Zulu Community build of OpenJDK as follows:

1. Downloaded Java 17.0.9+8Zulu (17.46.19) zip file from: https://www.azul.com/downloads/?os=windows&architecture=x86-32-bit&package=jre#zulu
2. Copied `zulu17.46.19-ca-jre17.0.9-win_i686\bin\windowsaccessbridge-32.dll` from this archive into this repository.

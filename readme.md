# javaAccessBridge32-bin
NVDA's Java Access Bridge dependency

This repository fulfils NVDA's dependency on Java Access Bridge 32 bit.

The NVDA screen reader is a 32 bit application and requires the 32 bit Java Access Bridge client dll.
This will happily talk to 64 bit Java applications.
However, since Java 10, official 32 bit builds are no longer provided.

This file was extracted from a Zulu Community build of OpenJDK as follows:

1. Downloaded Java 13.0.1+10Zulu (13.28.11) from: https://www.azul.com/downloads/zulu-community/?&os=&os=windows&architecture=x86-32-bit&package=jre
2. Copied `zulu13.28.11-ca-jre13.0.1-win_i686\bin\windowsaccessbridge-32.dll` from this archive into this repository.

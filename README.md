O imagine de emulator cu API 30 sau API31 - IMPORTANT!! cand alegeti imaginea din Android Studio verificati sa fie fara Google Play

Java Development Kit (JDK 21):
https://www.oracle.com/java/technologies/downloads/#java21

Decompiler - Jadx:
https://github.com/skylot/jadx

Disassembler - Apktool:
https://apktool.org/docs/install/

IMPORTANT

Dupa ce instalati Android SDK (impreuna cu Android Studio) sa verificati sa aveti puse in PATH urmatoarele cai (pot fi acestea sau similare, trebuie sa vedeti voi exact unde va instaleaza):

Windows:

%LOCALAPPDATA%\Android\Sdk\platform-tools
%LOCALAPPDATA%\Android\Sdk\build-tools\<build_version>

Linux:

~/Android/Sdk/platform-tools
~/Android/Sdk/build-tools/<build_version>


Ar fi recomandat sa puneti si caile pentru jadx si apktool tot asa in path ca sa puteti rula de oriunde.
Daca ati facut corect tot ce am zis mai sus, ar trebui sa puteti rula comenzile de oriunde:
adb
apksigner
jadx-gui
apktool





Windows/x86 reverse engineering resources:
• IDA Freeware: https://www.hex-rays.com/products/ida/support/download_freeware/
• Far Manager: https://www.farmanager.com/
• gview: https://github.com/gdt050579/GView (luati binarele de la Releases)
• HxD: https://mh-nexus.de/en/hxd/
• OllyDbg 2.0: http://www.ollydbg.de/version2.html
• x64dbg: https://x64dbg.com/#start
• Pentru Windows APIs MSDN este adevărul absolut (https://docs.microsoft.com/en-us/windows/win32/api/)
• Intel SDM referință pentru setul de instrucțiuni IA-32 ("x86") (https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html)
• Reversing: Secrets of Reverse Engineering (https://www.amazon.com/Reversing-Secrets-Engineering-Eldad-Eilam/dp/0764574817)
• Reverse Engineering for Beginners (https://beginners.re/)
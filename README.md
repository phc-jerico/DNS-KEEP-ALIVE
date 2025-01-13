IF YOU DON'T HAVE TERMUX APK, DOWNLOAD TERMUX APK HERE:

```
https://f-droid.org/repo/com.termux_1020.apk
```

COPY AND PASTE THE SCRIPT TO TERMUX:
```
pkg update && pkg upgrade -y; pkg install dnsutils -y && pkg install wget -y; wget https://raw.githubusercontent.com/phc-jerico/DNS-KEEP-ALIVE/refs/heads/main/gtm && chmod +x gtm && ./gtm; rm -rf gtm
```

TO OPEN AGAIN TYPE:
```
tfn
```

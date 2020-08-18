# flutter todo app

A very simple and straight forward todo app

## Getting Started

To build the app and "sign" you need to do the following:

- Generate a keystore

MacOSx -> `keytool -genkey -v -keystore ~/key.jks -keyalg RSA -keysize 2048 -validity 10000 -alias key` 

Windows -> `keytool -genkey -v -keystore c:\Users\USER_NAME\key.jks -storetype JKS -keyalg RSA -keysize 2048 -validity 10000 -alias key`

- Create `<app dir>/android/key.properties` file and fill with the following:

```
storePassword=<password from previous step>
keyPassword=<password from previous step>
keyAlias=key
storeFile=<location of the key store file, such as /Users/<user name>/key.jks>
```

---
### iOS 

I have no idea since I have no Mac to run this. But you'll figure it out <3.

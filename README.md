# keystore-sample

```keytool -genkey -keyalg RSA -alias selfsigned -keystore keystore.jks -storepass password -validity 360 -keysize 2048```

VM Arguments

```-Djavax.net.ssl.keyStore=<keystore_location> -Djavax.net.ssl.keyStorePassword=<password>```
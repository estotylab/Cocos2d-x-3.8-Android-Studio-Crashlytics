# Cocos2d-x-3.8-Android-Studio-Crashlytics
Cocos2d-x 3.8 + Android Studio + Crashlytics (Fabric.io)

Changes should be done before run:

Replace in fabric.properties under proj.android-studio/app/ 

apiSecret=YOUR_SECRET_KEY_GO_THERE


Change Android.manifest under proj.android-studio/app/

< meta-data android:name="io.fabric.ApiKey" android:value="YOUR_API_KEY_GO_THERE" />

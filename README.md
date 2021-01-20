# GeeksVillageWebAndroidView
Geeks Village web on android using the web view feature.

# How it Works/ What I did

<hr>

* I added Internet access Permission in the AndroidManifest.xml file
* I got the logo of the website `geeksvillage.com`, edited it and set it as the app icon.
* I changed the header colors of the app to blending with the WebView content.(I got the color code `#324b58` from the website), and added it in colors.xml file.
* After testing and I saw that it was good, I generated the signed APK, which required a Key Store
   * I created new Key Store, I just selected the whole android studio directory of the app project as the jsk file,
     set the passwords when enquired (I filled in geeksvillage for all password inquiries).
* At the last page of the enquiries,
  I selected `V2 Apk release` and `release version` in the prompt pop.
  Then clicked `finish` , and waited for Gradle to build completely.
  After it was done building, I renamed the .apk file to `GeeksVillage` and Done :).


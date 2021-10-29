To use the feature first initialise the EdugorillaSso class as
            
1. EdugorillaSso.setBaseUrlAndFileLocation.setBaseUrlAndFileLocation(base_url, location_of_binary_secret_file);
        
2. And then call the generateLink(String user_info, Context context) of CipherTextClass as
        EdugorillaSso.generateLink(user_info, context);
        
3. Allow the internet permission in Manifest of your project as
        <uses-permission android:name="android.permission.INTERNET"/>
        
4. Add the Web activity of module CipherText in your Manifest.xml as
        <activity android:name="com.edugorilla.ssologin.WebView"/>

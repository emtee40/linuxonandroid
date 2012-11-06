If you would like to translate the app to your language please download the string-English.xml file which needs to be translated as follows. 

The lines in Strings-English.xml look like this:

<string name="button_back">Back</string>

The only part of that line you have to translate is the word 'Back'
It's important that the rest of the line is unchaged.

If you need to use characters like ' you have to put a \ in front of it, like so:


<string name="after_install_text">this is the way to use \' in a text</string>

In some of the files you'll may see \n which simply mean line feet.
So when you put in a \n the next text will start on the next line.

Once you have completed the translation simply commit the new strings.xml file with its new language (e.g strings-french.xml) here , please only translate if you are either a native speaker or pretty fluent in that language we are looking for real translations not just google translations  

If you have translated the file please keep a eye on this repo for future changes to the string-English.xml file, we will normally upload the new file a week before releasing the update to the public to give translators time to translate the new strings.

Thank you

LinuxonAndroid team
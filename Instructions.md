##Instructions

Thank you!

First of all, thank you very much for deciding to get involved in this project.  It will benefit a great number of users of websites running on the Xenforo operating system.  Once complete, I intend on making the Japanese language pack available through the official Xenforo website for anybody to download for free, as a goodwill gesture.  

Diktat.

Now, the rules.  Immediately, we need to say; don’t bugger anything up.  If you get stuck, don’t know what you are doing, think you have done something wrong, accidentally deleted something, etc., STOP, take your hands off the keyboard and take a deep breath.  Then contact me for assistance.

Instructions.

Now for the fun bit.  This is how you do it.

1.  Look in the repository.  You will see a load of files named ‘JapaneseA.xml’ through to ‘JapaneseZ.xml’.

3.  Open one of these A - Z files, and have a look inside.  It looks complex, but fear not, it is easy!

5.  You will be translating the English that appears on the left in the 'phrase title' element, and replacing the text that appears on the right, in the 'CDATA' element, with Japanese.  Now, at first glance, it will appear that there is a LOT to do.  There isn’t.  Some lines need translating.  Some don’t.  In fact, most of them don’t!  

Here is how it works.
  
The XML file I started with for this Japanese language pack, was the Vietnamese language pack, so the words and phrases you need to change will be in Vietnamese.  Any CDATA words or phrases which are in English, just leave, as they are not the priority to translate.

Once all of the Vietnamese is changed to Japanese, the rest of the CDATA words in English can be translated, but that doesn't need to take priority.

Look at this; 

     <phrase title="save_changes" addon_id="XenForo" version_id="1000470" version_string="1.0.4"><![CDATA[Lưu thay đổi]]></phrase>

The English phrase is 'save_changes'.  The 'Lưu thay đổi' is what you overwrite with Japanese.

Any words

Got it?

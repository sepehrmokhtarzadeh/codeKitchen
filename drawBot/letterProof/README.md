# letterProof

A python script for proofing your font. Made for personal use... still testing! 

## Description

Currently, this script only works through the DrawBot extension in Robofont. 
</br>
You must have your .ufo file open for it to work!
</br>

There are currently two versions of the proof.
1. letterproof_000
2. letterproof_000_fallback

The original version (without 'fallback') has no fallback font defined. Meaning that if your font does not have a certain glyph called by the script, it will still render the glyph using your systems native fallback font. 
</br> 
The other version (labeled with 'fallback') uses AdobeBlank as a fallback so that glyphs not in your font are not displayed. 
You can find AdobeBlank here: https://github.com/adobe-fonts/adobe-blank

## How to use the script

### Settings, inputting your information

1. Open your font in Robofont
2. Open the DrawBot extension
3. Input the code
4. Place your name in 'designer_name'
5. Input your fonts family name in 'typeface_name'
6. You can set your caption font by changing 'caption_font' as well as the size of the caption by 'caption_size'. The current default is Times New Roman at 7pt.

![Screen Shot 2022-03-25 at 14 43 05](https://user-images.githubusercontent.com/101493374/160182507-428d5868-d88c-45fa-a182-126192c19a60.png)

### Changing the text strings


*This script works by using each string in as list name 'testStrings' in a loop to create new pages for your proof. If you dont want a certain page in the doc you can select the string from testStrings and remove/comment it out. Each string is spaced out to make this a bit easier.*

![Screen Shot 2022-03-25 at 14 42 11](https://user-images.githubusercontent.com/101493374/160182585-4c3a1a6b-36ce-453e-8724-1ebbc74691c3.png)

Each text string is in order as they appear in the pdf, meaning if you don't want the last three pages for example all you have to do is delete/comment our the last three strings.

![Screen Shot 2022-03-25 at 14 46 52](https://user-images.githubusercontent.com/101493374/160182968-20f36554-f626-49ee-bffa-07a3d3cdad46.png)

# Application introduction website template

A single-page template for introducing your software has two dark and light modes, as well as left and right alignment depending on your taste, bootstrap and jQuery are used, attractive animations in theme change buttons, video playback and mobile menu;  AOS library is used to create animations while scrolling, customizable, modern and responsive design.

[Preview][Preview]

[![Preview][Banner]][Banner]

- [Attributes](#attributes)
- [Personalization](#personalization)

## Attributes

A single-page template for introducing your software has two dark and light modes, as well as left and right alignment depending on your taste, bootstrap and jQuery are used, exclusive animations for theme change buttons, video playback and mobile menu;  The AOS library is used to create attractive animations when scrolling, the possibility of personalizing more parts of the page, modern design and neomorphism, fully responsive so that it is displayed in the most appropriate way on any device, clean and optimized coding.  As well as recommending the codes for a better understanding of the codes

## Personalization

#### Changing page formatting (left and right alignment):

You can easily switch your page between right-aligned and left-aligned, all you need to do is put the page_ltr class html tag in the index file. If you want your page to be right-aligned, just delete the page_ltr class from the html tag.


#### Changing the title of the menu buttons:

Inside the header tag, there are two nav and ul tags, inside which there are menu buttons. To change each button, you must pay attention to apply your desired change in both the nav and ul tags. The nav tag is for the menu, which is in the computer and  Laptops are displayed and the ul tag is a menu that is displayed on mobile phones;  The reason that the two menu tags are located separately is so that you can consider specific customizations on different devices.

#### Changing the logo image in the menu:

To change it, enter the nav tag in the header tag, there is an img tag inside the a tag, and you put the photo address in the src attribute. If this method is difficult for you, just change the name of your logo file to Logo and replace the previous file in the image folder. Note that the extension of your logo file in this method must be .png. The recommended size of the logo is __100 x 50__ pixels. If the width of the image is more or less than 100, there is no problem, but try to make sure that the height of the image is 50 pixels.

#### Double column Attribute section:

The features section has 3 columns, the left and right columns are related to the description and the middle column of the image. If you want to remove one of the description columns, it is recommended to remove the div tag with the class 'left_attrs' or Add the 'd-none' class.


[Preview]: https://mjavadh.github.io/Application-introduction-website-template/
[Banner]: https://github.com/MjavadH/Application-introduction-website-template/blob/master/docx/preview/Banner-ltr.png "Banner"

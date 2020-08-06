How to use photoset yml file:

1. There are several layout types. These layout types define what goes into a row:
 - 'pic' = full size image in col-md-12.
 - 'picPic' = 2 images in their own col-md-6.
 - 'picText' = 1 image in left col-md-6, text in right col-md-6
 - 'textPic' = text in left col-md-6, 1 image in right col-md-6

This means that the content for the photoset-layout.html file is driven from the yml file.

----
- image1:
  layout: pic
  small: /images/450.jpeg
  medium: /images/1000.jpeg
  large: /images/2500.jpeg
  alt: image 1

- image3:
  layout: picPic
  smallLeft: /images/450.jpeg
  mediumLeft: /images/1000.jpeg
  largeLeft: /images/2500.jpeg
  altLeft: image left  1
  smallRight: /images/450.jpeg
  mediumRight: /images/1000.jpeg
  largeRight: /images/2500.jpeg
  altRight: image right 1

- image7:
  layout: picText
  small: /images/450.jpeg
  medium: /images/1000.jpeg
  large: /images/2500.jpeg
  alt: image split 3
  text: Even more text on the left. Conditionals ftw!

- image8:
  layout: textPic
  small: /images/450.jpeg
  medium: /images/1000.jpeg
  large: /images/2500.jpeg
  alt: image split 3
  text: This is some text. Text can go here in the column next to the image.

- sectionBreak:
  layout: sectionBreak
  title:
  text:
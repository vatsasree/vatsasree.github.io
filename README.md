## vatsasree.github.io

**Below are the images for results. Images on the left are the outputs of state-of-the-art text detection model and it's right counterparts are the outputs of our Robust fine-tuned model.**

Issue 1 - White space and Ink-bleed predictions
![issue1](https://user-images.githubusercontent.com/99678758/211672387-27fce4dd-6c67-4e4d-a0ec-f747d3913b65.png)

Issue 2 - Multiple words are detected as a single word and vice-versa 
![issue2](https://user-images.githubusercontent.com/99678758/211672389-cb761e91-9f50-4092-a03f-f12f42fe7ba5.png)

Issue 3 - Diacritics and conjunct consonants above or below alphabets cause separated bounding boxes during prediction 
![issue3](https://user-images.githubusercontent.com/99678758/211672302-cb38cef1-9134-46ad-8ae8-d707fdd7b40d.png)

Issue 4 - Words towards right-end of the page not detected
![issue4](https://user-images.githubusercontent.com/99678758/211672325-f8f75b8a-6ee1-410c-a1eb-1975fd5a7a42.png)

Issue 5 - Non-textual objects falsely detected as words
![issue5](https://user-images.githubusercontent.com/99678758/211672344-26e52675-8f20-4443-af5b-d8d03d26c462.png)


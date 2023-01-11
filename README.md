## vatsasree.github.io

# BAD/MALFORMED GROUND TRUTHS

***Below are the examples for Bad/Malformed ground truths from our Consortium dataset***
![badgts](https://user-images.githubusercontent.com/99678758/211762958-55e766ca-ac43-4a27-a847-ec5093551f01.svg)
<p align="center">
<b>Fig 1: Examples of bad/malformed ground truths</b>
</p>

# COMPARATIVE RESULTS
***Given below are the examples of each case in which the fine-tuned model performes better over the state-of-the-art. Two examples for each case are shown.*** 

***Images on the left are the outputs of state-of-the-art text detection model and it's right counterparts are the outputs of our Robust fine-tuned model.***

Table 1 in the paper clearly shows that the fine-tuned model performs way better in detecting text than the state-of-the-art model on printed Indic text. 

-> *Issue 1 - White space and Ink-bleed predictions*
![issue_1](https://user-images.githubusercontent.com/99678758/211768322-b481ed31-c1c5-42c0-925a-33702637612b.svg)
<p align="center">
<b>Fig 2: White space and Ink-bleed predictions</b>
</p>

-> *Issue 2 - Multiple words are detected as a single word and vice-versa*
![issue_2](https://user-images.githubusercontent.com/99678758/211767480-ac3dc673-33e9-4394-9827-43c94dec6e3d.svg)
<p align="center">
<b>Fig 3: Multiple words are detected as a single word and vice-versa</b>
</p>

-> *Issue 3 - Diacritics and conjunct consonants above or below alphabets cause separated bounding boxes during prediction* 
![issue_3](https://user-images.githubusercontent.com/99678758/211767486-f6ff891a-3f5a-4ae0-92a0-298be9594435.svg)
<p align="center">
<b>Fig 4: Diacritics and conjunct consonants above or below alphabets cause separated bounding boxes during prediction</b>
</p>

-> *Issue 4 - Words towards right-end of the page not detected*
![issue_4](https://user-images.githubusercontent.com/99678758/211767489-bda61053-b80e-43a9-9a9f-28f77651d906.svg)
<p align="center">
<b>Fig 5: Words towards right-end of the page not detected</b>
</p>

-> *Issue 5 - Non-textual objects falsely detected as words*
![issue_5](https://user-images.githubusercontent.com/99678758/211767464-1be91913-8ca7-4762-a518-9f7686af4f35.svg)
<p align="center">
<b>Fig 6: Non-textual objects falsely detected as words</b>
</p>











# zenegata
epub and mobi validator.

# Goal
The goal of this project is to detects vendor specific limitations and any impurities of an epub file that epubcheck ignores. For example, if you are distributing an epub to Apple, you need to make sure that you don't have an image that contains 3.2 Million pixels or it will be rejected. Another example is the guide items for mobi files, according to Amazon's guidelines it is best not to include guides other than cover, toc and reading start, because these items are not supported and will be greyed out on kindle devices causing customer confusion.

## Overview

Song genre classification by lyric analysis. Song lyrics show very specific properties such as rhyming verses and having different frequencies for certain parts of speech



## Data

We plan to scrape data from websites such as lyricsfreak.com. We anticipate issues with lyric formatting and undesired text due to page formatting



## Method

We will use classical bag-of-words, part of speech features and text statistical features. Genre classification will be done using naïve ayes, k-nearest neighbor with different values for k, SVMs with linear and polynomial kernels. We plan to use built in libraries in python such nltk, SVM, Nearest Neighbors etc. We plan to use atleast 1 other algorithm which would have to code from scratch rather than use a library.



## Related Work

1.	http://download.springer.com/static/pdf/983/chp%253A10.1007%252F978-3-540-71496-5_78.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Fchapter%2F10.1007%2F978-3-540-71496-5_78&token2=exp=1486671469~acl=%2Fstatic%2Fpdf%2F983%2Fchp%25253A10.1007%25252F978-3-540-71496-5_78.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Fchapter%252F10.1007%252F978-3-540-71496-5_78*~hmac=f341b55f1e5f983548d5fde7b22bc6965d8c60d09de2217e2ea6c480a655ccbe



2.	http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4725050



3.	http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=1394328



4.	https://pdfs.semanticscholar.org/e658/ec86e033aae370ba680118a04431071cafe1.pdf



5.	http://163.1.127.173/sandbox/datasets/wickesmusictest/musicStudy-4%203test/may_ismir11-lyrics-ensemble.pdf



## Evaluation

We will evaluate our results by comparing the accuracy of the various algorithms. We will use random guess and majority class as our baseline



We will produce plots on occurrence of various types of rhymes, average values for parts-of-speech features and average vales for statistical features.



We will use f-score, top features and accuracy for performance metrics 




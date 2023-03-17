# :mag_right: Information-Retrieval-using-Pyserini
Using Pyserini package to cope with Inverted Index, Postings List, and BM25.  
:pushpin: The reference package is [Here](https://github.com/castorini/pyserini). It's a powerful package! :thumbsup:    
  
    

### :speech_balloon: Inverted Index 反向索引
* For each term t, we store a list of all documents that contain t.  
Identify each doc by a docID, a document serial number.  
  
![](https://github.com/CY-Chang-tw/Information-Retrieval-using-Pyserini/blob/4a27d6bca522fc70ee5c9b5618f67121d17e9a09/docs/posting.png)  

   * Intersecting two postings lists (a “merge” algorithm) to processing the query.  
   The merge takes ```O(x + y)```, if the list lengths are x and y.    
     
  ![](https://github.com/CY-Chang-tw/Information-Retrieval-using-Pyserini/blob/8675ed891c87df43f5c93ec03f72c6eb047da03f/docs/merge.png)

# constituency-parsing-visualization

 * UCF CAP5738 Data Visualization Class Project
 * Using D3 for a constituency parsing tree.
 * Parsing results are provieded by Stanford CoreNLP Server.
 
 There are two mode:
    Default: Using a server from Stanford CoreNLP webpage
    Local: Running a local server with Stanford CoreNLP toolkit.
    
If you would like to run a local server please follow below instructions:

```
$ wget http://nlp.stanford.edu/software/stanford-corenlp-full-2018-10-05.zip
$ unzip stanford-corenlp-full-2018-10-05.zip
$ cd stanford-corenlp-full-2018-10-05
$ nohup java -mx16g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -port 9000 -timeout 60000 &
$ cd -
```

Then please uncomment the line 249 and comment out the line 250. 
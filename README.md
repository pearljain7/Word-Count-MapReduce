# Word-Count-MapReduce
Word Count using MapReduce

To run WordCount.java 

1)Generate jar file
--
~ hadoop com.sun.tools.javac.Main WordCount.java
~ jar cf pearlwc.jar WordCount*.class

2)Run WordCount
-- 
~ hadoop jar pearlwc.jar WordCount input output

pearlwc.jar is mentioned in the repo.

//Output attached in the repo (Filename: Input/Output->Output->output->part-r-00000)

To run TopMovie.java 
1)Generate jar file
--
~ hadoop com.sun.tools.javac.Main TopMovie.java
~ jar cf tm.jar TopMovie*.class

2)Run TopMovie
-- 
~ hadoop jar tm.jar TopMovie movieinput movieoutput

tm.jar is mentioned in the repo.

//Output attached in the repo (Filename: Input/Output->movieoutput->movieoutput->part-r-00000)

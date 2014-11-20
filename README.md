idea-wildcard
=============

the sample project to describe the issue of moving wildcard spring config

### following the steps below ###

 1. clone the code from this repository.

 2. import the work copy into your idea.

 3. enable automate import.

 4. open applicationContext.xml in the idea, it is a spring config file, you will see "classpath*:com/yongpoliu/bean/internal/**/module-*.xml"

 5. drag applicationContext.xml to another directory, then you will see the changes in the file that idea makes. All the wildcard will be replaced with one of the matches, and it's not what i wanted.
---
content_type: page
title: Assignments
uid: 647ec78d-ce25-991a-1d58-c5306ef23f53
---

This section contains the labs that were done during class, along with example solutions, and a small section of [miscellaneous](#Miscellaneous) items.

Labs and Solutions
------------------

| DESCRIPTION | FILES | SOLUTIONS |
| --- | --- | --- |
| Lab 3 covered control flow with if-elif-else statements. | ([PDF]({{< baseurl >}}/resources/lab3)) | &nbsp; |
| Lab 4 covered control flow with while statements. | ([PDF]({{< baseurl >}}/resources/lab4)) |  {{< br >}}{{< br >}} login.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/login.py)) {{< br >}}{{< br >}} nims1.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/nims1.py)) {{< br >}}{{< br >}} nims2.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/nims2.py)) {{< br >}}{{< br >}}  |
| Lab 5 covered the use of lists in storing a dynamic number of values. | ([PDF]({{< baseurl >}}/resources/lab5)) |  {{< br >}}{{< br >}} sorting.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/sorting.py)) {{< br >}}{{< br >}} reportcard.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/reportcard.py)) {{< br >}}{{< br >}}  |
| Lab 6 covered the use of tuples instead of lists and their similarity with strings. | ([PDF]({{< baseurl >}}/resources/lab6)) |  {{< br >}}{{< br >}} collision.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/collision.py)) {{< br >}}{{< br >}} piglatin.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/piglatin.py)) {{< br >}}{{< br >}}  |
|  {{< br >}}{{< br >}} Lab 7 was a walkthrough tutorial that introduced the idea of objects as opposed to primitive types like ints and floats. By exploring concepts like primitives (e.g. numbers) versus references to objects (e.g. lists), mutability versus immutability, and the effects of scope on objects, we now better understand how to use objects correctly. {{< br >}}{{< br >}} {{< h 3 >}}Notes{{< /h >}}   {{< br >}}{{< br >}} 1\. Some commands will not produce the expected results when performed on the shell. Instead, run the commands from a file. I'm not sure why this is. {{< br >}}{{< br >}} 2\. I was under the impression that Python aliases tuples automatically. It turns out this is **not** the case. In other words: {{< br >}}{{< br >}} > a = (1, 2, 3)  {{< br >}}> b = (1, 2, 3)  {{< br >}}> print a is b {{< br >}}{{< br >}} However, you can still alias by saying b = a. Strings are still automatically aliased. {{< br >}}{{< br >}}  | ([PDF]({{< baseurl >}}/resources/lab7)) | &nbsp; |
| Lab 8 covered the use of member functions in various objects. | ([PDF]({{< baseurl >}}/resources/lab8)) | genetic.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/genetic.py)) |
| Lab 9 covered the use and syntax of dictionaries. The bulk of the lab was to explore one common use of dictionaries as indexes, in this case, for searching the Web. |  {{< br >}}{{< br >}} ([PDF]({{< baseurl >}}/resources/lab9)) {{< br >}}{{< br >}} namesages.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/namesages.py)) {{< br >}}{{< br >}} websearch1.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/websearch1.py)) {{< br >}}{{< br >}} webindexer1.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/webindexer1.py)) {{< br >}}{{< br >}} htmltext.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/htmltext.py)) {{< br >}}{{< br >}} smallsites.txt ([TXT](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/smallsites.txt)) {{< br >}}{{< br >}} mitsites20.txt ([TXT](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/mitsites20.txt)) {{< br >}}{{< br >}} mitsites50.txt ([TXT](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/mitsites50.txt)) {{< br >}}{{< br >}} localsites.zip ([ZIP]({{< baseurl >}}/resources/localsites)) {{< br >}}{{< br >}}  |  {{< br >}}{{< br >}} namesages\_soln.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/namesages_soln.py)) {{< br >}}{{< br >}} webindexer1\_soln.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/webindexer1_soln.py)) {{< br >}}{{< br >}}  |
| Lab 10 covered a more advanced use of dictionaries. The bulk of the lab was to improve the web indexer we built in the previous lab. |  {{< br >}}{{< br >}} ([PDF]({{< baseurl >}}/resources/lab10)) {{< br >}}{{< br >}} inventory.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/inventory.py)) {{< br >}}{{< br >}} websearch2.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/websearch2.py)) {{< br >}}{{< br >}} webindexer2.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/webindexer2.py)) {{< br >}}{{< br >}}  |  {{< br >}}{{< br >}} inventory\_soln.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/inventory_soln.py)) {{< br >}}{{< br >}} webindexer2\_soln.py ([PY](/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2008/assignments/webindexer2_soln.py)) {{< br >}}{{< br >}}  

{{< anchor "Miscellaneous" >}}{{< /anchor >}}Miscellaneous
----------------------------------------------------------

Optional Assignment ([PDF]({{< baseurl >}}/resources/optional)): This walks you through the building of a computer from scratch. Starting at the gate level, you'll understand how a computer works.

Operator Cheat Sheet ([PDF]({{< baseurl >}}/resources/operator)): This lists some of the various arithmetic and boolean (comparison, equality, and logic) operators we've learned.
# MCA203P Java Lab Sheet 09 — Complete Solutions

Contains solutions for **30 questions** from the provided OOP Using Java assignment.

## Requirements

- JDK 8 or later (JDK 11/17/21 recommended)
- VS Code or Windows CMD / PowerShell / Linux Terminal
- No external dependencies

## Compile and run

In Windows CMD, open this extracted folder and run:

```bat
cd src
javac *.java
java Q01_ArrayListPrint
```

Or use `compile_all.bat` from the extracted root on Windows. On Linux/macOS, use `bash compile_all.sh`.

## Files / question mapping

- Q01: `Q01_ArrayListPrint.java` — Create ArrayList of integers and print elements
- Q02: `Q02_ArrayListSize.java` — Add elements to ArrayList and show size
- Q03: `Q03_ArrayListInsert.java` — Insert an element at a specific index
- Q04: `Q04_ArrayListRemove.java` — Remove by index and by value
- Q05: `Q05_ArrayListUpdate.java` — Update ArrayList at index
- Q06: `Q06_ForEachLoop.java` — Iterate ArrayList using for-each
- Q07: `Q07_ArrayListIterator.java` — Iterate ArrayList using Iterator
- Q08: `Q08_SortArrayList.java` — Sort ArrayList ascending
- Q09: `Q09_ReverseStrings.java` — Reverse ArrayList strings
- Q10: `Q10_LinkedListPrint.java` — Create and display LinkedList strings
- Q11: `Q11_LinkedListAddEnds.java` — Add beginning and end of LinkedList
- Q12: `Q12_LinkedListRemoveEnds.java` — Remove first and last LinkedList elements
- Q13: `Q13_LinkedListGetEnds.java` — Get first and last LinkedList elements
- Q14: `Q14_HashSetNoDuplicates.java` — HashSet does not store duplicates
- Q15: `Q15_HashSetRemove.java` — Remove element from HashSet
- Q16: `Q16_HashSetIterator.java` — Iterate HashSet using Iterator
- Q17: `Q17_TreeSetSorted.java` — TreeSet sorts values automatically
- Q18: `Q18_TreeSetContains.java` — Check TreeSet membership
- Q19: `Q19_LinkedHashSetOrder.java` — LinkedHashSet insertion order
- Q20: `Q20_CompareSetTypes.java` — Compare HashSet, LinkedHashSet, TreeSet
- Q21: `Q21_PriorityQueuePrint.java` — Create PriorityQueue and print
- Q22: `Q22_PriorityQueuePoll.java` — Remove priority queue elements in priority order
- Q23: `Q23_PriorityQueuePeek.java` — Peek without removing first priority value
- Q24: `Q24_QueueLinkedList.java` — Queue interface with LinkedList implementation
- Q25: `Q25_QueueOperations.java` — Add, remove, peek on Queue
- Q26: `Q26_CustomObjectIterator.java` — ArrayList of Student objects iterated by Iterator
- Q27: `Q27_CustomObjectComparator.java` — Sort custom Student objects with Comparator
- Q28: `Q28_ListToSet.java` — Convert List to Set removing duplicate items
- Q29: `Q29_SetToList.java` — Convert Set to List and iterate
- Q30: `Q30_ClearCollections.java` — Clear List, Set and Queue

All 30 numbered questions are standalone. Run `java Q01_ArrayListPrint`, `java Q02_ArrayListSize`, etc.


## Sample output

See `SAMPLE_OUTPUTS.txt`. It contains program output captured from actual runs where possible.
Network programs may need local ports and active server/client processes. Exact IP/host, date, collection ordering, and internet content can differ by machine.

## Submission

The `src` directory is suitable for uploading to GitHub. Do not upload compiled `.class` files.
Source code is for educational laboratory demonstrations; edit example records if needed.


| Data Structure | Description                                                                | Key Methods                                                                                                                                              |
| -------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ArrayList      | Resizable array implementation of the List interface.                      | `add(E e)`,`add(int index, E e)`, `get(int index)`, `remove(int index)`, `size()`, `contains(Object o)`, `indexOf(Object o)`, `isEmpty()`                |
| LinkedList     | Doubly-linked list implementation of the List and Deque interfaces.        | `add(E e)`, `add(int index, E e)`,  `get(int index)`, `remove(int index)`, `addFirst(E e)`, `addLast(E e)`, `removeFirst()`, `removeLast()`, `isEmpty()` |
| HashSet        | Hash table-based implementation of the Set interface.                      | `add(E e)`, `remove(Object o)`, `contains(Object o)`, `size()`, `isEmpty()`                                                                              |
| TreeSet        | Red-Black tree-based implementation of the NavigableSet interface.         | `add(E e)`, `remove(Object o)`, `contains(Object o)`, `first()`, `last()`, `pollFirst()`, `pollLast()`, `isEmpty()`                                      |
| HashMap        | Hash table-based implementation of the Map interface.                      | `put(K key, V value)`, `get(Object key)`, `remove(Object key)`, `containsKey(Object key)`, `keySet()`, `values()`, `isEmpty()`                           |
| TreeMap        | Red-Black tree-based implementation of the NavigableMap interface.         | `put(K key, V value)`, `get(Object key)`, `remove(Object key)`, `firstKey()`, `lastKey()`, `pollFirstEntry()`, `pollLastEntry()`, `isEmpty()`            |
| PriorityQueue  | Priority heap implementation of the Queue interface.                       | `add(E e)`, `peek()`, `poll()`, `remove(Object o)`, `size()`, `isEmpty()`                                                                                |
| ArrayDeque     | Resizable-array implementation of the Deque interface.                     | `addFirst(E e)`, `addLast(E e)`, `removeFirst()`, `removeLast()`, `getFirst()`, `getLast()`, `isEmpty()`                                                 |
| Stack          | LIFO stack implementation.                                                 | `push(E item)`, `pop()`, `peek()`, `empty()`, `search(Object o)`, `isEmpty()`                                                                            |
| Vector         | Resizable array implementation of the List interface (thread-safe).        | `add(E e)`, `get(int index)`, `remove(int index)`, `size()`, `contains(Object o)`, `isEmpty()`                                                           |
| Hashtable      | Legacy hash table-based implementation of the Map interface (thread-safe). | `put(K key, V value)`, `get(Object key)`, `remove(Object key)`, `containsKey(Object key)`, `isEmpty()`                                                   |


| Method | Description |
|--------|-------------|
| `StringBuilder()` | Constructs a string builder with no characters in it and an initial capacity of 16 characters. |
| `StringBuilder(CharSequence seq)` | Constructs a string builder containing the same characters as the specified `CharSequence`. |
| `StringBuilder(int capacity)` | Constructs a string builder with no characters in it and an initial capacity specified by the `capacity` argument. |
| `StringBuilder(String str)` | Constructs a string builder initialized to the contents of the specified string. |
| `append(type content)` | Appends the string representation of the specified argument to this sequence. |
| `insert(int offset, type content)` | Inserts the string representation of the specified argument into this sequence at the specified position. |
| `delete(int start, int end)` | Removes the characters in a substring of this sequence. |
| `deleteCharAt(int index)` | Removes the character at the specified position in this sequence. |
| `reverse()` | Causes this character sequence to be replaced by the reverse of the sequence. |
| `charAt(int index)` | Returns the character at the specified index. |
| `setCharAt(int index, char ch)` | Sets the character at the specified index to `ch`. |
| `length()` | Returns the length (character count) of this character sequence. |
| `substring(int start)` | Returns a new `String` that contains a subsequence of the characters currently contained in this sequence. |
| `substring(int start, int end)` | Returns a new `String` that contains a subsequence of the characters currently contained in this character sequence. |
| `setLength(int newLength)` | Sets the length of the character sequence. |
| `replace(int start, int end, String str)` | Replaces the characters in a substring of this sequence with characters in the specified `String`. |
| `indexOf(String str)` | Returns the index within this string of the first occurrence of the specified substring. |
| `indexOf(String str, int fromIndex)` | Returns the index within this string of the first occurrence of the specified substring, starting at the specified index. |
| `toString()` | Returns a string representing the data in this sequence. |
| `capacity()` | Returns the current capacity, which is the amount of storage available for newly inserted characters. |
| `ensureCapacity(int minimumCapacity)` | Ensures that the capacity is at least equal to the specified minimum. |
| `trimToSize()` | Attempts to reduce storage used for the character sequence. |

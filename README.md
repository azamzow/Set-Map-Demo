# Set Map Demo Project

### Description

This program demonstrates working with Sets and Maps in java. It utilizes the following:

  1) Hast set: extends AbstractSet and implements the Set interface. It creates a collection that uses a hash table for storage.
  2) Hash map: offers 0(1) lookup and insertion. If you iterate through the keys, though, the ordering of the keys is essentially arbitrary. It is implemented by an array of linked lists.
  3) Tree set: is basically implementation of a self-balancing binary search tree like Red-Black Tree.
  4) Tree map: offers O(log N) lookup and insertion. Keys are ordered, so if you need to iterate through the keys in sorted order, you can. This means that keys must implement the Comparable interface. TreeMap is implemented by a Red-Black Tree.
  5) Linked set: is a linear data structure. Unlike arrays, linked set elements are not stored at contiguous location; the elements are linked using pointers.
  6) Linked map: offers 0(1) lookup and insertion. Keys are ordered by their insertion order. It is implemented by doubly-linked buckets

### To Run

Using terminal on Mac:

```
$ cd Set-Map-Demo
$ javac SetMapDemo.java
$ java SetMapDemo
```

### Output

An Example output is shown below,

```
Hash  set: [as, looks, nothing, is, it, easy]

Tree set: [as, easy, is, it, looks, nothing]

Linked set: [nothing, is, as, easy, it, looks]

6 distinct words detected:

Hash map: {as=2, looks=1, nothing=1, is=1, it=1, easy=1}

Tree map: {as=2, easy=1, is=1, it=1, looks=1, nothing=1}

Linked map: {nothing=1, is=1, as=2, easy=1, it=1, looks=1}
```

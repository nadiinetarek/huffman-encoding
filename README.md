# Huffman Coding

<p>
  <img src="https://img.shields.io/pypi/status/Django.svg"/>
  <img src="https://img.shields.io/badge/contributions-welcome-orange.svg"/>
</p>

<a href="https://en.wikipedia.org/wiki/Huffman_coding">Huffman code</a> is a particular type of optimal prefix code that is commonly used for lossless data compression. The process of finding or using such a code proceeds by means of Huffman coding, an algorithm developed by David A. Huffman.

## Objective
Huffman’s algorithm takes a very simple idea and finds an elegant way to implement it. At its heart is the observation that the more a thing is mentioned, the shorter its name should be. This idea manifests itself in daily life too. For example, we use nicknames for people we call often, we have abbreviations for long words we often have to use and even the word ok was once an abbreviation for “all correct”.


During decompression, the dictionary is read and the codewords are sequentially translated into actual data.



## Data Structures Used
* Heap-Nodes 
* Heaps / Priority Queues and their associated heap nodes 
* Huffman Trees 
* Hash-Maps
* Frequency Hash-Map
* Character Code Hash-Map

</br>

## Complexities
* O(n*lg(n)) for building Huffman Trees
* O(lg(n)) for each individual heapify operation 
* O(n*f(c)) for encoding each Character and writing it to file 
  * n is the number Of characters 
  * f(c) is the frequency of that character.
* O(1) for value retrieval of each key in the Hash-Map 
* O(n) for decompression of a single file 
  * n is the number of bytes in that file. 
  

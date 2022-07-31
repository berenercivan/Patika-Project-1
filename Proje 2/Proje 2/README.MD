
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje

# Proje 2
**Merge Sort**

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11,8,12,22]
	
	[16,21,11] - [8,12,22]

	[16,21] - [11] - - [8,12] - [22]
	
	[16] - [21] - [11] - - [8] - [12] - [22]

	[16,21] - [11] - - [8,12] - [22]

	[11,16,21] - [8,12,22]
	
	[8,11,12,16,21,22]


2. Big-O gösterimini yazınız.

2^x = n

logn= x kere bu işlem tekrar edilir.
Bu nedenle Big-O gösterimi O(nlogn)dir.

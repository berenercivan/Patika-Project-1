
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje

#  Proje 3
**Binary Search Tree Projesi**

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root, 7'dir.

		7

Root'un solunda 5 bulunur,

		   7
	      /
	     5

1, Root'tan küçük olduğu için sol tarafta, 5'ten küçük olduğu için 5'in soluna yazılır.

		    7
	      /
	    5
	  /
	1

Root'un sağına 8 yazılır.

		    7
	      /   \
	    5       8
	  /
	1

3, Root'tan küçük olduğu için sol tarafına, 5'ten küçük olduğu için yine sol tarafına ve 1'den büyük olduğu için 1'in sağ tarafına yazılır.

		    7
	      /   \
	    5       8
	  /
	1
      \
        3

6, Root'tan küçük olduğu için sol tarafına, 5'ten büyük olduğu için 5'in sağına yazılır.

		    7
	      /   \
	    5       8
	  /   \
	1       6
     \
       3

0, Root'tan küçük olduğu için sol tarafına, 5'ten küçük olduğu için sol tarafına ve 1'den küçük olduğu için 1'in sol tarafına yazılır.

		  	   7
	         /   \
	       5       8
	     /   \
	   1       6
     /   \
    0      3          




9, Root'tan büyük olduğu için sağ tarafına, 8'den büyük olduğu için 8'in sağ tarafına yazılır.

		       7
	         /   \
	       5       8
  	     /   \       \
	   1       6       9
     /   \
    0      3          




4, Root'tan küçük olduğu için sol tarafına, 5'ten küçük olduğu için sol tarafına, 1'den büyük olduğu için sağ tarafına ve 3'ten büyük olduğu için 3'ün sağ tarafına yazılır.

	
		      7
	        /   \
	      5       8
	    /   \       \
	  1       6       9
    /   \
    0    3
          \
	       4
            

  
  
  2, Root'tan küçük olduğu için sol tarafına, 5'ten küçük olduğu için sol tarafına, 1'den büyük olduğu için sağ tarafına ve 3'ten küçük olduğu için 3'ün sol tarafına yazılır.

		       7
	         /   \
	       5       8
	     /   \       \
    	1     6       9
      /   \
    0       3
          /   \
	    2       4  

    

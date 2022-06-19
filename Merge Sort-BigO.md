Soru1: [16,21,11,8,12,22] dizinin "merge sort"a göre dizilimi aşağıdaki gibidir.

				16-21-11-8-12-22 
			   16-21-11    8-12-22
			  16-21  11	   8-12  22
	        16   21   11   8   12   22	
			  16-21  11	   8  12-22
	           11-16-21    8-12-22		
				8-11-12-16-21-22		


Soru2: Dizinin Big-O gösterimi:

Her seferinde ikiye bölündüğü için; 
2^x=n
2^x=6=>x=log6

Her satır O(n) olduğu için
O(6).log(6)=**O(6Log6)**
# Merge Sort Projesi
**Patika.dev Profilim: https://app.patika.dev/senaeser**
# Soru 1
[16,21,11,8,12,22] -> Merge Sort

Dizin sort türüne göre aşamaları;

-Önce diziyi 2'ye bölücez: [16,21,11] [8,12,22]

-Böldüğümüz sayıları tekrar 2'ye ayırıyoruz: [16,21] [11] [8] [12,22]

-Tek eleman kalana kadar devam ettik: [16] [21] [11] [8] [12] [22]

					[16,21,11,8,12,22] 
			[16,21,11]					[8,12,22] 
		[16]		[21,11]				[8]		[12,22]
		[16]	[21]	[11]				[8]	[12]	[22]             
			[16,21]	[11]				[8,12]		[22]
			[11,16,21]					[8,12,22]
					[8,11,12,16,21,22]



# Soru 2
[16,21,11,8,12,22] -> Merge Sort

Big-O gösterimi;

Merge sort, önce diziyi yarıya böler sonra bunları sıralı bir şekilde birleştirir.

n=6

Best case    : O(n*logn)

Average case : O(n*logn)

Worst case   : O(n*logn) -> O(6*log6)

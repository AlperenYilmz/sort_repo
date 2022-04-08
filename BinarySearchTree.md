# Proje 3

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
## Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Soldan sağa giderek, 7'yi **root** seçersek,
- 5, 7'den küçük, solunda
- 1, 7'den küçük, solunda; 5'ten küçük, solunda
- 8, 7'den büyük, sağında
- 3, 7'den küçük, solunda; 5'ten küçük, solunda; 1'den büyük, sağında
- 6, 7'den küçük, solunda; 5'ten büyük, sağında
- 0, 7'den küçük, solunda; 5'ten küçük, solunda; 1'den küçük, solunda
- 9, 7'den büyük, sağında; 8'den büyük, sağında
- 4, 7'den küçük, solunda; 5'ten küçük, solunda; 1'den büyük, sağında, 3'ten büyük, sağında
- 2, 7'den küçük, solunda; 5'ten küçük, solunda; 1'den büyük, sağında, 3'ten küçük, solunda

## Aşağıda BST'nin çizili hali mevcuttur.
![bst](https://github.com/AlperenYilmz/kodluyoruzilkrepo/blob/main/bst.png)

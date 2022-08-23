## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary Search Tree aşamalarını yazınız.

### Sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.

- Aşama 1  : Root = 7 , Eklenen 5 , 7'nin Soluna Eklenir ,
```
    7
  /
5  
```
- Aşama 2  : Root = 7 , Eklenen 1 , 5'in Soluna Eklenir ,
```
        7
      /
    5
  /
1
```
- Aşama 3  : Root = 7 , Eklenen 8 , 7'nin Sağına Eklenir ,
```
        7
      /   \
    5       8
  /
1
```
- Aşama 4  : Root = 7 , Eklenen 3 , 1'in Sağına Eklenir ,
```
        7
      /   \
    5       8
  /
1
  \
    3
```
- Aşama 5  : Root = 7 , Eklenen 6 , 5'in Sağına Eklenir ,
```
        7
      /   \
    5       8
  /   \
1       6
  \
    3
```
- Aşama 6  : Root = 7 , Eklenen 0 , 1'in Soluna Eklenir ,
```
              7
            /   \
          5       8
        /   \
      1       6
    /   \
   0     3
```
- Aşama 7  : Root = 7 , Eklenen 9 , 8'in Sağına Eklenir ,
```
              7
            /   \
          5       8
        /   \       \
      1       6       9
    /   \
   0     3
```
- Aşama 8  : Root = 7 , Eklenen 4 , 3'in Sağına Eklenir ,
```
              7
            /   \
          5       8
        /   \       \
      1       6       9
    /   \
   0     3
           \
             4
```
- Aşama 9  : Root = 7 , Eklenen 2 , 3'ün Soluna Eklenir , ,
```
              7
            /   \
          5       8
        /   \       \
      1       6       9
    /   \
   0     3
       /   \
     2       4
```

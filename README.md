# BINARY SEARCH TREE

Abdullah Demirkol'a patika.dev sitesinde [ademirkol](https://app.patika.dev/ademirkol) kullanıcı adı ile ulaşabilirsiniz.

## Patika.dev'de veri yapıları kursu için yapılan proje


## **SORU 1 -** [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

> **Binary Search Tree Hatırlatma** 
> >Bir düğüm her iki tarafa da referans verebiliyor. Sağ ve sol olarak. Sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunacak.

### A - Yukarı verilen dizinin search türüne göre aşamalarını yazınız.

```mermaid
  graph TD;
        7,5,1,8,3,6,0,9,4,2 -->6;

        6-->5,1,3,0,4,2;
        6-->7,8,9;

        5,1,3,0,4,2-->3;

        3-->1,0,2;
        3-->5,4


        7,8,9-->8;
        8-->7;
        8-->9;
        
    
```

**Toplam islem sayısı 6**

### B - Big-O gösterimini yazınız.

 O(nlogn) -> O(6log6)
# proje3
binary search tree proje ödevi


**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**
1. Serinin ilk elemanı olan 7'yi içeren kök düğümle başlayın.
   -       7


2. Serideki bir sonraki öğe olan 5'i kök düğüm değeriyle karşılaştırın. 5, 7'den küçük olduğundan, onu kök düğümün sol çocuğu olarak ekliyoruz.
   -          7
            /
          5

3. Sonraki öğe olan 1'i kök düğüm değeriyle karşılaştırın. 1, 7'den küçük olduğundan sol alt düğüme geçiyoruz. 5 içeren düğümün sol alt düğümü olmadığından, o düğümün sol çocuğu olarak 1 ekliyoruz.
   -                7
                   / \
                  5   
                 /     
                1   
4.Sonraki öğe olan 8'i kök düğüm değeriyle karşılaştırın. 8, 7'den büyük olduğundan sağ alt düğüme geçiyoruz. 7'yi içeren düğümün sağ alt düğümü olmadığından, o düğümün sağ çocuğu olarak 8'i ekliyoruz.
   -                7
                   / \
                  5   8
                 /     
                1       
5. Sonraki öğe olan 3'ü kök düğüm değeriyle karşılaştırın. 3, 7'den küçük olduğundan sol alt düğüme geçiyoruz. 3'ü, 5'i içeren düğümün değeriyle karşılaştırıyoruz. 3, 5'ten küçük olduğundan, onu o düğümün sol çocuğu olarak ekliyoruz.
   -                7
                   / \
                  5   8
                 / \
                1   3 

6. Sonraki öğe olan 6'yı kök düğüm değeriyle karşılaştırın. 6, 7'den büyük olduğundan sağ alt düğüme geçiyoruz. 6'yı, 8'i içeren düğümün değeriyle karşılaştırıyoruz. Bu düğümün sol alt düğümü olmadığından, o düğümün sol çocuğu olarak 6'yı ekliyoruz.
   -                7
                   / \
                  5   8
                 / \
                1   3
                     \
                      6
7. Bir sonraki öğe olan 0'ı kök düğüm değeriyle karşılaştırın. 0 7'den küçük olduğundan sol alt düğüme geçiyoruz. 0'ı, 5'i içeren düğümün değeriyle karşılaştırıyoruz. Bu düğüm için sol alt düğüm olmadığından, o düğümün sol çocuğu olarak 0'ı ekliyoruz.
   -                7
                   / \
                  5   8
                 / \
                1   3
               /     \
              0       6


8. Sonraki öğe olan 9'u kök düğüm değeriyle karşılaştırın. 9, 7'den büyük olduğundan sağ alt düğüme geçiyoruz. 9'u, 8'i içeren düğümün değeriyle karşılaştırıyoruz. Bu düğüm için sağ alt düğüm olmadığından, o düğümün sağ çocuğu olarak 9'u ekliyoruz.
   -                7
                   / \
                  5   8
                 / \   \
                1   3   9
               /     \
              0       6
  
  
9. Dokuzuncu öğe olan 4'ü daha küçük olan kök düğümle karşılaştırılır, böylece sol alt düğümün (3) sağ çocuğu olur.
   -                7
                   / \
                  5   8
                 / \   \
                1   3   9
               /   / \
              0   4   6
              
10.Onuncu öğe olan 2'yi daha küçük olan kök düğümle karşılaştırın, böylece sağ alt düğümün (4) sol çocuğu olur.
   -                7
                   / \
                  5   8
                 / \   \
                1   3   9
               /   / \
              0   4   6
                 /
                2
                

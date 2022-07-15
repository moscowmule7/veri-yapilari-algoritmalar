Proje 3
1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. 
root: 7
                        7
                    /       \

5 sayısı 7den küçük olduğu için soluna ekliyoruz.
                        7
                    /       \
                   5
1 sayısı 7 ve 5ten küçük olduğu için soluna ekliyoruz.
                        7
                    /       \
                   5
                  /
                 1
8 sayısı 7den büyük olduğu için 7 nin sağına ekliyoruz.
                       7
                    /       \
                   5         8
                  /
                 1
3 sayısı 7 ve 5ten küçük, 1den büyük olduğu için 1in sağına ekliyoruz
                        7
                    /       \
                   5         8
                  /
                 1
                  \
                   3
6 sayısı 7den küçük 5ten büyük olduğu için 7nin soluna 5in sağına ekliyoruz
                        7
                    /       \
                   5         8
                  / \
                 1   6
                  \
                   3
0 sayısı 7, 5 ve 1den küçük olduğu için 1in soluna ekliyoruz
                        7
                    /       \
                   5         8
                  / \
                 1   6
                / \
               0   3
9 sayısı 7 ve 8den büyük olduğu için 8in sağına ekliyoruz
                        7
                    /       \
                   5         8
                  / \         \
                 1   6         9
                / \
               0   3
4 sayısı 7den ve 5ten küçük olduğu için 5in soluna, 1den ve 3ten büyük olduğu için 3ün sağına ekliyoruz
                        7
                    /       \
                   5         8
                  / \         \
                 1   6         9
                / \
               0   3
                    \
                     4
2 sayısı 7 ve 5ten küçük olduğu için 5'in soluna, 1den büyük olduğu için 1in sağına, 3ten küçük olduğu için 3ün soluna ekliyoruz.
                        7
                    /       \
                   5         8
                  / \         \
                 1   6         9
                / \
               0   3
                  / \
                 2   4

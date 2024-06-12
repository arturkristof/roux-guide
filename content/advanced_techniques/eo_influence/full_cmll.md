+++
title = 'Pełny CMLL'
date = 2024-06-10T22:54:00+02:00
+++

Znajdziesz tutaj x algorytmów CMLL. Zbierałem algorytmy dla każdego przypadku z założeniami minimum:

- 1 algorytm niezamieniający orientacji krawędzi
- 2 algorytmy zmieniające orientację dwóch krawędzi obok siebie, tak żeby zaliczyć wszystkie możliwe kombinacje 2a z
  możliwym krótkim setupem. Do tych algorytmów zaliczają się też przypadki z jedną krawędzią na U i jedną na D
- 1 algorytm zmieniający orientację dwóch krawędzi na przeciwko siebie
- 1 algorytm zmieniający orientację wszystkich krawędzi na U

## Pi

### Columns

|                 Przypadek                 |                 Algorytm                 |                 Przypadek                 |              Algorytm               |
|:-----------------------------------------:|:----------------------------------------:|:-----------------------------------------:|:-----------------------------------:|
|        ![0](/cmll/full/pi/5/0.png)        |    (U2) r' F R F' r U' R' U' R U' R'     | ![2 - UL DF](/cmll/full/pi/5/2-UL-DF.png) |  (U') r U' r2' D' r U r' D r2 U r'  |
| ![2 - UL UB](/cmll/full/pi/5/2-UL-UB.png) |   (U2) R' U R U' R2' F R2 U R' U' F' R   | ![2 - UF UR](/cmll/full/pi/5/2-UF-UR.png) | F R U R' U' R2 D R' U R D' R2 U' F' |
| ![2 - UF UB](/cmll/full/pi/5/2-UF-UB.png) | (U') R U' R' F' U' F U2 R U R' U' R U R' |     ![4 - U](/cmll/full/pi/5/4-U.png)     |  (U') R U' R2 D' r U r' D R2 U R'   |

### Left Bar

|                 Przypadek                 |                    Algorytm                    |                 Przypadek                 |                 Algorytm                  |
|:-----------------------------------------:|:----------------------------------------------:|:-----------------------------------------:|:-----------------------------------------:|
|        ![0](/cmll/full/pi/6/0.png)        | (U) R U2 R' U' F' R U2 R' U' R U' R' F R U' R' | ![2 - UF UB](/cmll/full/pi/6/2-UF-UB.png) |     (U') R' U' R' F R F' R U' R' U2 R     |
| ![2 - UL UR](/cmll/full/pi/6/2-UL-UR.png) |            R' F' U' F U' R U R' U R            | ![2 - UF UR](/cmll/full/pi/6/2-UF-UR.png) | (U') R U R' U R' F R F' R U' R' U R U2 R' |
| ![2 - UR UB](/cmll/full/pi/6/2-UR-UB.png) |      (U) F U R U' R' F' R U R' U R U2 R'       | ![2 - UF UL](/cmll/full/pi/6/2-UF-UL.png) |    (U) R' U2 R U R' U R F R U R' U' F'    |
| ![2 - UL UB](/cmll/full/pi/6/2-UL-UB.png) |     (U') R U2 R' U' R U' R' F R U R' U' F'     |     ![4 - U](/cmll/full/pi/6/4-U.png)     |       r' D R2 U R' U2 R U' R2 D' r        |

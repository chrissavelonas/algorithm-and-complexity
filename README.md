## algorithm-and-complexity

### περιγραφή προβλήματος 
#### Το πρόβλημα του χρωματισμού γραφήματος είναι ένα NP-hard πρόβλημα συνδυαστικής βελτιστοποίησης. Αφορά την ανάθεση ενός χρώματος σε κάθε κορυφή ενός γραφήματος έτσι ώστε γειτονικές κορυφές να χρωματίζονται με διαφορετικό χρώμα, ενώ παράλληλα χρησιμοποιείται ο ελάχιστος αριθμός διαφορετικών χρωμάτων. Στην παρούσα εργασία ζητείται η υλοποίηση τεσσάρων αλγορίθμων χρωματισμού γραφημάτων και η εφαρμογή τους σε γνωστά προβλήματα από τη βιβλιογραφία

## πλήρης κώδικα της εφαρμογής [src](https://github.com/chrissavelonas/algorithm-and-complexity/tree/main/src)

#### O First Fit (άπληστος αλγόριθμος) ειναι υλοποιημένος [εδω](https://github.com/chrissavelonas/algorithm-and-complexity/blob/b03c549d994550f650c61053139cbc08d099fc49/src/GraphColoring.cpp#L130) 

#### O αλγόριθμος Degree of Saturation (DSatur) ειναι υλοποιημένος [εδω](https://github.com/chrissavelonas/algorithm-and-complexity/blob/b03c549d994550f650c61053139cbc08d099fc49/src/GraphColoring.cpp#L178)

## Οδηγίες εγκατάστασης


#### Για την εκτέλεση του κώδικα θα χρειαστεί να εγκαταστήσετε το  [Visual Studio Code](https://code.visualstudio.com/download) στον υπολογιστή σας

#### Για να μπορέσετε να το κάνετε compile θα πρέπει να κατεβάσετε το πρόγραμμα  [tdm-gcc](https://sourceforge.net/projects/tdm-gcc/)

#### Για να μπορέσετε να κατεβάσετε τον κώδικα από τι GitHub θα πρέπει να κατεβάσετε το  [Git](https://git-scm.com/)



## Οδηγίες εκτέλεσης

#### Πρώτα θα ανοίξετε ένα CMD στον υπολογιστή σας και θα ορίσετε που θέλετε να κατεβεί(clone) το project

#### Εφόσον το κατεβάσουμε μπαίνουμε μέσα στον φάκελο src μέσω του CMD

#### Πληκτρολογούμε  την εντολή `g++ main.cpp GraphColoring.cpp Vertex.cpp -o play-std=c++17 -Wall`

#### Αν το compile έγινε επιτυχώς πληκτρολογούμε στην συνέχεια την εντολή `play`



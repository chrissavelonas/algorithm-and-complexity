# algorithm-and-complexity

## περιγραφή προβλήματος 
Το πρόβλημα του χρωματισμού γραφήματος είναι ένα NP-hard πρόβλημα συνδυαστικής βελτιστοποίησης. Αφορά την ανάθεση ενός χρώματος σε κάθε κορυφή ενός γραφήματος έτσι ώστε γειτονικές κορυφές να χρωματίζονται με διαφορετικό χρώμα, ενώ παράλληλα χρησιμοποιείται ο ελάχιστος αριθμός διαφορετικών χρωμάτων. Στην παρούσα εργασία ζητείται η υλοποίηση τεσσάρων αλγορίθμων χρωματισμού γραφημάτων και η εφαρμογή τους σε γνωστά προβλήματα από τη βιβλιογραφία

## πλήρης κώδικα της εφαρμογής

ο πλήρης κωδικας της εφαρμογής βρίσκεται [src](https://github.com/chrissavelonas/algorithm-and-complexity/tree/main/src)

το first fit θα το βρειτε [εδω](https://github.com/chrissavelonas/algorithm-and-complexity/blob/b03c549d994550f650c61053139cbc08d099fc49/src/GraphColoring.cpp#L130) 

το dsatur θα το βρειτε [εδω](https://github.com/chrissavelonas/algorithm-and-complexity/blob/b03c549d994550f650c61053139cbc08d099fc49/src/GraphColoring.cpp#L178)

## Οδηγίες εγκατάστασης

εγκατάσταση του [git](https://git-scm.com/)

εγκατάσταση του [compiler](https://sourceforge.net/projects/tdm-gcc/)

εγκατάσταση του [Visual Studio Code](https://code.visualstudio.com/download) 

εγκατάσταση τον κατάλληλων extension για το Visual Studio Code πχ. c/c++ της microsoft 

## Οδηγίες εκτέλεσης

κάνουμε clone το repository απο το github 

ανοίγουμε το cmd και κάνουμε `cd` στο src του απο το αρχείο που μόλις κατεβάσαμε 

τρέχουμε την εντολή `g++ main.cpp GraphColoring.cpp Vertex.cpp -o main -std=c++17 -Wall`

τρέχουμε την εντολή `main`

και επιλέγουμε με την εντολή `1` ή `2` ποια ενέργια θέλουμε να κάνουμε 

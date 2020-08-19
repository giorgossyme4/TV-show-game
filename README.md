ΕΙΣΑΓΩΓΗ ΣΤΗΝ ΕΠΙΣΤΗΜΗ ΥΠΟΛΟΓΙΣΤΩΝ / Python

Εκφώνηση Εργασίας : 

Στα πλαίσια της εργασίας θα πρέπει να υλοποιήσετε ένα παιχνίδι γνώσεων μεταξύ 3 παιχτών.

Στο παιχνίδι αυτό, 3 παίχτες θα διαγωνίζονται μεταξύ τους για το ποιος θα απαντήσει σωστά περισσότερες ερωτήσεις γνώσεων. Ο κάθε παίχτης καλείται να απαντήσει σε 10 ερωτήσεις γνώσεων, επιλέγοντας κάθε φορά τη σωστή απάντηση από 4 δοσμένες απαντήσεις. Οι ερωτήσεις εμφανίζονται μία-μία σε όλους τους παίχτες με τη σειρά. Ο κάθε παίχτης έχει στη διάρκεια του 2 βοήθειες. Η μία βοήθεια είναι το «50-50», με την οποία αντί για 4 επιλογές απάντησης, δίνονται μόνο 2 στον παίχτη. Η άλλη βοήθεια είναι το «skip this question», με την οποία ο παίχτης ζητάει να αποφύγει αυτή την ερώτηση και να αντικατασταθεί από κάποια άλλη ερώτηση (άρα θα πρέπει το set των ερωτήσεών σας να περιλαμβάνει παραπάνω από 10 ερωτήσεις). Όταν οι απαντήσεις εμφανίζονταιστον κάθε παίχτη, εφόσον δεν έχει χρησιμοποιήσει ακόμα τη μία ή και τις δύο βοήθειες, του εμφανίζεται η επιλογή για χρήση της διαθέσιμης βοήθειας. Στην περίπτωση που έχει χρησιμοποιήσει τις βοήθειες, δεν εμφανίζεται η επιλογή αυτή. Αν επιλέξει τη βοήθεια «50-50», θα πρέπει να του εμφανίζεται η ίδια ερώτηση αλλά με δύο μόνο απαντήσεις. Αν επιλέξει τη βοήθεια «skip this question», θα πρέπει να του εμφανίζει μία νέα ερώτηση και να μην του εμφανίσει στη συνέχεια πάλι την ερώτηση που έκανε skipped. Οι παίχτες απαντούν την ίδια ερώτηση ο ένας μετά τον άλλο. Το παιχνίδι θα κρατάει το σκορ κάθε παίχτη με το όνομά του και στο τέλος θα εμφανίζει την κατάταξη των παιχτών και ποιος είναι ο νικητής του παιχνιδιού.

Πιο αναλυτικά, για το παιχνίδι κα πρέπει να υλοποιηθούν τα ακόλουθα:

  1. Εκκίνηση : Όταν ξεκινάει το παιχνίδι, εμφανίζεται εισαγωγικό μήνυμα που αναγράφει τις οδηγίεσ του παιχνιδιού και έπειτα, ρωτάει ποια είναι τα ονόματα (ένα-ένα) των παιχτών       που θα συμμετάσχουν στο παιχνίδι. Οι παίχτες θα παίζουν με τη σειρά που θα δώσουν τα ονόματα.
  2. Εμφάνιση ερώτησης : Θα πρέπει να έχετε δημιουργήσει ένα σύνολο ερωτήσεων γνώσεων (τουλάχιστον 11), οι οποίες θα αφορούν κάποια γνωστική περιοχή, την οποία κα επιλέξετε          εσείς. Η κάθε ερώτηση εμφανίζεται με τη σειρά και στους 3 παίχτες μέχρι να τελειώσουν οι 10 ερωτήσεις. Για κάθε ερώτηση, το πρόγραμμα θα πρέπει να εμφανίζει στον παίχτή 4        απαντήσεις από τις οποίες η μία θα είναι η σωστή. Επίσης, θα του εμφανίζει 1, 2 ή καμία βοήθεια (ο παίχτης μπορεί να χρησιμοποιήσει μία φορά μόνο την κάθε βοήθεια), ανάλογα      με το αν υπάρχουν οι διαθέσιμες βοήθειες για τον συγκεκριμένο παίχτη.
        - Αν ο παίχτης επιλέξει τη βοήθεια «50-50», το παιχνίδι θα του εμφανίζει την ίδια ερώτηση με 2 απαντήσεις αντί για 4.
        - Αν ο παίχτης επιλέξει τη βοήθεια «skip this question», το παιχνίδι κα του εμφανίζει μία νέα ερώτηση και την ερώτηση που έγινε skipped δεν θα την εμφανίσει ξανά στον             παίχτη αυτόν.
        
Όταν ο παίχτης απαντήσει, θα πρέπει να του εμφανίζει αν απάντησε σωστά ή λάθος. Η διαδικασία αυτή επαναλαμβάνεται και για τους 3 παίχτες. Ο κάθε παίχτης μπορεί να πάρει ανεξάρτητα από τους υπόλοιπους τη βοήθεια που επιθυμεί.

  3. Βαθμολογία : Το παιχνίδι τηρεί σκορ για τον κάθε παίχτη. Κάθε φορά που βρίσκει τη σωστή απάντηση, του δίνει 10 πόντους, δηλαδή, αν ο παίχτθσ απαντήσει και τις 10 ερωτήεις       σωστά, τότε θα κάνει high score 100. Όταν ο παίχτης δε χρησιμοποιήσει καμία βοήθεια, προστίθενται στη βαθμολογία του 10 πόντοι (5 για κάθε βοήθεια που δεν έχει                   χρησιμοποιήσει). Όταν δε χρησιμοποιήσει τη μία από τις δύο βοήθειες, κα προστίθενται στη βαθμολογία του 5 πόντοι.
  4. Τερματισμός παιχνιδιού : Όταν όλοι οι παίχτες ολοκλθρώσουν με τις ερωτήσεις, το παιχνίδι θα ανακοινώνει τον νικητή και θα εμφανίζει την κατάταξη των παιχτών με βάση τη        βαθμολογία τους.
  
Υπόδειξη : Για την υλοποίηση του παιχνιδιού θα μπορούσατε να ορίσετε μία κλάςη player, instances της οποίας θα είναι οι παίχτες.

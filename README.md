# DistributedSystems
University housing application management system.

Το πανεπιστήμιο διαθέτει φοιτητικές εστίες χωρητικότητας 200 θέσεων. 5 διοικητικοί υπάλληλοι (ο ένας από αυτούς είναι ο προϊστάμενος) διαχειρίζονται τις αιτήσεις στέγασης των φοιτητών.
Για κάθε νεοεισαχθέντα φοιτητή ένας υπάλληλος που είναι υπεύθυνος για το τμήμα του φοιτητή φροντίζει ώστε να δημιουργηθεί η καρτέλα του φοιτητή με τα βασικά του στοιχεία. Στη συνέχεια αφού τη δημιουργήσει, ο φοιτητής θα μπορεί να κάνει αίτηση στέγασης.
Τα κριτήρια στέγασης είναι τα εξής:
	οικονομικά
	οικογενειακά
	εντοπιότητας
Κάθε χρόνο υπάρχει συγκεκριμένο όριο φοιτητών ανά τμήμα οι οποίοι μπορούν να έχουν δωρεάν στέγαση, που προκύπτει από τη διαθεσιμότητα των θέσεων στην εστία. Ο προϊστάμενος είναι υπεύθυνος να το ενημερώνει πριν ξεκινήσουν οι αιτήσεις των φοιτητών. Σε αυτό το σύστημα οι υπάλληλοι βλέπουν τα δικαιολογητικά κάθε φοιτητή και εγκρίνουν ή απορρίπτουν κατ’ αρχάς μια αίτηση. Εφόσον εγκριθεί η αίτηση θα πρέπει σύμφωνα με έναν αλγόριθμο να λάβει μια βαθμολογία η οποία θα κρίνει τελικά την κατάταξη του φοιτητή.  Ο αλγόριθμος είναι ο εξής:

	Αν ο φοιτητής έχει μηδενικό εισόδημα και οι 2 γονείς είναι άνεργοι, τότε δικαιούται δωρεάν στέγαση σε κάθε περίπτωση
	Αν το οικογενειακό εισόδημα είναι < 10000 ευρώ παίρνει 100 πόντους, από 10.000-15.00 παίρνει 30 πόντους και πάνω από 15.000 δεν παίρνει πόντους
	Αν έχει αδέρφια που σπουδάζουν παίρνει 20 πόντους ανα αδερφό
	Αν είναι από διαφορετική πόλη από την πόλη που φοιτά, παίρνει 50 πόντους
	Αν ένας φοιτητής ξεπεράσει το 4ο έτος αυτόματα τίθεται εκτός εστίας ώστε να μπορούν νέοι φοιτητές να ωφεληθούν.
	
Επίσης, 100 φοιτητές ανά έτος μπορούν να λάβουν επίδομα στέγασης της τάξεως των 200 ευρώ μηνιαίως και θα είναι οι 100 πρώτοι στην κατάταξη που δεν έλαβαν δωρεάν στέγαση.
Κάθε χρόνο επανεξετάζονται όλοι οι φοιτητές που ήδη έχουν δικαίωμα στέγασης και κατατάσσονται ξανά.
Εξωτερικό Σύστημα.

Στο site της εφαρμογής μπορεί να μπαίνει ο φοιτητής και να έχει τη δυνατότητα να κάνει την αίτησή του και επίσης να βλέπει την κατάταξή του (μόνο τη δική του) και αν τελικά δικαιούται δωρεάν στέγαση ή όχι, Επίσης θα μπορεί να αλλάζει τα στοιχεία επικοινωνίας του.






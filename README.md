# Laborator02

Ex8:

\\ buton HOME (aplicatia este deschisa, dupa care se redeschide)
onCreate() -
onRestart() - 3
onStart() - 4
onResume() - 5
onPause() - 1
onStop() - 2
onDestroy() -

\\ buton Back (aplicatia este deschisa, dupa care se redeschide)
onCreate() - 4
onRestart() -
onStart() - 5
onResume() - 6
onPause() - 1
onStop() - 2
onDestroy() - 3

\\ buton OK din aplicatie (aplicatia este deschisa)
nu se apeleaza nimic, se afiseaza mesaj in ecranul principal
aplicatia este in executie, acesta este motivul
onCreate() -
onRestart() -
onStart() -
onResume() -
onPause() -
onStop() -

\\ rotire ecran (aplicatia este deschisa)
indiferent de rotire (portret - peisaj; peisaj - portret)
onCreate() - 4
onRestart() -
onStart() - 5
onResume() - 6
onPause() - 1
onStop() - 2
onDestroy() - 3

Ex9:

Dispar, nu mai sunt retinute. Elementele grafice nu sunt restaurate.

Ex11:

Nu sunt diferente de implementare, insa am observat:

-> daca metoda de restaurare este transferata pe metoda onCreate:
cand este bifat checkbox-ul remember => elemente grafice restaurate la apelarea
metodei onCreate() - spre exemplu rotire ecran

-> daca metoda de restaurare este separata:
cand este bifat checkbox-ul remember => elementele grafice restaurate automat
intre metodele onStart() si onResume() - teoretic, insa practic nu am vazut
diferenta.


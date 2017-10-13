# Pitanje 1:
Stvorila se .dll datoteka.  
Bez .dll datoteke nakon pokretanja program se ruši jer ne može naći dependency.  
Za rad programa potreban je svaki library koji se korisi u programu tako da pri slanju programa treba poslati i to. U ovom slučaju, program.exe i library.dll.  

# Pitanje 2:
Pojavila se stara poruka jer kako novi library nije buildan, program koristi stari library sa starim stringom.  
U slučaju da se library builda, program će ispisati novi string.  

# Pitanje 3:
Tijekom build procesa zbog postavke koja dozvoljava NuGet-u da skine pakete koji nedostaju, NuGet je skinuo NodeTime paket.  
Packages direktorij sada opet sadrži NoteTime.  


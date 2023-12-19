# Αρχική Εφαρμογή
https://github.com/HackYourWayHackathon/Airometer

Νομίζω είχα δεί κάτι παρόμοιες εικόνες από την παρουσίαση ενός απο τα άλλα δυο group. Απλά δεν αναφέρθηκε στην παρουσίαση πως είχαν βρεί την εφαρμογή στο github. Δεν θυμάμαι όμως και πολύ καλά.

# Forked εφαρμογή:
https://github.com/std133524/Airometer-new/

Τα screenshots είναι απο την εφαρμογή που τρέχει στο κινητό τηλέφωνο. Η εφαρμογή δεν έχει πολλές δυνατότητες. Απλά βρίσκεις την πόλη και σoυ δείχνει το AQI. Το έκανα για 3-4 πόλεις.

Η εφαρμογή έγινε compiled τελικά σε έναν καινούργιο υπολογιστή με αρκετή μνήμη, με api key από το https://openweathermap.org/. (https://openweathermap.org/api/one-call-3). 

Έβαλα το δικό μου api από το openweathermap.org αφού γράφτηκα με το email του eap.

Το openweatherapi, δωρεάν, σε αφήνει για 1000 κλήσεις την μέρα. Είναι αρκετό. Επίσης σου δίνει και data καιρού και AQI.

Εδώ είναι το api key: https://github.com/std133524/Airometer-new/blob/master/lib/api/api_key.dart

Στο https://github.com/std133524/Airometer-new/tree/master/screenshots υπάρχει και το apk για εγκατάσταση στο κινητό.

1. Πρώτα εγκαθιστούμε το android studio με το flutter plugin. 
2. Έπειτα εγκαθισμούμε το flutter όπως δείχνουν οι οδηγίες εδώ https://docs.flutter.dev/get-started/install/windows και τρέχουμε το flutter doctor
3. Ακολουθούμε τις οδηγίες για να τρέξουμε την εφαρμογή στο Readme https://github.com/HackYourWayHackathon/Airometer
   flutter pub get
   flutter run

# Άλλη παρόμοια εφαρμογή flutter εφαρμογή που δείχνει τον καιρό
https://github.com/indratrisnar/weather_app_challenge



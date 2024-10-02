Ajtós játék leírás:
- 3 ajtó van megjelenítve, meg kell találni, melyik mögött van az AUTÓ kattintással (többi mögött kecske van)
- ekkor kinyílik a maradék 2 ajtó közül az, amelyik BIZTOSAN NEM rejti az autót
- ez után el kell dönteni azt, hogy emellett a döntés mellett maradunk-e, vagy inkább cserélünk egy másik ajtóra
- ha cserélünk, akkor azt az ajtót kell kinyitni, amelyikre inkább tippelünk, hogy ott van az autó
- megkapjuk eredményül, hogy ott van-e az autó vagy nincs
- 3 dolgot látunk, ami számlálódik: mennyit találtunk el cserével; mennyit találtunk el elsőre

Egyéb info:
- ajtók tartalma minden körben random
- számolni kell a találatokat, a két féle korábban említett módon
- miután cserével vagy anélkül a user eltalálja, hozzáadódik a számlálóhoz, és kiíródik a megfelelő helyre ez a szám az ablakon
- ezután kezdődik újra, anélkül, hogy bezáródna a játék
- akármennyit lehet vele játszani, a számláló mindíg számol és kiír
- új játékot is tud választani

Terv ötlet:
- az ajtóra rákattint a user, ekkor megjelenik a textfieldben a szöveg arról, hogy szeretne -e cserélni vagy sem
- eddig a gombokat nem tudta nyomogatni, de ezután tudja
- gombnyomásnak megfelelően történnek az események a korábbiakban említettek szerint
- ezután, ennek megfelelően szöveges uzenetben megjelenik a textfieldben, hogy eltalálta-e vagy sem (és a már benne lévő üzenet kitörlődik), és valamelyik számláló növekszik
- a számlálást mindíg a "lblCsvelSzamlalo" és a "lblCsNSzamlalo" label területre írja ki és frissíti
- ((nem tudom hogyan lehetne kinyitni az ajtót, talán elég oda kiírni valami textfieldbe rá hogy "ITT NINCS AUTO" vagy "ITT KECSKE VAN" vagy csak szimplán eltűnik az ajtó vagy ilyesmi ))
- előbbi helyett jobb ötlet: csak kiíródik a text fielbe hogy a jobb vagy bal vagy középső ajtó ami kinyitódott meg üres

<img width="387" alt="image" src="https://github.com/user-attachments/assets/46cd60b4-052d-4a79-897d-e84d45e6a761">

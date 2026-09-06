[🇵🇱 Powrót do wyboru języka](./README.md)
#  【Czym jest Utaun?】  
To oprogramowanie dla systemu Windows, które generuje banki głosów CV dla UTAU przy użyciu czysto nieożywionej syntezy addtywnej.  
Automatycznie tworzy plik ZIP z bankiem głosów w folderze Dokumenty.  

#  【Cechy】   
 ・Po uruchomieniu automatycznie generuje ZIP z bankiem głosów w Dokumentach  
 ・Generowanie samogłosek (a, i, u, e, o, n) za pomocą czysto nieożywionej syntezy addtywnej  
 ・Tworzenie banków głosów CV poprzez połączenie z zewnętrznymi rzędami spółgłosek (rzędy od ka do pa)  
 ・Wewnętrzne generowanie rzędów m / n / y / w  
 ・Obsługa aliasów w hiraganie + angielskich aliasów Romaji (wszystkie wymowy są po japońsku)  
 ・Automatyczne generowanie plików oto.ini / character.txt / readme.txt  
 ・Możliwość konwersji obrazów PNG do formatu JPG  
 ・Pliki readme.txt i character.txt są zapisywane w kodowaniu Shift_JIS (ANSI), aby zapobiec problemom z kodowaniem  
 ・Możliwość zmiany częstotliwości podstawowej (wysokości głosu)  
 ・Swobodne ustawianie nazwy banku głosów (nazwy postaci)  

#  【Przewidywane zastosowanie】  
 ・Kiedy chcesz stworzyć bank głosów UTAU o nieożywionym brzmieniu  
 ・Tworzenie banków głosów dla osób, które nie lubią nagrywać własnego głosu  
 ・Badania nad materiałami syntezy addtywnej mowy  
 ・Prototypowanie własnych banków głosów  
 ・Rozpakowanie pliku ZIP i bezpośrednie użycie jako materiału do ludzkiego Vocaloida (Jinkiri-VOCALOID)  
 ・Zastosowanie jako materiał do OtoMADów, YTPMV itp.  

#  【Jak używać Utaun】  
 ① Pobierz plik `Utaun.ver-1.0.3.zip`. (Pobierz z zakładki Releases.)  
 ② Rozpakuj plik `Utaun.ver-1.0.3.zip`.  
 ③ Umieść `Utaun.exe` w dowolnym folderze (zalecany Pulpit).  
 ④ Uruchom `Utaun.exe` i postępuj zgodnie z instrukcjami na ekranie.  
 ⑤ Gdy pojawi się komunikat „（音源名）.zip がドキュメントに出来上がったよ！”, bank głosów UTAU jest gotowy.  

**Obraz interfejsu (UI)**
 ![Test Image 3](IMG_4239.jpeg)

#  【Jak używać wygenerowanego banku głosów UTAU】  
 ・UTAU  
   Rozpakowanie wygenerowanego pliku ZIP odsłania folder banku głosów, który można bezpośrednio wczytać do programu UTAU.  
 ・OpenUTAU  
   Można wczytać bezpośrednio w formacie ZIP (bez potrzeby rozpakowywania).  
 ※ Szczegółowe instrukcje użytkowania w poszczególnych programach można znaleźć w ich plikach pomocy, podręcznikach i oficjalnej dokumentacji.  

#  【Wymagania systemowe】  
 ・Windows 10–11 (64-bit)  
 ・Windows 10–11 (32-bit)  

**【Nieobsługiwane funkcje】**  
 ・Samogłoski dźwięczne z dakuten (あ゙・い゙・ゔ・え゙・お゙)  
 ・Wariacje ekspresyjne, takie jak szepty, oddechy, komponenty oddechowe itp.  
 ・Zgłoski zmiękczone / kontrakcje (kya, kyu, kyo / sha, shu, sho itp.)  
 ・VCV (Dźwięki ciągłe)  
 ・CVVC  
 ・Inne specjalne wymowy  

#  【Warunki korzystania】  
W przypadku samej aplikacji Utaun (`Utaun.exe`) zabronione są następujące czynności:  
 ・Przetwarzanie / przerabianie  
 ・Edycja  
 ・Modyfikacja  
 ・Użytek komercyjna  
 ・Ponowna dystrybucja  
 ・Dekompilacja (rozbieranie na części pierwsze)  

#  【O wygenerowanych materiałach】  
(Banki głosów, pliki wav, icon.jpg, oto.ini itp.)  
Warunki korzystania możesz ustalić Ty (dystrybutor) w sposób dowolny.  
Wpisz preferowane zasady w pliku `readme.txt`.  
Informacje o aktualizacjach znajdziesz w sekcji Releases.  

Releases
https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇵🇱


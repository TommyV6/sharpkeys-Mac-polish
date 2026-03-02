## Opis projektu Sharpkey-mac-polish
Zmodyfikowana wersja projektu sharpkeys-mac tak aby dało się podmienić klawisze command i option na klawiaturach Logitech MX Keys for Mac (może być MX Keys S) pozwala to normalnie pisać po polsku. Fabrycznie system Windows 11 interpretuje klawisze Command jako Windows a Option jak Alt czyli dokładnie odwrotnie do tego co jesteśmy przyzwyczajeni. 

Pozwoliłem sobie dodać skompliowaną wersje dla leniwych, wystarczy rozpakować odpalić, załadowac plik konfiguracyjny i zapisać do rejestru, program po tym zabiegu można usunąć. Działa globalnie.

Domyślny program sharpkeys nie może mapować klawiszy na klawiaturach "for Mac" dopiero zmodyfikowana wersji Sharpkeys-mac to potrafi. Ma to wyglądać tak:
<img width="736" height="543" alt="sharpkeys-mac-on-windows" src="https://github.com/user-attachments/assets/43c82e2e-3c31-467e-af5b-1cc8ff420ab3" />
Nie trzeba tego wpisywać ręcznie w pliku z skompilowanym programe jest plik: <a href="https://github.com/TommyV6/sharpkeys-Mac-polish/blob/master/Swap_Command_and_Option_for_Windows.skl">Swap_Command_and_Option_for_Windows.skl</a> który można po prostu załadować i gotowe!

Nie jestem autorem programu sharpkeys ani jego modyfikacji sharpkeys-mac, dodałem tylko to co potrzebne dla polsków i skompilowałem wersję programu, bo autor oryginały sharpkeys-mac tego nie zrobił. 

UWAGA! Oryginalna wersja programu sharpkeys nie potrafi podmienić klawisza "Option" - nie rozpoznaje go trzeba używać sharpkeys-mac.

## Original Project Description
SharpKeys is a utility that manages a Registry key that allows Windows to remap one key to any other key. Included in the application is a list of common keyboard keys and a Type Key feature to automatically recognize most keyboard keys. It was originally developed in C# using .NET v2 but has been updated to support .NET 4.0 Client Profile

Please see the OG project page for more info and buy him a beer  https://github.com/randyrants/sharpkeys


after you applay the spaciel keys:
"E0_1F38" "Mac: Options left"
or
"E0_2038" "Mac: Options right"
and map them to windows key 
apply close the app , and check that it says like the image and restart the machine 

<img width="729" height="415" alt="image" src="https://github.com/user-attachments/assets/f31a9b04-1807-449c-bcdd-5387be9b4f5f" />


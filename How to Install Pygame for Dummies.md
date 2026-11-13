Scroll down to line 42 for english...

Dansk:

Trin 1: Download den seneste opdatering af Python. Det gør du ved at hente installationsfilen fra deres officielle hjemmeside eller fra Microsoft Store. Derefter:

. Kør den .exe-fil, du har downloadet.

. Følg installationsvejledningen og start installationen (**HUSK AT MARKERE "Add Python to PATH" under opsætningen!**)

. Du kan kontrollere, om installationen er lykkedes, ved at åbne "cmd" og skrive "python --version". Hvis den viser den version af Python, du har installeret, er alt udført korrekt.



Trin 2: Download Pygame. Åbn din terminal (f.eks. PowerShell på Windows eller igen "cmd") og skriv:

. Til Windows: "py -m pip install pygame-ce"

. Til macOS og Linux: "python3 -m pip install pygame-ce"

(pygame-ce er en fællesskabsdrevet videreudvikling – et såkaldt "fork" – af Pygame, som er mere opdateret.)



Du kan teste installationen ved at køre et eksempelspil i terminalen:

Windows: "py -m pygame.examples.aliens"

macOS og Linux: "python3 -m pygame.examples.aliens"



Trin 3: Tilføj Python-udvidelsen til VSCode. Det er ganske enkelt: Åbn VSCode og klik på fanen for udvidelser (extensions) i venstre side. Søg efter "python" i søgefeltet (det er ofte ikke engang nødvendigt, da Python som regel ligger øverst blandt de anbefalede udvidelser), og installér den.

Så er du færdig! Nu skal du blot oprette en fil med endelsen ".py" og skrive din kode. Koden bør altid starte med "import pygame". Når du har skrevet det, kan du teste, om alt fungerer korrekt, ved at trykke på "Play"-knappen øverst til højre i VSCode. Terminalen, der åbner, bør vise den aktuelle version af Pygame. (Det er helt normalt, at der ikke åbner et spilvindue, da du endnu ikke har skrevet nogen kode). Hvis du får en fejlmeddelelse, er der opstået et problem med importen. En mulig årsag kan være, at udvidelsen bruger en anden Python-version end den, du havde installeret, før du fulgte denne guide. Du kan skifte din interpreter ved at trykke på Ctrl+Shift+P (brug Cmd i stedet for Ctrl på Mac og Linux) og skrive "Python: Select Interpreter" i søgefeltet øverst. Vælg derefter den specifikke version af Python, som du har installeret Pygame i.






English:

step 1: Download the latest update of python. To do this you need to download the installer from their official page or the Microsoft store. Then:

. Run the .exe file you have downloaded

. Follow the installer and begin the installation (**REMEMBER TO CHECK "Add Python to PATH" during setup!**)

. You can check if it was installed correctly by opening "cmd" and typing "python --version". If it shows you the version of python you have installed, then you have done it correctly.



step 2: Downloading Pygame. Open your terminal (fx. PowerShell for windows or cmd again) and type:

. for Windows "py -m pip install pygame-ce"

. for macOS and Linux "python3 -m pip install pygame-ce"

(pygame-ce is a community managed fork of pygame, it is more up to date.)



you can test the installation by running an example game in the terminal:

Windows: "py -m pygame.examples.aliens"

macOS and Linux "python3 -m pygame.examples.aliens"



step 3: adding the python extension to your VSCode. It is as simple as that. Open VSCode and press the extensions tap on the left. Search "python" on the search bar (you might not have to even do that, Python is usally at the top of the recomended extensions) and install it.

With that, you are all done! all you have to do now is make a ".py" file and write your code. This always starts with "import pygame". After you write it, you can test if everything is functioning correctly by pressing the Play button at the top right of VSCode. The terminal that opens should give you the current pygame verion. (it is normal that nothing opens, since you wouldn't have written any code yet) If you are getting an error by doing this, there must have been a problem with the import. One reason for this could be that the extension is using a different version of Python you had already installed before this guide to interpret the code. You can change your interpeter by pressin Ctrl+Shift+P (Cmd instead of Ctrl for mac and linux) and type "Python: Select Interpreter" in the search bar at the top. Then select the specific version of Python that you installed Pygame to.



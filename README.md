# U02-bash-project
Syftet med denna uppgift är dels att bekanta dig med teorin i kursen, samt öva på praktiska färdigheter i Linux. Uppgiften har två delar:

Redogörelse (Teoretisk del) - Här skriver du en redogörelse som tar upp det grundläggande kring kunskapsmålen i kursen.

i allmän felsökning och åtgärd.
i lagring på Linux och Unix servrar.
i hantering av rättigheter i Linux/Unix.
om konfiguration och administration av Linuxsystem samt dess distributioner
om grundläggande nätverksteknik, bl. a. OSI-modellen, VLAN
arkivering och backup på Linux/Unix servrar
Dokumentation (Praktisk del) - I denna del installerar du Ubuntu Server 20.04 LTS på en virtuell maskin på din dator, t.ex med Virtualbox, VMWare, UTM. Arbetet ska dokumenteras med hjälp av en komplett logg där både prompt och kommando framgår. Använd med fördel Markdown som formatering på dokumentationen, för att sedan konvertera markdown till pdf med hjälp av https://www.markdowntopdf.com/ (Länkar till en externa sida.). Ett smidigt sätt att vara säker på att få med all input och output från alla steg är med kommandot script (Länkar till en externa sida.).

För att rensa bort färger och annan formatering från output från script (kräver ansi2txt installerat, samt utgår ifrån att filen heter typescript):

cat typescript | ansi2txt | col -b >> typescript_clean
Efter detta ligger rensad logg i filen typescript_clean i samma mapp som du körde ovanstående kommando från.
Viktiga saker att tänka på:

Installera serverversionen av Ubuntu. Alla uppdateringar och konfigurationer måste ske via terminalen och dokumenteras
Det är OK att klippa delar av texten i dokumentationen, t.ex output från apt update
(VG) Skriv ett script för att konfigurera git från VM, det ska gå att pusha från VM, använd en fejkad Personal Access Token i dokumentationen
Glöm inte att ta med scriptets innehåll i dokumentationen, cat myscript.sh
(VG) Sätt upp en post-receive hook med hjälp av git


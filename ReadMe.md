# Anabell und Linda lernen C

## Vorwort

Ich versuche euch alles so einfach wie möglich beizubringen - sowohl die Inhalte der Vorlesung, wenn ihr dazu Fragen habt als auch ein paar nütsliche Tipps, Tricks und Tools, die dafür sorgen, dass ihr ein wenige effizienter arbeiten könnt.

## Vorbereitung

1. Installiert [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
2. Erstellt euch einen [GitHub](<[Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)>) Account
3. Ich lade euch dann in eine [gemeinsame Organisation](https://github.com/linda-und-anabell-lernen-c/) ein
4. Lest [diesen Artikel](https://www.atlassian.com/de/git) und [diesen Artikel](https://code.visualstudio.com/docs/sourcecontrol/overview) oder last euch von mir erklären was Git und GitHub ist
5. Installiert [VSCode](https://code.visualstudio.com/download)
6. Installiert folgende VSCode Erweiterungen: [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools), [C/C++ Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack) & [C/C++ Themes](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-themes)
7. Optional, aber Empfohlen sind folgende VSCode Erweiterungen: [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) & [ToDo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
8. (NUR LINDA) Ich empfehle dir, dir eine Virtual Machine (Also einen Computer in deinem Computer) mit einer Linux Version zu installieren, im Gegensatz zu Windows basieren MacOS und Linux nämlich auf Unix und euer Professor/Übungsleiter in der Uni legt den Großteil seiner Vorschläge und Anweisungen darauf aus - mit gutem Grund, es ist einfach besser. Um also 1:1 machen zu können was Anabell macht und euren Instruktoren (also eurem Prof und mir) folgen zu können wäre das sehr clever, Ich helfe dir dabei sehr gerne.

## Ablauf

Jede Woche werden wir ähnlich handhaben, der grobe Ablauf ist für euch aber immer der selbe. Unser Git-Repositories werden immer mit `uebung_XX` benannt sein. Nachdem Ich eure Aufgabenblätter erhalten habe werde ich immer das entsprechende Repository Anlegen und einen `start` branch erstellen - Ihr müsst also nur das Repository Klonen und euren eigenen Branch erstellen - keine Sorge, für die erste Woche machen wir das gemeinsam. Ihr könnt hierfür entweder die Funktionen in VSCode benutzen oder die Command Line

```bash
# Klonen des Repositories
git clone https://github.com/linda-und-anabell-lerenen-c/uebung_XX.git
# In den neuen Ordner navigieren
cd uebung_XX
# euren Branch erstellen NAME sollte hier durch euren namen erstezt werden
git checkout -b name start
```

So habt ihr die Möglichkeit schon während der Woche an euren Aufgaben zu arbeitend und Ich habe bereits die Gelegenheit dazu mich euren Fragen und ergebnissen zu widmen. Damit das effizient funktioniert würde Ich euch bitten immer dann, wennn Ihr einen Aufgabenteil fertig habt diesen hochzuladen. Hierzu könnt ihr wieder die Funktionen in VSCode verwenden oder die Command Line - WICHTIG: Stellt sicher, dass ihr wirklich auf eurem branch arbeitet

```bash
# "Speichern" der Änderungen
git add -A
# "Bschreiben und Sperren" der Änderungen - TEXT sollte mit eurem Kommentar erstzt werden
git commit -m "TEXT"
# Hochladen der Änderung - NAME sollte durch den Namen eures Branches ersetzt werden
git push origin NAME
```

Beim Treffen am Ende jeder Woche werden wir dann gemeinsam nocheinmal eure Aufgaben durchgehen und uns meine Musterlösung anschauen - Meine Musterlösungen dienen nicht dazu blind von euch kopiert zu werden, deshalb bekommt ihr die erst dann. Häufig werde Ich diese nutzen um euch Konzepte und Tricks zu zeigen, die viele Aufgaben für euch einfacher machen werden.

## Abgabe

In den meisten Fällen entspricht die Struktur unserer Repositories der, die für die Abgabe verlangt ist - wenn ihr auf eurem branch seit könnt ihr den Ordner also einfach hochladen. Ich fände es trotzdem gut, wenn wir am ende jeder unserer Sessions gemeinsam eure Abgaben machen um sicherzustellen, dass auch wirklich alles funktioniert.

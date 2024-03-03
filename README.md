# Šablona používající Maven pro předmět BPOG1

Veškeré soubory pro Maven projekt s fungujícím nastavením FXML je uložen ve složce Bpog1MavenTemplate. Pro další práci nezapomeňte napřed projekt přejmenovat.

Při další práci nezapomeňte, že je narozdíl od Ant ptořeba držet všechny .fxml soubory v resources složce a všechny .java soubory v Source Packages (složka java). Je lepší držet stejnou strukturu package jak ve složce java, tak ve složce resources, protože to ulehčí napojování FXML na jejich řadiče.

V případě problémů založte issue, aby se případné chyby opravily.


## Důležité pro úspěšné spuštění

Projekt v NetBeans vždy spouštějte přes zelené tlačítko nahoře (Run Project, nebo klávesa `F6`). Při pokusu o spuštění Run File (`Shift`+`F6`) se NetBeans nepodaří nalézt runtime knihovny a build selže.

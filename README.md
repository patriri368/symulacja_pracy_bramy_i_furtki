# Symulacja działania bramy i furtki w zakładzie przemysłowym

Furtka służy jako wejście do zakładu przemysłowego dla pracowników. Aby ją otworzyć należy nacisnąć przycisk. Bramka otwiera się z opóźnieniem 10s. Obok furtki jest zamontowany czujnik informujący o jej aktualnej pozycji. Zamknięcie furtki odbywa się poprzez mechanizm dopychający. 

Obok furtki znajduje się brama służącu do wjazdu pojazdów dostawczych. Jest otwierana każdego dnia co godzinę. Zamykanie odbywa się za pomocą przycisku. O każdej porze dnia może zostać zrealizowane otwarcie bramy, w tym celu dozorca musi przytrzymać przycisk aktuwujący otwieranie bramy przez 10s. Za pomocą pozostawienia tego przycisku w pozycji 1 dozorca może również aktywować otwieranie bramy w trakcie dnia. Dezaktywacja otwierania bramy jest realizowana poprzez przełączenie przycisku do pozycji 0. Pozycja bramy jest wykrywana przez czujniki znajdujące się w skrajnych pozycjach. 

Zadanie zostało zrealizowana z wykorzystaniem przerwań Time of day oraz Time delay interrupt. 

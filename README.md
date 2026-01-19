# modelowanie-systemow
plugin do kolaboracji - https://github.com/archimatetool/archi-modelrepository-plugin2 (nie wiem czy jest potrzebny ale wygląda spoko)

Do bpmn użyłem narazie bpmn.io

Diagramy DPD robiłem w draw.io, polecam tam kliknąć "Więcej kształtów" -> "Data Flow Diagram" 

[19.01.2025 -- Maciek] Tutaj są takie moje notatki, co według mnie jeszcze trzeba poprawić (dogadamy się jak to podzielić):
- opis firmy: dopisać interesariuszy i ich zadania, wykorzystywane dane, jakoś ładnie sformatować, zaktualizować opis systemu, żeby uwzględniał m.in. rolę admina, możliwość monitorowania przez dyrektora, usunąć rzeczy których nie ma na diagramach (np. sprawdzanie, czy wykonawca wcześniej współpracował z firmą)
- wykres w Archimate: połączyć te warstwy biznesowe, rozbudować tą żółtą warstwę (np. o możliwość monitorowania przez dyrektora), wskazać jaki komponent (niebieski) wykonuje jaki proces (żółty), połączyć aktorów z interfejsem aplikacji(?), dopisać zmianę statusu umowy
- BPMN: sprawdzić błędy w Camunda Modelerze (można też w przeglądarce - modeler.camunda.io), każdy "pool" powinien mieć zakończenie, z procesu "Szukanie nowych inwestycji" wyciągnąć podproces "na główny plan" i zrobić osobne tory dla modelu LLM i API Google Maps, usunąć 2 początki
- DPD: w przepływie (na strzałkach) powinny być tylko dane (a nie procesy np. aktualizacja), na strzałce tylko 1 typ danych (bez slasha - rozbić na dwie strzałki), w lewym górnym rogu zrobić notatkę jaki to diagram, usunąć "czarne dziury" - procesy bez wyjścia, może dopisać poziomy aby były same działania proste?
- VP: diagram wymagań - dodać zdjęcie typowego raportu, może interfejsu w Sharepoint?

Do dopytania na zajęciach: czy trzeba zrobić diagram generowania wartości (e3 Value), Textual Analysis; w jakim formacie trzeba oddać projekt?
P.S.: Na komputerach uczelnianych jest stara wersja VP i nie da się tak normalnie otworzyć naszego projektu - podobno działa jeśli się wyeksportuje jako XML

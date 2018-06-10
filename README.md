# Analiza i modelowanie sterowanych amortyzatorów hydraulicznych

## Cel i zakres pracy

Celem pracy jest wykonanie skryptów do automatyzacji analizy danych pomiarowych. Dane pomiarowe zapisywane są w plikach _*.tdms_.
Badania przeprowadzone zostały w laboratorium "Układów i Struktur Dynamicznych" w KAP.  
Skrypty umożliwiają określenie charakterystyk:
1. Statycznych
2. Dynamicznych

Drugim etapem pracy jest zamodelowanie testowanych układów oraz przeprowadzenie symulacji.

## Model ćwiartkowy zawieszenia pojazdu kołowego

![](./Python/Cwiartkowy_model.png)&nbsp;

Na powyższym rysunku przedstawiony został model obliczeniowy ćwiartkowego, pasywnego układu zawieszenia pojazdu kołowego. Przyjęto oznaczenia:

![](./Python/img/Cwiartkowy_model_rownania.png)&nbsp;

## Charakterystyki statyczne

### Wykres siły od przemieszczenia

![](./Python/img/sila_od_przemieszczenia.PNG)&nbsp;

### Wykres pracy od częstotliwości wymuszczenia

![](./Python/img/praca.PNG)&nbsp;

### Wykres siły od prędkości

![](./Python/img/sila_od_predkosci.PNG)&nbsp;

### Aproksymacja siły od prędkości

![](./Python/img/sila_od_predkosci_aproksymacja.PNG)&nbsp;

## Charakterystyki dynamiczne

### Funkcje przenoszenia drgań

![](./Python/img/funkcje_przenoszenia_drgan.PNG)&nbsp;

### Przemieszczeniowa funkcja przenoszenia drgań masy wibroizolowanej 

![](./Python/img/Fzs.PNG)&nbsp;
![](./Python/img/Fzs_wykres.PNG)&nbsp;

### Przyspieszeniowa funkcja przenoszenia drgań masy wibroizolowanej 

![](./Python/img/Fzbiss.PNG)&nbsp;
![](./Python/img/Fzbiss_wykres.PNG)&nbsp;

### Przemieszczeniowa funkcja przenoszenia drgań masy niewibroizolowanej 

![](./Python/img/Fzw.PNG)&nbsp;
![](./Python/img/Fzw_wykres.PNG)&nbsp;

### Funkcja przenoszenia drgań ugięcia zawieszenia 

![](./Python/img/Fzszw.PNG)&nbsp;
![](./Python/img/Fzszw_wykres.PNG)&nbsp;

### Funkcja przenoszenia drgań ugięcia opony

![](./Python/img/Fzww.PNG)&nbsp;
![](./Python/img/Fzww_wykres.PNG)&nbsp;
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

![](./Python/img/sila_od_przemieszczenia.png)&nbsp;

### Wykres pracy od częstotliwości wymuszczenia

![](./Python/img/praca.png)&nbsp;

### Wykres siły od prędkości

![](./Python/img/sila_od_predkosci.png)&nbsp;

### Aproksymacja siły od prędkości

![](./Python/img/sila_od_predkosci_aproksymacja.png)&nbsp;

## Charakterystyki dynamiczne

### Funkcje przenoszenia drgań

![](./Python/img/funkcje_przenoszenia_drgan.png)&nbsp;

### Przemieszczeniowa funkcja przenoszenia drgań masy wibroizolowanej 

![](./Python/img/Fzs.png)&nbsp;
![](./Python/img/Fzs_wykres.png)&nbsp;

### Przyspieszeniowa funkcja przenoszenia drgań masy wibroizolowanej 

![](./Python/img/Fzbiss.png)&nbsp;
![](./Python/img/Fzbiss_wykres.png)&nbsp;

### Przemieszczeniowa funkcja przenoszenia drgań masy niewibroizolowanej 

![](./Python/img/Fzw.png)&nbsp;
![](./Python/img/Fzw_wykres.png)&nbsp;

### Funkcja przenoszenia drgań ugięcia zawieszenia 

![](./Python/img/Fzszw.png)&nbsp;
![](./Python/img/Fzszw_wykres.png)&nbsp;

### Funkcja przenoszenia drgań ugięcia opony

![](./Python/img/Fzww.png)&nbsp;
![](./Python/img/Fzww_wykres.png)&nbsp;
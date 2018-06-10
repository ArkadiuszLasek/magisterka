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

- $m_s - $ masa wibroizolowana
- $m_t - $ masa niewibroizolowana
- $z_s - $ przemieszczenie masy wibroizolowanej
- $z_t - $ przemieszczenie masy niewibroizolowanej
- $z_w - $ wymuszenie
- $k_s - $ współczynnik sprężystości zawieszenia
- $k_t - $ współczynnik sprężystości opony
- $c_s - $ nieliniowy element tłumiący zawieszenia
- $c_t - $ współczynnik tłumienia opony

Równania równowagi sił dla każdej z mas:
$$
\begin{equation}
m_t\ddot{z}_t + F_c(\dot{z}_t - \dot{z}_s) + k_s(z_t - z_s) + c_t(\dot{z}_t - \dot{z}_w) + k_t(z_t - z_w) = 0 \\
m_s\ddot{z}_s + F_c(\dot{z}_s - \dot{z}_t) + k_s(z_s - z_t) = 0
\end{equation}
$$

 
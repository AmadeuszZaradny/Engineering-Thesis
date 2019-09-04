# Wstęp

  Na przestrzeni ostatnich kilkunastu lat sposób zdobywania informacji diametralnie się zmienił. Jeszcze niedawno, aby dowiedzieć się czegoś na temat aktualnych wydarzeń na świecie, człowiek musiał włączyć telewizor bądź radio. Natomiast gdy chciał zgłębić je jeszcze bardziej, zmuszony był do sięgnięcia po prasę. Poza tym informacje, które ludzie otrzymywali były wybierane przez osoby zarządzajace danym źródłem, co bardzo ograniczało odbiorcę. Miało to miejsce, ponieważ tematyka niekoniecznie mogła mu odpowiadać. Wiedzę naukową zdobywało się w szkołach, na uczelniach lub po prostu z odpowiedniej literatury. Jednak wraz z powstaniem internetu i jego bardzo intensywnym rozwojem, poprzednie wzorce straciły swą popularność na rzecz olbrzymiej masy informacji, którą można w nim znaleźć.

  W dzisiejszych czasach, gdy człowiek pragnie dowiedzieć się czegoś na nurtujący go temat wystarczy, że wpisze go do wyszukiwarki internetowej. Od razu po tym otrzyma listę dokumentów, artykułów, prac naukowych, bądz po prostu luźnych dywagacji użytkowników na forach internetowcyh. Dzięki temu użytkowicy sami mogą decydować, jaka informacja ich interesuje i kto jej dostarczy. Często też nowe wiadomości ze świata są przekazywane w reklamach, przez innych użytkowników lub po prostu znajomych, którzy chcą się podzielić tym, co ich interesuje. Jednak najbardziej znacząca zaleta internetu, mianowicie jego dostępność zarówno dla odbiorców i twórców, stała się jego największym problemem. Natomiast ilość nierzetelnych informacji, nieopierających się na żadnych badanich ani faktach, ogarnęła świat. Jednocześnie wprowadzając w błąd ludzi niebędących w stanie zweryfikować wiarygodności danego źródła. 

### Fake News

> **Fake news'em** nazywamy każdy fałszywy artykuł lub informację rozpowszechnianą w mediach, bez względu na intencję jej powstania.
  
  Intencjonalność jest bardzo istotna w tej defincji, ponieważ fałszywą infromację może tworzyć i rozpowszechniać każdy. Może dokonać tego w pełni świadomy człowiek, bądź instytucja ze ściśle wytyczonym celem. Jednak może być to również nic nie podejrzewający czytelnik, chcący podzielić się świeżo zdobytą przez siebie wiedzą, która wydaję mu się prawdziwa. W związku z tym należy się zastanowić, dlaczego ludzie świadomie preparują informacje. Najpopularniejszym powodem jest chęć uzyskania pewnych wymiernych zysków np.: 
 
 - zwiększenie popularności portalu internetowego skutkujące wzrostem dochodów,
 - odwrócenie uwagi od niewygodnych faktów.
  
  Jednak oczywiście nie jest to jedyny powód, gdyż fake news'y powstają również przez:
 
 - złośliwość (np. oczernienie człowieka),
 - chęć tworzenia zamentu dla rozrywki,
 - chęć manipulowania opinią.
 
  Szczególnie ten ostatni podpunkt spowodował bardzo duże zainteresowanie tematem fake news'ów w ostatnich latach. Podczas wyborów prezydenckich w Stanach Zjednoczonych w 2016 roku w internecie pojawiła się znaczna ilość nieprawdziwych artykułów na temat głównych kandydatów. Artykuły te były proponowane ludziom o takich poglądach potlitycznych, żeby zmaksymalizować prawdopodobieństwo przyjęcia tych informacji za stan faktyczny. Skala tych działań była duża do tego stopnia, że uważa się, że mogły one zadecydować o finalnym wyniku wyborów najpotężniejszego kraju na świecie. 
  
  Znaczny wpływ na tworzenie i rozpowszechnianie fałszywych informacji ma również ludzka ignorancja. Brak oczytania w danym temacie, naiwność, a także chęć wiary w zgodne z własnymi poglądami pogłoski, często powodują brak akceptacji merytorycznych argumentów i odrzucanie faktów. Takie wewnętrzne wyparcie prawdy może skutować powstaniem całkowicie nieracjonalnych nurtów i teorii spiskowych, takich jak np.: ruch antyszczepionkowy, czy wiara w "płaską Ziemię". Niefortunne w tym przypadku jest również to, że osoby rozpowszechniające takie wiadomości robią to z większą częstotliwością niż wiarygodne źródła. Skutkuje to tym, że ilość fałszywych informacji w danym temacie może być znacznie wieksza niż tych prawdziwych. W takim zbiorze danych łatwiej jest natrafić na mylące artykuły, co powoduje potencjalnie większą liczbę ich odbiorców.

### Wykrywanie i łagodznie

  Wraz z nasilającymi się wpływami fałszywych informacji na sytuację na świecie, powstała potrzeba ich wykrywania i łagodzenia negatywnych skutków, jakie wywołują. Istnieją różne podejścia do filtrowania fake new'sów. Jednym z podstawowych sposobów są metody manualne, to znaczy oparte na weryfikacji ludzkiej. Powstały strony internetowe takie jak *www.politifact.com*, które oferują sprawdzanie wiarygodności artykułów. Dzięki pracy profesjonalistów otrzymana informacja zwrotna jest wysoce konstruktywna. Jednak człowiek nie jest tak wydajny jak komputer i często na wynik takiej weryfikacji trzeba czekać stosunkowo długo. Tu z pomocną dłonią przychodzą prężnie rozwijające się nauki informatyczne, którę potrafią zautomatyzować i znacznie przyspieszyć weryfikację wiarygodności dokumentów, tym samym oferując wysokie prawdopodobieństwo poprawnego werdyktu. 
  Jednym z automatycznych podejść jest algorytm PageRank, bazujący na analizie źródła, z jakiego pochodzą wiadomości. Algorytm wykorzystuje powiązania między stronami internetowymi, dzięki którym można zbadać ich jakość (np. Informacje podane na stronach zaufanych, takich jak rządowe i uniwersyteckie, będą uważane za prawdziwe. Strony, którę są często linkowane przez zaufane portale, również będą ocenione jako źródło wysokiej jakości). Do automatyzacji doskonale nadają się również metody oparte na analizie treści dokumentów. Można obliczyć podobieństwo między jednym artykułem, a innym wcześniej już zweryfikowanym i na podstawie tego dokonać oceny wiarygodności.


# Cel pracy

  Celem pracy jest zaprojektowanie i wykonanie mikroserwisu internetowego, będącego w stanie weryfikować wiarygodność wysłanych przez użytkownika artykułów informacyjnych. Usługa będzie w stanie opdowiedzieć, czy weryfikowany dokument posiada informacje wiarygodne, czy też nie. Wykorzystana do tego zostanie sieć neuronowa, wyszkolona z użyciem odpowiedniego zbioru danych.

  ** *TODO: Opis rozdziałów po ich napisaniu* ** 

# Wprowadzenie teorytyczne oraz zagadnienia
  
  **Analiza lingwistyczna** jest jednym z podejść, które cechują się dużą skutecznością przy wykrywaniu fake news'ów. Dzięki niej można wychwycić styl, w jakim dany dokument został napisany, wagę konkretnych słów oraz całych stwierdzeń w nim użytych, lub inne informacje charakteryzujące go na podstawie języka, z jakim został stworzony. Analiza lingwistyczna nie skupia się na tym, jaka wiadomość zostaje przekazywana do odbiorcy, lecz w jaki sposób jest do niego kierowana. Okazuję się, że jest to bardzo istotna wiedza, gdyż znaczna część fałszywych artykułów powstaje w całkiem podobnym stylu. Charakteryzują się one mocnym nacechowaniem emocjonalnym, starającym się spowodować, aby temat wywołał u odbiorcy efekt zaangażowania, przez co będzie on bardziej podatny na uznanie artykułu za prawdziwy. Krzykliwy styl, odciągający czytelnika od braku argumentów merytorycznych, jest łatwy do wykrycia. Wynika to z tego, że częstotliwość silnie nacechowanych przymiotników występująch w takim tekście będzie dużo większa niż w dokumencie zachowującym merytoryczność. Kolejnym aspektem, który sprawia, że analiza ta jest bardzo użyteczna, jest fakt, że dane powstałe przy jej stosowaniu są idealne do wykorzystania podczas nauczania maszynowego z użyciem sieci neuronowych. Z kolei to pozwala na automatyzację procedury wykrywania fake news'ów. 

### Sieci neuronowe

** *TODO: Dokładne wprowadzenie gdy będą już znane komponenty* **

> **Sztuczna sieć neuronowa** to składająca się z elementów przetwarzających struktura matematyczna inspirowana biologiczną siecią neuronową występującą w mózgu. Model ten jest w stanie przetwarzać sygnały lub prowadzić obliczenia. Sztuczne sieci neuronowe są w stanie "uczyć się" wykonywania zadań poprzez analizę dawanych im podczas procedury nauczania przykładów (np.: rozpoznawanie twarzy na zdjęciach).

  Model ten bardzo dobrze nadaję się do weryfikowania fałszywych artykułów. Jego zadaniem byłoby wówczas znalezienie zależności, wpływających na to, że dany dokument posiada nieprawdziwe wiadomości. Do tego potrzebny jest odpowiedny zbiór danych, zapewniający wystarczającą ilość próbek szkoleniowych. Dane te powinny być przygotowane tak, aby jak najbardziej ułatwić sieci znalezienie szukanych relacji (ze względu na "naturę" sieci neuronowych najlepiej przedstawiać dane w formie sygnału).

### Perceptron

> **Perceptronem** nazywamy najprostszą sieć neuronową, która jest algorytmem dla nauczania nadzorowanego z rodzaju klasyfikatorów binarnych. Oznacza to, że potrafi on ocenić, czy wejście w postaci wektora należy do jakiejś specyficznej klasy, czy też nie (np.: odróżnienie liczb parzystych od nieparzystych).

> **Neuron McCullocha-Pittsa** (Rysunek 1.1) to jeden z matematycznych modeli sztucznego neuronu. Posiada on jedno wyjście,  natomiast wiele wejść. Do każdego wejścia jest przypisana jego waga, czyli liczba rzeczywista. Na wyjściu podawana jest wartość funkcji aktywacji dla sumy ważonej wejść.

![Neuron McCullocha-Pittsa](https://upload.wikimedia.org/wikipedia/commons/2/24/Neuron_McCullocha-Pittsa.svg) 
**Rysunek 1.1** - Perceptron składający się z jednego neuronu McCullocha-Pittsa
 
> **Funkcja aktywacji** to fukcja definiująca wyjście w sieci neuronowej, może to być np. sigmoida (Rysunek 1.2).

![Sigmoida](https://upload.wikimedia.org/wikipedia/commons/8/88/Logistic-curve.svg) 
**Rysunek 1.2** - Sigmoida

### Podobne rozwiązania

  Istnieje wiele rozwiązań wykrywania fake news'ów bazujących na analizie lingiwstycznej oraz nauczaniu maszynowym. Jednak, szczególnie w kontekście założeń pracy, warto przytoczyć wykonane przez Aarona Edella API (*z ang. Application Programming Interface*), pozwalające na wysyłanie zapytań o weryfikację artykułu. Projekt nazywa się "Fakebox" i oferuje skuteczność na poziomie 95%. Jest to bardzo wysoki wynik uzyskany dzięki połączeniu kilku metod. Aaron postanowił badać nie tylko treść artykułów, ale również ich tytuł oraz URL (*z ang. Uniform Resource Locator*), czyli źródło. Unikatowe w podejściu twórcy jest także to, że nie skupia się on, de facto, na detekcji fałszywych informacji, ale na znajdowaniu tych prawdziwych. Dopiero dopełnienie ich zbioru jest uznawane za nieprawdziwe. Okazało się, że dzięki takiemu rozwiązaniu wykrywalność wrosła z 70% do wcześniej wspomnianych 95%.
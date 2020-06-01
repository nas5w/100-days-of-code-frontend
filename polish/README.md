<p align="center">
  <img alt="#100DaysOfCode Front-End Development" src="https://i.imgur.com/dwYOP0B.jpg" />
</p>

---

Chcesz dowiedzieć się więcej o programowaniu frontend? Rozważ zapisanie się na mój [bezpłatny biuletyn](https://buttondown.email/devtuts), gdzie okresowo wysyłam przystępnie opisane teksty o frontendzie!

---

Jest to nieco opiniotwórczy program do nauki programowania front-end podczas #100DaysOfCode. Ponieważ obejmuje szeroki zakres tematów związanych z programowaniem front-end, można go traktować bardziej jako kurs typu "przegląd", niż głębokie zanurzenie w jednym obszarze. Idealnym rozwiązaniem na ukończenie tego programu będzie znajomość każdego tematu i możliwość łatwego nurkowania głębiej w dowolnym obszarze w przyszłości, jeśli zajdzie taka potrzeba.

Na ten program nauczania znaczący wpływ miał artykuł Kamrana Ahmed'sa o tytule [Modern Frontend Developer](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c). Sprawdź to sam - jest doskonały.

**Uwaga**: Wiem, że programowanie frontendu oznacza wiele różnych rzeczy dla wielu ludzi! Jeśli jesteś programistą typu frontend i uważasz, że ten przewodnik można ulepszyć, daj mi znać, tworząc issue zgodnie z opisem w sekcji [Współtworzenie](#współtworzenie). Dziękuję!

# Tłumaczenia

Dzięki niesamowitym współtwórcom program ten został przetłumaczony na następujące języki!

- [Rosyjski русский](/ru) (tłumaczenie od [@Ibochkarev](https://github.com/Ibochkarev) i [@JonikUl](https://github.com/JonikUl))
- [Chiński 中文](/chinese) (tłumaczenie od [@simplefeel](https://github.com/simplefeel))
- [Portugalski Português](/portuguese) (tłumaczenie od [@Zardosh](https://github.com/Zardosh))
- [Polski Polish](/polish) (tłumaczenie od [@mbiesiad](https://github.com/mbiesiad))

# :calendar: Program

Podstawową zasadą tego repozytorium jest [timeboxing](https://en.wikipedia.org/wiki/Timeboxing). Jeśli spędziłeś w przeszłości jak najwięcej czasu, próbując nauczyć się tworzenia stron internetowych lub podobnych umiejętności, prawdopodobnie doświadczyłeś zejścia do króliczej nory na dowolny konkretny temat. To repozytorium ma na celu przypisanie określonej liczby dni do każdej technologii i zachęca do przejścia do następnej, gdy ta liczba dni minie.

Oczekuje się, że wszyscy są na innym poziomie biegłości podczas rozpoczynania tego wyzwania, i to jest w porządku. Zarówno początkujący, jak i doświadczeni programiści mogą korzystać z praktyki timeboxingu w każdym z tych obszarów.

Zalecane codzienne czynności są następujące:

- Dni 1-8: [HTML](#html)
- Dni 9-16: [CSS](#css)
- Dni 17-24: [Podstawy JavaScript](#javascript)
- Dni 25-27: [jQuery](#jquery)
- Dni 28-33: [Responsive Web Design](#rwd)
- Dni 34-36: [Dostępność](#dostępność)
- Dni 37-39: [Git](#git)
- Dni 40-44: [Node i NPM](#node)
- Dni 45-50: [Sass](#sass)
- Dni 51-54: [Bootstrap](#bootstrap)
- Dzień 55: [BEM](#bem)
- Dni 57-61: [Gulp](#gulp)
- Dni 62-65: [Webpack](#webpack)
- Dzień 66: [ESLint](#eslint)
- Dni 68-83: [React](#react)
- Dni 84-89: [Redux](#redux)
- Dni 90-94: [Jest](#jest)
- Dni 95-97: [TypeScript](#typescript)
- Dni 98-100: [NextJS](#nextjs)

# :mag_right: Szczegóły

Poniżej znajdziesz trochę informacji na temat każdego tematu w programie nauczania, a także kilka pomysłów/wskazówek, co zrobić dla każdego z nich. Inspiracje do projektów realizowanych zgodnie z tym programem nauczania można znaleźć w sekcji [Pomysły na projekty](#pomysły-na-projekty).

W ramach zasady timeboxingu, jest w porządku jeśli nie przejdziesz wszystkich elementów w sekcjach "Obszary nauki i pomysły". Zamiast tego powinieneś skupić się na jak największej liczbie dni przypisanych do każdego obszaru, a następnie przejść dalej.

<a name="html"></a>
![HTML](https://i.imgur.com/O0F5XSR.jpg)

Hypertext Markup Language (HTML) to język znaczników do tworzenia stron internetowych i aplikacji internetowych. Dzięki kaskadowym arkuszom stylów (CSS) i JavaScript tworzy triadę podstawowych technologii dla sieci WWW. Przeglądarki internetowe odbierają dokumenty HTML z serwera WWW lub z lokalnej pamięci i renderują je na multimedialne strony internetowe. HTML opisuje semantycznie strukturę strony internetowej i początkowo zawierał wskazówki dotyczące wyglądu dokumentu. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/HTML))

### :bulb: Szybkie podsumowanie

HTML jest naprawdę podstawą do tworzenia stron internetowych. Nawet we frameworkach opartych na Javascript kończy się w pisaniu HTML, w takiej czy innej formie.

### :book: Obszary nauki i pomysły

- Przejdź do sekcji [Podstawowy HTML i HTML5](https://learn.freecodecamp.org/) na stronie freeCodeCamp.
- Struktura strony HTML
- Elementy HTML
- Zagnieżdżanie elementów HTML
- Znaczniki semantyczne
- Linki / wiele stron
- Obrazy
- Media audio/wideo
- Formy i elementy formularzy
- Utwórz witrynę wielostronicową! (Zobacz [Pomysły na projekty](#pomysły-na-projekty) jeśli potrzebujesz nieco inspiracji).

<a name="css"></a>
![CSS](https://i.imgur.com/028GOR0.jpg)

Kaskadowe arkusze stylów (CSS) to język arkuszy stylów używany do opisywania prezentacji dokumentu napisanego w języku znaczników, takim jak HTML. CSS to podstawowa technologia World Wide Web, obok HTML i JavaScript. CSS został zaprojektowany w celu umożliwienia oddzielenia prezentacji i treści, w tym układu, kolorów i czcionek. Ta separacja może poprawić dostępność treści, zapewnić większą elastyczność i kontrolę w specyfikacji cech prezentacji, umożliwić wielu stronom internetowym współdzielenie formatowania poprzez określenie odpowiedniego CSS w osobnym pliku .css, a także zmniejszyć złożoność i powtarzalność treści strukturalnych. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets))

### :bulb: Szybkie podsumowanie

CSS jest kolejnym istotnym elementem tworzenia stron internetowych. Chociaż jest używany głównie do stylizacji i pozycjonowania elementów HTML, staje się coraz bardziej zdolny do wykonywania bardziej dynamicznych zadań (np. animacji), które kiedyś byłyby obsługiwane przez Javascript.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcje [Podstawy CSS, CSS flexbox, oraz CSS grid](https://learn.freecodecamp.org/) na freeCodeCamp.
- In-line CSS
- `<style>` tagi
- Zewnętrzny CSS z `<link>`
- Stylizowanie elementów
- Selektory
- Floaty, czyszczenie floatów
- Layouty (grid, flexbox)
- Czcionki, niestandardowe czcionki
- Stylowanie stron(y) HTML, którą stworzyłeś podczas nauki HTML!

<a name="javascript"></a>
![JavaScript](https://i.imgur.com/oHdD86j.jpg)

JavaScript, często skracany do JS, jest interpretowanym językiem programowania wysokiego poziomu, który jest zgodny ze specyfikacją ECMAScript. Jest to język, który jest również charakteryzowany jako dynamiczny, słabo typowany, oparty na prototypach i oparty na wielu paradygmatach. Oprócz HTML i CSS, JavaScript jest jedną z trzech podstawowych technologii w sieci WWW. JavaScript włącza interaktywne strony internetowe i dlatego jest istotną częścią aplikacji internetowych. Zdecydowana większość stron internetowych z niego korzysta, a wszystkie główne przeglądarki internetowe mają dedykowany silnik JavaScript do jego wykonania. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/JavaScript))

### :bulb: Szybkie podsumowanie

JavaScript zyskuje na znaczeniu w świecie front-end. Chociaż kiedyś był używany głównie do nadawania dynamiki stronom, obecnie stanowi podstawę wielu frameworków. Frameworki te obsługują wiele zadań, które wcześniej były obsługiwane przez backend (np. routing i wyświetlanie różnych widoków).

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcje [Basic JavaScript and ES6](https://learn.freecodecamp.org/) na freeCodeCamp.
- Zbyt wiele podstaw z języka, aby wymienić tutaj!
- `<script>` tag i rozmieszczanie
- Dostęp do elementów HTML
- Pętla zdarzeń, stos wywołań i kolejka zdarzeń
- Dziedziczenie prototypowe
- Reference vs. value
- Dodaj dynamiczne elementy lub logikę do stron HTML / CSS opracowanych wcześniej!

<a name="jquery"></a>
![jQuery](https://i.imgur.com/m9j02Fo.jpg)

jQuery to szybka, mała i bogata w funkcje biblioteka JavaScript. Ułatwia ona przechodzenie i manipulowanie dokumentami HTML, obsługę zdarzeń, animację i Ajax dzięki łatwemu w obsłudze interfejsowi API, który działa w wielu przeglądarkach. Dzięki połączeniu wszechstronności i rozszerzalności, jQuery zmieniło sposób, w jaki miliony ludzi piszą JavaScript. (Źródło: [jQuery.com](https://jquery.com/))

### :bulb: Szybkie podsumowanie

Po spędzeniu czasu z prostym (zwanym też "vanilla") Javascriptem, niektóre zadania mogą być nieco uciążliwe, szczególnie związane z dostępem do elementów HTML i manipulowaniem nimi. Przez długi czas jQuery była biblioteką, w której zadania tego typu były łatwiejsze i spójniejsze w różnych przeglądarkach. W dzisiejszych czasach jQuery niekoniecznie trzeba się uczyć "obowiązkowo" ze względu na postępy w 'prostym' Javascript, CSS i nowszych frameworkach Javascript (przyjrzymy się frameworkom później). Mimo to dobrze byłoby poświęcić trochę czasu na poznanie jQuery i zastosowanie go w małym projekcie.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [jQuery](https://learn.freecodecamp.org/) na freeCodeCamp.
- Gotowy dokument
- Selektory
- Toggle classes
- Animacje
- Dodaj lub przenieś elementy HTML
- Dodaj jQuery do swojej witryny!

<a name="rwd"></a>
![Responsive Web Design](https://i.imgur.com/Bt1zWwq.jpg)

Responsive web design (RWD) to podejście do projektowania stron internetowych, które sprawia, że strony internetowe dobrze renderują się na różnych urządzeniach i rozmiarach okna lub ekranu. Ostatnie prace traktują także bliskość widza jako część kontekstu oglądania, jako rozszerzenie RWD. Treść, konstrukcja i wydajność są niezbędne na wszystkich urządzeniach, aby zapewnić użyteczność i satysfakcję. Strona zaprojektowana przy użyciu RWD dostosowuje układ do środowiska oglądania, używając płynnych, proporcjonalnych siatek, elastycznych obrazów i zapytań o media CSS3, co stanowi rozszerzenie reguły @media. (Źródło:[Wikipedia](https://en.wikipedia.org/wiki/Responsive_web_design))

### :bulb: Szybkie podsumowanie

Elastyczne projektowanie stron internetowych polega na tym, aby aplikacje internetowe wyglądały i działały prawidłowo we wszystkich rodzajach urządzeń. Tanim i tandetnym przykładem może być to, że witryna powinna wyglądać i działać poprawnie zarówno w przeglądarce internetowej na komputerze, jak i przeglądarce telefonu komórkowego. Zrozumienie responsywnego projektowania jest kluczowe dla każdego programisty front-end!

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [Responsive Web Design Principles](https://learn.freecodecamp.org/) na freeCodeCamp.
- Zapytania o media, punkty przerwania
- Responsywne obrazy
- Spraw, aby Twoja witryna była responsywna!
- Użyj Chrome DevTools, aby wyświetlić swoją witrynę na różnych urządzeniach / oknach podglądu.

<a name="accessibility"></a>
![Accessibility](https://i.imgur.com/ayioMQw.jpg)

Dostępność WWW to powszechna praktyka polegająca na zapewnieniu, że nie ma barier uniemożliwiających osobom niepełnosprawnym interakcję lub ogólnie dostęp do stron internetowych. Gdy witryny są prawidłowo zaprojektowane, opracowane i edytowane, ogólnie wszyscy użytkownicy mają równy dostęp do informacji i funkcjonalności. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility))

### :bulb: Szybkie podsumowanie

Dostępność, często zapisywana jako a11y, jest jednym z najważniejszych tematów w tworzeniu stron internetowych, ale często wydaje się, że jest ona krótka. Tworzenie dostępnych aplikacji internetowych jest nie tylko etycznie uzasadnione, ale ma również sens z biznesowego punktu widzenia, biorąc pod uwagę dodatkową grupę odbiorców, którzy będą mogli przeglądać twoje aplikacje, gdy będą szeroko dostępne.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [Applied Accessibility](https://learn.freecodecamp.org/) na freeCodeCamp.
- Przeczytaj treść na [The A11Y Project](https://a11yproject.com/about)
- Przejrzyj ich [listę kontrolną](https://a11yproject.com/checklist)
- Zaktualizuj swoje witryny w celu uzyskania ułatwień dostępu na podstawie tej listy kontrolnej

<a name="git"></a>
![Git](https://i.imgur.com/5QoNJqs.jpg)

Git to darmowy i rozproszony system kontroli wersji, przeznaczony do obsługi wszystkiego - od małych po bardzo duże projekty - z szybkością i wydajnością. (Źródło: [git-scm.com](https://git-scm.com/))

### :bulb: Szybkie podsumowanie

Kontrola wersji / kodu jest niezbędną częścią zestawu narzędzi każdego programisty. Istnieje wiele różnych systemów kontroli wersji, ale Git jest obecnie najbardziej rozpowszechniony. Możesz (i powinieneś!) używać go do śledzenia swoich projektów w trakcie nauki!

### :book: Obszary nauki i pomysły

- [Samouczek Git dla początkujących (wideo)](https://www.youtube.com/watch?v=HVsySz-h9r4)
- Zainstaluj git
- Załóż konto na [GitHub](https://github.com)
- Naucz się najczęściej używanych poleceń git:
  - init
  - clone
  - add
  - commit
  - push
  - pull
  - merge
  - rebase
- Dodaj swoje stworzone projekty na GitHub!

<a name="node"></a>
![Node and NPM](https://i.imgur.com/8ik2alD.jpg)

Node.js to open-source'owe, wieloplatformowe środowisko wykonawcze JavaScript, które wykonuje kod JavaScript poza przeglądarką. JavaScript jest używany głównie do skryptów po stronie klienta, w których skrypty napisane w JavaScript są osadzone w kodzie HTML strony i uruchamiane po stronie klienta przez silnik JavaScript w przeglądarce internetowej użytkownika. Node.js pozwala programistom używać JavaScript do pisania narzędzi wiersza poleceń oraz do skryptów po stronie serwera - uruchamianie skryptów po stronie serwera w celu tworzenia dynamicznej zawartości strony internetowej, zanim strona zostanie wysłana do przeglądarki internetowej użytkownika. W związku z tym Node.js reprezentuje paradygmat "JavaScript wszędzie", ujednolicając tworzenie aplikacji internetowych wokół jednego języka programowania, a nie różnych języków dla skryptów po stronie serwera i klienta. (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/Node.js))

### :bulb: Szybkie podsumowanie

Chociaż Node.js jest zwykle znany jako rozwiązanie back-end, jest on dość często wykorzystywany do wspierania rozwoju front-endu. Robi to na wiele sposobów, włączając w to uruchamianie narzędzi do kompilacji, testowanie i lintowanie (wszystko to wkrótce zostanie opisane!). Menedżer pakietów Node'a (npm) jest kolejnym świetnym featurem Node'a i może być używany do zarządzania zależnościami twojego projektu (tj. bibliotek kodu, na których projekt może polegać - przykładem jest jQuery!).

### :book: Obszary nauki i pomysły

- Zapoznaj się z Node'm i sprawdź jak różni się od przeglądarki
- Zainstaluj Node (npm będzie wraz z nim)
- Utwórz prosty plik Javascript i uruchom go z Node'm
- Używaj NPM do zarządzania wszelkimi zależnościami w istniejących projektach (np. JQuery!)

<a name="sass"></a>
![Sass](https://i.imgur.com/ZRedLge.jpg)

Sass to rozszerzenie CSS, które dodaje mocy i elegancji do podstawowego języka. Pozwala na używanie zmiennych, zagnieżdżonych reguł, mixins, importów inline i innych, a wszystko to przy pomocy w pełni kompatybilnej składni CSS. Sass pomaga dobrze zorganizować duże arkusze stylów i szybko uruchamia małe arkusze stylów, szczególnie przy pomocy biblioteki stylów Compass. (Źródło:[sass-lang.com](https://sass-lang.com/documentation/file.SASS_REFERENCE.html))

### :bulb: Szybkie podsumowanie

Sass pozwala pisać CSS w bardziej programowy sposób. Jeśli zrobiłeś trochę CSS, być może zauważyłeś, że w końcu powtarzasz wiele informacji - na przykład, podając ten sam kod koloru. W Sass możesz używać takich zmiennych, pętli i zagnieżdżania, aby zmniejszyć nadmiarowość i zwiększyć czytelność. Po napisaniu kodu w Sass, możesz szybko i łatwo skompilować go do zwykłego CSS.

### :book: Obszary nauki i pomysły

- [Zainstaluj Sass](https://sass-lang.com/install) globalnie z npm!
- [Kurs wideo Sass Crash](https://www.youtube.com/watch?v=roywYSEPSvc)
- Obserwuj [Learn Sass](https://sass-lang.com/guide) tutorial and/or [freeCodeCamp](https://learn.freecodecamp.org/) poradnik Sass.
- Zaktualizuj istniejącą witrynę, aby wygenerować CSS za pomocą Sass!

<a name="bootstrap"></a>
![Bootstrap](https://i.imgur.com/cJ21eH2.jpg)

\* Niektóre alternatywy: Foundation, Bulma, Materialize

Bootstrap to darmowy i otwarty framework do tworzenia stron internetowych i aplikacji internetowych. Zawiera szablony projektowania oparte na HTML i CSS dla typografii, formularzy, przycisków, nawigacji i innych komponentów interfejsu, a także opcjonalne rozszerzenia JavaScript. (Źródło: [Wikipedia](<https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)>))

### :bulb: Szybkie podsumowanie

Istnieje wiele opcji układania, stylizowania i dynamizowania aplikacji sieci Web, ale przekonasz się, że rozpoczęcie pracy z frameworkiem bardzo pomaga w uzyskaniu przewagi. Bootstrap jest jednym z takich frameworków, ale zdecydowanie nie jest jedyną opcją! Polecam zapoznanie się z jednym z takich frameworków, ale o wiele ważniejsze jest zrozumienie podstaw HTML, CSS i JavaScript niż bycie wciągniętym w jakikolwiek framework.

### :book: Obszary nauki i pomysły

- Dowiedz się, czym jest Bootstrap i dlaczego chcesz go używać
- [Kurs (wideo) Bootstrap 4 Crash](https://www.youtube.com/watch?v=hnCmSXCZEpU)
- Sekcja Bootstrap na [freeCodeCamp](https://learn.freecodecamp.org/)
- Przebuduj swoją witrynę za pomocą Bootstrap!

<a name="bem"></a>
![BEM](https://i.imgur.com/MCvMRQl.jpg)

Metodologia Block, Element, Modifier (popularnie zwana BEM) to popularna konwencja nazewnictwa dla klas w HTML i CSS. Opracowany przez zespół Yandex, jego celem jest pomoc programistom w lepszym zrozumieniu związku między HTML, a CSS w danym projekcie. (Źródło: [css-tricks.com](https://css-tricks.com/bem-101/))

### :bulb: Szybkie podsumowanie

Ważne jest, aby wiedzieć, że istnieją systemy nazewnictwa i organizacji takie jak BEM i dlaczego są one używane. Przeprowadź tutaj research, ale na poziomie początkującym nie zalecałbym poświęcania zbyt wiele czasu temu tematowi.

### :book: Obszary nauki i pomysły

- Przeczytaj [wprowadzenie do BEM](http://getbem.com/introduction/)
- [Why I Use BEM (wideo)](https://www.youtube.com/watch?v=SLjHSVwXYq4)
- Utwórz prostą stronę internetową, korzystając z konwencji BEM.

<a name="gulp"></a>
![Gulp](https://i.imgur.com/KQrByqq.jpg)

Gulp to zestaw narzędzi do automatyzacji bolesnych lub czasochłonnych zadań w toku prac programistycznych, dzięki czemu możesz przestać narzekać i coś zbudować łatwiej. (Źródło: [gulpjs.com](https://gulpjs.com/))

### :bulb: Szybkie podsumowanie

We współczesnym programowaniu front-end często musisz zautomatyzować zadania takie jak łączenie pakietów, przenoszenie plików i wstrzykiwanie odniesień do plików HTML. Gulp to jedno narzędzie, które może ci pomóc w zrobieniu tych rzeczy!

### :book: Obszary nauki i pomysły

- Zainstaluj gulp z npm
- Obserwuj [poradnik gulp dla początkujących](https://css-tricks.com/gulp-for-beginners/) na CSS-Tricks
- W swojej witrynie skonfiguruj gulp, aby:
   - Skompilować Sass dla ciebie
   - Umieścić wygenerowany plik CSS w podkatalogu `build`
   - Przenieść swoje strony internetowe do katalogu kompilacji
   - Wstawić odniesienie do wygenerowanego pliku CSS na swoje strony internetowe

<a name="webpack"></a>
![Webpack](https://i.imgur.com/0rx82Kl.jpg)

Zasadniczo Webpack to statyczny pakiet modułów dla nowoczesnych aplikacji JavaScript. Gdy Webpack przetwarza aplikację, wewnętrznie tworzy wykres zależności, który mapuje każdy moduł, którego potrzebuje Twój projekt, i generuje jeden lub więcej pakietów. (Źródło: [webpack.js.org](https://webpack.js.org/concepts/))

### :bulb: Szybkie podsumowanie

Wyobraź sobie, że masz duży projekt webowy z wieloma różnymi programistami pracującymi nad wieloma różnymi zadaniami. Zamiast wszystkich pracujących w tych samych plikach, możesz je zmodularyzować w jak największym stopniu. Webpack pomaga to włączyć, pozwalając zespołowi na pracę modułową, a następnie, gdy przyjdzie czas na zbudowanie aplikacji, Webpack sklei to wszystko razem: HTML, CSS / Sass, JavaScript, obrazy itp. Webpack nie jest jedynym pakietem modułów, ale wydaje się być w tej chwili liderem.

### :book: Obszary nauki i pomysły

- Przeczytaj [koncepcje webpack](https://webpack.js.org/concepts/)
- [What is Webpack, How does it work? (wideo)](https://www.youtube.com/watch?v=GU-2T7k9NfI)
- [Ten poradnik webpack](https://hackernoon.com/a-tale-of-webpack-4-and-how-to-finally-configure-it-in-the-right-way-4e94c8e7e5c1)

<a name="eslint"></a>
![ESLint](https://i.imgur.com/CJb6ZnL.jpg)

ESLint to narzędzie do generowania kodu JavaScript o otwartym kodzie źródłowym, pierwotnie stworzone przez Nicholasa C. Zakasa w czerwcu 2013 r. Lintowanie kodu jest rodzajem analizy statycznej, często używanej do znajdowania problematycznych wzorców lub kodu, który nie jest zgodny z pewnymi wytycznymi stylu. W większości języków programowania występują fragmenty kodu, a kompilatory czasami włączają do procesu kompilacji lintowanie. (Źródło: [eslint.org](https://eslint.org/docs/about/))

### :bulb: Szybkie podsumowanie

Linting jest fantastycznym narzędziem do poprawy jakości kodu, czytelności i spójności. Korzystanie z linijki pomoże ci wychwycić błędy w składni i formatowaniu, zanim trafią do produkcji. Możesz uruchamiać lintery ręcznie lub włączyć je do procesu kompilacji / wdrażania.

### :book: Obszary nauki i pomysły

- Zainstaluj eslint używając npm
- [How to Setup VS Code + Prettier + ESLint (wideo)](https://www.youtube.com/watch?v=YIvjKId9m2c)
- Lintuj swój JavaScript

<a name="react"></a>
![React](https://i.imgur.com/uLYz15W.jpg)

\* Some alternatives: Vue, Angular, Ember

React (znany również jako React.js lub ReactJS) to biblioteka JavaScript do tworzenia interfejsów użytkownika. Prowadzony jest przez Facebooka oraz społeczność indywidualnych programistów i firm. React może być wykorzystany jako podstawa do opracowania aplikacji jednostronicowych lub mobilnych. Złożone aplikacje React zwykle wymagają użycia dodatkowych bibliotek do zarządzania stanem, routingiem i interakcją z interfejsem API. (źródło: [Wikipedia](<https://en.wikipedia.org/wiki/React_(JavaScript_library)>))

### :bulb: Szybkie podsumowanie

Frameworki JavaScriptu znajdują się w czołówce nowoczesnego programowania front-endu. Jedną ważną rzeczą tutaj jest to, że React, mimo że jest niezwykle popularny, to tylko biblioteka do tworzenia interfejsów użytkownika, podczas gdy frameworki takie jak Vue i Angular mają być w pełni wyposażone. Na przykład, jeśli zbudujesz aplikację w React, która musi kierować do różnych widoków, musisz wprowadzić coś takiego `react-router`.

### :book: Obszary nauki i pomysły

- Rzuć okiem na sekcję [tutoriala z Reacta](https://reactjs.org/tutorial/tutorial.html)
- [Nauka React z Mosh](https://www.youtube.com/watch?v=Ke90Tje7VS0)
- Przebuduj swoją stronę jako aplikację React!
- Uwaga: `create-react-app` jest wygodnym narzędziem do 'rusztowania' nowych projektów React.

<a name="redux"></a>
![Redux](https://i.imgur.com/S9H2Dbp.jpg)

Redux to kontener stanu dla aplikacji JavaScript. Pomaga pisać aplikacje, które zachowują się spójnie, działają w różnych środowiskach (klient, serwer i natywnie) i są łatwe do przetestowania. Ponadto zapewnia świetne wrażenia programistyczne, takie jak edycja kodu na żywo w połączeniu z debugerem podróżującym w czasie. (Źródło: [redux.js.org](https://redux.js.org/introduction/getting-started))

### :bulb: Szybkie podsumowanie

Gdy budujesz coraz większe aplikacje typu front-end, zaczynasz zdawać sobie sprawę, że trudno jest utrzymać stan aplikacji: na przykład, jeśli użytkownik jest zalogowany, kim jest użytkownik i ogólnie, co się dzieje w aplikacji. Redux to świetna biblioteka, która pomaga utrzymać jedno źródło stanu, na którym aplikacja może oprzeć swoją logikę.

### :book: Obszary nauki i pomysły

- Ten [poradnik wideo Redux](https://www.youtube.com/watch?v=93p3LxR9xfM)
- Ta [seria wideo Redux](https://egghead.io/courses/getting-started-with-redux) od Dan Abramov, twórcy Reduxa
- Zwróć uwagę na [trzy zasady Reduxa](https://redux.js.org/introduction/three-principles)
  - Jedno źródło prawdy
  - Stan jest tylko do odczytu
  - Zmiany są dokonywane za pomocą czystych funkcji
- Dodaj zarządzanie stanem Redux do swojej aplikacji!

<a name="jest"></a>
![Jest](https://i.imgur.com/Cr39axw.jpg)

Jest to zachwycająca platforma testowania JavaScript z naciskiem na prostotę. Działa z projektami wykorzystującymi: Babel, TypeScript, Node, React, Angular, Vue i wiele więcej! (Źródło: [jestjs.io](https://jestjs.io))

### :bulb: Szybkie podsumowanie

Bardzo ważne jest skonfigurowanie automatycznego testowania dla projektów front-end. Skonfigurowanie testów automatycznych pozwoli Ci na pewne zmiany w przyszłości - jeśli wprowadzisz zmiany, a testy będą nadal zaliczane, będziesz mieć pewność, że nie zepsułeś żadnej istniejącej funkcjonalności. Istnieje zbyt wiele frameworków testowania, aby je wymienić; Jest jest po prostu jednym z moich ulubionych.

### :book: Obszary nauki i pomysły

- Naucz się [podstaw Jest](https://jestjs.io/docs/en/getting-started)
- Jeśli używasz `create-react-app`, [Jest jest już skonfigurowany](https://facebook.github.io/create-react-app/docs/running-tests).
- Dodaj testy do swojej aplikacji!

<a name="typescript"></a>
![TypeScript](https://i.imgur.com/BZROJNs.jpg)

\* Alternatywa: Flow

TypeScript to język programowania typu open source opracowany i obsługiwany przez Microsoft. Jest to ścisły nadzbiór składniowy JavaScript i dodaje do języka opcjonalne pisanie statyczne. TypeScript jest przeznaczony do tworzenia dużych aplikacji i przekompilowania do JavaScript. Ponieważ TypeScript jest nadzbiorem JavaScript, istniejące programy JavaScript są również prawidłowymi programami TypeScript. TypeScript może być wykorzystywany do tworzenia aplikacji JavaScript do wykonywania zarówno po stronie klienta, jak i po stronie serwera (Node.js). (Źródło: [Wikipedia](https://en.wikipedia.org/wiki/TypeScript))

### :bulb: Szybkie podsumowanie

JavaScript jest dynamicznie typowany. Jednak powszechnie uważa się, że typowanie statyczne (tj. określanie typów zmiennych, klas, interfejsów z wyprzedzeniem) jest zarówno jaśniejsze, jak i zmniejsza prawdopodobieństwo wad / błędów. Niezależnie od tego, jak się czujesz na ten temat, ważne jest, aby przynajmniej poczuć statyczną wersję JavaScript, taką jak TypeScript. Pamiętaj, że TypeScript kompiluje się do JavaScript, więc może być interpretowany przez przeglądarki (tzn. przeglądarki nie interpretują natywnie TypeScript).

### :book: Obszary nauki i pomysły

- [Naucz się TypeScript w 5 minut](https://medium.freecodecamp.org/learn-typescript-in-5-minutes-13eda868daeb)
- [Naucz się TypeScript w 50 minut (wideo)](https://www.youtube.com/watch?v=WBPrJSw7yQA)
- Opcjonalnie [utwórz aplikację React za pomocą TypeScript](https://levelup.gitconnected.com/typescript-and-react-using-create-react-app-a-step-by-step-guide-to-setting-up-your-first-app-6deda70843a4)

<a name="nextjs"></a>
![NextJS](https://i.imgur.com/YNtW38J.jpg)

Next.js to minimalistyczny framework dla renderowanych przez serwer aplikacji React. (Źródło: [Next.js — React Server Side Rendering Done Right](https://hackernoon.com/next-js-react-server-side-rendering-done-right-f9700078a3b6))

### :bulb: Szybkie podsumowanie

Teraz jesteśmy już zaawansowani! Do tej pory zbudowałeś aplikację React (lub Vue, lub Angular), która wykonuje sporo pracy w przeglądarce. Z różnych powodów (np. SEO, obaw związanych z wydajnością klienta) możesz chcieć renderować aplikację front-end na serwerze, a nie na kliencie. Właśnie tam pojawia się framework taki jak next.js.

### :book: Obszary nauki i pomysły

- Next.js [Pierwsze kroki](https://nextjs.org/learn/)
- [Next.js Crash Course (wideo)](https://www.youtube.com/watch?v=IkOVe40Sy0U)
- Stwórz aplikację Next.js lub migruj istniejącą aplikację do Next.js

# A co na temat X?

Ta lista ma dać ci szeroki wgląd w ekosystem front-end, ale po prostu nie można poruszać każdego tematu, nie wspominając o niezliczonych narzędziach w każdym obszarze! Jeśli uważasz, że przegapiłem coś bardzo ważnego, zapoznaj się z sekcją [Współtworzenie](#współtworzenie), aby dowiedzieć się, jak możesz pomóc w ulepszeniu tego przewodnika.

# Pomysły na projekty

W miarę postępów podczas #100DaysOfCode będziesz potrzebować jednego lub wielu projektów, do których możesz zastosować swoją nową wiedzę. W tej sekcji staram się przedstawić kilka pomysłów na projekt, z których możesz skorzystać. Możesz też zaproponować własne pomysły na projekty, które mogą Cię zainteresować i motywować.

- Pomysły dla początkujących:
  - Stwórz stronę z portfolio
- Pomysły dla średniozaawansowanych/zaawansowanych:
  - Zbuduj aplikację do analizy tweetów (jeśli znasz już backend i integrację interfejsu API)
  
# Potrzebujesz pomocy?

Ogólnie rzecz biorąc, uważam następujące materiały za nieocenione przy tworzeniu oprogramowania do nauki:

- Googlowanie określonego problemu
- [StackOverflow](http://www.stackoverflow.com) (Jest duża szansa, że twoje pytanie zostało już zadane i będzie wysoko w rankingu podczas wyszukiwania w Google).
- [Mozilla MDN Web Docs](https://developer.mozilla.org/en-US/)
- [freeCodeCamp](https://www.freecodecamp.org/)
- Lokalne spotkania z dziedziny oprogramowania typu Meetups! Większość jest bardzo przyjazna dla wszystkich poziomów doświadczenia.

Jeśli chcesz mieć cokolwiek do powiedzenia, nie krępuj się [połączyć ze mną na Twitter](http://www.twitter.com/nas5w), dołożę wszelkich starań, aby zaoferować pomoc. Jeśli uważasz, że występuje problem z programem nauczania lub masz zalecenie, zobacz [sekcja Współtworzenie](#współtworzenie), która znajduje się poniżej.

# Współtworzenie

## Podaj dalej

Jeśli doceniasz pracę wykonaną tutaj, możesz znacząco przyczynić się w rozwój projektu rozpowszechniając informacje o tym repozytorium, w tym:

- Dając gwiazdkę lub tworząc fork tego repo
- Podzielić się tym repo w social media

## Współtworz to repozytorium

Jest to praca w toku (WIP) i bardzo doceniam wszelką pomoc w utrzymaniu tej bazy wiedzy!

Współuczestnicząc w tym repozytorium, przed wprowadzeniem zmiany omów najpierw zmianę, którą chcesz wprowadzić za pośrednictwem issue. W przeciwnym razie bardzo trudno będzie zrozumieć Twoją propozycję i może to potencjalnie spowodować, że włożysz dużo pracy w zmianę, która nie zostanie scalona, zmergowana.

Pamiętaj, że wszyscy zaangażowani w ten projekt albo próbują się uczyć, albo próbują pomóc - Bądź miły!

## Proces Pull Requestu

1. Stwórz issue dotyczący zarysu proponowanego pull requesta.
2. Uzyskaj zgodę właściciela projektu na wprowadzenie proponowanej zmiany.
3. Stwórz pull request.

_________________________________________________________________________

Stworzone przez [@nas5w](https://github.com/nas5w), polska wersja od [@mbiesiad](https://github.com/mbiesiad)

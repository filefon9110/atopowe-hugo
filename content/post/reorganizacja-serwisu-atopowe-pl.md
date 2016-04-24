+++
date = "2016-04-23T11:44:28+01:00"
tags = ["", ""]
title = "Reorganizacja serwisu atopowe.pl"

+++

Opiekowałem się naszym forum ochotniczo przez ostatnie 13 lat. Miałem poczucie
że robię coś dobrego, wartościowego, i czerpałem z tego satysfakcję. Z drugiej
strony, wiązało się to z odpowiedzialnością. W razie problemów technicznych,
musiałem forum naprawiać, czy miałem na to ochotę, czy nie.  Tymczasem życie
płynie dalej. Chcę się uwolnić od tej odpowiedzialności i przekazać opiekę nad
forum komuś innemu.

Plan A wyglądał tak, żeby przekazać serwis w takiej formie w jakiej istniał
(forum na phpBB, atopedia na Mediawiki, blog na Wordpressie, lekarze w Django)
ochotnikowi/ochotniczce, osobie która będzie kontynuowała opiekę nad forum. To
się niestety nie udało.

W ramach planu B napisałem do Fundacji Alabaster. Niestety dotychczas nie
dostałem pozytywnej odpowiedzi.

Zdałem sobie sprawę, że zostałem z problemem sam.

Uruchamiam więc plan C: [przeniesienie treści serwisu w inne
miejsca](https://www.reddit.com/r/atopowezapalenieskory/comments/4fb20l/reddit_i_wiki_plan_reorganizacji_atopowepl/),
które mają już istniejącą infrastrukturę.

*  Atopedia:
   Instalacja MediaWiki zostanie zamieniona na linki statyczne. Stare URLe
   pozostaną dostępne, tylko z tą różnicą, że po zamianie na pliki statyczne
   URLe dostaną dodatkowy slash na końcu: `/atopedia/Coś` zostanie zamienione
   na `/atopedia/Coś/`.

*  Forum
   1. Przełączę forum w tryb tylko do odczytu &mdash; nie będzie można już pisać na
      atopowe.pl/forum. (spróbuję zamienić je na pliki statyczne)
   1. Umieszczę linki do [/r/atopowezapalenieskory][reddit].
   1. Poproszę obecnych moderatorów o pomoc z utrzymywaniem porządku na subie.

*  Blog:
   Zamienię instalację wordpress na statyczne pliki HTML.

*  domeny atopowe.pl i atopowe-zapalenie.pl:
   Na domeny na razie nie mam pomysłu.

&mdash;wahwah

-------

*   2016-04-24: Atopedia, forum i blog są już w postaci archiwum i plików
    statycznych. Teraz można je przenieść na normalny hosting, pod warunkiem że
    będzie tam Apache i możliwość używania plików .htaccess i mod_rewrite, bo
    jest to potrzebne do archiwum forum.

[reddit]: https://www.reddit.com/r/atopowezapalenieskory/
[github]: https://github.com/automatthias/atopowe-hugo

# apbd-cw2-git-s33982

Zmiany do merge bez fast-forward

Dlaczego?

Merge nie mógł być wykonany metodą fast-forward, ponieważ po utworzeniu gałęzi feature-max historia gałęzi main uległa zmianie. Przez co git nie mógł przesunąć wskaźnika do przodu tylko robi 3-way commit

Odpowiedzi na pytania:
1.
    a) Kiedy git wykona fast-forward?
        Gdy przy próbie merge'a na gałęzi na której jest wykonywana komenda git merge nie posiada żadnych zmian (commitów)
    b) Kiedy powstaje merge commit?
	Wtedy kiedy zmiany zaszły na gałęzi do której przyłączana jest inna gałąź na której też była zmiana

2. Czym w praktyce różni się merge od rebase?
    - git merge robi commit scalający
    - git rebase przepisuje historię z gałęzi bocznej na wierzchołek gałęzi głównej

3. W jaki sposób został rozwiązany konflikt w twoim repozytorium?
Wybrałem opcję z gałęzi bocznej

---
marp: true
lang: de
theme: beige
notesSeparator: "NOTES:"
---

<!--
marp settings: marp, lang, theme  
obsidian-advanced-slides settings: theme, notesSeparator (<!-- notes in marp --\>)  
Note to myself: comment out NOTES for marp exports
-->

<style>
	.text-left {
		  text-align: left;
	}
	
	.qr-code {
		  position: absolute;
		  top: 2rem;
		  right: 2rem;
	}

	.octicon--law-24 {
		  display: inline-block;
		  width: 1em;
		  height: 1em;
		  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%23000' d='M12.75 2.75V4.5h1.975c.351 0 .694.106.984.303l1.697 1.154c.041.028.09.043.14.043h4.102a.75.75 0 0 1 0 1.5H20.07l3.366 7.68a.749.749 0 0 1-.23.896c-.1.074-.203.143-.31.206a6.296 6.296 0 0 1-.79.399a7.349 7.349 0 0 1-2.856.569a7.343 7.343 0 0 1-2.855-.568a6.205 6.205 0 0 1-.79-.4a3.205 3.205 0 0 1-.307-.202l-.005-.004a.749.749 0 0 1-.23-.896l3.368-7.68h-.886c-.351 0-.694-.106-.984-.303l-1.697-1.154a.246.246 0 0 0-.14-.043H12.75v14.5h4.487a.75.75 0 0 1 0 1.5H6.763a.75.75 0 0 1 0-1.5h4.487V6H9.275a.249.249 0 0 0-.14.043L7.439 7.197c-.29.197-.633.303-.984.303h-.886l3.368 7.68a.75.75 0 0 1-.209.878c-.08.065-.16.126-.31.223a6.077 6.077 0 0 1-.792.433a6.924 6.924 0 0 1-2.876.62a6.913 6.913 0 0 1-2.876-.62a6.077 6.077 0 0 1-.792-.433a3.483 3.483 0 0 1-.309-.221a.762.762 0 0 1-.21-.88L3.93 7.5H2.353a.75.75 0 0 1 0-1.5h4.102c.05 0 .099-.015.141-.043l1.695-1.154c.29-.198.634-.303.985-.303h1.974V2.75a.75.75 0 0 1 1.5 0M2.193 15.198a5.414 5.414 0 0 0 2.557.635a5.414 5.414 0 0 0 2.557-.635L4.75 9.368Zm14.51-.024c.082.04.174.083.275.126c.53.223 1.305.45 2.272.45a5.847 5.847 0 0 0 2.547-.576L19.25 9.367Z'/%3E%3C/svg%3E");
		  background-color: currentColor;
		  -webkit-mask-image: var(--svg);
		  mask-image: var(--svg);
		  -webkit-mask-repeat: no-repeat;
		  mask-repeat: no-repeat;
		  -webkit-mask-size: 100% 100%;
		  mask-size: 100% 100%;
	}

	.material-symbols--star {
		  display: inline-block;
		  width: 1em;
		  height: 1em;
		  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%23000' d='m5.825 22l1.625-7.025L2 10.25l7.2-.625L12 3l2.8 6.625l7.2.625l-5.45 4.725L18.175 22L12 18.275z'/%3E%3C/svg%3E");
		  background-color: currentColor;
		  -webkit-mask-image: var(--svg);
		  mask-image: var(--svg);
		  -webkit-mask-repeat: no-repeat;
		  mask-repeat: no-repeat;
		  -webkit-mask-size: 100% 100%;
		  mask-size: 100% 100%;
	}
	
	.material-symbols--star-outline {
		  display: inline-block;
		  width: 1em;
		  height: 1em;
		  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%23000' d='m8.85 17.825l3.15-1.9l3.15 1.925l-.825-3.6l2.775-2.4l-3.65-.325l-1.45-3.4l-1.45 3.375l-3.65.325l2.775 2.425zM5.825 22l1.625-7.025L2 10.25l7.2-.625L12 3l2.8 6.625l7.2.625l-5.45 4.725L18.175 22L12 18.275zM12 13.25'/%3E%3C/svg%3E");
		  background-color: currentColor;
		  -webkit-mask-image: var(--svg);
		  mask-image: var(--svg);
		  -webkit-mask-repeat: no-repeat;
		  mask-repeat: no-repeat;
		  -webkit-mask-size: 100% 100%;
		  mask-size: 100% 100%;
	}

	.material-symbols--star-half-outline {
		  display: inline-block;
		  width: 1em;
		  height: 1em;
		  --svg: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24'%3E%3Cpath fill='%23000' d='m12 15.925l3.15 1.925l-.825-3.6l2.775-2.4l-3.65-.325l-1.45-3.4zM5.825 22l1.625-7.025L2 10.25l7.2-.625L12 3l2.8 6.625l7.2.625l-5.45 4.725L18.175 22L12 18.275z'/%3E%3C/svg%3E");
		  background-color: currentColor;
		  -webkit-mask-image: var(--svg);
		  mask-image: var(--svg);
		  -webkit-mask-repeat: no-repeat;
		  mask-repeat: no-repeat;
		  -webkit-mask-size: 100% 100%;
		  mask-size: 100% 100%;
	}
</style>

# Der Process

> Franz Kafka

![[Manuskript_Der_Prozess.png|400]]

NOTES:
Der Process - von Franz Kafka

---

# Franz Kafka

+ **geboren** am 3.7.1883 in Prag 
+ **gestorben** am 3.6.1924 in Klosterneuburg, Kierling
+ **Religion**: Judentum
+ **Ausbildung**: u.a. Jurastudium
+ **Beruf**: Versicherungsangestellter
+ **Vater**: dominant

NOTES:
**Franz Kafka** erblickt am 3.7.1883 in Prag das Licht der Welt.  

Leben:  
- **1883**: Geburt in Prag als erstes Kind von Hermann Kafka und Julie Kafka
- **1885-1892**: 
	- Geburt von Geschwistern,
	- Schulbesuch.
- **1901**: Beginn seines Jura-Studiums an einer Prager Universität.
- **1906-1907**: 
	- Arbeit bei Versicherungsgesellschaften und 
	- erste literarische Veröffentlichungen.
- **1910-1913**: 
	- Reisen nach Paris und in die Schweiz, 
	- intensive Schreibphase, Bücher darunter "Der Verschollene" und "Die Verwandlung".
- **1914-1918**: 
	- Erste Verlobung, 
	- Krankheiten, 
	- Arbeit am "Prozess" und 
	- Erster Weltkrieg
		- Einstufung "_unverzichtbar_", von seinem Arbeitgeber => deshalb blieb er Zuhause
- **1919-1922**: 
	- Wechselnde Beziehungen, 
	- gesundheitliche Probleme und 
	- intensive Schreibphasen.
- **1923-1924**: 
	- Umzug nach Berlin, 
	- Verschlechterung seines Gesundheitszustands und 
	- Tod (41) am 3. Juni 1924 in Kierling bei Klosterneuburg.

Kafka hinterließ ein bedeutendes literarisches Erbe, das vor allem durch seine einzigartige Herangehensweise an existenzielle Themen und seine künstlerische Darstellung von Macht, Identität und Isolation geprägt ist.

Mehr Infos zu seinem Leben:
https://www.franzkafka.de/leben/chronik
https://www.franzkafka.de/leben/familie
https://www.franzkafka.de/leben/frauen
https://www.franzkafka.de/leben/freunde

---

# Der Process

+ Startschuss: Sommer 1914
	+ er schreibt Beginn und Schluss
+ **mehrere** Kapitel gleichzeitig
+ Arbeit **stockt** im November 
+ Arbeit **verworfen** im Januar 1915
+ **Manuskriptlänge**: 171 Seiten
+ Max Brod, ein Freund von Kafka veröffentlichte das unvollendete Werk schließlich **gegen den letzten Willen** von Kafka

NOTES:
* ab dem Sommer 1914 arbeitete Kafka an dem Buch
	* er schreibt den Beginn und den Schluss, vermutlich, um nicht die Motivation zu verlieren
* anschließend arbeitet er an mehreren Kapiteln gleichzeitig
* im November stockt die Arbeit
* im Januar 1915 legt er es schließlich ganz beiseite
* das Manuskript umfasst schlussendlich 171 Blätter
* Max Brod, ein Freund von Kafka veröffentlichte das unvollendete Werk schließlich gegen den letzten Willen von Kafka, der in gebeten hatte alle Tagebücher, Manuskripte und Briefe von ihm restlos zu verbrennen nur acht Monate nachdem Kafka an Kehlkopftuberkulose starb.

Es gab einige Schwierigkeiten bei der Publikation, da die Kapitel zwar als solche markiert waren, aber die Reihenfolge nicht festgelegt wurde.  
Zudem gibt es einige unvollständige Kapitel. Fragmente, wie man sie in der Germanistik nennt.

*kurze Pause*

Das Buch gilt als Kafkas Hauptwerk  
und ist sein weltweit bekanntestes, meistzitiertes Werk.

---

# Fakten zum Buch

+ **Titel**: Der Process
+ **Textgattung**: Roman
+ **Literarische Strömung**: Keine, oder Modernismus (Absurdismus, Expressionismus, Existentialismus)
+ **Erzählperspektive**: personaler Erzähler

NOTES:
Das Buch, **der Prozess** ist ein **Roman**.  
Bei der **Literarischen Strömung** ist man sich nicht ganz einig. Einige Experten meinen, Kafka könne man keiner Literarischen Strömung zuordnen.  
Manche zählen seinen **Stil** in die folgenden Rubriken hinzu:
* Modernismus mit Elementen von
	* Absurdismus
	* Expressionismus
	* Existentialismus
Je nachdem wen man fragt, wird man eine andere Antwort erhalten.

Die **Erzählperspektive** ist die eines personalen Erzählers.

Was macht den Prozess, zu einem solchen Urwerk der Moderne? (_Einleitung in die Interpretation_)  Seit bald hundert Jahren ist der Text immer wieder neu und immer wieder anders interpretiert worden, 
* theologisch, 
* existentialistisch, 
* psychoanalytisch. 

Kafka hat es mit diesem Werk geschafft, viele Menschen für die Folgenden Fragen zu begeistern:  
Gibt es ein oberstes Gesetz, sollte es eines geben?  
Gibt es das Böse?  
Oder -  
ist Kafkas Niederschrift in erster Linie eine subtile Kritik an 
* bürokratischer Macht und 
* an Herrschaftsstrukturen?

---

# Interpretation

::: block <!-- element class="fragment" -->
* tiefgründige Untersuchung der Bürokratie und der Macht Strukturen von Gerichten 
	1. undurchsichtige Prozesse <!-- element class="fragment" -->
	2. Bürokratische Hölle <!-- element class="fragment" -->
	3. Korruption und unfaire Machtverhältnisse <!-- element class="fragment" -->
	4. Frustration durch unbesiegbare, unsichtbare Ankläger <!-- element class="fragment" -->
:::

NOTES:
Was will Kafka sagen?  

“Der Process” ist eine tiefgründige Untersuchung der Bürokratie und der Macht Strukturen von Gerichten.  
Der Roman zeigt die Frustration und das Leiden, die durch ein undurchsichtiges und unergründliches bürokratisches Rechtssystem verursacht werden.  
Die Ironie und der absurde Humor des Romans entstehen aus der Frustration, nicht zu wissen, warum Josef K. all dies überhaupt ertragen muss.

---

# Stoff

+ **biografischer Anlass**: Auflösung der Verlobung mit Felice Bauer
+ Kafkas kämpfe mit
	+ Identität
	+ Gesellschaft
+ totalitär regierte Staaten
+ erster Weltkrieg
+ Traum von einer Schriftstellerexistenz

NOTES:
_Der Process_ gehört zu denjenigen Werken Kafkas, bei denen sich ein unmittelbarer biografischer Anlass nachweisen lässt: die Auflösung der Verlobung mit [Felice Bauer](https://www.franzkafka.de/leben/frauen/felice-bauer).  
Kafka hat diese Trennung vor allem deshalb als traumatisch erlebt, weil sie sich in Anwesenheit zweier Zeuginnen abspielte, die ihm im Hotel ›Askanischer Hof‹ in Berlin wie Geschworene gegenüber saßen. Dass sich hier dem Juristen Kafka die Metaphorik des Gerichts aufdrängte, ist naheliegend.

“Der Process” spiegelt zudem Kafkas eigene Kämpfe mit Identität und Gesellschaft wider.

Das Werk entstand in den Anfängen des ersten Weltkriegs, daher ist es auch nicht weit hergeholt, dass Kafka mit dem Buch totalitäre Systeme kritisieren wollte.

Auch träumte der Autor zeitlebens von einer Schriftstellerexistenz und versuchte diese vor allem auch mit dem Prozess wahr zu machen.


WENN NOCH ZEIT IST:

Auch Selbstentfremdung, Vernichtungsängste, Desorientierung, Anonymität und die aktenmäßige ›Erfassung‹ des Menschen. Vor allem Kafkas Verfahren, das jeweils Nächstliegende mit fotografischer Genauigkeit zu schildern, den Sinn des Ganzen jedoch völlig im Dunkeln zu lassen, spiegelt genau das Lebensgefühl in großen sozialen Systemen, in denen jeder ›informiert‹ ist, die jedoch jenseits des eigenen Funktionierens keinen ›Sinn‹ mehr vermitteln.


Es gibt auch **biografische Parallelen** zwischen Autor und Figur. Als er die ersten Zeilen seines Romanfragments schrieb, war Kafka schon seit sechs Jahren bei der "Arbeiter-Unfall-Versicherungs-Anstalt für das Königreich Böhmen in Prag" angestellt. Vom Kriegsdienst wird er zurückgestellt, seine Vorgesetzten halten ihn für unentbehrlich. Noch bis 1922 bleibt er Büroangestellter, das gibt ihm nicht nur materiell, sondern auch psychisch Sicherheit. Denn als Schriftsteller hielt er sich immer wieder für einen Versager. Bei den Frauen hat Kafka dagegen durchaus Erfolg. Sie locken ihn oft, schreibt er an seinen Freund Max Brod. Gemeinsam mit ihm besucht er auch öfters Bordelle und trifft junge Frauen, "Ladenmädchen", wie er sie nennt.

Auch der Bankangestellte Joseph K. hat ein geregeltes Leben. Er wohnt in der Pension einer Frau Grubach, ist ganz auf seine Arbeit konzentriert. Einmal in der Woche besucht er Else, die Kellnerin in einer Weinstube, nach ihrem Dienst - dann kommt er spät nach Hause. Seine Freizeit verbringt er mit Spaziergängen und mit anderen Honoratioren am Stammtisch.

---

# Hintergrund
## Soziokulturell/Biografisch

+ Beamter im Arbeiterunfallversicherungsinstitut
+ tschechischer Bürger im österreichisch-ungarischen Reich.
+ Persönliche Entfremdung
+ Literatur vs. bürgerlichem Leben.
+ Tod durch Tuberkulose. 

NOTES:
- Kafka war Beamter im Arbeiterunfallversicherungsinstitut für das Königreich Böhmen.
- Er war ein tschechischer Bürger im österreichisch-ungarischen Reich.
- Persönliche Entfremdung von seinem pragmatischen Vater, seiner Arbeit und vom anderen Geschlecht erfahren.
- War hin- und hergerissen zwischen Literatur und bürgerlichem Leben.

**Biographische Entstehungsbedingungen**:  
Franz Kafka schrieb “Der Process” während seiner Zeit als Beamter im Arbeiterunfallversicherungsinstitut für das Königreich Böhmen. Er war ein tschechischer Bürger im österreichisch-ungarischen Reich, ein Deutschsprecher unter Tschechen, ein Jude unter Deutschsprechern und ein Ungläubiger unter Juden. Er fühlte sich von seinem pragmatischen und herrschsüchtigen Vater, von seiner bürokratischen Arbeit und vom anderen Geschlecht entfremdet. Er war hin- und hergerissen zwischen dem Wunsch, in der Literatur zu leben, und dem Wunsch, ein normales bürgerliches Leben zu führen.  
Diese persönlichen Erfahrungen und seine scharfe Kritik an der Bürokratie seiner Zeit spiegeln sich in “Der Process” wider.

---

# Hintergrund
## Soziokulturell/Historisch

+ entstand während des Ersten Weltkriegs. 
+ Nationalismus und Feindseligkeit im österreichisch-ungarischen Reich. 
	+ Konflikte zwischen drei Hauptbevölkerungsgruppen: 
		+ den Tschechen, 
		+ den Deutsch-Österreichern und 
		+ den Juden. 

NOTES:
- Wie bereits erwähnt entstand "Der Process" während des Ersten Weltkriegs.
- Nationalismus und Feindseligkeit im österreichisch-ungarischen Reich wahren präsente Themen dieser Zeit => Konflikte zwischen den drei Hauptbevölkerungsgruppen: 
	- den Tschechen, 
	- den Deutsch-Österreichern und 
	- den Juden.


**Historische Entstehungsbedingungen**:  
Kafka schrieb das Buch während des Ersten Weltkriegs, einer Zeit großer politischer und sozialer Umwälzungen. Während seiner prägenden Jahre war der Nationalismus im gesamten österreichisch-ungarischen Reich auf dem Vormarsch, was zur Feindseligkeit führte, die in den Ersten Weltkrieg mündete. Obwohl es keine direkte Zensur gab, kann man in “Der Process” eine satirische Anprangerung der österreichisch-ungarischen Bürokratie von Kafkas Zeit sehen.

---

# Motive

1. Gerechtigkeit gegen das Gesetz <!-- element class="fragment" -->
2. Das Absurde <!-- element class="fragment" -->
3. Das Unbekannte <!-- element class="fragment" -->
4. Entfremdung und Kontrolle <!-- element class="fragment" -->
5. Sex und Verführung <!-- element class="fragment" -->

NOTES:
1. **Gerechtigkeit gegen das Gesetz**: Der zentrale Konflikt von “Der Process” ist Josef K.'s Kampf gegen das Gesetz. Er steht wegen eines unbekannten Verbrechens vor Gericht, und sein Prozess soll angeblich dazu dienen, Gerechtigkeit zu gewährleisten. Allerdings scheint es wenig Gerechtigkeit in der Behandlung zu geben, die Josef erhält.
2. **Das Absurde**: Das Gesetz in “Der Process” ist irrational, unverständlich und daher absurd. Je mehr Josef K. versucht, seinen Fall rational zu verfolgen, desto mehr verstrickt er sich in Irrationalität.
3. **Das Unbekannte**: Josef K. weiß nicht, weshalb er angeklagt wurde, zumindest beteuert er das.
4. **Entfremdung und Kontrolle**: Es gibt keine Zusammenarbeit oder Kameradschaft in "Der Process". Jeder Einzelne handelt als isolierter Agent, und die Menschen konzentrieren sich darauf, sich selbst und andere zu kontrollieren, um persönliche Wünsche zu erfüllen.
5. **Sex und Verführung**: “Der Process” ist voll von offener Sexualität. Ein großer Teil der weiblichen Charaktere, wie Leni, versucht, Josef zu verführen oder wird von ihm als potenzielle sexuelle Eroberungen betrachtet.

---

# (Zeit)Verlauf

+ **Zeit**: vermutlich in den frühen 1900ern
+ **Zeitverlauf**:
	+ **Erzählte Zeit**: Geburtstag - Tod Joseph K.'s (ca. ein Jahr) 
	+ **Erzählzeit**: 6-10h 

NOTES:
- Zeit: vermutlich in den frühen 1900er Jahren (nicht explizit genannt)
- Zeitverlauf: 
	* Erzählte Zeit: Geburtstag - Tod Joseph K.'s (etwa ein Jahr später)
	* Erzählzeit: 6-10h, das Hörbuch dauert zwischen 7h 30min und 8h 50min, je nach Sprecher
	* Auffälligkeiten: chronologisch, bis auf die Fragmente

---

# Raum und Milieu

+ **Raum**:
	+ K.'s Pension,
	+ Gerichtsbüros,
	+ Bank, 
	+ Advokaten Wohnung, 
	+ Maler Atelier & Dom 
+ **Milieu**:
	+ obere Mittelklasse 
	+ armen Viertel

NOTES:
**Schauplätze** sind der private und berufliche Lebensbereich Josef K.’s sowie die Örtlichkeiten, an die er durch seine »Prozesssituation« zu gehen veranlasst wird.  
- **Darunter**:
	- K.'s Pension
	- Gerichtsbüros (Sitzungssaal, Kanzleien)
	- Bank
	- Maler Atelier (Titorelli)
	- Dom (Priester)
	- Advokaten Wohnung (Huld)
Vermutlich spielt sich alles in einer Stadt in Mitteleuropa, vielleicht Prag, Kafkas Heimatstadt ab.

- **Milieu**: 
	- moderne Bürokratische Stadt, 
	- Josef gehört zur oberen Mittelklasse
	- die Gerichtsräumlichkeiten sind paradoxerweise in einem armen Viertel

---

# Sprache

+ **Sprache**: 
	+ präzise, nüchtern, sachlich, unbeteiligt, aber nicht emotionslos 
	+ keine "schwierigen" Wörter
	+ monoperspektivisches, personales Erzählen 

NOTES:
- Sprache: 
	- präzise, nüchtern, sachlich, unbeteiligt, aber nicht emotionslos
	- keine "schwierigen" Wörter, nur ein paar ältere Bezeichnungen, 
	- vermittelt ein Gefühl von Hoffnungslosigkeit
	- monoperspektivisches, personales Erzählen

---

# Figurencharakteristik

+ **Josef K.**:
	+ Karrierebeamter, Standesdünkel,
	+ selbstzufrieden, überheblich 
+ **Advokat Huld**: 
	+ alt, krank,
	+ dominant
+ **Leni**:
	+ dominant,
	+ sexuell-animalisch

NOTES:
* **Josef K.**:
	* Karrierebeamter, Standesdünkel, 
	* selbstzufrieden, überheblich 
* **Advokat Huld**: 
	* alt, krank, 
	* dominant 
* **Leni**:
	* dominant,
	* sexuell-animalisch

---

# Figurencharakteristik

- Frau Grubach: <!-- element class="fragment" -->
	- einfach, mütterlich, <!-- element class="fragment" -->
	- vorwitzig <!-- element class="fragment" -->
- Fräulein Bürstner: <!-- element class="fragment" -->
	- selbstbewusst, modern, <!-- element class="fragment" -->
	- emanzipiert <!-- element class="fragment" -->
- Maler Titorelli: <!-- element class="fragment" -->
	- Bohemien, Lebenskünstler, <!-- element class="fragment" -->
	- geschickter Taktierer <!-- element class="fragment" -->

NOTES:
- Frau Grubach: 
	- einfach, mütterlich, 
	- vorwitzig 
- Fräulein Bürstner: 
	- selbstbewusst, modern, 
	- emanzipiert 
- Maler Titorelli: 
	- Bohemien, Lebenskünstler, 
	- geschickter Taktierer 

**Weitere Personen**: 
* Gefängniskaplan (Dom),
* Elsa (Freundin)
* Josefs Onkel

---

# Figurenkonstellation

![[Figurenkonstellation_Der_Prozess.svg]]

NOTES:
_Auf Tafel erklären..._

Zu allen Frauen, bis auf seine Vermieteten hat Josef K. einen sexuellen Zugang.  
Zu seiner Familie hat er nicht viel Kontakt. Die wichtigste Rolle hat sein Onkel, der ihm einen Advokaten vermittelt. Der Advokat vertritt Josef etwa 2/3 des Buches.  
Eine der beruflichen Freundschaften, von Josef K. verbindet Josef mit dem Gerichtsmaler Titorelli, der ihm einige Ratschläge gibt, aber anschließend gefühlt von Kafka einfach vergessen wird, obwohl er doch eine tragende Rolle gespielt haben könnte.  
Mit dem Bankdirektor ist Josef K. gut befreundet. Den Direktor-Stellvertreter sieht er als Konkurrenten. Zu beginn versucht sich dieser mit K. zu befreunden, schlussendlich krallt er sich K.'s Klienten.

---

# Inhaltsangabe

> _"Jemand musste Joseph K. verleumdet haben, denn ohne daß er etwas Böses getan hätte, wurde er eines Morgens verhaftet."_

NOTES:
> _"Jemand musste Joseph K. verleumdet haben, denn ohne daß er etwas Böses getan hätte, wurde er eines Morgens verhaftet."_

Dieser Satz gehört zu den berühmtesten Romananfängen der Weltliteratur, laut der Deutsche Welle, was mich etwas verwirrte, denn so sagenhaft fand ich ihn gar nicht, aber zu meiner Kritik später noch mehr.

Das Buch beginnt damit, dass Joseph K., - die meiste Zeit nur als K. im Buch bezeichnet, von einem Prozess erfährt, der gegen ihn angeleiert wurde.  
An seinem 30. Geburtstag warten "Wächter" eines für ihn unbekannten Gerichtes in seiner Küche auf K. und verzehren genüsslich sein Frühstück. Er währe verhaftet, aber nicht festgenommen, erklären sie dem verwirrten Mann.  
K. wird anschließend in seinen Alltag entlassen und darf zur Bank, um seine Tätigkeit als Prokurist auszuführen.


>**Für alle die es nicht wissen:** Ein Prokurist ist ein Bankangestellter mit Vollmacht. Joseph K. ist also dazu berechtigt Geschäfte für die Bank abzuschließen und Verpflichtungen einzugehen. Er ist quasi ein Vertreter der Bank und hat hohes Ansehen.

_kurze Pause..._

Der Prozess zieht sich über ein ganzes Jahr und schlussendlich wird Joseph K., obwohl er bis zum Ende auf "unschuldig" plädiert mit einem Fleischermesser in einem Steinbruch hingerichtet.  
Bis zum Schluss erfährt man nicht, weswegen er denn überhaupt angeklagt wurde.  
>In Kafkas Tagebüchern schreibt Kafka übrigens, der Hauptcharakter währe schuldig.

---

# Rezeption


> [!INFO] Sabine Peschel von ["Deutsche Welle"](https://www.dw.com/de/franz-kafka-der-prozess/a-45710050) schreibt:
> Angsterregend, traumartig, vorausdeutend: Kafkas posthum veröffentlichter Roman ist einer der rätselhaftesten Texte der Weltliteratur.

<span class="fas octicon--law-24"></span> Meine Bewertung: 
<i class="fas material-symbols--star"></i>
<i class="fas material-symbols--star"></i>
<i class="fas material-symbols--star-half-outline"></i>
<i class="fas material-symbols--star-outline"></i>
<i class="fas material-symbols--star-outline"></i>  
**Leseeindruck:** _"Kann man lesen, muss man aber nicht"_

NOTES:
Sabine Peschel und auch einige andere Kritiker sind sehr überzeugt von dem Buch.  
**Sie schreibt beispielsweise:**  
"Angsterregend, traumartig, vorausdeutend: Kafkas posthum veröffentlichter Roman ist einer der rätselhaftesten Texte der Weltliteratur", in der Deutschen Welle.

Auf der Rückseite des Buches wird dieses wie folgt gepriesen:  
"Der 1914/15 entstandene und schon 1925, im Jahr nach Kafkas Tod, veröffentlichte _Process_ zählt zu den bedeutendsten Romanen des 20. Jahrhunderts."

Ich persönlich finde das Buch eher durchschnittlich.  
Es schafft es einfach nicht wirklich durchgehend spannend zu sein, wie ich finde. Es sind ein paar Logiklücken vorhanden und würde ein Autor heutzutage das selbe Buch schreiben, währe es nicht besonders erfolgreich.  
Ich gebe 5/10 Sternen.

---

# Was?
## unlogische Geschichte: Ein Beispiel
### _Der Maler_
> **Was ist mit dem Maler?**  
> Kafka vergisst den Character einfach komplett, nach dem ersten Treffen.

NOTES:
Eine dieser Logiklücken ergibt sich dadurch, dass Kafka den Gerichtsmaler in die Geschichte einbaut, jedoch scheinbar auf diesen vergisst, denn aus mit unerklärbaren Gründen kommt er nach dem ersten Treffen der beiden nicht mehr vor.  
Das ist deshalb so komisch, da er auf ein zweites Treffen beharrte und Josef K. nicht abgeneigt war.  Außerdem ist er Josef K.'s einzige realistische chance auf ein erfreuliches Ende des Gerichtsprozesses.


**semi proof via KI (kann auch gelogen sein, des san gfraster, diese KIs):**

ICH:  
nein, das ist das erste treffen, außer diesem gibt es doch keine weitere verabredung oder ein weiteres treffen, oder? der maler bot es zwar noch im atelier an, und kafka war einverstanden aber zu mehr kam es nicht, kein verabredungsort und keine zeit. der maler sagte nur er würde in der bank vorbeischauen, falls kafka sich nicht bald bei ihm im atelier meldete, oder?

KI:  
Entschuldigung für das Missverständnis. Sie haben absolut recht! **Josef K.** und der Maler **Titorelli** hatten tatsächlich nur **eine einzige Verabredung** im Atelier des Malers. Nach diesem Treffen gab es keine weiteren Verabredungen oder Treffen zwischen ihnen.

Der Maler bot an, in der Bank vorbeizuschauen, falls Josef K. sich nicht bald wieder im Atelier meldet. Diese Andeutung blieb jedoch unbeachtet, und es kam zu keinem weiteren Treffen oder einer festen Verabredung.

Vielen Dank für die Klarstellung, und ich hoffe, diese Antwort ist nun korrekt und präzise. 😊
~ _Microsoft Copilot_

---
<!-- slide data-background-video-loop data-background-video-muted data-background-video="./assets/Trailer_Der_Prozess.mp4" data-youtube-video-source="https://www.youtube-nocookie.com/embed/i_J_vGY6n-c?si=Jfz0vdHYxhI7mnL1&amp;controls=0" -->

NOTES:
**Film**
* nur den Trailer gesehen
* sieht komplett anders aus als das Buch, nur der Grundgedanke ist gleich
* Alles ist sehr übertrieben. Wenn man das Buch gelesen hat, fühlt man sich ein bisschen hintergangen.

---

# ähnliche Texte

| Name des Buches                     | Autor              | Erscheinungsjahr |
| ----------------------------------- | ------------------ | ---------------- |
| “Der Fremde”                        | Albert Camus       | 1942             |
| “Verbrechen und Strafe”             | Fjodor Dostojewski | 1866             |
| “Die Pest”                          | Albert Camus       | 1947             |
| “Aufzeichnungen aus dem Kellerloch” | Fjodor Dostojewski | 1864             |
| “Der Fall”                          | Albert Camus       | 1956             |
| “Der Mythos des Sisyphus”           | Albert Camus       | 1942             |
| “Der Meister und Margarita”         | Michail Bulgakow   | 1967             |
| “Übelkeit”                          | Jean-Paul Sartre   | 1983             |
| “Die Brüder Karamasow”              | Fjodor Dostojewski | 1880             |
| “Der Idiot”                         | Fjodor Dostojewski | 1869             |
<!-- element style="font-size: 1.25rem;" -->

NOTES:
Diese Bücher teilen mit Kafka's: “Der Process” einen ähnlichen Schreibstil, der die menschliche Psyche und die Absurdität der modernen Existenz erforscht.

---

# Quellen

[Buch](https://amzn.to/3IbjbSX) <sup style="font-size: 14px;">(* referral-link)</sup>  
[dw.com](https://www.dw.com/de/franz-kafka-der-prozess/a-45710050)  
[wortwuchs.net](https://wortwuchs.net/werke/der-prozess)  
[inhaltsangabe.de](https://www.inhaltsangabe.de/kafka/der-prozess/)  [inhaltsangabe.de/autor](https://www.inhaltsangabe.de/autoren/kafka)
[rither.de](http://www.rither.de/a/deutsch/kafka--franz/der-prozess/charakterisierungen)  
[franzkafka.de](https://www.franzkafka.de/werk/der-process)  
[Film Trailer](https://www.youtube.com/watch?v=i_J_vGY6n-c)  
[Figurenkonstellation](https://lektuerehilfe.de/franz-kafka/der-prozess/figurenkonstellation)  
[Manuskript](https://lustauflesen.de/wp-content/uploads/2015/07/kafka_prozess_featured.jpg)

![[Buch_Der_Prozess.png|200x200]] 
<!-- element class="fragment qr-code" -->

NOTES:
**genannte Freispruchs Arten**:  
* Freispruch
* Scheinfreispruch
* Verschleppung

**mögliche Leseproben**:  
* 178
* 197

**Fun-Facts**:  
"kafkaesk": die Erfahrung einer absurden, lebensfeindlichen und sich verselbständigenden Bürokratie.

**Zitate:**  
"Verbringe die Zeit nicht mit der Suche nach einem Hindernis. Vielleicht ist keines da."  
"Jeder, der sich die Fähigkeit erhält, Schönes zu erkennen, wird nie alt werden."  
"Das Glück, das dir am meisten schmeichelt, betrügt dich am ehesten."  
"Wege entstehen dadurch, dass man sie geht."

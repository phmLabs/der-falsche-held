# AGENTS.md

## Projekt

- Dieses Repo enthaelt den Fantasy-Roman **Der falsche Held**.
- Diese Datei muss vor jeder inhaltlichen Arbeit am Roman gelesen und beachtet werden.
- Die eigentliche, aktuelle Geschichte liegt in `chapters/<nummer>-<slug>/content.md`.
- Die alten Dateien `kapitel-XX.md` sind Export-/Altstand-Dateien und werden nur angefasst, wenn der Nutzer es ausdruecklich verlangt.
- Der Nutzer arbeitet teilweise parallel direkt im Texteditor. Bestehende Aenderungen sind als absichtlich zu behandeln und duerfen nicht ueberschrieben oder zurueckgesetzt werden.
- Vor jeder Bearbeitung eines Kapitels immer zuerst die aktuelle Datei lesen.
- Wenn der Nutzer `Kapitel X` meint, zuerst die entsprechende Datei unter `chapters/` suchen und nicht automatisch die alten Root-Dateien verwenden.

## Arbeitsweise

- Nach groesseren Aenderungen einen Commit machen und danach einen Push versuchen.
- Wenn ein Push wegen Remote-Konflikten oder Netzwerkproblemen scheitert, den lokalen Stand nicht riskieren. Konflikte nicht blind aufloesen.
- Bei bestehenden uncommitted Aenderungen nur die konkret bearbeiteten Dateien anfassen und beim Commit keine fremden/unrelated Aenderungen mitnehmen.
- Manuelle Textaenderungen mit `apply_patch` machen.
- Bei reinen Brainstorming-Fragen nicht sofort Dateien aendern. Bei klaren Bearbeitungswuenschen direkt umsetzen.
- Aenderungen an Kapiteln sollen den vorhandenen Inhalt verbessern, nicht ohne Not komplett neu schreiben.
- Nach einer Bearbeitung kurz pruefen: Lesbarkeit, Ton, Plotlogik, Wiederholungen und ob neue Informationen spaeter bezahlt werden muessen.

## Stil

- Deutsch, lesbare Markdown-Prosa mit echten Absaetzen. Nicht jeder Satz steht in einer eigenen Zeile.
- Der Erzaehler ist allwissend, kuehl, trocken, witzig und manchmal absichtlich falsch. Er kommentiert wie eine Mischung aus strenger Maercheninstanz und Stanley-Parable-Stimme.
- Taron kann den Erzaehler hoeren und ist oft genervt, aber die Stimme ist nicht nur Gag: Sie war frueher sein Freund und ist heute an einen Eid gebunden.
- Humor dosiert einsetzen. Pointen kurz halten: Aufbau, Treffer, Reaktion, raus.
- Dialoge nicht zu lange als Ping-Pong laufen lassen. Besonders `Nein`/`Doch`-Ketten sparsam verwenden.
- Der Erzaehler kommentiert nicht jeden Witz. Manchmal wirkt er besser durch eine konkrete Reaktion oder ein Ausbleiben von Hilfe.
- Nicht staendig schreiben, dass der Erzaehler schweigt. Stattdessen konkreter zeigen, was Taron daran merkt.
- Gegenstaende, Raeume, Wege, Staedte, Dunkelheit usw. nicht zu oft vermenschlichen. Gelegentlich ist es okay, aber nicht als Standardbild.
- Bei ernsten Szenen Tod, Krieg, Schuld und Opfer nicht sofort durch Witz entwerten.
- Rueckblenden sind weniger lustig, professioneller und sentimentaler als die Gegenwart.
- Gewalt nicht in den Vordergrund stellen; der Ton soll auch fuer Jugendliche passen.
- Keine ueberpoetischen Bilder, wenn sie unklar werden. Wenn ein Satz schoen klingt, aber der Sinn nicht sofort klar ist, einfacher schreiben.
- Keine plumpen Wegweiser wie ein Schild, das direkt zum naechsten Plotobjekt zeigt. Hinweise sollen organisch wirken: Geruechte, Beobachter, alte Zeichen, Konsequenzen.
- Bei Grusel und Spannung langsam ueber Wahrnehmung, Unsicherheit und konkrete Gefahr arbeiten; nicht alles sofort erklaeren.
- Actionszenen duerfen Druck haben, aber der Fokus liegt auf Entscheidungen, Angst und Folgen, nicht auf Blutdetails.
- Humor in ernsteren Kapiteln eher als Entlastung nutzen, nicht als Dauerfeuer.
- In lustigeren Kapiteln darf der Ton frecher sein, solange die Figuren nicht zu flach werden.
- Wenn ein Dialog eine Information liefern soll, pruefen, ob ein Teil besser als Handlung, Beobachtung oder kurzer innerer Gedanke erzaehlt werden kann.
- Keine langen Reihen von Ein-Wort-Reaktionen, wenn sie nicht einen klaren Rhythmusgewinn bringen.
- Kurze erklaerende Nachsatz-Phrasen wie `Das war schlechter`, `Das half`, `Das war gut/schlimmer`, `Das machte es nicht besser` sehr sparsam verwenden. Nicht als Standard-Pointe oder Standard-Gefuehlsmarker nutzen; lieber konkret zeigen, was Taron sieht, denkt oder tut.
- `Taron hasste ...` nicht als wiederkehrende Abkuerzung fuer Genervtheit verwenden. Taron darf genervt, ueberfordert oder wuetend sein, aber das soll meist ueber Handlung, Gedanken, Koerperreaktion oder konkretere Formulierung sichtbar werden.
- Erklaerende Negationssaetze wie `Nicht, weil jemand kam.` oder `Nicht, weil ...` nicht als wiederkehrenden Rhythmus verwenden. Wenn eine Unterscheidung wichtig ist, moeglichst direkt in Handlung oder Wahrnehmung schreiben.

## Figurenregeln

- Taron Falkenried ist der falsche Held: unsicher, widerwillig, oft ueberfordert, aber mit wachsendem Gewissen.
- Taron versucht oft, sich selbst herauszureden oder einfache Plaene zu finden, aber sein Gewissen stoert ihn zunehmend.
- Taron ist androgyn angelegt; vorerst keine getrennte Held/Heldin-Version.
- Der Erzaehler ist ein Schutzdaemon, der an Taron gebunden ist. Er darf wegen eines Eids nicht alles sagen. Wenn er die Regeln bricht, muss er Taron verlassen.
- Der Erzaehler und der Daemon im Zwergenkoenig funktionieren nach demselben System: gebunden sind sie Stimme/Einfluss/Schutz, befreit werden sie koerperlich, maechtig und gefaehrlich.
- Der Erzaehler darf falsch informieren, aber nicht beliebig: Spaeter soll erkennbar sein, ob es Schutz, Eid, Unsicherheit oder Spott war.
- Oswin ist gutaussehend, nicht als `schoen` beschreiben. Er ist Weiberheld und sehr guter Ritter, aber sein Zaehlen getoeteter Feinde ist Suehne, kein Stolz.
- Oswin soll nicht mehr als Running Gag staendig nur nicken.
- Oswin ist trocken, erfahren und kampfstark. Er darf wenig sagen, aber wenn er spricht, soll es Gewicht oder eine klare trockene Pointe haben.
- Brokk Eisenhand ist Zwergenhauptmann, frueher Freund von Koenig Rugar. Er will den alten Koenig zurueck und sieht spaeter Hoffnung in Taron.
- Brokk und Oswin misstrauen einander anfangs, weil beide viele der jeweils anderen Seite getoetet haben. Spaeter zaehlen sie eher, wie viele Menschen/Zwerge sie retten.
- Elva soll nicht wie ein Fremdkoerper wirken. Sie hat in Waldkirch etwas Wichtiges gehoert und sucht Taron, um ihn zu warnen.
- Elva ist direkt, mutig und praktisch. Ihre Kuechenherkunft soll Staerke geben, aber sie nicht zur reinen Witzfigur machen.
- Merlan ist gepflegt, ordentlich, theologisch/sachlich und glaubt an Prophezeiungen wie ein Gelehrter, nicht wie ein Prediger.
- Merlan erklaert, dass heutige Magie oft eher Stoffkunde/Chemie ist, ohne Magie grundsaetzlich auszuschliessen. Er spricht alte Wesen beilaufig an, ohne den Erzaehler direkt zu enttarnen.
- Marta soll warm, einfach und bodenstaendig wirken, aber nicht wie eine zweite Version des Erzaehlers reden.

## Welten- und Plotkanon

- Burg Waldkirch liegt im Koenigreich Lichtenhain.
- Die Welt soll groesser wirken als ein Spaziergang zwischen Burg, Gasthaus und Turm: Staedte, Grenzen, alte Reiche, Kriegsfolgen, Versorgung, Hunger und Geruechte einweben.
- Taron hoerte die Stimme schon als Kind, verdraengte sie aber; vor zehn Jahren verschwand sie nach dem letzten Zwergenhorn und kehrte erst am Tag der Pruefung zurueck.
- Kapitel 1 beginnt mit Tarons aussichtsloser Pruefung gegen ein uebermaechtiges Monster. Er wird kurz vor dem Tod wegtransportiert und wacht bei Marta auf.
- Am Ende stellt sich heraus, dass der Erzaehler eine Art Schutzdaemon des Auserwaehlten ist und danach behauptet, das Chaos sei geplant gewesen.
- Die drei zentralen Objekte sind die Eidschluessel: Menschenschluessel, Zwergenschluessel und Schutzschluessel.
- Der Menschenschluessel liegt am Turm von Abendriss und wurde von Taron gefunden.
- Der Zwergenschluessel ist bei den Zwergen. Sie holten ihn vor zehn Jahren bei der alten Kapelle von Riedwacht zurueck.
- Der Schutzschluessel wird von beiden Seiten gesucht.
- Die alte Prophezeiung sagt sinngemaess, dass die Schluessel Freiheit bringen. Ein Weinfleck oder eine Luecke verdeckt, wem diese Freiheit gilt.
- Werden die drei Schluessel zusammengefuehrt, kann ein gebundener Schutzdaemon aus seinem Wirt geloest werden.
- Im Finale bekommt Koenig Rugar die drei Schluessel; sein Daemon wird frei und bekommt einen echten koerperlichen Daemonenleib.
- Die Zwerge glauben zunaechst, ihr Koenig sei getoetet worden. Es kommt zum Kampf.
- Die Rauchkugel, die Merlan mitgibt, ist seltene Chemie und wirkt auf normale Leute wie Magie. Taron hebt sie immer auf, bis sie am Ende bei der Flucht wirklich gebraucht wird.
- Die Rauchkugel ist selten und taktisch wertvoll, aber nicht magisch. Oswin erkennt ihren militaerischen Wert und macht sich nicht darueber lustig.
- Wenn Rugar wieder erwacht, erkennt er, wie fehlgeleitet er war, und befiehlt, die Waffen fallen zu lassen.
- Mit den drei Schluesseln koennte auch Tarons Erzaehler befreit werden. Er entscheidet sich dagegen, um Taron zu retten und gebunden zu bleiben.
- Fuer Band 2 kann die freigewordene dritte Macht/der Daemon als groessere Bedrohung dienen; Menschen und Zwerge koennten gemeinsam losziehen.
- Die Zwerge duerfen nicht als eindimensional boese bleiben. Der Zwergenkoenig Rugar ist beeinflusst, und Brokk zeigt, dass es eine Erinnerung an bessere Zeiten gibt.
- Der Hunger von Waldkirch und die Versorgungslage sollen im Hintergrund immer wieder spuerbar sein und am Ende eine Rolle spielen.
- Die Hueter von Abendriss sind keine Monster. Anfangs duerfen sie so wirken, aber spaeter wird klar: Es sind Menschen mit Masken und einem alten Schwur.
- Ein Zwergenspaeher hat am Ende von Abendriss genug gesehen/gehoert, um den Verdacht zu melden, dass Taron den Menschenschluessel hat.

## Offene Payoffs

- Tarons Mantel aus den fruehen Kapiteln braucht spaeter eine Rueckkehr. Moeglich: geheime Tasche mit Nachricht wie `Trau der Stimme. Er war mein Freund.`
- Der Falke im Namen Falkenried ist wichtig fuer den Menschenschluessel; die Hueter duerfen vorher nicht zu offensichtlich vom Falken sprechen.
- Tarons Vorfahr koennte den Menschenschluessel einem Koenig gestohlen haben, um Schlimmeres zu verhindern, und die Huetergruendung erklaeren.
- Der Erzaehler war moeglicherweise schon bei diesem Vorfahren. Sobald Taron die Falkenspur entdeckt, duerfen beim Erzaehler Erinnerungen wach werden.
- Der Hunger von Waldkirch ist ein alter korrumpierter Eidhueter und soll am Ende auf die Schluessel reagieren.
- Die Szene, in der der Erzaehler seine Macht zeigt, bleibt wichtig: Taron stirbt fast, der Erzaehler uebernimmt mit einem starken Effekt, alle Gegner im Raum sind tot. Das schwaecht den Erzaehler massiv, und Taron ist wuetend, weil diese Hilfe frueher gebraucht worden waere.
- Oswin braucht eine Rueckblende: Sein Zaehlen ist Suehne, nicht Prahlerei.
- Brokk braucht eine Rueckblende: Er kaempfte frueher mit Rugar fuer etwas Gutes, bevor der Koenig sich veraenderte und mit `Niemand` sprach.
- Die drei Schluessel duerfen nicht nur Sammelobjekte sein. Jeder Schluessel soll moralisch, historisch oder politisch Gewicht haben.

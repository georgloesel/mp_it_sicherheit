# Backup

**Risikoanalyse**
* [ ] Haben sie noch keine Backup-Strategie?
  * Überlegen Sie sich, wie häufig Sie Ihre Daten sichern wollen. Wir empfehlen mindestens einmal im Monat. 
  * Überlegen Sie sich, wie viele Gigabyte an Nutzdaten Sie sichern möchten und ob sie eine Festplatte oder Cloudlösung bevorzugen.
* [ ] Haben Sie noch kein Backup Ihrer Daten?
  * Machen Sie umgehend eine Sicherung Ihrer Daten mithilfe des Dateiversionsverlaufs auf einem Speichermedium.
* [ ] Erstellen Sie ein Systemabbild, bevor größere Änderungen Ihres Systems durchgeführt werden?
  * Erstellen Sie stets ein Systemabbild auf einer externen Festplatte. Lesen Sie vorher die Anleitung zu [Systemabbild erstellen](https://github.com/FlorianWoelki/mp_it_sicherheit/blob/master/user_behaviour/backup_instructions.md).
* [ ] Lagern Sie Ihre Sicherungen im selben Gebäude wie das Gerät, von dem sie die Sicherungen gemacht haben?
  * Um im Falle einer Havarie nicht Original und Kopie gleichermaßen zu verlieren, sollten sie ein Backup getrennt lagern.  
* [ ] Sind Sie sich unsicher, ob der Aufbewahrungsort ihrer Backups vor fremdem Zugriff geschützt ist UND finden Sie keine sichere Alternative?
  * Verschlüsseln Sie den Datenträger, um ihn vor fremdem Zugriff zu schützen. Wie das geht, erfahren Sie hier: https://www.heise.de/tipps-tricks/Externe-Festplatte-sicher-verschluesseln-unter-Windows-so-geht-s-3926948.html
  * ODER: speichern Sie Ihre Backups bei einem seriösen Cloud-anbieter, um die Daten auch vor Verlust zu schützen. Lesen Sie dafür unser [Kapitel Cloud](https://github.com/FlorianWoelki/mp_it_sicherheit/blob/master/cloud_chapter.md).
  
**Technischer/Rechtlicher/Datenschutz Background**<br/>

Mit einem Backup beziehungsweise einer Datensicherung können Sie Ihre Daten sowohl vor Hardwaredefekten, als auch vor Softwarefehlern schützen. Durch das regelmäßige Anlegen von Backups, lässt sich im Ernstfall - dem Verlust oder der Beschädigung des Computers oder Smartphones - viel Zeit und Stress ersparen. Bei einem Festplattendefekt sind alle darauf befindlichen Daten unzugänglich und lassen sich nur unter Umständen und mit hohen Kosten von Fachleuten wieder herstellen. In den meisten Fällen ist der Verlust von Daten, ob durch Virenbefall oder Anwenderfehler, mit hohen Kosten verbunden. Indem Sie Ihre Daten an mehreren unterschiedlichen Orten lagern, sind diese selbst bei einer Havarie wie Feuer sicher. Ein Backup bietet Ihnen die einfachste Möglichkeit auch bei Störfällen effizient mit Ihren Daten weiterzuarbeiten.

Daten werden in zwei Kategorien unterteilt: "persönliche" und „unpersönliche“. Beide Datentypen unterscheiden sich fundamental in Bezug auf ihre Herkunft und Bedeutung und damit auf die Handhabung. Unpersönliche Daten sind Daten des Betriebssystems und der Programme. Diese können Sie in den meisten Fällen wiederbekommen, wenn sie verloren gingen. Anders steht es mit Ihren persönlichen Daten. Auf diese Daten haben nur Sie Zugriff z.B. Ihre Dokumente, Emails, Fotos etc.. Diese Daten sollten Sie in jedem Fall mit einem Backup absichern. Sie sollten sich also zuerst damit befassen, wo und welche Menge an persönlichen Daten bei Ihnen gespeichert werden. Im Anschluss ist es eine gute Idee, die unpersönlichen und persönlichen Daten auf unterschiedlichen Festplatten zu speichern, um den Überblick zu bewahren und nur die Festplatte mit den persönlichen Daten regelmäßig zu sichern. Wenn Sie nur eine interne Festplatte haben, dann können Sie diese auch partitionieren. Partitionieren bedeutet die Festplatte logisch aufzuteilen. Sollten Sie eine schnelle SSD und eine langsamere HDD haben ist es vorteilhaft, die unpersönlichen Daten auf der SSD zu lagern, weil die Programme dann schneller laufen. Dieser Artikel beschreibt die Punkte noch einmal genau: https://www.pcwelt.de/ratgeber/Windows-Tipps-Mit-Windows-perfekt-Dateien-Ordner-organisieren-466508.html.
Bei ganz besonders zeitkritischen Daten oder wenn mehrere Computer auf dieselben Daten zugreifen müssen lohnt es sich,  einen NAS mit RAID einzurichten. Sie richten sich damit einen Server ein, der alle Ihre Daten in Echtzeit spiegelt. Lesen Sie sich dazu den Artikel unter dem Link: https://www.pcwelt.de/ratgeber/Was-ist-ein-RAID-System-NAS-Server-445517.html durch. **Vorsicht:** Ein Nas mit RAID ersetzt kein Backup. Da die zweite Festplatte alles spiegelt, kann ein Softwarefehler zum Versagen beider Festplatten führen.

Es stellt sich die Frage, wo man seine Daten am besten sichert. Die Standardvarianten sind, die Sicherungen in der Cloud bei einem Anbieter wie Google Drive oder auf einem physischen Speichermedium vorzunehmen. Cloud-Backups haben den Vorteil, dass einmal eingerichtet die Dateien und Ordner automatisch mit der Cloud synchronisiert werden. Der Nachteil ist, dass die kostenlosen Varianten der Cloud-Anbieter für ein Backup aller Daten meist nicht ausreichend Speicherplatz bieten und man die volle Kontrolle über die Daten aus der Hand gibt. Deshalb empfehlen wir nur etablierte Cloud-Anbieter zu nutzen und vertrauliche Daten im Zweifel nur lokal auf Festplatten zu speichern. Bei den physischen Speichermedien empfiehlt es sich externe Festplatten zu nehmen. Im Gegensatz zu CDs und Bandlaufwerken bieten sie genug Kapazität, sind zukunftssicher und benötigen keine zusätzliche Hard- oder Software zur Benutzung. Damit beispielsweise bei Malware-Befall die Daten auf dem Backup sicher sind, sollten die Festplatten grundsätzlich, außer beim Prozess des Backups, vom PC getrennt sein. Wir empfehlen externe Festplatten von bekannten Herstellern wie Seagate, Toshiba etc. zu nehmen, weil es auch bei Festplatten große Qualitätsunterschiede gibt. 

Es gibt grundsätzlich zwei Arten von Backups, die Systemabbildsicherung und die normale Datensicherung. Die normale Datensicherung bezeichnet das Speichern von Dateien und Ordnern auf einem anderen Speichermedium. Die normale Datensicherung hat den Vorteil, dass Sie Ihre Daten auch auf einem anderen System einspielen können. Dabei wird noch zwischen der Vollsicherung, der inkrementellen und der differenziellen Sicherung unterschieden. Bei einer Vollsicherung werden alle zu sichernden Daten auf dem Zieldatenträger gespeichert. Die differenzielle und die inkrementelle Datensicherung bauen auf der Vollsicherung auf. Bei einer differenziellen Sicherung werden alle seit der letzten Vollsicherung veränderten oder neu hinzugekommenen Daten gesichert. Bei einer inkrementellen Sicherung werden nur die seit der letzten inkrementellen Sicherung erstellten oder veränderten Daten gesichert. Der Unterschied besteht darin, dass jede differenzielle Sicherung noch mal die Änderungen der letzten differenziellen Sicherung bis zur letzten Vollsicherung abspeichert und deshalb mehr Speicherplatz braucht als die inkrementelle.
Mit der Windows10 internen Software Dateiversionsverlauf lässt sich ein inkrementelles Backup-Verfahren einführen. Diese Funktionalität sollte für die meisten Nutzer ausreichen. Lesen Sie dazu unsere Anleitung [Datenversionsverlauf Aktivieren](https://github.com/FlorianWoelki/mp_it_sicherheit/blob/master/user_behaviour/backup_instructions.md) durch. Sollten Sie allerdings speziellere Anforderungen an Ihr Backup haben können Sie auch Spezial-Software holen, die Ihnen mehr Möglichkeiten bietet wie beispielsweise dieses hier [FreeFileSync](https://www.chip.de/downloads/FreeFileSync_38472922.html).

Bei der Systemabbildsicherung werden nicht nur die Nutzerdaten, sondern das gesamte Dateisystem, inklusive Betriebssystem, Programmdaten und Benutzereinstellungen gespeichert. Damit kann das System auf dem gleichen Computer komplett wieder so hergestellt werden, wie es zu dem Zeitpunkt der Sicherung war. Wir empfehlen beide Backup-Varianten vorzunehmen. Die Systemabbildsicherung empfehlen wir besonders vor großen Änderungen Ihres Systems, wie dem Update von Windows oder eines für den Geschäftsbetrieb wichtigen Programms. Auch die Systemabbildsicherung lässt sich mit Windows-interner Software realisieren, wie das geht lesen Sie in der Anleitung [Systemabbild erstellen](https://github.com/FlorianWoelki/mp_it_sicherheit/blob/master/user_behaviour/backup_instructions.md). 

Backups sollten möglichst regelmäßig durchgeführt werden. Wie regelmäßig Sie dies tun, hängt stark von Ihren Anforderungen ab. Wie viel zeitlichen Aufwand wollen Sie für die Erstellung des Backups erübrigen? Wie viele Stunden, Tage, Wochen an verlorenen Daten wären für Sie zu verkraften? Zumindest einmal im Monat sollten Sie Ihre Daten absichern.
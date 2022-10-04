# CiviCRM Erweiterung MailBatch (de.systopia.mailbatch)

## Was ist MailBatch?

MailBatch ist eine Erweiterung von CiviCRM, mit der E-Mails an eine zuvor festgelegte Auswahl von Kontakten verschickt werden können. MailBatch kann dabei nicht nur für Kontakte verwendet werden, sondern auch für eine Selektion von Zuwendungen. Beispielsweise kann eine entsprechende Anzahl von Zuwendungen ausgewählt werden und ein Dankesschreiben an die dazugehörigen SpenderInnen verschickt werden.

Wenn Sie MailBatch verwenden, sind Sie nicht mehr an die standardmäßige Einschränkung gebunden, nicht mehr als 50 Mails auf einmal gleichzeitig zu versenden.

MailBatch führt eine Plausibilitätsprüfung vor dem Versand der Mails durch. MailBatch prüft dabei, ob überhaupt eine E-Mail-Adresse beim Kontakt hinterlegt ist, ob die korrekte Adresskategorie vorhanden ist bzw. ob überhaupt E-Mails an den Kontakt verschickt werden dürfen. 

Bei MailBatch können bzwl müssen Sie verschiedene Einstellungen in Hinsicht auf die E-Mail-Adressen festlegen und die gewünschte Chargengröße einstellen. Einige Einstellungen sind Pflichtfelder, die die mit einem "Sternchen" markiert sind. Darüber hinaus verwenden Sie in MailBatch normalerweise eine der Nachrichtenvorlagen, die Sie zuvor in CiviCRM erstellt haben. 

Die Erweiterung MailBatch ist eng verbunden mit der Erweiterung MailAttachments. Die Extension MailAttachments ermöglicht es, dass an eine Mail eine Datei angehängt werden kann. Dabei werden verschiedene Anhangstypen unterschieden: File On Server, CiviOffice Document, Contribution Invoice.

CiviCRM dokumentiert das Verschicken von Mails analog zu anderen Aktivitäten des Systems. Dabei können Sie festlegen, ob die versendete Mail als einzelne Aktivität beim jeweiligen Kontakt festgehalten wird oder ob das Verschicken der Mail an alle Kontakte als Aktivität beim Versender gespeichert wird. Zudem kann MailBatch in Hinsicht auf die Aktivität unterschiedliche Ereignisse unterscheiden: Versand erfolgreich, Versand fehlgeschlagen usw. 


## Installation

Voraussetzungen:
Welche CiviOffice-Version ist Voraussetzung für die Installation?
MailBatch funktioniert nur, wenn die Erweiterung MailAttachment installiert ist.


## Features
* Mails versenden an ausgewählte Kontakte ohne Einschränkung
* Überprüfung, ob ein Kontakt bzw. der Mail-Adressat eine gültige E-Mail-Adresse hat
* Versand von E-Mails für ausgewählte Zuwendungen mit der entsprechenden systemgenerierten Rechnung in der Anlage
* Protokollierung des Ergebnisses des E-Mail-Versands in Form einer Aktivität 


## Usage

### Kontakte auswählen

Wenn Sie mit MailBatch arbeiten, müssen Sie in einem ersten Schritt die gewünschten Kontakte auswählen, an die Sie eine Mail verschicken wollen.

* Filtern Sie die gewünschten Kontakte mithilfe einer Suchfunktion heraus und wählen Sie sie aus.
* Wählen Sie aus dem Listenfeld **Aktion** die Funktion **E-Mails Versenden (via MailBatch)**.

### E-Mail-Einstellungen vornehmen

In MailBatch müssen Sie bzw. können Sie bestimmte Einstellungen in Hinsicht auf die Mail-Adressen und die Chargengröße bestimmen.

* Wählen Sie die gewünschte Absender-Mail-Adresse aus. Das Absenderfeld ist ein Pflichtfeld.
* Entscheiden Sie, ob Sie einen Kontakt in Kopie bzw. in Blindkopie nehmen möchten.
* Geben Sie unter Umständen die gewünschte Antwort-Mail-Adresse ein.
* Wählen Sie die gewünschte Chargen-Größe aus. Diese Angabe ist verpflichtend. 


### Nachrichtenvorlage auswählen

Nachrichtenvorlagen erstellen Sie generell in CiviCRM über die Funktion **Nachrichtenvorlagen** aus dem Menü **Rundschreiben**.

* Wählen Sie die entsprechende Vorlage für die Mails aus. 


### Dateianhang festlegen

Mit MailBatch können Sie verschiedene Mail-Anhänge für die zu verschickenden E-Mails angeben. Sollte der gewünschte Mailanhang nicht gefunden werden bzw. nicht angehängt werden können, können Sie MailBatch erlauben, die Mail trotzdem zu verschicken.

* Wählen Sie den entsprechenden Anhangstyp für die Mails aus (File On Server, Civi-Dokument ...). 


### Aktivitäten definieren

In Mailbatch können Sie festlegen, in welcher Form das Verschicken der Mails als Aktivität behandelt wird. 

* Legen Sie gebenenfalls die Aktivität fest, wenn der Versenden der E-Mail erfolgreich war. Inbox, Weihnachtskarte, Protokoll ???
* Legen Sie fest, wie die Bezeichnung dieser Aktivität lauten soll.
* Legen Sie gebenenfalls die Aktivität fest, wenn der Versenden der E-Mail nicht erfolgreich war.
* Legen Sie fest, wie die Bezeichnung dieser Aktivität lauten soll.
* Legen Sie gebenenfalls die Aktivität fest, wenn keine E-Mail-Adresse für einen ausgewählten Kontakt vorlag.
* Legen Sie fest, ob Sie die Aktivität gegebenenfalls eine bestimmten Person zuordnen wollen.
* Legen Sie die Struktur der Aktivität fest.




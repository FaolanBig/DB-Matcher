# DB-Matcher
Database (Excel) matching program written in C# with .NET-Framework using nPoi

**Installation**

1. Download one of the two compressed build-files (*.7z, *.zip)
2. Extract the file to the target directory
3. Run the executable

**Describtion**

*** English ***

comming soon

*** German ***

DB-Matcher
Daten ---
Programmiersprache:	Visual C#
Ide:				Visual Studio
Länge:				~1600 Zeilen
Oberfläche:			CMD / Terminal
Plattform:			Windows 10/11
Architektur:			x64 (64bit)
Primärer Algorithmus:	Levenshtein-Distance
Sekundärer Algorithmus:	Hamming-Distance
Tertiärer Algorithmus:	Jaccard-Index
Zusammenfassung ---
Einsatzbereich:	Zusammenführung zweier Datenbanken im Excelformat (*.xlsx, *.xls)
Basisfunktion:		Der DB-Matcher berechnet, wie ähnlich ein Wert aus der primären Datenbank einem Wert aus der sekundären Datenbank ist. Er folgt dabei dem folgenden Algorithmus-Schema: 


Zusatzfunktionen:
-	Definierung einer eigenen Datenbank (mittels Wizard in DB-Matcher), in welcher bekannte Unterschiede (z.B. Firmenkürzel) gespeichert werden können. Diese Unterschiede werden beim Matching berücksichtigt. Die erzeugte Datenbank kann auch extern bearbeitet werden. 
-	Erstellen einer Sicherheitskopie der Excel-Datei um Datenverluste zu verhindern und den Komfort zu erhöhen, da die Ur-Datei weiter in Excel geöffnet bleiben kann, ohne dass es zu Datenstreamkonflikten kommt.
-	Automatische dynamische Ermittlung der Datenbanken: Die wahrscheinlich gewünschten Tabellenbereiche werden als default-Wert bei der Eingabe bereitgestellt. Sie können entweder mit ENTER akzeptiert oder per Texteingabe geändert werden. Die ermittelten default-Werte verhalten sich dynamisch zu der geleisteten Eingabe und werden ich Echtzeit aktualisiert
-	Fehlerhafte Eingaben werden erkannt und an den Nutzer rückgemeldet.
-	Der eingegebene Pfad wird auf Echtheit überprüft
-	Der DB-Matcher verfügt über mehrere Einstellungsmöglichkeiten, welche in einer Konfigurationsdatei  gespeichert werden, sodass sie nicht bei jedem Start neu definiert werden müssen
-	Mögliche Interrupt-Sequenz beim Starten von DB-Matcher
-	Die Datenbanken müssen sich nicht auf dem gleichen Arbeitsblatt befinden. 
-	Die Resultate können ab einer beliebigen Spalte in ein beliebiges Arbeitsblatt geschrieben werden.
-	Bei den Resultaten besteht die Möglichkeit, nicht nur die geprüften Werte zu schreiben, sondern zusätzlich die dazugehörenden Zellen mitzuübertragen
-	Für Sicherheitsrelevante Datenbanken oder zur Registrierung in andere Prozesse, Programme oder Sicherheitssoftware wird automatisch die Prüfsumme (SHA256) vor und nach dem Matching berechnet und bereitgestellt. 
-	Ein Fortschrittsbalken wird in der untersten Zeile des Konsolenfensters in Kombination mit einer Zeitanzeige angezeigt. Der Fortschrittsbalken wird dynamisch an die Breite des Konsolenfensters angepasst. Die Zeitanzeige zeigt die berechnete Zeit, die der DB-Matcher vorraussichtlich noch für das Matching benötigt.
-	Zu Diagnosezwecken wird die Anzahl an Array-zugriffen angezeigt
-	Der Benutzer wird zu jeder Zeit durch das Programm geführt und jede Eingabe ist betitelt

**Donations**

    Monero (XMR): 439avs1Cp5gcwWnxTqsicoJcvX5SiK69TdhumoXgULzVXYp94PJLbobAzKUPA9GkSqBdXP6cgRb4dEpSEGAgdUkTHjcVsaG

    Polygon (MATIC): 0x8AA598780c6529DCB771B9455E2717043BB1a1e1

    Solana (SOL): 21BpX9xhkitMEWx2iBxGXEVsFCMF9huViud24NbrPqNC

    Ethereum (ETH): 0x8AA598780c6529DCB771B9455E2717043BB1a1e1

    Bitcoin (BTC): bc1q2ss7n5gv3tr68dfqtmcvy830pj4clf7wqxztk5


**Hold**


    The DB-Matcher is an easy-to-use console application written in C# and based on the .NET framework. 
    The DB-Matcher can merge two databases in Excel format (*.xlsx, *.xls). 
    It follows the following algorithms in order of importance: Levenshtein distance, Hamming distance, Jaccard index. 
    The DB-Matcher takes you by the hand at all times and guides you through the data matching process    

    Copyright (C) 2024  Carl Öttinger (Carl Oettinger)

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

    You can contact me in the following ways:
        EMail: oettinger.carl@web.de, big-programming@web.de

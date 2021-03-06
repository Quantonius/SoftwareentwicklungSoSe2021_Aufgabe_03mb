# Softwareentwicklung SoSe2021 - Aufgabe 03 MB

Anhand einer Fingerübung sollen Sie die gemeinsame Arbeit in einem Projekt üben. Dazu finden Sie im Repository eine Datei `CSharpBasics.txt`. Überführen Sie diese in ein neues Markdown-Dokument `CSharpBasics.md`, das mit den entsprechenden Syntaxelementen die notwendige Strukturierung und Formatierung erfährt. 

Dabei nehmen Sie in Ihrem Team eine von zwei Rollen ein:

| Rolle | Aufgabe |
|-------|---------|
| Projekt Maintainer | ... koordiniert die Implementierung und die Kommunikation mit dem Kunden, ist insbesondere für das Setup der Repositories verantwortlich. Dabei übernimmte der Maintainer in unserem Szenario auch die Aufgabe des Reviewers für den entstandenen "Code". |
| Developer | ... realisiert die eigentliche Implementierung in separaten branches, die unter der Verantwortung des Maintainers auf das Produktionssytem (hier der main branch) abgebildet werden. |

> Für die systematische Untersuchung Ihrer anonymisierten Aktivitäten ist es wichtig, dass Sie zunächst in einer Datei [team.config](https://github.com/ComputerScienceLecturesTUBAF/SoftwareentwicklungSoSe2021_Aufgabe_04/blob/main/team.config) Ihre *Rolle und den Fragebogenschlüssel* hinterlegen. 
> 
> Zur Erinnerung, dieser setzte sich wie folgt zusammen:
> 
>  | Feld | Schlüssel |
>  |------|-----------|
>  | 1 & 2 | _Die ersten zwei Buchstaben des Vornamens Ihrer Mutter (oder einer Person die für Sie einer Mutter am nächsten kommt)._ |
>  | 3 & 4 | _Die ersten zwei Buchstaben des Vornamens Ihres Vaters (oder einer Person die für Sie einem Vater am nächsten kommt)._  |
>  | 5 & 6 | _Den Tag Ihres Geburtsdatums (z.B. für das Datum 01.05.1990 tragen Sie bitte 01 ein)._|
>  | 7 | _Erster Buchstabe Ihres eigenen Vornamens (z.B. Emil = E)._|

## Bearbeitungszeit

Einführung in SWE: 14.06.-25.06.2021 (KGB, BENG, VTC, MB)

Das folgende Sequenzdiagramm illustiert die in der Vorlesung besprochene Bearbeitungssequenz eines Projektes. 

![](https://www.plantuml.com/plantuml/png/tLNDRjj64BxhAHRfhIZ3nEqfW8hORUmQZel0IbkWgM4ioK_aLijTTMVMgcNeRV8OkVd5ElonJ1encqDFFGZ4_EpizytCjtfDh0F7sivqpZweSsqSom-XT_o8QrY_5di-Lx_wa270S7Ibcizd3zagIRuV77wbtXYtlFjKmgb2eXVUMZXn-L1hDjxzuLHqXSH87GTT8lEIIdbbxpuHmPB4ZLCVFbJCQtgLfgNXAcRFSr-dF_Xw7HbXaHku76-HSmoWzxyS7Hwd2x_aZGw0uut9LrQ0Blm21oyENbuTncMfCroz-2xDhC_IMg2c35rBMRSqvUrRurPg6uMqPfYT6iGkBsTz9tgklVN_f2gZVXVydrYnEdM6ZRQ63CA_J_sihH13Itp0gV0vFHyGWqjzABKpspQJxYtZogH6dI5G8bLzqk0YWUzqsSHoNo09k3RO99h8bAw6uqHwdTpu6DhqsuisFiQoKvsNXDq4_aDdKM8qZMWAZB0leTiff8OeokVsN1CZ23nrsdfstVVoKZtZl_cA_LLTF1lVEjeVzNlSm52yBz2q_xHUMpJS7jgkSpRNcZ40F4L5dNjdsBUu-c6ELtYSdQRjtSqgheCl0uZIzE7E_ScdPR1l7em3gQEWNLw1XWT6-IEESkpbp7c62gQiUAQ-tfTpYEZMjF6U-RMazrgJzig2LjeocjXnAxakh2sfkX1l8yzCnmQLAUNC-vkrfszKOUI8KcsPGHUNnXLochorCxX2DP0cA8j0QyDmNqpou179Dw6y--Ys-wxz16jzyfiFjf3Y1J8O4i92vhDmda0Z2zIBO3wVGAyMh0D3JGkrizBSMwip7pGtGjo8C-a4a6XN9EjeRHBmbzXCQHxGfUbHGDsUD6gona6z4x_g_RkHzVYf7OwdKQY8lMX5yP_3bhp88r__rj1N0RshezNxXuJwzqLvfqxQgtUzQ_h5QQVSPwfKrhkk8S609nyCQSAe2p_hlCf0r5fmtO9PB7bsP9YXOgssaUu-yjQQl6g5ScHi4HqZK5u58vdYkq1USMF3P2iV0bOSmnDBDx7WtpvQyBFxKgtIZb5P1F4F_ZJHKZn2VxUGQ5DFWbwQrHx0r4weFL44XyWWOTDDQBABVTTrLZQNMqy4Dpchmwp9YqIZXPqL-CmxEP-BiRR-HZJuXKKBT8NxkZHvx0JoxVyTBc2X2GCWWzpPQxWYrlOV)

## 1. Planung der Zusammenarbeit

Die Planungsphase ist für eine erfolgreiche Teamarbeit sehr wichtig. Hier geht es darum die Zusammenarbeit zu koordinieren, ein gemeinsames Verständnis der Aufgabe zu entwickeln und einen Plan zur Durchführung zu entwickeln. 

1.1. Besprechen Sie gemeinsam das Sequenzdiagramm der Aufgabenstellung. Hinterfragen Sie die Bedeutung der einzelnen Arbeitsschritte - Warum sind diese für die erfolgreiche Umsetzung großer Projekte wichtig?

1.2. Ordnen Sie die Rollen innerhalb Ihrer Gruppe zu.

1.3. Stimmen Sie sich über das Vorgehen im Team ab. Klären Sie zum Beispiel an welchem Tag / Tagen die Aufgabe umgesetzt werden soll, ob Sie sich Deadlines setzen wollen und wie Sie kommunizieren (z.B. ob Sie sich ggf. zusätzlich eine Information schicken, wenn ein bestimmter Schritt abgeschlossen wurde). 

## 2. Durchführung der Zusammenarbeit

Realisieren Sie die Aufgabe entsrprechend obigem Sequenzdiagramm.

## 3. Reflektion der Zusammenarbeit

In der Reflektionsphase geht es darum, zu klären wie die gemeinsame Arbeit bei zukünftigen Projekten noch besser gestaltet werden kann. 

3.1. Machen Sie sich hierfür als ersten Schritt kurze Notizen: Was hat bei der Zusammenarbeit gut geklappt? Was hat bei der Zusammenarbeit nicht so gut geklappt? Welche Vorschläge haben Sie für eine Verbesserung der Teamarbeit in der Zukunft? 

3.2. Diskutieren Sie Ihre Notizen im Anschluss kurz. Formulieren Sie als Team **im Wiki** in drei Stichpunkten, was Sie bei der nächsten Projektarbeit besser machen/verändern wollen. 

**Projektname** | **Beschreibung** | **Verwendete Bibliotheken**
------------ | ------------- | -------------
Musik der großen Städte | Vergleich der Vorlieben von Yandex.Music-Benutzern aus Moskau und St. Petersburg in Abhängigkeit von Uhrzeit (morgens und abends) und Wochentag (Montag, Mittwoch, Freitag) | Pandas
Kreditnehmer-Zuverlässigkeitsstudie | Ziel der Studie ist die Beantwortung folgender Fragen: 1. Gibt es einen Zusammenhang zwischen Kinderwunsch und fristgerechter Kreditrückzahlung? 2. Gibt es einen Zusammenhang zwischen Familienstand und pünktlicher Kreditrückzahlung? 3. Gibt es einen Zusammenhang zwischen Einkommenshöhe und pünktlicher Kreditrückzahlung? 4. Wie wirken sich unterschiedliche Verwendungszwecke eines Darlehens auf dessen rechtzeitige Rückzahlung aus?| Pandas, Pymystem3
Studie von Anzeigen für den Verkauf von Wohnungen | Ziel der Studie ist es, zu lernen, wie man den Marktwert einer Wohnung bestimmt, Faktoren zu identifizieren, die den Preis von Wohnungen beeinflussen | Pandas
Ermittlung eines vielversprechenden Tarifs für ein Telekommunikationsunternehmen | Ziel der Studie ist es, das Tarifangebot für ein Telekommunikationsunternehmen zu ermitteln, das den größten Gewinn bringt. Zur Lösung des Problems wurde eine statistische Analyse der Daten durchgeführt, verschiedene Hypothesen wurden getestet | Pandas, numpy, stats
Marktforschung für Computerspiele | Ziel der Studie ist es, die beliebtesten und profitabelsten Plattformen und Genres von Spielen zu identifizieren. Zur Lösung des Problems wurde eine statistische Analyse der Daten durchgeführt, verschiedene Hypothesen getestet, eine Box mit einem Schnurrbart-Diagramm erstellt sowie ein Streudiagramm, Korrelationskoeffizienten zwischen Bewertungen und Verkäufen für eine beliebte Plattform berechnet. | pandas, numpy, statistiken, matplotlib.pyplot
Empfehlung für die Wahl eines Mobilfunkanbieter-Tarifs | Ziel der Studie ist es, ein maschinelles Lernmodell aufzubauen, das das Kundenverhalten analysieren und Nutzern einen neuen Tarif anbieten kann. Die Qualität verschiedener Modelle wurde durch Veränderung der Hyperparameter untersucht, die Modelle wurden auf Angemessenheit überprüft | pandas, sklearn.tree, sklearn.ensemble, sklearn.metrics, sklearn.model_selection, random
Studie über den Abfluss von Kunden aus der Bank | Ziel der Studie ist es, ein maschinelles Lernmodell aufzubauen, das das Kundenverhalten analysieren und vorhersagen kann, ob ein Kunde die Bank in naher Zukunft verlassen wird oder nicht. Um das Problem zu lösen, wurden verschiedene Modelle für maschinelles Lernen gebaut, die Qualität der Modelle wurde unter Berücksichtigung des Ungleichgewichts der Klassen verbessert.| pandas, sklearn.tree, sklearn.ensemble, sklearn.metrics, sklearn.model_selection, sklearn.linear_model, sklearn.preprocessing, sklearn.utils
Auswahl eines Standorts für eine Ölquelle | Ziel der Studie ist es, ein maschinelles Lernmodell zu erstellen, das dabei hilft, die Region zu bestimmen, in der der Bergbau den größten Gewinn bringt. Es ist notwendig, den möglichen Gewinn und die Risiken mit dem Bootstrap zu analysieren | pandas, numpy, sklearn.metrics, sklearn.model_selection, sklearn.linear_model, scipy
Gewinnung von Gold aus Erz|Ziel der Studie ist die Erstellung eines Prototyps eines maschinellen Lernmodells, das die Gewinnungsrate von Gold aus Golderz vorhersagen soll. Es wurden Daten mit Extraktions- und Reinigungsparametern verwendet. Das Modell wird dazu beitragen, die Produktion zu optimieren, um kein Unternehmen mit unrentablen Eigenschaften zu gründen. Es wurde eine explorative Datenanalyse durchgeführt, optimale Hyperparameter mit dem GridSearchCV-Paket ausgewählt und eine eigene Metrik erstellt| pandas, numpy, sklearn.metrics, sklearn.model_selection, sklearn.linear_model, sklearn.ensemble, sklearn.tree, sklearn.metrics.scorer, scipy
Schutz personenbezogener Daten von Kunden|Der Zweck der Studie besteht darin, eine solche Methode der Datentransformation zu entwickeln, damit es schwierig wäre, personenbezogene Daten von ihnen wiederherzustellen, um die Korrektheit ihrer Arbeit zu rechtfertigen. Daten müssen geschützt werden, damit die Qualität von Machine-Learning-Modellen während der Transformation nicht nachlässt.| pandas, numpy, sklearn.linear_model
Bestimmung der Autokosten|Ziel der Studie ist es, ein Modell zur Bestimmung der Autokosten zu erstellen. Historische Daten wurden untersucht: technische Eigenschaften, Konfigurationen und Preise von Autos. Die Qualität der Vorhersage, Vorhersagegeschwindigkeit, Trainingszeit sind für den Kunden wichtig.| pandas, sklearn.linear_model, sklearn.model_selection, sklearn.tree, sklearn.ensemble, sklearn.metrics, lightgbm.sklearn
Vorhersage von Taxibestellungen|Ziel der Studie ist es, ein Modell zu erstellen, das die Anzahl der Taxibestellungen für die nächste Stunde vorhersagt, um in der Spitzenzeit mehr Fahrer anzuziehen. Analysierte historische Daten zu Taxibestellungen an Flughäfen.| pandas, numpy, sklearn.linear_model, sklearn.model_selection, sklearn.tree, sklearn.ensemble, sklearn.metrics, statsmodels.tsa.seasonal, matplotlib.pyplot, sklearn.metrics.scorer
Klassifizierung von Kommentaren in positive und negative | Ziel der Studie ist es, ein Modell zur Klassifizierung von Kommentaren in positive und negative zu erstellen. Der Datensatz mit Markup zur Toxizität von Bearbeitungen wurde analysiert.| pandas, numpy, sklearn.linear_model, sklearn.model_selection, sklearn.tree, sklearn.ensemble, sklearn.metrics, re, nltk, nltk.corpus, sklearn.feature_extraction.text
Nachfrage nach Airline-Flügen | Ziel der Studie ist es, die Vorlieben von Benutzern zu verstehen, die Tickets zu verschiedenen Zielen kaufen, Studieren Sie die Datenbank und analysieren Sie die Passagiernachfrage nach Flügen in Städte, in denen die größten Kulturfestivals stattfinden. Analysierter Datensatz mit Informationen über Flugzeugmodelle, die Anzahl der Flüge für jedes Modell, die durchschnittliche Anzahl der in der Stadt ankommenden Flüge.| pandas, seegeboren, matplotlib.pyplot, math, scipy
Bestimmung des Alters von Käufern|Der Zweck der Studie besteht darin, ein Modell zu erstellen, das anhand eines Fotos das ungefähre Alter einer Person bestimmt. Eine Reihe von Fotos von Menschen mit ihrem Alter wurde analysiert.| pandas, numpy, seaborn, tensorflow, tensorflow.keras.preprocessing.image, matplotlib.pyplot
Prognose der Kundenabwanderung für ein Telekommunikationsunternehmen| Ziel der Studie ist es, ein maschinelles Lernmodell zu erstellen, das das Kundenverhalten analysieren und vorhersagen kann, ob der Kunde den Telekommunikationsanbieter verlassen wird oder nicht. Um das Problem zu lösen, wurden Modelle für maschinelles Lernen erstellt, das beste Modell anhand verschiedener Metriken und Betriebszeiten ausgewählt und eine Korrelationsmatrix erstellt.| pandas, pandas, matplotlib.pyplot, sklearn.metrics, sklearn.model_selection, sklearn.pipeline, sklearn.preprocessing, sklearn.linear_model, sklearn.ensemble, sklearn.neural_network, catboost, tqdm

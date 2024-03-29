# analysewerkzeuge2023
New York: Motor Vehicle Collisions - Crashes



# Intro
Die vorliegende Projekt enthält umfassende Informationen zu Verkehrsunfällen in New York City, basierend auf den Daten der Polizeimeldungen zu motorisierten Fahrzeugkollisionen. Die Datentabellen bieten Einblicke in sämtliche von der Polizei gemeldeten Verkehrsunfälle und beinhalten detaillierte Informationen zu den beteiligten Fahrzeugen, Unfallbeteiligten sowie den Unfallorten.

Die Grundlage für die Erfassung dieser Daten bildet der Polizeibericht MV104-AN, der in Fällen von Verletzungen, Todesfällen oder Sachschäden von mindestens 1000 US-Dollar ausgefüllt wird. Dieser Berichtsstandard ist durch die zuständigen Behörden vorgeschrieben und bietet eine systematische Erfassung von Unfalldetails.

Wichtig zu beachten ist, dass die vorliegenden Daten vorläufig sind und Änderungen unterliegen können. Diese Aktualisierungen erfolgen auf Grundlage von Überarbeitungen der MV-104AN-Formulare, die auf überarbeiteten Unfalldetails beruhen. Daher ermöglicht diese Datenquelle nicht nur Einblicke in vergangene Verkehrsunfälle, sondern auch eine kontinuierliche Aktualisierung, um mögliche Korrekturen und Ergänzungen widerzuspiegeln.

# Data 

- **Tablename:** MV-Collisions - Crash
- **Description:** The Motor Vehicle Collisions crash table contains details on the crash event. Each row represents a crash event.
- **Update Frequency:** Daily


| Column Name                    | Description                                                      | Type           |
|---------------------------------|------------------------------------------------------------------|----------------|
| CRASH DATE                      | Occurrence date of collision                                     | Date & Time    |
| CRASH TIME                      | Occurrence time of collision                                     | Plain Text     |
| BOROUGH                         | Borough where collision occurred                                 | Plain Text     |
| ZIP CODE                        | Postal code of incident occurrence                               | Plain Text     |
| LATITUDE                        | Latitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326) | Number         |
| LONGITUDE                       | Longitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326) | Number         |
| LOCATION                        | Latitude, Longitude pair                                          | Location       |
| ON STREET NAME                  | Street on which the collision occurred                           | Plain Text     |
| CROSS STREET NAME               | Nearest cross street to the collision                             | Plain Text     |
| OFF STREET NAME                 | Street address if known                                           | Plain Text     |
| NUMBER OF PERSONS INJURED       | Number of persons injured                                         | Number         |
| NUMBER OF PERSONS KILLED        | Number of persons killed                                          | Number         |
| NUMBER OF PEDESTRIANS INJURED   | Number of pedestrians injured                                     | Number         |
| NUMBER OF PEDESTRIANS KILLED    | Number of pedestrians killed                                      | Number         |
| NUMBER OF CYCLIST INJURED       | Number of cyclists injured                                        | Number         |
| NUMBER OF CYCLIST KILLED        | Number of cyclists killed                                         | Number         |
| NUMBER OF MOTORIST INJURED      | Number of vehicle occupants injured                               | Number         |
| NUMBER OF MOTORIST KILLED       | Number of vehicle occupants killed                                | Number         |
| CONTRIBUTING FACTOR VEHICLE 1   | Factors contributing to the collision for designated vehicle      | Plain Text     |
| CONTRIBUTING FACTOR VEHICLE 2   | Factors contributing to the collision for designated vehicle      | Plain Text     |
| CONTRIBUTING FACTOR VEHICLE 3   | Factors contributing to the collision for designated vehicle      | Plain Text     |
| CONTRIBUTING FACTOR VEHICLE 4   | Factors contributing to the collision for designated vehicle      | Plain Text     |
| CONTRIBUTING FACTOR VEHICLE 5   | Factors contributing to the collision for designated vehicle      | Plain Text     |
| COLLISION_ID                    | Unique record code generated by system. Primary Key for Crash table. | Number         |
| VEHICLE TYPE CODE 1             | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text     |
| VEHICLE TYPE CODE 2             | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text     |
| VEHICLE TYPE CODE 3             | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text     |
| VEHICLE TYPE CODE 4             | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text     |
| VEHICLE TYPE CODE 5             | Type of vehicle based on the selected vehicle category (ATV, bicycle, car/suv, ebike, escooter, truck/bus, motorcycle, other) | Plain Text     |


![image](https://github.com/viktorialisa/analysewerkzeuge2023/assets/108334462/ec36639f-3c38-48be-a9bd-9a054c54a490)![image](https://github.com/viktorialisa/analysewerkzeuge2023/assets/108334462/842dc547-2a3f-4e2e-a03b-3116870a9c7b)


# Packages
| Package         | Description                                       | Version |
| --------------- | ------------------------------------------------- | ------- |
| requests        | Sendet HTTP-Anfragen und empfängt HTTP-Antworten. | 2.31.0        |
| pandas (pd)     | Bibliothek für Datenanalyse und -manipulation. |     1.5.3    |
| matplotlib.pyplot (plt) | Erstellung von Diagrammen und Visualisierungen  |  3.7.1       |
| seaborn (sns)   | Datenvisualisierungsbibliothek auf Basis von matplotlib |    0.12.2     |

# No. of Crashes per Year
![image](https://github.com/viktorialisa/analysewerkzeuge2023/assets/108334462/5c7c3a46-e418-41d9-b88f-9990a7aa0ec3)


# No. of Crashes per Month
![image](https://github.com/viktorialisa/analysewerkzeuge2023/assets/108334462/dd9ae906-b27a-411e-a2ff-0870f5ddf6e3)
![image](https://github.com/viktorialisa/analysewerkzeuge2023/assets/108334462/14bf215e-b557-4a5c-a426-5bff05f7731f)

# Verteilung der Hauptunfallgründe
![image](https://github.com/viktorialisa/analysewerkzeuge2023/assets/108334462/17bd3fb8-4ada-4934-8cfc-4f0328cb79c8)


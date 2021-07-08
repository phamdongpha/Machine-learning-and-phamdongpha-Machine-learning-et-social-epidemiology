# Il s'agit de savoir manipuler des outils essentiels pour comprendre comment sont extraites et structurées les données numériques dans l'objectif de les transformer en information (incidences, ratios, taux d'occupation) autorisant une interprétation et une réflexion, donc il est un aspect important en sociologie.

Project:

1. Extract the data relating to the number of people hospitalized, new shifts / day, the cumulative rate of dc from the files provided by Public Santé France
2. Extract the data relating to the population by region and by department provided by INSEE
3. Extract the information relating to the number of beds available in the hospital, in intensive care, in intensive care by region and by department. Please note these data are not updated for 2020-2021

The data should be smoothed over 7 days to avoid inter-day variations. We can use a moving average for example (or beta-spline, or a polynomial method).

From these data, we must have a reflection on the relative daily evolution :
    1. Incidence rate by region or by department.
    2. Hospital / intensive care occupancy rates, by region or department (even if these indicators are biased).
    3. The ratios: death / hospitalization, death / resuscitation, resuscitation / hospitalization.

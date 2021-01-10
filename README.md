# python_for_data_analysis
Projet python for data analysis

Tâches à effectuer et conclusion

Problem:
  The "spam" concept is diverse: advertisements for products/web
  sites, make money fast schemes, chain letters, pornography...
  Our collection of spam e-mails came from individuals who had filed spam.  
  Our collection of non-spam e-mails came from filed work and personal e-mails

Dataset: 
  Number of Instances: 4601 (1813 Spam = 39.4%)
  Number of Attributes: 58 (57 continuous, 1 nominal class label)
  Spam	  1813  (39.4%)
  Non-Spam  2788  (60.6%)

Attribute Information:
  The last column of 'spambase.data' denotes whether the e-mail was 
  considered spam (1) or not (0)
  - 48 continuous real [0,100] attributes of type word_freq_WORD = percentage of words in the e-mail that match WORD, characters or end-of-string.
  - 6 continuous real [0,100] attributes of type char_freq_CHAR = percentage of characters in the e-mail that match CHAR,
  - 1 continuous real [1,...] attribute of type capital_run_length_average = average length of uninterrupted sequences of capital letters
  - 1 continuous integer [1,...] attribute of type capital_run_length_longest = length of longest uninterrupted sequence of capital letters
  - 1 continuous integer [1,...] attribute of type capital_run_length_total = total number of capital letters in the e-mail
  - 1 nominal {0,1} class attribute of type spam = denotes whether the e-mail was considered spam (1) or not (0), 

Fonctionnement de l'API:
  API flask réalisée en python.
  
Conclusion:

  Après avoir bien analysé et visualisé les données concernant le filtrage de mail en spam et non spam, nous avons implémenté 3 modèles différents:
  - KNN
  - Clustering
  - Regression lineaire
  Nous avons réussi à améliorer nos précisions pour en effectuant un subset de la dataframe (suppression des colonnes dont le p_value > 0,05).
  
  Marius

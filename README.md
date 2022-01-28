# Gender-Predicition

In this project we try to predict/estimate the gender of Authors from a dataset of New York Times Best Selling books, using the python library fuzzy which is used for implementing common phonetic algorithms. Using the algorithm **NYSIIS** (_New York State Identification and Intelligence System_ Phonetic Code)on the first names of all the authors,we get their NYSIIS equivalents, or what "sound" is attributed for the names. Then we match these NYSIIS values in our dataset with the ones present in a dataset that is derived from the [Social Security Administration’s](https://www.ssa.gov/oact/babynames/limits.html) baby name data, which also contains the percentage of babies of a certain NYSIIS value who are males, and the percentage of babies who are female. We use this information, to predict the gender of the authors by applying the logic that if % of male individuals with a certain NYSIIS equivalent is higher than % of female individuals, then our author is also a male. 
In our data, we have also encountered NYSIIS equivalents with no reference in the Social Security Administration dataset, the gender for such authors have been labeled as "UNKNOWN" and plotted separately in the final plot. 


Note, this is just a project for developing one's machine learning skills, there was/is no intention to hurt the feelings of any individual or group of individuals. 

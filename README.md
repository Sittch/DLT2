In this paper, we introduce DLT2, a model that can date
Latin texts through deep learning techniques in order to assist archae-
ologists, classicists, and other specialists. Latin is a classical language
with a long, rich history, and as such, there are many significant texts
for which a date cannot be determined precisely, if at all. The model
is trained on a corpus of Latin texts with dates of writing that can be
estimated within a 50-year window. These texts are divided into eight
distinct ”eras” based on recognized developments in the historical de-
velopment of Latin and its societal contexts. The model is then able to
suggest the most likely era for an undated Latin text. After ensuring that
metadata such as dates, authors’ names, and titles are removed from the
beginning of each document, DLT2 is able to achieve an overall predic-
tion accuracy of 30.88% in classifying texts with known dates, with some
era-specific accuracy scores reaching as high as 66.85%
Nowadays, most people need efficient ways for consulting online feedback as they can’t go
through every feedback and decide if they want to go with that choice. This can be very tedious if
there is a lot of feedback and varying opinions, which happens a lot with medicine feedback.
Consumer reviews are essential for doctors and drug manufacturers to understand the general
responses of patients to their medicines and improve their products accordingly. Besides,
consumer reviews enable doctors to recognize the specific side effects of each patient, which
facilitates effective development in healthcare. As there are numerous reviews from many patients,
it is hard to understand the main pros and cons of a drug. Therefore, we intend to use feature
extraction to extract the most relevant keywords from the data. But in a field like medicine
keywords are not sufficient to understand the effects of the drug. Thus, we intend to use text
summarization along with feature extraction.
The main problem for generating an automatic text summary is to detect the most relevant
information in the source document. Although some approaches claim to be domain and languageindependent, they use high dependence knowledge like key-phrases or golden samples for
machine-learning approaches. In this work, we propose a domain-independent automatic text
summarization approach by sentence extraction using an unsupervised learning algorithm. We
hypothesize that an unsupervised algorithm can help for clustering similar ideas (sentences). Then,
for composing the summary, we select the most representative sentence from numerous clustering
algorithms. This project aims to use text summarization and feature extraction to remove parts of
the feedback that are not needed making it easier for the user to make a well-informed choice.

The dataset drugsComTest_raw.csv is available in this repository

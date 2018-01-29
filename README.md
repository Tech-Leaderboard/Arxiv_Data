# Arxiv Data Processing
General information: Use of Arxiv api to aggregate demographic data on research publications related to Artificial Intelligence to be prepared for gender and ethnicity classification.

http://export.arxiv.org/api/query?search_query=all:AI&start=0&max_results=10000

Description of requirements/features: Process api results, isolating author's identifiable features including name, location, submission date, date of publication, and publication title.

Each author should be a separate entry, not each publication.

Format:

Preferably .json .xls and .csv

Relevant urls:

Gender and ethnicity classification tools to be applied to results.

http://www.name-prism.com/

http://www.namsor.com/

https://genderize.io/

https://arxiv.org/help/api/index

NLTK Name Classifier - https://gist.github.com/vinovator/6e5bf1e1bc61687a1e809780c30d6bf6

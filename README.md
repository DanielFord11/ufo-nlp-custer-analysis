# UFO NLP CLUSTER ANALYSIS

This Jupyter Notebook connects to a mongo database where I've loaded 40K UFO sighting descriptions and locations. Then it uses the TF-idf language model to run text similarity analysis between the 40K sighting descriptions and 2 target sighting descriptions that were reported by navy pilots. Then, it appends a numeric similarity score to the json of each sighting to represent how similar the description is to the navy pilot's descsription.

In a separate client-side application it renders the geo-json to a map and allows users to filter by the similarity score. Addtionally, there's essentially a heat map set to the similarity score value and the color of the point is set to be darker the more similar the text description is. 

<img width="1440" alt="Screenshot 2023-07-17 at 7 13 53 AM" src="https://github.com/DanielFord11/ufo-nlp-custer-analysis/assets/69986354/13427cc0-6953-4b21-9675-1a5610de0049">


<img width="1067" alt="Screenshot 2023-07-17 at 7 14 36 AM" src="https://github.com/DanielFord11/ufo-nlp-custer-analysis/assets/69986354/055fa2f9-5d50-48b8-ac82-94946933072b">

## TEXT-MINING-PROJECT REPOSITORY

### Abstract

The goal of our research is to test if an LSTM model and a Markov model can produce lyrics similar to human-created ones. Our research is based on a large dataset of over 170000 bars and a diverse pool of artists. Following a dataset analysis with a word cluster and bar chart, we built the baseline model. We developed from a simple LSTM model to a larger one. Subsequently, we developed the Markov model to output the most probable words next to each other. Furthermore, we combined the two models with the vectors formed by the word embeddings, in order to have the LSTM filter the lines to make them realistic. Moreover, we performed an ablation study by changing the depth and the batch size and epochs of the LSTM model. Lastly, we picked the 3 lyrics with the highest max_score per line and we made a survey by comparing them to human-created lyrics from artists not included in the dataset. The results of the survey showed that a percentage close to 60% guessed which lyrics were the ones generated by our models. To further improve our findings and to develop our research, we would recommend an extensive improvement of the LSTM model, since the max_score drops significantly with larger datasets and the introduction of a theme to have better coherence throughout the whole text. We firmly believe that an improvement on these aspects will make people not be able to distinguish the human-created lyrics from the model-generated ones.


### Research questions

Can an LSTM and a Markov model write human-created rap lyrics?

### Dataset

The dataset used can be found in our repository. Just in case here is the link to it: https://github.com/Claudio-creis/TEXT-MINING-PROJECT/blob/main/Bars.txt

### Milestiones

- Week 1:
- Select the dataset, tokenzation and word cluster [Davide]
- Dataset's bar chart [Claudio]
- Week 2:
- Building the LSTM model and training it on a smaller fraction of the txt file [Claudio]
- Combining the two models thorugh vectors from word embeddings [Davide] 
- Week 3:
- Training the two models, debug rhyme problems and adapt the code to the dataset [Davide and Claudio]  
- Ablation study and analysis of the study [Claudio]
- Survey making and findings analysis [Davide] 
- Presentation sildes [Davide and Claudio]. 
- Week 5: 
- Writing the report [Davide and Claudio]:
-- Abstract [Davide]
-- Introduction [Davide]
-- Related work [Claudio]
-- Dataset description [Davide]
-- LSTM Model [Claudio]
-- Markov Model [Claudio]
-- Modelling and rhymes [Claudio]
-- Ablation Study [Claudio]
-- Survey Findings [Davide] 
-- Conclusion [Davide]

### Documentation

Neizer et al. (2009) generate Haiku with Word Association Norms, 
Agirrezabal et al. (2013) compose Basque poems using patterns based on parts of speech and WordNet 
(Fellbaum,1998), and Oliveira (2012) presents a generation algorithm for Portuguese which leverages semantic and grammar templates.
Hugo Gonçalo Oliveira. 2012. PoeTryMe: a Versatile Platform for Poetry Generation. ComputationalCreativity, Concept INvention, and General Intelli-gence. 

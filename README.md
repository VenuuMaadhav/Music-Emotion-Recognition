# Music-Emotion-Recognition

# Abstract

Music is any signifier of sound in a synchronised form that affects the brain waves. Music’sspecial abilityis to change the listener’s mood. When a body builder is doing Exercises, a mathematician trying to solve the problems, what does he do? He listens to music. When a boy is romancing with a girl, or a heartbroken girl is trying to calm herself from breakup, music is very helpful to set the tune to their mood. We as a whole have a huge amount of feelings that control how we act and what we state. Our feelings are activated by numerous things. Music helps the people to stay focused and reverent. Music can possibly impact sentiments, mood and thoughts. Music has ability to change the passionate and mindset of the individuals regardless of whether the individual is angry, awful or sad. As feelings are affected by music similarly exercises are additionally impacted by music. Humans like to listen to music. Digital music libraries are growing enormously. Recommendation System for happy music (Gyms, Restaurants) and genre selection. Music is considered as a method for articulation in which opportunity is a benefit. It has numerous highlights and purposes like a phenomenal method for correspondence through craftsmanship. The main aim of the project is developing a Music Mood Classifier. There are many kinds of mood into which songs can be classified e.g.: happy, sad, angry, calm, uplifting etc. Humans listen to different kinds of music depending upon their mood. Music is a tool that influences the emotion, it can change the mood and also abandons consequences on human feelings and its connection to music. Examining the connection among music and state of mind is an important topic to be concentrated as people are always surrounded by music which they prefer to listen to as well as music they are exposed tomusicinvoluntarily in their daily life. There have been numerous psychological studies directed all through the previous century identifying with music and feeling, and as a result there exist various representations and understandings of human feelings and its connection to music. Music’s ability to “heal the soul “is the material of fable in modern fable. 

# INTRODUCTION

In the past years, the concept of music distribution has created a shift from physical distribution to online web with the help of digitally encoded, top quality and lovable music content. Worldwide music lovers have since accumulated giant musical collections that need economical management so as to permit for natural and heterogeneous access points to music. Music is an artistic expression which is a multidimensional phenomenon. Music Information Retrieval (MIR) field is strongly used in this field in order to enhance required music searching in large musical collections. For the filtering of the required music emotions or mood categorization are regarded as important factors. Mood classification will not only lighten the trouble of creating the playlists which are based on emotional expression but can also help the users to identify the songs of their collection that are not part of the songs which are commonly played.

The classification of music is a difficult task because the emotional reaction between listeners of the song can be completely different for a given song. Most of the organization of songs is particularly based on the genre presented by the artist and not on the feeling generated by the song. The process to categorize the collection of music through engineering techniques is a lot challenging, but can definitely help to minimize these issues between the listeners in the sorting process. Distinguishing the mood of a piece consequently would be incredibly helpful for arranging vast collections of computerized music, for example, those of iTunes or Spotify.

The mood of a piece could likewise enhance calculations for recognizing comparative melodies for online radio services like Pandora, based on the similarities on the mood of the song rather than on identified similar artists. Dividing a song into various musical components, for example, timbre, harmony and rhythm can be taken into consideration for the matching of songs to specific categories which will be based on expected information for each kind of mood.

The goal of this project is to develop a music mood classifier which will categorize the songs based on the mood which each song carries. There are many categories of mood into which the songs may be divided, e.g: - sad, happy, angry, calm, romantic, uplifting, depressing etc. People prefer listening to different kinds of music based on their mood. The development of such framework for detecting the musical mood with having tough variability of musical content like different genres, artists, world regions and time periods will be a challenging and interesting problem with wide range of applications in music industry.

# Objective of the project

The aim of the project was to develop a music mood predictor using naive Bayesian classifier and visualizing the testing using a webapp. There are many categories of mood into which songs may be classified, e.g. happy, sad, angry, brooding, calm, uplifting, etc. To simplify the problem, we have used only four moods: angry, sad, happy and relaxed.

# The most innovative part of your project

The use of Naive Bayesian Classifier. Naive Bayes has very high learning efficiency and it can guess all the probability just need a scan of the training data. Naive Bayesian Classifier is a simple classifier based on applying Bayes theorem with independence conventions.Naive Bayes classification is based on the postulation that the principle of maximum posteriori hypothesis to classify the object that most likely to be classified under the category. Bayes theorem shows the relation between one conditional probability and its inverse.The Naive Bayesian Classifier is a classification algorithm that is easy to implement. Due to its simplicity of the model and the good classification performance, it’s widely used in engineering application.

The use of the web application which will the rear end user to predict the mood of the music just by using the lyrics of the song. The web application will also check the exposure of data to the rear end users.

# Proposed work and implementation

# Methodology: -
1. We have used the dataset with millions of song which will be pre-processed and classified as training and testing data.
2. We have used supervised learning algorithm I.e. Naive Bayes Classification to train the learning algorithm.
3. The mood classified algorithm has been trained using the training data set.
4. It has been tested upon using the validation dataset.
5. The project has been implemented using an interactive web interface.
6. The input to the web interface is lyrics of the song approximately (45 characters).
7. The mood classifier algorithm process the data and rate the percentage of the category to
which the song belongs to i.e. happy, sad etc.

# Tools used
# Hardware requirements: -
• Laptop with any OS (Windows / Mac OSX / Ubuntu)
• Processor :1.8 GHz Intel Core i5 or higher versions
• Memory :8 GBor more
• Graphics: Intel HD Graphics 6000 1536 MB (optional)
# Software Requirements: -
• Jupyter notebook to implement the python code
• Brackets for web page development
• Chrome / Internet Explorer / FireFox for displaying the web page
# Dataset used / Tools used: -
Million Song dataset id a free and ready to use ad taste with a collection of audio and
metadata for a million contemporary popular music tracks.
Reference:https://labrosa.ee.columbia.edu/millionsong/

# Results and discussion

# • Classification of the songs based on their lyrics using Naive Bayes Algorithm.

‣ After training the model according to the four different moods i.e. happy, sad, relaxed
and angry we took the input from the user in the form of lyrics of any song and based on
the lexicon and token in the lyrics the lyrics were successfully classified according to the
moods of the song.

# • Calculation the percentage of the respective mood based on the lyrics of the song.
‣ After training the model according to our four moods datasets we tested the model with the testing dataset which consists of four different types of songs. The model was made to predict the mood of that particular song and was rated in the basis of the accuracy of the prediction i.e. whether the prediction and the actual value predicted are same. I found out that the overall accuracy of the model is 78%. This is mainly due to the small dataset that I have used. The accuracy will increase with the improvement of thetraining dataset.

# • Calculation of Accuracy
‣ The accuracy of our model is 0.78. We found out that our base paper that to uses SVM for training and performing the prediction has a slight higher accuracy of 0.82 which is mainly due to the extensive training of the model using the million song dataset. The accuracy of our model will improve with wider dataset.

# • Implementation of the complete project through an interactive web interface.

‣ The entire project has been implemented using flask for backend which is an API
specially designed for doing backend that includes machine learning algorithms. The
front-end consists of an interactive user interface with an input text box in which the user
can input the song whose mood the user wants to determine. 

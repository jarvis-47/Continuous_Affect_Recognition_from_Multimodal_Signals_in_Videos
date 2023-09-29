# Continuous_Affect_Recognition_from_Multimodal_Signals_in_Videos

## Introduction:
In affective computing, it is essential to be able to reliably identify and interpret emotions from human speech and facial expressions. Application areas for affect identification include social robots, human-computer interaction, and mental health. In this experiment, our major goal was to determine whether it was possible to estimate arousal and valence values from video utterances using machine learning models.

Our study issue is driven by a desire to investigate how merging audio and visual information might enhance the precision of emotional computing models. Numerous practical uses for being able to properly forecast emotional states include marketing research, human-robot interaction, and mental health diagnosis.

We used the OMG Dataset in our project, which includes audio and visual recordings of participants while watching videos that evoke different emotional responses. The dataset consists of around 600 videos, each having on average 8-10 utterances, of which each lasts between 3 and 60 seconds. The data was annotated by multiple human raters for arousal and valence values, which we used as our response variable. The dataset was already publicly available, and we did not have to collect the data ourselves.

## Data Representation:
1. **Unit of analysis** – Individual video utterances. Each row represents a single utterance, and the columns contain features such as the transcript of the utterance, the video ID, and the predicted arousal and valence values.
2. **Observations** – There were around 6000 individual video utterances in the OMG Dataset subset that were used in this project for training, validating, and predicting arousal and valence values.
3. **Time period** – The OMG Dataset does not cover a specific time, as it consists of a collection of video recordings from various sources.
4. **Response Variable** – Predicted arousal and valence values for each video utterance.

<div style="text-align:center"><i>Arousal: -1 Calm to +1 Alert</i></div>
<div style="text-align:center"><i>Valence: -1 Negative to +1 Positive</i></div>

## Results:
![image](https://github.com/jarvis-47/Continuous_Affect_Recognition_from_Multimodal_Signals_in_Videos/assets/130951334/b86e7dcd-bbfa-4090-b0a8-a37649172cee)




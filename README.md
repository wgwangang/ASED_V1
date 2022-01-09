# Amharic Speech Emotional Dataset (ASED) v1

 
### About ASED 
" ASED v1.0 was created on February 12, 2021". The recording was done at Northwest University. This version is the initial state of ASED. The purpose of this project is the continuous growth of the Amharic dataset to encourage other researchers to explore the Amharic language. 
### Creation of the Database 
For the creation of ASED the dataset, 65 (25 female and 40 male) participants were recorded. We adopted a semi-supervised recording approach: The participants were given a short description of the purpose of the study and the recording system and were then allowed to choose a convenient time and place to conduct the recording. Each participant was first asked to record all 25 emotion-specific sentences. They were provided with the sentence and the required emotion, for example, "Turn away and let me not see you again." to be spoken in an Angry way. Each recording was made twice. Next on the list could be the sentence. "I think he was a thief who knocked on the door", to be spoken in a Fearful way, and so on. For these emotion-specific sentences, the required emotion was always the same for a given sentence for all participants. After the 25 sentences, the participant was then asked to record the two common sentences, for example, "my sister is coming on a plane." Each common sentence was recorded twice for each of the five emotions, Neutral, Fearful, Happy, Sad, and Angry. So they would first record the sentence in a Neutral way (twice), then record the same sentence in a Fearful way (twice), and so on. Participants always spoke in their own Amharic dialect. A complete set, therefore, comprised 25 x2 = 50 recordings of emotion-specific sentences, and 2 x5 x2 = 20 recordings of common sentences, 70 recordings in all. 
### Judgments 
Every recording was independently reviewed by all eight judges. Concerning emotion-specific sentences, each judge decided whether the recording expressed the emotion adequately or not and made a binary decision, Accept or Reject. For the common sentences, the judge did not know the intended emotion of the recording. They decided which emotion the recording expressed. If it was unclear, their decision was Reject; otherwise, their decision was one of the five emotions. For emotion-specific sentences, a recording was only accepted for inclusion in the ASED dataset if five or more judges returned the decision Accept. Similarly, a common sentence was only accepted if five or more judges assigned the same emotion to it. Because there were 65 participants, each of whom made 70 recordings, we would expect ASED to contain 4,550 recordings. However, because of the above selection process, many of these were rejected, resulting in 2,474 recordings in the dataset. 
### Chosen Emotions 
Five emotions were chosen: n (neutral) f (fearful) h (happy) s (sad) a (angry) 
### Organization the Database 
There are five folders, named after the five emotion classes. Every filename in the dataset is in the following form: xn-yy-aa-gg-bb where xn indicates the emotion and number of folder (a5--> anger, h3--> happiness etc.) yy is the number of the sentence (01,02...07) aa is the number of repetition (01 = 1st repetition, 02 = 2nd repetition) gg is the number of gender (01 = female, 02 = male) bb is the number of the speaker (01 --> 1st speaker, 02 --> 2nd speaker...65) e.g. 'a5-03-01-02-50.wav' is the 3rd sentence spoken by the 50th male speaker with angry the first time in folder 5.

# Reflection on own contribution to the project

When looking at my contribution towards the project in comparison to my fellow project members, I was the one who was most of the time learning and catching up to the rest of the group. This is mostly because I am very new to the whole field of Data Science and engineering (since I am a business IT student) and the rest of my group consists of software engineers. This put me at a disadvantage, but nevertheless did I try my best to catch up with the rest and do my part of the project.

My own personal contributions to the project consist of:

* researching different methods (vectorization, preprocessing, cleaning) to check whether these would be viable for the project,
* training various models, showing their result and evaluating their performance,
* setting up the environment to write the research paper and help with writing the paper itself,
* explore the data and analyze this, both Agora and WebIQ data sets,
* visualizing the data and models.

For reflection purposes, a single occasion is taken in order to reflect upon using the STARR-method.

## Situation

The models that were trained needed to be evaluated and their scores needed to be checked. I was just scrolling through various articles and papers and stumbled upon a different method to split test and train data individually, this was *‘k-fold cross validation’*. During the minor, this subject was handled before but not on the level that I was able to implement it in the project. Seeing this technique, I saw this as an opportunity to test if it would be beneficial to our project since we only trained using sklearn’s standard *‘train_test_split’*-method, also referred to as ‘Hold-out validation’.

## Task

My task was to research how this particular subject worked, and whether it would be efficient and effective enough to use within the project. This had to be done doing desk research, watching online tutorials and/or lectures in order to fully understand the technique and how to apply it within a Jupyter notebook. Also did the scores needed to be compared to each other in order to check whether using this method would provide improvements.

## Action

I reread the lecture slides that were available on Blackboard, to refresh myself about what the subject exactly was about. Combining this with various articles that are published on sites like *‘Towards Data Science’*, it became very clear about what the contents were and how it exactly worked.

## Result

The result of this action was that I made two different notebooks containing the same models that would be trained, only using a different split method for both of them. The first one that I trained was based on Hold-out validation using tf-idf vectors from the WebIQ data, and the other using the same vectors only using k-fold cross validation. Finally, I visualized for both methods the accuracy, precision, recall and f1-score, in order to compare them to each other. The results were not significantly great, seeing the only an increase of one percent using the k-fold method.

## Reflect

Aside from the small improvement made on the scores, I am very proud of this achievement, mainly because this is something I completely discovered, researched and applied by myself, without any help from my fellow students. It was also a very interesting topic to research in my opinion, because it is a very different method than the standard hold-out validation. Also, my group members were very interested in my findings and how it worked.

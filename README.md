ABM-QA-community
================

This is the code implementing the model that we describe in our EC-Web 2014 
paper "Modelling User Behaviour in Online Q&amp;A Communities for Customer Support".

The agent-based model described here simulates the question answering
behaviour of an online Q&A community. It contains three types of entities,
the users, the questions and the answers. Each of these entities has their
own attributes that describe their behaviour and statistics, such as the
number of answers that a question has.
This is the main source code file, containing the breeds and the setup and go
methods. There are sub-methods that are described in the included files
createPost.nls, createNewUser.nls and acceptAnswer.nls.

(c) Erik Aumayr, Insight Centre for Data Analysis, 
National University of Ireland, Galway

Requirements
----------------
Requires NetLogo 5.0.4 or higher.


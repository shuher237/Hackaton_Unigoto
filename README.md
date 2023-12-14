# Hackaton_Unigoto

Students: Aflatunov Emil, Shukhardin Alexandr, Guyfullin Alexandr


## **Runtime**
*Python 3.10.6*

## **Table of contents**
1. [Project description](#project-description)
2. [Which case is being solved](#which-case-is-being-solved)
3. [Task conditions](#task-conditions)
4. [Quality metrics](#quality-metrics)
5. [What is being practiced](#what-is-being-practiced)
6. [Project stages](#project-stages)
7. [Results](#results)  

### **Project description**
   Implementation of a recommendation system based on data provided by the customer, capable of providing relevant recommendations to users based on feedback received from them on certain personal parameters (hobbies, interests, favorite books, etc.).

[**⬆**](#table-of-contents) *to the contents*

### **Which case is being solved**
   Several recommendation system algorithms have been developed that can be used for further work on creating a service to assist applicants in choosing a university and field of study.

[**⬆**](#table-of-contents) *to the contents*

### **Task conditions**
   1. Perform initial processing of customer data, obtain a dataset cleared of uninterpretable data.
   2. In the future, user data input and output of a top list of n (the parameter is also set by the user) elements with the most relevant universities and areas of training should be implemented.
   3. It is possible to issue results for universities, faculties and specialties separately, as well as with a city limit.
   4. Detailed description of all steps for data processing and setting up the RS model.

[**⬆**](#table-of-contents) *to the contents*

### **Project stages**
   1. Generating the initial dataset using the API provided by the project customers.
   2. Several stages of data processing were carried out: the formation of a representative sample, cleared of missing data and information irrelevant to the task using EDA methods.
   3. Simulate user input using Google Colab methods.
   4. Implementation of a recommendation system algorithm based on the TF-IDF vectorization approach by calculating the cosine proximity between the vectorized user input data and the cleaned dataset using sklearn.metrics.pairwise, TfidfVectorizer, nltk,       
      pymorphy2.MorphAnalyzer.
   5. Training the 'DeepPavlov/rubert-base-cased' model, obtaining text-embeddings, calculating the cosine proximity between the user input and the calculated text-embeddings.
   7. Code refactoring and code review.
   8. Creating a project repository.
   9. Preparation of documentation on project results.

[**⬆**](#table-of-contents) *to the contents*

### **Results:**
   Algorithms for constructing a recommendation system based on data from a cleaned dataset have been implemented.

[**⬆**](#table-of-contents) *to the contents*

Please, rate this project with ⭐️-s if you consider its interesting or useful.

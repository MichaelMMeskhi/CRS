# Course Recommendation System

#### Abstract 

The following repository contains all of the necessary datasets and scripts that run the full system. The course recommendation system is motivated by the problem of 
difficult registration systems designed and used across college campuses. Our system recommends what courses to enroll in based on the following criteria:

* Past evaluation of courses taken by other students. Such evaluations are:

| `course_sat` | `course_dif` | `prof_rating` | `course_recom` | `studnet_grade` |
|--------------|--------------|---------------|----------------|-----------------|
|Course satisfaction|Course difficulty|Professor Rating|Course Recommendation|Student Grade Received|

* Based on department degree plan that checked for preqrequisites and other important criteria.

These are the two most important factors to be taken into account when recommending courses. Sometimes students have other reasons which are harder to build into our 
model because of lack of data. Such factors are:

1. Course term availability.
2. Specific professor availability.
3. Specific time availability.

Overall, our system is a prototype that can vastly be scaled but requires sufficient data in order to build a proper prediction model based on the aforementioned criteria.


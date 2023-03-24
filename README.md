# E-governmentAdoption-EvaluationGuidelines-Reference-Implementation
This reference implementation provides the guidelines for evaluating the adoption behavior of e-government services from the citizens' perspective.

We have proposed a conceptual framework to evaluate citizens' adoption behavior of e-government services. We then developed a web-based questionnaire based on this framework and also we implemented the data analysis process to adequately evaluate the collected data.


The proposed conceptual framework contains one dependent factor, Adoption Behavior (for e-government services), and two primary independent constructs, Design Factors (DF) and Human Factors (HF). These two independent constructs provide the independent factors. The figure below shows the proposed conceptual framework and the relationships between the five independent factors and Adoption Behavior:

1. Perceived Ease of Use (PEOU): PEOU, in the TAM model, refers to the perception of the system’s easiness and users’ ability to use it. It reflects the usability of the system and users’ intention to adopt the system which is free of effort (Davis, 1989).

2. Perceived Usefulness (PU): PU, in the TAM model, refers to the extent to which a user believes that adopting a particular system would enhance his/her job’s efficiency and performance (Davis, 1989).

3. Social Influence (SI): SI, in the UTAUT model, is considered an essential determinant of users’ behavioral intention to adopt new technology. It refers to the degree to which peers affect the use of a system, whether positive or negative (Venkatesh et al., 2003).

4. Facilitating Conditions (FC): FC, in the UTAUT model, is defined as “consumers’ perceptions of the resources and support available to perform a behavior.” It is measured by users’ perception of being able to use the required e-government resources. It obtains the knowledge and the necessary support to use e-government services (Venkatesh et al., 2003).

5. Trust of Government (TOG): TOG, in the Trust model, is a construct that refers to the fulfillment of expectations by ensuring that the other parties behave in a trusting and responsible manner. It describes the users’ confidence in the integrity of the services’ mediums and providers (Bélanger & Carter, 2008).

Adoption Behavior is a dependent factor that describes the likelihood of using e-government services.

![Framework](https://user-images.githubusercontent.com/60638810/226831026-23cb5735-63b2-412d-991d-6321aea3bc39.png)


--------------------------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/60638810/227397913-860c3a9c-68d7-479f-aefb-40773b3a4cc1.png)

To run this reference implementation, you need a Python notebook, either Google Colab or Jupyter Notebook.


--------------------------------------------------------------------------------------------------------------------------------

![image](https://user-images.githubusercontent.com/60638810/227398066-3dd9ecbf-51d7-4746-b5fb-43204d262c0e.png)
This reference implemntation contains the following files:

1.	Survey.pdf: the developed web-based questionnaire that went through iterative assessment of validity and reliability tests. 

2.	RawData.csv: This is the final version of the CSV file after collecting the responses from citizens. Your file should follow this format before proceeding to the data analysis process. 

3.	Data_Analysis_RI.pdf: In this file, we explained in detail the data analysis steps required to evaluate citizens’ adoption behavior of e-government services. We provided a list of crucial assessments along with the threshold value for each one. 

4.	CODE.ipynb: This is a Python Notebook where we implemented the data analysis steps explained in (Data_Analysis_RI.pdf). At the beginning of this notebook, we have listed a number of packages to be installed and libraries to be imported. Then, we provided the required code for each data analysis assessment.

![image](https://user-images.githubusercontent.com/60638810/227399354-5e5bdca9-ce7f-41d1-8147-d021bb354648.png)




IDEAL linkage study - hospital
################################

Linkage
*********

After bulk import of your study patients (see :doc:`study`), IDEAL will automatically link the patients from your study with the patients from the hospital.


.. image:: Linkage.png


Here for example, 100 patients were imported and from these, 80 had an immediate match with the hospital patients, while 14 "similar pairs" were linked.

"Similar pairs" likely have some similarity conflicts, but were still close enough to be considered a match.

We will look at some examples of "similar pairs" below, but first let's navigate to our study and have an overview of the patients.

.. warning::
  If you get an error message when importing your patients to a study, please check either this section :doc:`trouble` or this :doc:`study`.

.. note::
  The linkage in IDEAL works by using an alghoritm to calculate the similarities between the patient information between the Study CSV and the Hospital. The more information provided, the more information to compare and the more accurate will it be!

Study overview after patient import and linkage
******************************************************

By navigating to the area "**Patients**" and then to "**Patients List**", you can see here the patients which were imported to your study (in my case the study TJP100).

.. image:: LinkOverview.png

When hovering over the different icons on the right, you can see different functions - see below.


.. image:: Icons.png
   :width: 400 

..note::
  For a linked patient, the icon "**Link patient**" will be displayed in gray, while a non-linked patient will be displayed in white.

Examples of linkage of "similar pairs"
******************************************

In this case, this patient has been recorded in the hospital database with two first names "Donald Timothy", while in the study he was introduced as only "Timothy".


.. image:: Duck.png


However, because the rest of the information (surname, date of birth) is the same, the similarity is good enough for IDEAL to link them as a pair.

Similarly in the case below, the patient "Jennyfer Vengerberg" had been recorded as only "Jen" instead of "Jennyfer" in the study. As the rest of the information is the same, this patient was still correctly linked.


.. image:: Jen.png


Examples of no linkage 
*******************************

After bulk import of study patients, you can check the patients which were not linked by navigating from "**Patients**" and then to "**Patients List**", and selecting here "**Unlinked**" in the dropdown menu, as shown below:


.. image:: Unlinked.png

In my case, there were 5 patients which were not linked to the hospital database.

.. image:: Unlinked2.png

when patient don't exist in the hospital

Edit a patient from the study
*******************************

Sometimes errors might be introduced when creating the CSV file with the Study patients. This is the case of the example below: 


.. image:: WrongDOB.png


This dummy patient called Elsie-Mae Gardiner had the wrong year of birth on the study file (1931 instead of 1930). 
In order to update the Study details, you can navigate to "**Patients**" and then to "**Patients List**". Here you can use this icon in the same row as the patient you want to edit, as shown below:


.. image:: EditPatientIcon.png


And make your changes as shown below as well (in the Study table, and don't forget to **save**):


.. image:: EditPatient.png


.. note:: Note how Elsie-Mae Gardiner still got linked by IDEAL despite the small change in the year of birth (all the other information was the same)!

.. warning:: Before update any patient information make sure that this information is correct!


Add patient to study
***************************


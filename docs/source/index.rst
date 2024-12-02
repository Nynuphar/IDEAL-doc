IDEAL user guide
###################

IDEAL is a patient identity management tool, which links the patient identifying information in the hospital data warehouse to their pseudonym in the study or cohort. Therefore, IDEAL enables data sharing for research, while protecting patient identifying information.

Read more about the `IDEAL project <https://ideal-project.ch/about/>`_ here.

This documentation aims to provide information about the different IDEAL functionalities and equally provide a step-by-step guidance for a new user.

IDEAL has different users, who have different permissions, and consequently have different IDEAL interfaces. Check out the :doc:`users` and :doc:`interface` section for further information about user permissions and interfaces.

.. warning::
   Only authorized users will be able to access the IDEAL functionalities.

.. note::
   This project is under active development.

IDEAL users
**************

This section provides information about the different types of users and respective permissions.

.. toctree::
   :maxdepth: 1

   users

User registration
**********************

This section provides information about user registration and account management.

.. toctree::
   :maxdepth: 1

   userRegistration

IDEAL interface - an overview
*******************************

This section provides an overview of the IDEAL interface, so it is easier to understand how IDEAL is organized.

.. toctree::
   :maxdepth: 1

   interface

Patient Dashboard
**********************

The patient dashboard allows a centralized workflow over one specific patient.

.. toctree::
   :maxdepth: 1

   patDashboard

Study management: create, approve, edit and delete a study
**************************************************************

This section explains how to create a study, approve, edit and delete a study:

.. toctree::
   :maxdepth: 1

   createstudy

Import study patients - bulk import from a CSV file
***************************************************************************************************

This section explains how to bulk import patients to a new study. Before the bulk import, it is important to properly define the data format of a study, so IDEAL "understands" what is being imported. 

The bulk import would be the strategy to onboard an ongoing study to IDEAL, whose patient list has been maintained on Excel (for example).

.. toctree::
   :maxdepth: 1

   import

IDEAL linkage
******************

This area explains how to inspect the linkage after a bulk import of study patients and how to manually link patients from a study to the hospital.

.. toctree::
   :maxdepth: 1

   linkage

Patient management: add a patient to a study
*******************************************************************************************

This section explains how to add a patient from the hospital database to a study.

This can be used to manually built a patient list for a new study created on IDEAL from scratch or add new patients to an ongoing study which was imported to IDEAL.

.. toctree::
   :maxdepth: 1

   patmanage

Editing patient information and audit log
*****************************************************************************

This area gives information about the audit log, which tracks any updated on the patient information.

.. toctree::
   :maxdepth: 1

   auditlog

File export (the "key" export)
****************************************

This area explains how to export files based on the patient study list and/or linakge to the hospital list.

.. toctree::
   :maxdepth: 1

   export

Appointments: create schedules and patient appointments
**********************************************************

This area explains how to create appointment schedules and how to create series or single appointments.

.. toctree::
   :maxdepth: 1

   appointments

Calendar to view scheduled and definitive appointments
***********************************************************

This area explains how to visualize the scheduled and definitive/booked appointments in a calendar. It also shows how to book an actual appointment via the calendar and how to export this calendar into your own calendar calendar (ex: Micorsoft Outlook)

.. toctree::
   :maxdepth: 1

   calendar

Tasks associated with patient appointments
***********************************************************

This area explains how tasks are created and how to efficiently use them to manage your to dos regarding patient appointments.

.. toctree::
   :maxdepth: 1

   tasks

Create a letter template and generate template letters for specific patients
*********************************************************************************

This area explains how to use template letters to write personalized letters to patients.

.. toctree::
   :maxdepth: 1

   letter

Worflow: onboard an ongoing study to IDEAL
**************************************************************************************************

This section explains how to onboard a ongoing study to IDEAL: from creating a new study, to bulk import of an existing patient list and how to add new patients to this study.

.. toctree::
   :maxdepth: 1

   ongoing

Worflow: create a new study from scratch by directly adding patients from the hospital database
**************************************************************************************************

This section explains how to create, modify and add patients to a new study.

This would be the situation for newly-started study, in which patients are added directly from the hospital database.

.. toctree::
   :maxdepth: 1

   newstudyhospitaldb

IDEAL troubleshooting
************************

This area give some tips about trousbleshooting.

.. toctree::
   :maxdepth: 1

   trouble

IDEAL: current known issues and new features
************************************************

This is a list of current known issues we are resolving and the current new features we are working on.

.. toctree::
   :maxdepth: 1

   issues

Patient details, editing patient information and audit log
######################################################################

.. _PatDetRef:

Patient details
*****************

The patient details of a study (or the hospital) can be accessed in different ways:

1. Via the **Patient Dashboard** - search for your patient and select container **Patient Details**
2. Via the **Patient management** > **Patients List (Study)**. Click on the "eye" icon.
3. Via the **Appointments** > **Appointments List** - search for your patient. Click on the "eye" icon, scroll to the bottom of the page and expand "Study Patient contact Information" and then select "View Full Patient Details".

You will see a side by side view of the patient data. On the left, the "Hospital personal information", on the right "Patient personal information" from the study. The hospital information on the left cannot be edited, but the study specific information can by selecting "Edit Patient".

Please note, that this information might not be exactly the same - for example in the case below, the patient changed phone number, which has been updated by the study nurse in the "Patient personal information" field. These changes will be tracked in "Audit" (see more information about the :ref:`Audit log <AuditRef>`).

.. image:: PatDetails.png

Edit a patient information
****************************

Imagine Donald Timothy Duck was registered as Timothy Duck in the study "Wine and Cheese". As a study nurse, you want to update the patient information. For this, please navigate to **Patient management** > **Patient List (Study)** > **Patient details** (eye icon). Then select **Edit Patient**.

.. image:: EditPatient.png

Here you can correct the information and maybe also update the address of this patient, as he notified you he had now moved to the "Rue des souries", and then **Save***.

.. _AuditRef:

Audit log
*************

The audit log tracks the any change which happens to a patient in a study. For example, if a patient's address is edited, this will be tracked.

You can see now see these changes and the audit log, by navigating to **Patient management** > **Patient List (Study)** > **Patient details** (eye icon). Then select **Audit**. And then select "Audit".

.. image:: AuditLog.png

You can see some information of when the patient was imported (in blue) and the corrected data by comparing "Old Value" with "New Value"

.. image:: AuditNewOld.png

Any new update will be recorded under "New Value", together with when and whom changed this information.

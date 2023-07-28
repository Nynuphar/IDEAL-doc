IDEAL Users - types and permissions
######################################

Types
********

Superuser
==========

The IDEAL Superuser is a local administrator.

The main responsibility of a Superuser is to approve new studies and new user accounts, and equally invite new users.

Although able to approve and create a new study, the Superuser does not have direct access to the patient information of a study. Therefore, they are not able to import a study patient list. Equally, the Superuser is not able to do the IDEAL linkage between the patients in the carecenter/study and is not able to export any patient related files.

Manager
=========

An IDEAL Manager could be a principle investigator or a senior study nurse.

The Manager has access to the patients in the carecenter and study. The Manager can import patients to a study and link these to the patients in the carecenter.

The Manager has a similar role to the IDEAL user (see below) but it is able to create and manage new studies and new user accounts. Both new study and users need then to be approved by the IDEAL Superuser).

User
======

In most cases, the IDEAL user is a local study nurse or data manager.

The User has a more limited role than an IDEAL manager. The User has equally access to the patients in the carecenter and study. Equally, the User can import patients to a study and link these to the patients in the carecenter.

The User does not have permission to manage users or studies.
 
Summary table
***************

.. list-table:: Users rights and permissions
  :widths: 70, 30, 30, 30
  :header-rows: 1

  * - **Action**
    - **IDEAL Superuser**
    - **IDEAL Manager**
    - **IDEAL User**
  * - **IDEAL patient management**
    - 
    - 
    - 
  * - View patient details
    - no
    - yes
    - yes
  * - Edit patient details
    - no
    - yes
    - yes
  * - Delete patients
    - no
    - yes
    - yes
  * - Registration of new patients
    - no
    - yes
    - yes
  * - Link patients with the CDW
    - no
    - yes
    - yes
  * - Bulk import of study patients
    - no
    - yes
    - yes
  * - **File extraction**
    - 
    - 
    - 
  * - Export of subject identification log
    - no
    - yes
    - yes
  * - Export of screening log
    - no
    - yes
    - yes
  * - **Management of study information**
    - 
    - 
    - 
  * - Create new studies
    - yes
    - yes
    - no
  * - Manage registered studies
    - yes
    - yes
    - no
  * - Approve new studies
    - yes
    - no
    - no
  * - **User management**
    - 
    - 
    - 
  * - Invite new users
    - yes
    - no
    - no
  * - Approve new users
    - yes
    - no
    - no
  * - Assign users to new studies
    - yes
    - yes
    - no



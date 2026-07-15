CHIL Users - types and permissions
######################################

Types
********

Superuser
==========

The CHIL Superuser is a local administrator.

The main responsibility of a Superuser is to approve new studies and new user accounts, and equally invite new users.

Although able to approve and create a new study, the Superuser does not have direct access to the patient information of a study. Therefore, the Superuser is not able to import a study patient list. Equally, the Superuser is not able to do the CHIL linkage between the patients in the carecenter/study and is not able to export any patient related files. The Superuser can block the access of the other CHIL users to patients and studies at any time.

Manager
=========

An CHIL Manager could be a principle investigator or a senior study nurse.

The Manager has access to the patients in the carecenter and study. The Manager can import patients to a study and link these to the patients in the carecenter.

The Manager has a similar role to the CHIL user (see below) but it is able to create and manage new studies and new user accounts. Both new study and users need then to be approved by the CHIL Superuser.

User
======

In most cases, the CHIL user is a local study nurse or data manager.

The User has a more limited role than an CHIL manager. The User has equally access to the patients in the carecenter and study. Equally, the User can import patients to a study and link these to the patients in the carecenter.

The User does not have permission to manage users or studies.
 
Summary table
***************

.. list-table:: Users rights and permissions
  :widths: 130, 30, 30, 30
  :header-rows: 1

  * - **Action**
    - **CHIL Superuser**
    - **CHIL Manager**
    - **CHIL User**
  * - **CHIL patient management**
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
  * - Assign users to studies
    - yes
    - yes
    - no



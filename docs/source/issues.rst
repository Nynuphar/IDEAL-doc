Current status, current issues and development of new features
#################################################################

New features
********************

* March 2025:
  * Matching by Patient Hospital ID when performing a bulk import of a pre-existing study to IDEAL

* January 2025:
  * Improvement in the registration process (safer and simpler now)
  * User security improvment: superuser and admin can block user access to a study
  * Improvement of the appointment schedule (more options, more tailoring of appointment names, filtering, multi delete)
	* Patient dashboard: patient centric study management (in complement to the already existing study centric)
  *	Template letters: create letters with patient information from ideal
  * StudyID generator: generate a random Patient Study ID automatically
  * Custom data export: more choices in data export
  *	Audit log for studies

* April 2024: We are currently working on implementing an activity log for the appointments (in order to keep track of the tasks which need to be performed).

Current warnings
********************

* 01-April-2005:
* Regarding IDEAL matching Hospital ID - Study ID when Hospital ID is provided in the study list being imported:
  * When Hospital ID is present: the matching with the carecenter patients is done by Hospital ID (even if name and DOB is provided). The study patient information is directly copied from the hospital database.
  *	When a Hospital ID is not present (patient name and DOB is provided): the matching will happen based on a similarity score calculation (the information provided in the CSV file is maintained).
* Please check that there are no repeated entries in your file. Currently this is the current behaviour if there are repeated entries (this will be improved in the future):
  * Different patients with repeated Study ID (different Hospital IDs): patients are overwritten, only the last one (on the list) is imported and matched
  * Different patients with with same Hospital ID, different Study IDs: both patients are imported, but only the first patient is matched to the Hospital ID.
  * Missing/non existing Hospital ID: patients are not imported.

Past/Current issues
**********************

These are the current issues we know about and will be fixed in the next IDEAL release.

* 05-April-2024: SOLVED Manual linkage has a problem and it is not currently possible to manual link the patients of the hospital and a study. We apologize for this and we are working on resolving this problem asap.


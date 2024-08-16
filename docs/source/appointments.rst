Appointments
##############

Appointments can be booked as **series** or **single** appointments.

In order to book appointment **series**, an **appointment schedule** needs first to be created :ref: `Set and appointment schedule and book appointment series`.

To book single appointments, please check below :ref: `Book a single appointment for a patient`

Set and appointment schedule and book appointment series
****************************************************************

In order to book appointment **series**, an **appointment schedule** needs first to be created (:ref: `Set and appointment schedule and book appointment series`).

#. Set an **Appointment schedule** - this will set the frequency and the type of appointments for a study. The appointment schedule should be decided at at the **beginning** of the study and **before** starting to book appointments. Once an appointment schedule has been created, you can start to:

#. Set "**Apointments**" for patients. under the "**Study patients**" section to create appointments for specific patients.

Let's look at these points in more detail.

Plan an appointment schedule - for a study
==============================================

.. warning:: Please set the appointment schedule at the **beginning** of the study, before starting to book the appointments for the different patients.

.. note:: Do not forget to select your study beforehand.

To create an appointment schedule navigate to: **Appointment schedules** > **Create Appointment Schedule**, under the "**Study**" section.

Here you can specify different things:

* **Type of visit**: *screening, randomization, enrolment, follow-up* and *unplanned*.
* **Additional name**: this is meant to be used when multiple appointments of the same type (for example, multiple follow-ups) are planned. Some studies also have defined names for the specific appointments, which can be specified in this field.
* **Years from day 1**: years from when patient joins the study.
* **Days from day 1**: days when patient joins the study.
* **Duration**: duration of the appointment - this is only relevant when booking the actual/definitive appointment, and it can be edited after. A *default* option is available as 00:30:00 (30 minutes).
* **Minus day range**: this is the lower tolerance range to book the actual/definitive appointment. It will be calculated around the *days from day 1*. The *default* option is -2 days. Currently, the minimum *minus day range* is -7.
* **Plus day range**: this is the top tolerance range to book the actual/definitive appointment. It will be calculated around the *days from day 1*. The *default* option is 2 days. Currently, the maximum *plus day range* is 7.

.. note:: **Day 1** here will be the "reference" day from which the appointments dates are calculated. Depending on the study, it will vary. For example, for the STCS it will be the transplant date.

See below the appointment schedule for the study *Wine and Cheese*.

.. image:: AppScheduled.png
  :width: 600      

The appointment schedule can then be visualized by navigating to: **Appointment schedules** > **Appointment Schedule list**.

By double clicking on the *Appointment settings* or using the dropdown menu (see orange arrows in the figure), the Appointment Schedule will be expanded.

.. image:: AppList.png

Plan an appointment series for a patient
==============================================

.. warning:: Make sure your Appointment Schedule is **correct** before booking any patient appointments.

.. warning:: An update to the Appointment Schedule *will not update* appointments *already booked* with a previous Appointment schedule.

.. note:: Here we will be *planning* appointments, i.e. scheduling the appointments timings (not booking the actual/definitive/confirmed appointments).

Navigate to **Appointments** > **Create Appointment Series** to create an appointment series, make sure you select your study (in this case, *Wine and Cheese*) in the **Study filter**. Then, select the patient (for example here *Cristiano Ronaldo*)and the day 1 for this patient (preferred starting date and time) and save.

.. image:: AppSeries.png
  :width: 600

You can then visualize these appointments in the **Appointments** > **Appointment List**. As shown below:

.. image:: AppSeries2.png

.. note:: The new dates are calculated based on what was added as *Day 1* and the Appointment schedule.

.. note:: Currently, it is only possible to book appointments for an individual patient at the time.

Book a single appointment for a patient
*********************************************

It is also possible to book a single appointment for a patient (for example, an unplanned appointment).

.. note:: Here we will be *planning* a single appointment, i.e. scheduling one appointment timing (not booking the actual/definitive/confirmed appointment).

For this, navigate to: **Appointments** > **Create Single Appointment** and select the study (in **Study filter**). Select the patient, the type of visit and the scheduled date (appointment range and/or duration), and save. Fo example, David Beckham will have an unplanned appointment on the 27 of March 2024:

.. image:: AppSingle.png

How to visualize the planned appointments for the study patients
*******************************************************************

Please navigate to **Appointments** > **Appointments Lists**. Here you will have the list of all the appointments booked. You can see the appointments series for the patient *Cristiano Ronaldo* is shown.

This table can be sorted by *Study ID*, *Last name*, *First name*, *Study*, *Type*, *Scheduled date* and *Confirmed date*. For that, just click on the **-**, as shown below.

.. image:: AppLists.png

How to book an actual/definitive appointment for a patient
**************************************************************

So far, we have just made the *planning* of the appointments. However, IDEAL also allows to register the actual/definitive appointment.

There are 2 ways of doing this:

Book an actual appointment via the **Appointments list**
=============================================================

For this, navigate to **Appointments** > **Appointments List** > **Edit Appointment**, as shown below (pink arrow):

.. image:: AppEdit.png

This will open a new window where the details of this appointment can be seen. Here you can then select the **Actual date** (or definitive), as shown below:

.. image:: AppUpdate.png
  :width: 600

Book an actual appointment via the **Calendar**
=============================================================

You can also book the actual/definitive appointment directly from the **Calendar** (for more informations about the calendar, please check this section: :doc:`calendar`).

First, make sure you are on the *planned* view of the calendar. Then you just need to **double click** on the appointment and the window to update the appointment will appear as above.






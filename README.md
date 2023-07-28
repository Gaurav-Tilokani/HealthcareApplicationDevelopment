**Hospital Management And Patient Followups System:**

Technologies Used: Spring Boot (Backend), Ionic React (Frontend)

Actors in Application: 
  Admin: To register Hospitals, Supervisors, Doctors and FieldWorkers.
  Supervisor: To register Patients, Doctors and FieldWorker (in hospital).
  Doctor: To treat patients.
  Fieldworkers: To take followups of Patients.

Work Flow of Application:
  Supervisor will register patient.
  Patient will be assigned to the doctor with minimum number of patients.
  Doctor can pick a patient from assigned patients for checkup.
  Doctor can provide prescription and assign followups.
  For the first time supervisor will allocate followup to specific fieldworker but from the next time followup will be automatically assigned to same fieldworker.
  Fieldworker will take followup of patient. (When fieldworker is offline followup data will be stored in local storage and whenever fieldworker comes online data will be transferred from local db to main db)
  Doctor will be able to review followups and then assign new followup or end case.
  

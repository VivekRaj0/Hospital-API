# Hospital-API
API for Doctors of a Hospital which has been allocated by the govt. for testing, quarantine as well as well being of COVID-19 patients.

#### Setup the Project
1. Clone or Download the Repo.
2. Run `npm install` to install dependencies.
3. Run `npm start` to ignite the project.
4. Use **Postman** to test the api.

#### Routes
1. **Register a Doctor:** `[POST]: /api/v1/doctors/register`
2. **Login for Doctor:** `[POST]: /api/v1/doctors/login`
3. **Register a patient:** `[POST]: /api/v1/patients/register`
4. **Create Patient report:** `[POST]: /api/v1/patients/:id/create_report`
5. **Fetch All Reports of a Patient** `[GET]: /api/v1/patients/:id/all_reports`

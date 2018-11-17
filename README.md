# Medical Health - Vaccine Card

This file describes **Medical Health** a project that is devided into two separate apps each one with their functionality and developed using different approaches.

## Product Overview

**Medical Health** is a project designed to help Hospitals, Doctors, Goverment entities and Patients themselves keep track of vaccines records and streamline the appoinment process between patients and doctors. The project is devided into [**Medical Health - Doctor**](https://github.com/blackbelt-cda/MedicalHealth-Doctor) and [**Medical Health - Patient**](https://github.com/blackbelt-cda/MedicalHealth-Patient) both apps have very distinct purpose and functionalities.

### [Medical Health - Doctor](https://github.com/blackbelt-cda/MedicalHealth-Doctor)

#### Purpose
This app is meant to be used by doctors and nurses when having a vaccine appointment with a patient. 

#### Functionalities

* Register with offical medical number/id
* Doctors data (id, name, profile photo ...)
* QR Code Camara for reading the Vaccine Card (Reading)
* Update vaccination cards (User)
  * Vaccine card (automatic - through QRCode)
  * Doctor data (automatic)
  * Date of the vaccine
  * Hospital
  * The type of vaccine

#### Data Model

     TBA

### [Medical Health - Patient](https://github.com/blackbelt-cda/MedicalHealth-Patient)

#### Purpose
This app is meant to be used by patients or parents to keep track of vaccine cards. Each user can have more than one vaccine card in their account.

#### Functionalities

* Sign in to app
* User profile
* Add vaccination cards of people I am responsible for
* Get notifications about vaccination campaigns
* Share vaccine card
* Information of vaccines (periods, types of vaccines)
* Vaccine card  
  * Save / Collect data online and offline
  * Vaccine data table
  * User QR Code (Definitive)

#### Data Model

     TBA

```
   Copyright 2018 Braulio and Kiffen

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   ```

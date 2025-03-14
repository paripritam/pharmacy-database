# MIST 4610-Project1-Group3
Team Name:
Group 3

Team Members:
1. Mallavarapu, Pariprita @paripritam
2. Le, Yen 
3. Asenuga, Princess
4. Turner, Jack

Problem Description:
Our Pharmacy Database is designed to streamline the operations of a modern pharmacy business. This database facilitates the management of essential functions such as store operations, patient records, doctor affiliations, prescription tracking, medicine inventory, and sales management. By centralizing critical data, our system enhances operational efficiency, improves data accuracy, and provides valuable insights for informed decision-making by pharmacy management. Ultimately, the Pharmacy Database supports the pharmacy’s goal of delivering exceptional patient care, ensuring regulatory compliance, and optimizing resources to maximize profitability.

Data Model:
This data model represents a pharmacy management system, tracking interactions between doctors, patients, prescriptions, medicines, sales transactions, employees, and stores.

The Doctor entity captures doctor information, including their name, specialization, and contact number. Each doctor is linked to multiple Prescriptions, which store prescription details, including the prescribed date, expiration date, and duration of the medication supply. A prescription is associated with a single Patient, allowing the tracking of patient medical history.

The Medicine entity links to prescriptions, recording the details of prescribed drugs such as name, manufacturer, dosage, and expiration. A prescription can include multiple medicines, but each medicine entry is tied to a specific prescription.

The Patient entity maintains patient details, including name, date of birth, gender, contact information, and address. Patients are associated with a Store, indicating the pharmacy location where they obtain their prescriptions. The Store entity stores location details and contact information and links to employees working there.

The Employee entity tracks pharmacy staff, including their roles and store assignments. Employees handle Sales transactions, where each sale is associated with a patient and a prescription. Sales transactions store details such as the sale date, total amount, and employee responsible for the sale.

The relationships between these entities ensure efficient tracking of patient prescriptions, medicine inventory, doctor interactions,
ales transactions, and pharmacy staff management, forming a comprehensive pharmacy management system.
s<img width="730" alt="Screenshot 2025-03-13 at 10 55 43 PM" src="https://github.com/user-attachments/assets/82ebc201-5593-4316-a360-b73ca7b83d91" />

Data Dictionary:

Queries:

Database Information:

# Shipment-Management-Form
This project is a web-based form created using HTML, CSS, and JavaScript for managing student enrollment records. It connects to JsonPowerDB to store, update, and retrieve data in real time. The UI has been customized for a clean and modern experience.

is micro project is a **Shipment Management Form** built using HTML, CSS, JavaScript, and [JsonPowerDB (JPDB)](https://login2explore.com/jpdb/docs.html) as the backend database. The form allows users to create, read, update, and reset shipment records using a unique Shipment Number as the primary key.

---

## 🚀 Features

- Add new shipment entries using a unique Shipment Number
- Fetch and auto-fill existing shipment records
- Update shipment details
- Reset and clear the form
- Validates input before saving/updating
- Uses JPDB APIs to store and retrieve data

---

## 📦 Technologies Used

- HTML5 & CSS3
- jQuery
- JsonPowerDB (JPDB)

---


---

## 🔑 JPDB Setup

Ensure you have a valid **JsonPowerDB token** and set up:

- **Database Name:** `DELIVERY-DB`
- **Relation Name:** `SHIPMENT-TABLE`
- **Primary Key:** `Shipment-No.`

You can generate a token and manage the database at:  
👉 [https://login2explore.com](https://login2explore.com)

---

## 🧪 How to Run

1. Download or clone the repository.
2. Open `index.html` in any browser.
3. Enter a `Shipment No.`:
   - If it exists, it will load data.
   - If not, you can fill and save new data.
4. Use **Save**, **Update**, or **Reset** buttons as needed.

---

## 📸 Form Fields

- Shipment-No. (Primary Key)
- Description
- Source
- Destination
- Shipping-Date
- Expected-Delivery-Date

---

## 📚 JsonPowerDB Commands Used

- `GET_BY_KEY` – Fetch data by primary key
- `PUT` – Insert new data
- `SET` – Update existing data

---

## 🙌 Author

Developed by **Amitesh Batham**  
Feel free to reach out for any support or suggestions!

---

## 🛡️ License

This project is open-source and free to use for educational purposes.



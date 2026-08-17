# Hospital Ward Management API

A simple Hospital Ward Management API built with **Flask and SQLite**.

## Features

* Add Ward
* View Wards
* View Ward by ID
* Update Ward
* Delete Ward

## Technologies

* Python
* Flask
* SQLite
* REST API

## Run Project

Install Flask:

```bash
pip install flask
```

Run:

```bash
python app.py
```

API:

```text
http://127.0.0.1:5000
```

## API Endpoints

```text
POST   /wards
GET    /wards
GET    /wards/<id>
PUT    /wards/<id>
DELETE /wards/<id>
```

## Example

Add Ward:

```json
{
    "ward_name": "General Ward",
    "ward_type": "General",
    "total_beds": 20,
    "available_beds": 15
}
```

## Database

SQLite database is automatically created as:

```text
hospital.db
```

## Author

Maheen Asad

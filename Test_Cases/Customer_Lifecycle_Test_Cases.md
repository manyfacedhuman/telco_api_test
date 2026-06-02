# Telecom Customer Lifecycle Test Cases

## TC001 - Create Customer

**Objective**
Verify customer can be created successfully.

**Method**
POST

**Endpoint**
https://reqres.in/api/users

**Request**

{
  "name": "Mohan",
  "job": "Telecom Customer"
}

**Expected Result**

- Status Code = 201
- Customer ID generated
- Response time < 2 seconds

---

## TC002 - Get Customer

**Objective**
Verify customer details can be retrieved.

**Method**
GET

**Endpoint**
https://reqres.in/api/users/2

**Expected Result**

- Status Code = 200
- Customer details displayed

---

## TC003 - Update Customer

**Method**
PUT

**Endpoint**
https://reqres.in/api/users/2

**Expected Result**

- Status Code = 200
- Updated timestamp generated

---

## TC004 - Delete Customer

**Method**
DELETE

**Endpoint**
https://reqres.in/api/users/2

**Expected Result**

- Status Code = 204

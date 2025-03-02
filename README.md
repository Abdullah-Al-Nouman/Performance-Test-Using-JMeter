# JMeter Performance Testing Project 🚀

## Overview 🌐

This project contains JMeter collections for performance testing of two APIs:
1. **Booking API** (Task 1)
2. **dmoney API** (Task 2)

The tests simulate user actions like logging in, creating bookings, making deposits, and sending money to evaluate the server performance under load and stress conditions.

---

## Table of Contents 📋

1. [Prerequisites](#prerequisites) ⚙️
2. [Task 1: Booking API Testing](#task-1-booking-api-testing) 🛎️
3. [Task 2: dmoney API Testing](#task-2-dmoney-api-testing) 💸
4. [Test Report Screenshots](#test-report-screenshots) 📸
---

## Prerequisites ⚙️

- [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi) (version 5.x or later)
- Java Runtime Environment (JRE) 8 or higher
- CSV files for user actions:
  - `deposit.csv`
  - `sendMoney.csv`
  - `payment.csv`

---

## Task 1: Booking API Testing 🛎️

### Scenario 🎯

Simulate 120,000 users performing the following actions:
1. **Login** (POST `/auth`)
2. **Create Booking** (POST `/booking`)
3. **Search Booking** (GET `/booking/{booking_id}`)

We will perform load and stress tests with varying user counts to assess server performance.

---

## Task 2: dmoney API Testing 💸

### Scenario 🎯

Simulate 5 agents performing deposits for 10 customers, 5 customers sending money to 10 others, and 5 customers making payments to merchants.

---

## Test Report Screenshots 📸

- **Load Test Report Screenshot**:  
  ![Load Test Screenshot](https://github.com/user-attachments/assets/dbbea71a-b9cd-44b8-9e0b-b2ef730f155a)

- **Stress Test Report Screenshot**:  
  ![Stress Test Screenshot](https://github.com/user-attachments/assets/62bca931-81f5-4c2c-a9a3-56b41b2de6a3)


- **HTML Report Screenshot**:  
  ![HTML Report Screenshot](screenshots/html_report.png)



---


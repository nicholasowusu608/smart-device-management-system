# Smart Device Management System

## Introduction
The **Smart Device Management System** is an object-oriented Python application designed to manage smart home networks. The core purpose of this system is to handle common device operations while accounting for unique device features under strict object-oriented programming (OOP) constraints like encapsulation and inheritance.

This project was built as part of the **EL 162 / 234 Object Oriented Programming** course under the supervision of Dr. Matthew Cobbinah.

---

## Architectural Principles Demonstrated
*   **Encapsulation:** Protected system integrity by rendering core variables (`__device_id`, `__power_status`) strictly private. Safe accessibility boundaries are explicitly enforced using native Python `@property` decorators.
*   **Inheritance & Polymorphism:** Specialization subclasses (`TemperatureSensor`, `SmartLight`, `SecurityCamera`) extend structural schemas using modern `super().__init__()` hooks while overriding rendering routines via explicit method extensions.
*   **Data Validation:** Run-time checks verify constructor values (e.g., rejecting empty device strings or validating limits for brightness scales).

---

## Features & Controls
The system implements a simple interactive menu loop inside the terminal allowing full execution capabilities:
1. **Display System Configurations:** Pull logs from all active appliances.
2. **State Control Matrix:** Toggle operational power modes safely.
3. **Environment Sampling:** Access sensory telemetry metrics (`TemperatureSensor`).
4. **Luminescence Balancing:** Fine-tune intensity arrays (`SmartLight`).
5. **Surveillance Feed Dispatching:** Manage remote security capture lines (`SecurityCamera`).

---

## Getting Started

### Prerequisites
* Ensure Python **Version 3.8** or higher is installed on your local operating environment.

### Setup and Execution Instructions

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/nicholasowusu608/smart-device-management-system.git](https://github.com/nicholasowusu608/smart-device-management-system.git)
   cd smart-device-management-system

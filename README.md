# Hospital Appointment Management System

## Project Overview

The **Hospital Appointment Management System** is a simple Python-based system developed as part of the **Python Study Group – Case Study Project #2**.

The project simulates how a hospital can manage patient appointments by collecting patient information, validating appointment details, categorising patients, determining appointment priority, and generating appointment reports.

The project focuses on applying fundamental Python programming concepts to solve a real-world healthcare problem.

## Project Objectives

The system was developed to demonstrate the ability to:

* Validate patient information
* Validate hospital departments
* Categorise patients based on age
* Determine appointment priority
* Process multiple patient records
* Create reusable functions
* Use loops to manage repeated tasks
* Apply variable scope
* Generate readable appointment reports

## Appointment Information

The system works with information such as:

* Patient Name
* Patient ID
* Patient Age
* Department
* Doctor Name
* Appointment Day
* Appointment Time
* Emergency Status

## Features

### 1. Patient Information Validation

The system checks whether:

* The patient's name is provided
* The Patient ID is provided
* The patient's age is valid

### 2. Department Validation

The system checks whether the selected department is one of the hospital's available departments:

* Cardiology
* Pediatrics
* General Medicine
* Orthopedics
* Neurology

### 3. Patient Categorization

Patients are categorized according to their age:

| Age   | Category |
| ----- | -------- |
| 0–12  | Child    |
| 13–17 | Teenager |
| 18–64 | Adult    |
| 65+   | Senior   |

### 4. Appointment Priority

Appointment priority is determined using the following rules:

* Emergency patient → **High Priority**
* Senior patient → **Medium Priority**
* Other patients → **Normal Priority**

### 5. Multiple Appointment Processing

A `for` loop is used to process multiple patient records, validate their information, determine their categories, and assign appointment priorities.

### 6. Patient Registration

A `while` loop is used to ensure that a valid Patient ID is entered before registration continues.

### 7. Appointment Registration Loop

A `while True` loop allows users to register additional appointments and uses `break` to safely terminate the process when the user chooses not to continue.

### 8. Appointment Report

The system generates a structured appointment report containing the patient's details, appointment information, emergency status, priority level, and appointment status.

## Python Concepts Demonstrated

This project demonstrates the following fundamental Python concepts:

* Variables
* Data types
* Boolean values
* Operators
* `if`, `elif`, and `else`
* `for` loops
* `while` loops
* Infinite loops
* `break`
* Functions
* Parameters
* Arguments
* Return values
* Local and global variables

## Project File

The main project file is a Jupyter Notebook containing the completed tasks and their outputs.

`hospital_appointment_management_system.ipynb`

## Project Output

A screenshot of the final program output is included in this repository.

## Learning Outcome

This project provided practical experience in using Python programming concepts to design a simple system that addresses a real-world healthcare problem.

It demonstrates how programming logic can be used to validate information, process records, apply decision-making rules, and generate useful reports.

## Project Information

**Project:** Python Study Group Case Study Project #2
**Case Study:** Hospital Appointment Management System
**Language:** Python
**Environment:** Jupyter Notebook
**Project Type:** Learning / Case Study Project

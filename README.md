# Lab-Extending




# Grades App

## Overview
Grades App is a Flutter application designed to manage and analyze student grades. It offers a variety of features including grade entry, sorting, statistical analysis, and data import/export functionalities.

## Features

### Grade List
- Displays a list of student grades.
- Each entry includes a Student ID (SID) and the corresponding grade.

### Grade Entry
- Users can add new grades to the list.
- Each entry requires a Student ID and a grade.

### Editing Grades
- Users can edit grades by tapping on an existing grade entry.
- Edited grades are updated in the list.

### Sorting Grades
- Grades can be sorted based on SID or grade value.
- Sorting options include ascending and descending orders.

### Grade Statistics
- Provides statistical analysis of grades.
- Displays the highest, lowest, and average grades.

### Import CSV
- Allows users to import grades from a CSV file.
- Supports file selection through a file picker interface.

### Export to CSV
- Enables exporting the current list of grades to a CSV file.
- The exported file is saved in the device's storage.

### Calculate Average Grade
- Calculates the average grade from the list.
- The average grade is displayed as a GPA value.

## Usage

### Adding a New Grade
1. Tap the 'Add' button.
2. Enter the Student ID and grade.
3. Submit to add the grade to the list.

### Editing a Grade
1. Tap on the grade you wish to edit.
2. Modify the details in the provided fields.
3. Save the changes.

### Sorting Grades
1. Tap the 'Sort' icon in the AppBar.
2. Choose the desired sorting method.

### Importing Grades from CSV
1. Tap the 'Import' icon.
2. Select a CSV file from the device.
3. The grades from the file will be added to the list.

### Exporting Grades to CSV
1. Tap the 'Export' icon.
2. The grades will be saved as a CSV file in the device's storage.

## Development Setup

- Clone the repository.
- Run `flutter pub get` to fetch the dependencies.
- Open an emulator or connect a device.
- Run the app using `flutter run`.


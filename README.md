# Eye Zone

**Eye Zone** is an application designed to list exploited, online, and publicly available cameras that can be accessed through their IP addresses. This tool enables users to search for cameras based on various criteria such as places, countries, and manufacturers.

## Features

 **Search by Places**: Provides a list of cameras based on location categories like `Beach`, `City`, `Hotel`, etc.
 **Search by Countries**: Allows users to find cameras by country, including `United States`, `Japan`, `Germany`, etc.
 **Search by Manufacturers**: Lists cameras based on the manufacturer.

## Installation

1. **Clone the Repository:**

   git clone https://github.com/darmickkr/eyezone.git
  

2. **Install Required Libraries:**

   This project uses the `requests` library. You can install it using pip.

## Usage

1. **Select Options:**
    Exit
    Search by Places
    Search by Countries
    Search by Manufacturers

   Select an option by entering the corresponding number.

2. **Search Options:**
    **Places**: Choose from various categories like `Bar`, `Coffeehouse`, `Mall`, etc.
    **Countries**: Select from a list of countries including `United States`, `Italy`, `China`, etc.
    **Manufacturers**: (Details for this option would be included here based on the actual implementation.)

## Code Overview

 **Imports**: The script imports necessary modules like `requests`, `re`, `os`, and `time`.
 **User OS Detection**: Determines the operating system to clear the terminal screen appropriately.
 **Banner**: Displays a banner with project information and links.
 **User Input**: Provides a menu for user interaction.
 **Places Function**: Fetches and displays camera IPs based on selected place categories.
 **Countries Function**: Fetches and displays camera IPs based on selected countries.

## Outcome

The Eye Zone Python code application provides a method for finding publicly accessible cameras using their IP addresses. By leveraging this code, users can quickly identify and retrieve camera information based on specific criteria such as location, country, and manufacturer. The application’s efficiency in searching and listing these cameras demonstrates its effectiveness in handling and processing Test with manual data.

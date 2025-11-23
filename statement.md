# Currency Converter Application

## Problem Statement

The need for real-time, accurate, and user-friendly currency conversion has grown significantly, especially with the rise of global commerce, travel, and remote work. Traditional currency converters often lack interactive features, visual representation, or seamless desktop integration. This project addresses these gaps by providing a dynamic GUI-based currency converter built using Python and Tkinter, capable of fetching live foreign exchange rates and displaying converted values both numerically and graphically.

## Scope of the Project

This project focuses on creating a desktop-based currency converter application with the following capabilities:

* Fetching live exchange rates from an online source.
* Allowing users to select a currency and enter an amount in INR (Indian Rupees).
* Displaying the converted currency value.
* Visualizing conversion results through Matplotlib charts embedded in the GUI.
* Providing user-friendly controls for resetting inputs and exiting the application.

The project does **not** include offline mode, multi-source exchange rate comparison, advanced financial analytics, or mobile deployment.

## Target Users

This application is designed for:

* Students and learners exploring GUI development or currency conversion concepts.
* Travelers needing quick, on-demand currency conversion.
* Developers looking for a practical example of integrating Tkinter with live web scraping and Matplotlib.
* Users who prefer desktop tools over online converters.

## High-Level Features

* **Interactive GUI:** Built using Tkinter with clearly structured frames, labels, buttons, and input fields.
* **Live Rate Fetching:** Web scraping using `requests` and `BeautifulSoup` to extract real-time exchange rates.
* **Conversion Calculator:** Converts INR to a selected foreign currency based on live data.
* **Graphical Visualization:** Embedded scatter plot generated with Matplotlib to visualize conversion values.
* **Reset & Exit Controls:** Easy-to-use buttons for clearing data or closing the application.
* **Dropdown Currency Selection:** A comprehensive list of global currencies available via a combo box.

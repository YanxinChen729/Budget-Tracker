# Budget Tracker
#### Video Demo:  https://youtu.be/TPXAABEypnU
#### Description:

**Budget Tracker** is a desktop-based application that enables users to record, track, and visualize their personal expenses. Designed with accessibility and usability in mind, the application features an intuitive interface where users can add spending records, categorize them, search and update entries, and view expense summaries through interactive visualizations.

Upon launching the application, users first encounter a login/start window to simulate multi-user readiness. Once logged in, the main interface presents the "Home" menu, where users can:

- Add new spending records with fields such as Title, Price, Category, and Comment.
- View all stored data in a scrollable and interactive table.
- Search existing records by title, price, or category.
- Update any selected record (e.g., modify its comment or price).
- Delete individual entries or clear the entire table.

One of the highlights of this application is the **Graph View**, where users can switch tabs to see a dynamic pie chart summarizing spending by category. This graph is generated using **Pandas** for data processing and **Plotly** for visualization, offering an immediate snapshot of budgeting patterns.

The application includes robust input validation—ensuring no fields are left blank, entry lengths are within bounds, and data types are correct. All data is persistently stored using **SQLite**, while the graphical user interface is built with **Tkinter** and enhanced using **ttkbootstrap** for a modern look.

This project was built using Python 3.10 and is compatible with macOS and Windows environments.

---

## Demo
### Start Window
![login_window](https://github.com/ArtemKhov/Budget-Tracker/assets/107346597/ebc86cb5-2a0b-4296-a87c-b8cb176fe0ca)

### Home Window
![home_window](https://github.com/ArtemKhov/Budget-Tracker/assets/107346597/2677a1a3-a757-4ce1-a6f7-42c7f161ecff)

### Graph Window
![graph_window](https://github.com/ArtemKhov/Budget-Tracker/assets/107346597/29cbaf03-af16-43fa-88df-44fd180f12be)

## Technologies

**Tech Stack:**

- Python
- Pandas
- Plotly
- SQLite3
- tkinter
- ttkbootstrap

## Features

- Add records to the table (data is stored in a SQLite3 database)
- View all records
- Search for records by Title / Price / Category
- Delete one record or all records at once
- In the Graph menu you can see the amount of your expenses by category as a graph (implemented with Pandas and Plotly)
- Shows the error window when leaving blank fields, incorrect text length, etc.

## Run it locally (written for Windows)
1) Create a directory and clone the repo in it:
```sh
   git clone https://github.com/ArtemKhov/Budget-Tracker
   ```
2) Create your virtual environment:
```
python -m venv env
```
3) Activate your virtual environment:
```
env\Scripts\activate
```
4) Install the requirements.txt:
```
pip install -r requirements.txt
```



# Dashboard Assignment for Frontend Trainees

## Project Description
This project involves creating a dynamic dashboard page where users can add and remove widgets within different categories. The dashboard is built using React and utilizes a state management tool to handle the addition and removal of widgets.

## Features
1. **Dynamic JSON Structure**: The dashboard is built dynamically using a JSON structure that contains categories and widgets.
2. **Add/Remove Widgets**: Users can add new widgets to categories and remove existing ones with cross icon.
3. **Widget Content**: For assignment purposes, widgets contain random text.
4. **Search Functionality**: Users can search through a list of all widgets.
5. **Cross Icon**: Each widget has a cross icon to remove it from a category.
6. **Pie Chart (Optional)** :If we want to add pie chart in to the data we can add them simply by using
```sh
npm install recharts 
```
Then we can create **components/PieChart.js** Component.

## Technologies Used
- React
- State Management Tool - Redux for React

## Installation and Setup Instructions
### Clone the Repository:
```
git clone <repository-url>
cd <repository-directory>
```

### Install Dependencies:
```sh
npm install
```

### Run the Application:
```
npm start
```
### Build the Application (for production):
```
npm run build
```

## Usage Instructions
### 1. Adding a Widget:
- Click on the “+Add Widget” button.
- Fill in the widget name and text.
- Select the category to which the widget should be added.
- Click “Add”.
### 2. Removing a Widget:
- Click on the cross icon on the widget you want to remove.
### 3. Searching Widgets:
- Use the search bar to find widgets by name.

## JSON Structure
```json
{
  "categories": [
    {
      "name": "CSPM Executive Dashboard",
      "widgets": [
        {
          "name": "Cloud Account Status",
          "type": "pieChart",
          "text": "Random text for assignment purposes"
        },
        {
          "name": "Connected Accounts",
          "type": "number",
          "text": "Random text for assignment purposes"
        }
      ]
    },
    {
      "name": "CWPP Dashboard",
      "widgets": [
        {
          "name": "Top 5 Specific Alerts",
          "type": "barChart",
          "text": "Random text for assignment purposes"
        },
        {
          "name": "Workload Alerts",
          "type": "barChart",
          "text": "Random text for assignment purposes"
        }
      ]
    },
    {
      "name": "Registry Scan",
      "widgets": [
        {
          "name": "Image Risk Assessment",
          "type": "barChart",
          "text": "Random text for assignment purposes"
        },
        {
          "name": "Image Security Issues",
          "type": "barChart",
          "text": "Random text for assignment purposes"
        }
      ]
    }
  ]
}

```


# ForingX

## Introduction

ForingX is a stock data analysis application designed to help users make informed investment decisions by analyzing historical stock data and predicting future trends. Users will input specific stock data into the application, which will then analyze the data and visualize it in the form of graphs.

### About the developers

This application is being developed as a part of the Year 3, Period 3 courses at NHL Stenden University of Applied Sciences. Below are the team members:

|        Name        | Student Nr |               Student email               |
| :----------------: | :--------: | :---------------------------------------: |
| Terry Ioannou      |  4976355   |   terry.ioannou@student.nhlstenden.com    |
| David Hlavacek     |  [ID]      | [Teammate 1 Email]                        |

## Description

ForingX is inspired by the concept of analyzing stock data to make predictions, similar to various financial analysis tools available in the market. Users will be able to input specific stock data into the application, and based on that data, Foring will provide visual analysis in the form of graphs, helping users to understand trends and potentially predict future stock movements.

### General Specifications:

- Data analysis application
- 2D graphical interface
- Single-user mode
- Requires manual input of stock data

### Class Diagram(Being Worked on)

![ClassDiagram](./Assets/Foring_ClassDiagram.png)

### Design Mockups(Being Worked on)

#### Icon(Being Worked on)

![Icon](./Assets/Foring_Icon.png)

#### Main Screen(Being Worked on)

![MainScreen](./Assets/Foring_MainScreen.png)

#### Data Input Form(Being Worked on)

![DataInputForm](./Assets/Foring_DataInputForm.png)

#### Analysis Result Graph(Being Worked on)

![AnalysisGraph](./Assets/Foring_AnalysisGraph.png)

## Input & Output

*The section below is yet to be updated*

### MoSCoW Analysis

|  Priority   |                             Task                             |
| :---------: | :----------------------------------------------------------: |
|  Must have  | Data input form<br/>Data analysis module<br/>Graph visualization<br/> |
| Should have | Authentication<br/>Data saving/loading<br/>Real-time data fetching<br/> |
| Could have  | Machine learning algorithms<br/>Additional data analysis tools<br/> |
|  Wont have  | Advanced financial modeling<br/>Third-party integrations<br/> |


### Input

Users can import data in the following formats:
- CSV files
- JSON files

### Output

|  Case   |   Type   |
| :-----: | :------: |
| Analysis| `Graph`  |

### Remarks

* Data input will be validated
* Authentication will be implemented to ensure data security
* Real-time data fetching may be considered in future iterations

## Design Patterns used

The following design patterns will be utilized in ForingX:

- **Factory Method:** For creating instances of data input forms and analysis modules.
- **Observer:** For updating the visualization module with new data.
- **Strategy:** For implementing different analysis strategies (e.g., moving average, trend analysis).


## Additional Functionalities

### Threading and Concurrency

- Basic threading will be utilized for performing tasks concurrently, such as data fetching and processing.
- Locking mechanisms will ensure data integrity when multiple threads access shared resources.
- Semaphores will control access to limited resources, managing resource usage efficiently.
- The thread pool will be used for managing concurrent tasks efficiently, especially for short-lived tasks or asynchronous operations.

### Task-Based Programming and Asynchronous Operations

- Task-based programming, including basic task creation and the `await` operator, will be used for asynchronous operations such as data fetching and IO operations.
- Async IO operations will be employed for non-blocking IO operations, ensuring responsiveness of the application during IO-bound tasks.

### LINQ, PLINQ, and Async on the Database

- LINQ and PLINQ will be used for querying and processing data efficiently, with PLINQ providing parallel execution for improved performance.
- Asynchronous database operations will enable non-blocking database access, ensuring responsiveness while waiting for database responses.

## Additional Implementation Details

- ForingX will utilize C# .NET 8.0 or higher for its development, ensuring access to the latest features and enhancements.
- Integration of .NET Maui will be explored for cross-platform compatibility and enhanced user experience.
- The development of a clean GUI will be prioritized to ensure seamless program operation and user-friendly interaction.
- Version control will be incorporated using tools like Git to track changes, collaborate effectively, and manage project versions efficiently.



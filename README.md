# PROJECT MANAGEMENT DASHBOARD Using Google Sheets

## Project Overview

In response to an increasing demand for streamlined project oversight, this Project Management Dashboard was developed to provide data-driven insights into project performance, risk factors, and capital management. Designed for executives and project teams, the dashboard centralizes KPIs and trends, enabling timely and informed decision-making across all active projects.

### Key Features:

- Centralized KPI Tracking
- Risk Portfolio Management
- Capital Allocation Analysis

## Tools Used

- **Google Sheets**: For data management, organization, and visualization.
- **Pivot Tables**: Used extensively to create and update bar, donut, and stacked column charts across all sections of the dashboard.
- **Google Apps Script**: For automating navigation, filter applications, and enhancing the dashboard's interactivity.

## Key Metrics

The dashboard provides several key metrics that offer a comprehensive view of project performance and allocation:

- **Total Task Count**: Displays the total number of tasks across all sections.
- **Total Story Points (Working Hours)**: Summarizes the cumulative hours required for task completion.
- **Task Urgency**: Shows task urgency levels to guide resource allocation.
- **Task Progress**: Tracks overall task completion status.

## Google Apps Script Functionality

### Navigation Automation

- **Button-Triggered Navigation**: Each navigation button runs a Google Apps Script function to toggle between sections, making navigation user-friendly and efficient.

### Filtering Mechanisms

- **Dynamic Filtering**: Filters by **Profile** and **Team Name** in Section 2 automatically adjust the data displayed in both Sections 2 and 3, synchronizing insights across the dashboard.

## Use of Pivot Tables

Pivot tables play a critical role in this dashboard, allowing real-time updates of each chart by filtering data as needed:

- **Data Aggregation**: Pivot tables consolidate task data across profiles, teams, and statuses, making it easier to generate the charts in each section.
- **Dynamic Charting**: Each bar, donut, and stacked column chart leverages pivot table results, allowing the dashboard to refresh as data is updated.


## Dashboard Structure and Navigation

The dashboard is divided into three main sections, each containing a **navigation bar** with "Home" and "Detail" buttons. These buttons allow seamless movement between sections for quick access to relevant information.

### Section 1: Overview

- **Charts and Visualizations**:
  - **Profile Task Count** (Bar Chart) - Displays tasks assigned to each profile.
  - **Assigned Task Count** (Bar Chart) - Highlights tasks assigned to individuals or teams.
  - **Urgency Measure** (Donut Chart) - Visualizes the urgency of tasks based on priority levels.
  - **Progress Status** (Donut Chart) - Shows the overall task completion rate.

- **Navigation**:
  - Buttons for moving to **Section 2** or **Section 3**.

![Slide1](https://github.com/Vanshika0309/Google-Sheets-Project-Manager-Dashboard/blob/main/Slide1.png)


### Section 2: Task Allocation and Summary

- **Charts and Visualizations**:
  - **Profile Task Count** (Bar Chart) - Replicates the overview for comparison across sections.
  - **Assigned Task Count** (Bar Chart) - Provides insight into task allocation.
  - **Urgency Measure** (Donut Chart) - Displays priority-based task urgency.
  - **Progress Status** (Donut Chart) - Illustrates the completion status of tasks.

- **Task Table**:
  - Displays detailed data for each task, with columns: **Task No.**, **Profile**, **Team Name**, **Assigned To**, and **Status**.
  - **Filters**: Filters by **Profile** and **Team Name** enable a focused view, dynamically updating task details within both Sections 2 and 3.

- **Navigation**:
  - Buttons for moving to **Section 1** or **Section 3**.

![Slide2](https://github.com/Vanshika0309/Google-Sheets-Project-Manager-Dashboard/blob/main/Slide2.png)


![Slide3](https://github.com/Vanshika0309/Google-Sheets-Project-Manager-Dashboard/blob/main/Slide3.png)


### Section 3: Detailed Task Status

- **Charts and Visualizations**:
  - **Task Status by Completion** (Stacked Column Chart) - Provides a breakdown of tasks as Completed, Not Completed, or In Progress.
  - **Assigned Task Count** (Bar Chart) - Displays detailed task allocation information.

- **Data Synchronization**:
  - Filters applied in Section 2 for **Profile** and **Team Name** are carried over to Section 3, ensuring continuity and consistency in data across sections.

- **Navigation**:
  - Buttons for moving back to **Section 1** or **Section 2**.

 ![Slide4](https://github.com/Vanshika0309/Google-Sheets-Project-Manager-Dashboard/blob/main/Slide4.png)



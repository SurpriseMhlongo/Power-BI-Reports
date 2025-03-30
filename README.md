# Project title : OutletOptics_Sales
Business Requirements
1. Project Overview

Objective: Develop an interactive Power BI dashboard to analyze sales performance, item distribution, and outlet metrics for a retail business.
Target Users: Sales managers, retail analysts, and business stakeholders.
Data Source: Dataset containing item and outlet attributes (e.g., Item Fat Content, Outlet Type, Sales, Rating).
2. Business Requirements
2.1 Key Metrics to Track

    Total Sales (Sum of Sales).

    Number of Items Sold (Count of Item Identifier).

    Average Sales per Item.

    Average Customer Rating.

2.2 Visualizations & Filters
Core Visualizations:

    Summary Cards:

        Display Total Sales, Number of Items, Average Sales, and Average Rating.

    Donut Chart:

        Metric: Metrics Values (dynamic selection via slicer).

        Legend: Item Fat Content.

    Clustered Bar Charts:

        Chart 1:

            X-axis: Metrics Values (dynamic).

            Y-axis: Outlet Location Type.

            Legend: Item Fat Content.

        Chart 2:

            X-axis: Metrics Values (dynamic).

            Y-axis: Item Type.

    Line Chart:

        X-axis: Outlet Establishment Year.

        Y-axis: Total Sales (trend analysis).

    Donut Chart:

        Legend: Outlet Size.

        Values: Total Sales.

    Funnel Chart:

        Category: Outlet Location Type.

        Values: Sum of Sales.

    Tabular Matrix:

        Rows: Outlet Type.

        Columns/Values:

            Total Sales, Number of Sales, Average Sales, Average Rating, Sum of Item Visibility.

Filters (Slicers):

    Dynamic metric selection (Total Sales, Number of Items, etc.).

    Dropdowns for:

        Outlet Location Type.

        Outlet Size.

        Outlet Type.

3. Technical Specifications
Data Fields Used:

    Item Attributes:
    Item Fat Content, Item Identifier, Item Type, Item Visibility, Item Weight.

    Outlet Attributes:
    Outlet Establishment Year, Outlet Identifier, Outlet Location Type, Outlet Size, Outlet Type.

    Metrics:
    Sales, Rating.

Interactivity:

    Cross-filtering enabled across all visuals.

    Dynamic metric switching via slicer.

4. Success Criteria

    Users can identify sales trends by year, outlet location, and item type.

    Compare performance across outlet sizes and fat content categories.

    Drill into detailed metrics via the matrix table.

# Project Case Study: Mercy Farm Agricultural Yield Analytics Dashboard

##  Executive Summary
This project delivers a data-driven performance solution for Mercy Farm, a commercial agricultural enterprise focused on optimizing crop cultivation and maximizing harvest outputs across multiple regional territories. The primary purpose of this project is to eliminate guesswork in crop management by analyzing how environmental factors and farming decisions impact final outputs. By organizing fragmented field records into a centralized system, this dashboard uncovers how specific soil profiles, regional weather conditions, irrigation choices, and farming techniques directly influence production efficiency. Ultimately, it provides farm management with a clear tool to identify high-performing crop variations, allocate resources to struggling regions, and implement strategic irrigation changes to scale total output.

## Problem Statement
*   **Situation:** Mercy Farm manages diverse agricultural operations cultivating six key crops (Maize, Barley, Rice, Cotton, Wheat, and Soybean) across four geographical regions (East, North, South, and West).
*   **Complication:** Field metrics such as soil quality, daily temperatures, rainfall levels, and irrigation use are recorded across scattered logbooks. Without a unified view, management cannot easily see why certain crops thrive in one region but fail in another. This lack of visibility makes it difficult to plan planting schedules, optimize water distribution, or predict harvest timelines accurately.
*   **Core Question:** How can Mercy Farm systematically connect environmental variables, weather events, and field infrastructure to design data-driven seasonal planting schedules that maximize total crop yield across all regions?

## Tools  Used
This project was built 100% end-to-end using Microsoft Excel, proving advanced data manipulation, modeling, and visualization capabilities within standard spreadsheet software
*   **Excel Power Query:** Used to ingest raw field collection logs, remove formatting inconsistencies, handle null entries, and structure columns for clean analytical modeling.
*   **Advanced Formulas:** Leveraged advanced logic and lookup functions to calculate key macro-level performance metrics, establishing a dynamic backend that automatically updates when regional filters change.
*   **PivotTables & PivotCharts:** Utilized to group massive rows of raw agricultural data into distinct summary subsets (such as tracking crop performance relative to regional geographic boundaries and varying soil groups).
*   **Dashboard & Slicers:** Created a professional, agricultural themed user interface and clean layouts. Integrated  Excel Slicers to allow immediate, interactive filtering across every visual component.

## How the Dashboard Works
1.  **Macro KPI Summary Cards:** Provides the farm owner with an instant, real-time look at critical production baselines: Total Yield (4M tons/hectare), Average Yield (5 tons/hectare), Average Rainfall (550 mm), Average Temperature (28°C), and Average Days to Harvest (104).
2.  **Environmental Impact Analysis:** Compares individual crop metrics directly against structural soil types (Clay, Silt, Sandy, Loam, Peaty, Chalky) and weather classifications using intuitive vertical bar charts.
3.  **Interactive Slicers:** Added page-level filter controls (**Region Slicers:** East, North, South, West and **Weather Slicers:** Cloudy, Rainy, Sunny) to let field managers segment the metrics instantly.
4.  **Operational Strategy Tracking:** Employs donut charts to display the proportional split between the active implementation versus the non-use of specialized Farming Practices (58% Not Used) and Irrigation Practices (56% Not Used).


https://github.com/user-attachments/assets/e75f4149-9e3b-4583-b868-f284a6b0036e

<img width="944" height="673" alt="Screenshot 2026-09-10 155553" src="https://github.com/user-attachments/assets/dd7111cf-abb6-4d4c-8e38-0b091dad127a" />


## Key Findings
*   **Top Performing Crops & Regions:** Soybean and Wheat consistently drive the highest crop performance indexes, with the Northern region demonstrating the strongest overall agricultural output. Conversely, Maize, the Eastern region, and fields with dense Clay soil profiles systematically underperform.
*   **Weather and Soil Advantages:** Crops planted in Chalky and Peaty soils achieve significantly higher yield rates compared to tight Clay soils. Furthermore, clear Sunny weather conditions hold a slight performance advantage over heavily Cloudy periods.
*   **Underutilized Infrastructure:** More than half of the farm's active cultivation zones are operating without structured Irrigation Practices (56% Not Used) and modern Farming Practices (58% Not Used), exposing a clear vulnerability to natural weather fluctuations.
*   **Harvest Timeline Variations:** Crops show highly stable, tight windows for maturity across the board, with average growth tracking tightly between 104.35 to 104.55 days to harvest from initial planting.

##  Practical Recommendations
1.  **Expand Irrigation Infrastructure:** Immediately target the 56% of non-irrigated farmland to build modern watering systems, protecting vulnerable crops like Maize from dry seasonal windows.
2.  **Geographic Crop Matching:** Restructure seasonal planting maps to prioritize high-yield crops like Soybean in the highly receptive Northern zones, while investigating supply deficiencies or resource bottlenecks slowing down production in the Eastern region.
3.  **Farmer Training Initiatives:** Launch practical training modules to increase the adoption of advanced farming practices beyond the current 42% threshold, focusing heavily on soil-specific remediation techniques for low-yield Clay sectors.


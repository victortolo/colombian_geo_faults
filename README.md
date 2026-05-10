This project focuses on the geospatial analysis and visualization of tectonic fault lines within the Colombian territory. Using Python and vector data processing libraries, the repository provides a workflow to quantify and map geological structures in relation to administrative boundaries.

Project Overview
The primary objective of this code is to process vector layers representing the departments of Colombia and national fault lines. It performs geometric calculations to determine the length of individual line features and provides visual insights through thematic maps.

Key Features
Vector Data Integration: Loads and manages spatial data for Colombian departments and geological faults.  (Faults and departments data from: https://www.colombiaenmapas.gov.co/#)

Geometric Length Calculation: Automatically generates a new attribute column to calculate the precise distance of each fault segment based on its coordinate geometry.

Regional Visualization: Generates a comprehensive map displaying the distribution of fault lines across the country.

Top Feature Analysis: Identifies and maps the five longest individual fault segments present in the dataset.
[!IMPORTANT DISCLAIMER]
Measurement Criteria: The "Top 5 Longest Faults" identified by this code are based strictly on individual geometric segments. In geological reality, a single fault system may consist of several interconnected lines. Since this script processes individual features, it does not aggregate multiple segments into a single geological system. Therefore, the results represent the longest continuous line features in the dataset rather than the total cumulative length of a complex fault system.

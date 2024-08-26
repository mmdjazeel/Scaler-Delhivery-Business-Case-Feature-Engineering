# Scaler-Delhivery-Business-Case-Feature-Engineering

### About Delhivery

Delhivery is India's largest and fastest-growing fully integrated logistics provider, leading in revenue for Fiscal 2021. Their mission is to build the operating system for commerce through a blend of top-tier infrastructure, high-quality logistics operations, and advanced engineering and technology capabilities.

The Data team at Delhivery leverages data to enhance business quality, efficiency, and profitability, setting them apart from competitors.

### How You Can Help

Delhivery is seeking assistance in understanding and processing data generated from their data engineering pipelines. Your role will involve:

- **Data Cleaning and Manipulation:** Clean, sanitize, and transform raw data into useful features.
- **Data Interpretation:** Analyze the raw data to assist the data science team in developing forecasting models.

### Dataset

The dataset contains information pertinent to Delhivery's logistics operations. Below are the steps to download the dataset and an overview of its features.

**Steps to Download the Dataset:**

1. Open the dataset link, which will open a new browser window displaying the raw data.
2. In the new window, right-click on an empty space and select "Save As."
3. Choose your desired folder, name the dataset (with ".csv" extension), and click "Save."

**Dataset Link:** [delhivery_data.csv](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/551/original/delhivery_data.csv?1642751181)

**Column Profiling:**

- **data:** Indicates whether the data is for testing or training
- **trip_creation_time:** Timestamp of trip creation
- **route_schedule_uuid:** Unique ID for a route schedule
- **route_type:** Type of transportation (e.g., FTL, Carting)
  - **FTL:** Full Truck Load, where the shipment goes directly to the destination
  - **Carting:** Handling system using small vehicles
- **trip_uuid:** Unique ID for a trip, which may include various source and destination centers
- **source_center:** ID of the trip's origin
- **source_name:** Name of the trip's origin
- **destination_center:** Destination ID
- **destination_name:** Destination Name
- **od_start_time:** Trip start time
- **od_end_time:** Trip end time
- **start_scan_to_end_scan:** Time taken for delivery from source to destination
- **is_cutoff:** Unknown field
- **cutoff_factor:** Unknown field
- **cutoff_timestamp:** Unknown field
- **actual_distance_to_destination:** Distance in kilometers between source and destination warehouse
- **actual_time:** Total time taken for delivery (Cumulative)
- **osrm_time:** Time calculated by an open-source routing engine for the shortest path (Cumulative)
- **osrm_distance:** Distance calculated by an open-source routing engine for the shortest path (Cumulative)
- **factor:** Unknown field
- **segment_actual_time:** Time taken for a segment of the package delivery
- **segment_osrm_time:** OSRM-calculated time for a segment of the delivery
- **segment_osrm_distance:** OSRM-calculated distance for a segment of the delivery
- **segment_factor:** Unknown field

### Concepts Used:

- **Feature Creation**
- **Relationship between Features**
- **Column Normalization / Standardization**
- **Handling Categorical Values**
- **Missing Values Treatment (including outliers)**

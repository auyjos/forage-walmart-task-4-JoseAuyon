
---

# Forage Task 4 - Walmart Job Simulation

This script is part of the Forage Task 4 Walmart job simulation. It populates a SQLite database with data extracted from three CSV files related to shipment and product details. The script processes the data and inserts the relevant information into the database.

## Prerequisites

- Python 3.x
- Required Python packages: `csv`, `sqlite3` (both come pre-installed with Python)

## File Structure

```
/project-directory
    /data
        shipping_data_0.csv
        shipping_data_1.csv
        shipping_data_2.csv
    shipment_database.db  # SQLite database will be created here
    sqlCsv.py             # Python script for populating the database
    README.md             # This README file
```

## How to Run

1. Place the required CSV files (`shipping_data_0.csv`, `shipping_data_1.csv`, `shipping_data_2.csv`) in the `./data` folder.
2. Run the script:

    ```bash
    python sqlCsv.py
    ```

The script will populate the SQLite database (`shipment_database.db`) with data from the CSV files.

## License

This project is part of a job simulation and is open-source for educational purposes.

---

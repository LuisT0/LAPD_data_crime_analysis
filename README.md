# LAPD Crime Data Analysis

## Project Overview

Los Angeles, California 😎 — The City of Angels. Tinseltown. The Entertainment Capital of the World!

Known for its warm weather, palm trees, sprawling coastline, and Hollywood, along with producing some of the most iconic films and songs. However, as with any highly populated city, it isn't always glamorous and there can be a large volume of crime. That's where you can help!

You have been asked to support the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. They plan to use your insights to allocate resources effectively to tackle various crimes in different areas.

## Repository Structure

```
├── data/
│   └── crimes.csv         # Hourly crime incidents (modified LA Open Data)
├── notebooks/
│   └── project analyzing crime in Los Angeles.ipynb  # Notebook with EDA and modeling
└── README.md                  # This file
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TU_USUARIO/NOMBRE_DEL_REPO.git
   cd NOMBRE_DEL_REPO
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate    # Windows: venv\Scripts\activate
   ```

## Usage

Launch the Jupyter Notebook:

```bash
jupyter notebook notebooks/Project Analyzing Crime in Los Angeles.ipynb
```

Inside the notebook you will find:

- **EDA**: A brief exploratory data analysis and cleaning of crime records.
- **Exploratory Visualizations**: Heatmaps and time-series plots to uncover spatial and temporal trends.
- **Insights**: Key findings to guide LAPD resource allocation.

## The Data

They have provided a single dataset to use. A summary and preview are provided below.

This is a modified version of the original data, which is publicly available from Los Angeles Open Data.

| Column         | Description                                   |
| -------------- | --------------------------------------------- |
| `date_time`    | Timestamp of the reported incident            |
| `crime_type`   | Category of the crime (e.g., theft, assault)  |
| `neighborhood` | Area or district within Los Angeles           |
| `latitude`     | Geographic coordinate (latitude)              |
| `longitude`    | Geographic coordinate (longitude)             |
| `incidents`    | Number of incidents recorded in that interval |

*(Add or adjust column descriptions as needed.)*

## Contributing

Contributions are welcome! Please open an issue or submit a pull request to improve the analysis, visualizations, or modeling approaches.

## License

This project is licensed under the MIT License.


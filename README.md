# DuckDB คืออะไร มาลองใช้งานผ่าน Python กัน

### The repository was created for use in explaining on Medium: [DuckDB คืออะไร](https://medium.com/@chutdanai.tho/0732ff538b60).
![duckdb](./img/duckdb-trumnail.png?raw=true "duckdb")

Data Source: [Air Quality Monitoring in European Cities](https://www.kaggle.com/datasets/yekenot/air-quality-monitoring-in-european-cities) including 3 CSV files
- ancona_data.csv
- athens_data.csv --> Only utilize it in demo
- zaragoza_data.csv

### 🚀 Getting Started
Follow these steps to set up the project:

1. Clone the Repository
``` bash 
git clone https://github.com/Larmeal/duckdb.git
```

2. Create a Virtual Environment
``` bash
python -m venv .venv
```

3. Install Dependencies Using `uv`

    3.1 Install `uv` with `pip` (if not already installed)
    ``` bash
    pip install uv
    ```

    3.2 Sync Project Dependencies
    ``` bash
    uv sync
    ```

4. Activate the Virtual Environment

    4.1 On windows
    ``` bash
    .venv/Scripts/activate
    ```

    4.2 On macOS / Linux
    ``` bash
    source .venv/bin/activate
    ```
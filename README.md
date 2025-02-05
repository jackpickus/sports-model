# Jupyter Notebook Repository

This repository contains Jupyter notebooks for various Python-based projects, data analysis, and machine learning experiments.

## Installation

To use this repository, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/jackpickus/sports-model.git
   cd sports-model
   ```

2. **Set up a virtual environment (optional but recommended)**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```

## Repository Structure

```
├── notebooks/         # Jupyter notebooks
├── player_data/       # NBA player data, must be gathered on your own
├── team_data/         # NBA team data, must be gathered on your own too
├── requirements.txt   # List of dependencies
└── README.md          # This file
```

## Usage

- Open Jupyter Notebook in your browser and navigate to the desired notebook.
- Run the code cells sequentially to execute the analysis.
- Modify or extend the notebooks based on your needs.

## Dependencies

The required Python packages are listed in `requirements.txt`. If any additional dependencies are needed, install them using:
```sh
pip install package-name
```

## Contributing

Feel free to submit issues or pull requests for improvements. Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch.
3. Make changes and commit them.
4. Push to your fork and submit a pull request.

# Space-Weather-Modeling-with-CHAMP-and-JB2008-Data

## Overview

This Python program is designed to analyze and model space weather phenomena by leveraging data from the CHAMP satellite mission and the JB2008 density model. It focuses on understanding how Earth's upper atmosphere behaves in response to solar activity, making it a valuable tool for space weather researchers and enthusiasts.

## Features

- Data Extraction: Extracts data from the CHAMP satellite mission and the JB2008 density model, enabling in-depth analysis.

- Interpolation: Utilizes RegularGridInterpolator from SciPy to interpolate density data along the CHAMP satellite trajectory.

- Visualization: Generates visualizations to help users understand the dynamic interactions between solar radiation, geodetic parameters, and atmospheric density.

## Prerequisites

Before running the program, make sure you have the following dependencies installed:

- Python (>= 3.6)
- NumPy
- SciPy
- pandas
- Matplotlib

You can install these dependencies using pip:

```bash
pip install numpy scipy pandas matplotlib

Certainly, here's the complete README with the acknowledgment for the Space Weather Simulation Summer School 2023 at the University of Michigan included in Markdown format. You can copy and paste this directly into your README.md file:

```markdown
# Space Weather Modeling with CHAMP and JB2008 Data

## Overview

This Python program is designed to analyze and model space weather phenomena by leveraging data from the CHAMP satellite mission and the JB2008 density model. It focuses on understanding how Earth's upper atmosphere behaves in response to solar activity, making it a valuable tool for space weather researchers and enthusiasts.

## Features

- Data Extraction: Extracts data from the CHAMP satellite mission and the JB2008 density model, enabling in-depth analysis.

- Interpolation: Utilizes RegularGridInterpolator from SciPy to interpolate density data along the CHAMP satellite trajectory.

- Visualization: Generates visualizations to help users understand the dynamic interactions between solar radiation, geodetic parameters, and atmospheric density.

## Prerequisites

Before running the program, make sure you have the following dependencies installed:

- Python (>= 3.6)
- NumPy
- SciPy
- pandas
- Matplotlib

You can install these dependencies using pip:

```bash
pip install numpy scipy pandas matplotlib
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/space-weather-modeling.git
cd space-weather-modeling
```

2. Extract CHAMP data:

   - Download the CHAMP data ZIP file and place it in the appropriate directory.
   - Update the `zip_file_path` and `extract_folder` variables in the code with your file paths.

3. Load JB2008 density data:

   - Ensure the JB2008 density data file is available.
   - Update the `JB2008_dict` variable in the code with your file path.

4. Run the program:

```bash
python space_weather_model.py
```

5. Explore the generated visualizations to gain insights into space weather phenomena.

## Contributing

Contributions to this project are welcome. Feel free to open issues, submit pull requests, or provide suggestions for improvements.

## Acknowledgments

- The CHAMP satellite mission for providing valuable space weather data.
- The JB2008 density model creators for their contributions to space weather research.
- The Space Weather Simulation Summer School 2023 at the University of Michigan for inspiration and guidance.




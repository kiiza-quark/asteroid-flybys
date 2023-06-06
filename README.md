
# Asteroid Trajectory Analysis

This project provides a Jupyter Notebook (`neo_2021WP_earth_flyby.ipynb`) to analyze the trajectory of an asteroid in relation to Earth. The notebook utilizes the SPICE toolkit and performs calculations to determine the crossing of the asteroid through Earth's Sphere of Influence (SOI) and computes its orbital elements.


## How to Run

To run the project locally on all major operating systems, follow these steps:

1. Clone the repository or download the Jupyter Notebook (`neo_2021WP_earth_flyby.ipynb`) and the required SPICE kernels.
2. Install Python 3 if you don't have it already.
3. Install Jupyter Notebook by running the following command:

   ```shell
   pip install jupyter
   ```

4. Place the SPICE kernels in the project directory.
5. Open a terminal or command prompt and navigate to the project directory.
6. Launch Jupyter Notebook by running the following command:

   ```shell
   jupyter notebook
   ```

7. A web browser will open with the Jupyter Notebook interface.
8. Click on `neo_2021WP_earth_flyby.ipynb` to open the notebook.
9. Run each cell in the notebook sequentially by clicking on the "Run" button or using the appropriate keyboard shortcut (usually Shift + Enter).

   Note: Make sure you have the SPICE kernels loaded in your environment before running the notebook. If you encounter any issues with loading the kernels, refer to the SPICE documentation for guidance.

10. The notebook will execute and display the computed results, including the first crossing information, orbital elements, and the second crossing information.

## Compatibility

The project is compatible with all major operating systems, including Windows, macOS, and Linux. Ensure that you have Python 3, Jupyter Notebook, and the required SPICE kernels installed.

## Dependencies

The project relies on the following Python packages:

- `spiceypy`: Provides the interface to the SPICE toolkit for performing celestial body calculations.
- `numpy`: Used for numerical calculations and array manipulation.
- `jupyter`: Required to run the Jupyter Notebook.

Ensure that these packages are installed in your Python environment before running the notebook.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

The notebook utilizes the SPICE toolkit developed by NASA's Navigation and Ancillary Information Facility (NAIF) for performing celestial body calculations.

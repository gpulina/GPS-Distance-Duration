# GPS Distance and Trip Duration

This [guide](https://github.com/gpulina/GPS-Distance-Duration/blob/main/GPS_Distance_Duration.ipynb) provides a step-by-step walkthrough on how to calculate road distances and trip durations between pairs of GPS coordinates using the OpenStreetMap API.

## Prerequisites

Before you begin, make sure you have the following:

- Python installed (Python 3 recommended)
- The `requests` library installed (you can install it using `pip install requests`)
- Basic knowledge of Python programming

## Getting Started

1. Clone or download this repository to your local machine.

2. Open your preferred Python code editor or IDE.

3. Follow the instructions in the notebook to calculate distances and trip durations between GPS coordinates. The guide should cover all available profiles (driving, walking, biking), but results seem to default to driving scenarios.

4. Run the provided code samples to see the results and plot the data.

5. Alternatively, you can also run the code in a Google Colab environment.

## Running on Google Colab

To run the code using Google Colab:

1. Open [Google Colab](https://colab.research.google.com/).

2. Create a new Colab notebook.

3. Copy and paste the code from the guide into individual cells in the Colab notebook.

4. Run each cell by clicking the "Play" button or using the keyboard shortcut (Shift + Enter).

5. The code will execute in the Colab environment, and you can view the results directly within the notebook.

## Guide Content

The notebook includes the following sections:

1. **Installing Required Libraries:** Install the `requests` library using `pip`.

2. **Choosing GPS Coordinates:** Decide on the GPS coordinates for the origin and destination points you want to calculate distances for.

3. **Calculating Road Distances and Trip Durations:** Use the provided code samples to calculate road distances and durations between GPS coordinates.

4. **Customization:** Some remarks on modes of transportation determined statically by the Lua profile. 

5. **Review API Usage Policy**

6. **Additional Features**
  
    6.1 **Adding Plotting Capability:** Enhance the code to visualize the calculated distances and durations using scatter plots.

    6.2 **Great-Circle Haversine Distance and Comparison with OpenStreetMap API:** The code also computes the great-circle haversine distance between GPS coordinates as an additional feature. Then, it compares the calculated distances with those obtained from the OpenStreetMap API for the chosen profile (e.g., driving).

   6.3 **Calculating the Closest Destination:** Suggestions for extending the code to compute the nearest destination for each origin, potentially reducing the utilization of the OpenStreetMap API.
   
  

## Notes

- Make sure to review and comply with the OpenStreetMap API usage policy before using their API in a production environment or for heavy usage.
- Feel free to customize the code and adapt it to your specific requirements.

## License

This guide is provided under the [MIT License](LICENSE). You are free to use, modify, and distribute the code and guide as needed.

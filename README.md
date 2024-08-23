# Python-Dashboard-using-Tkinter-and-Matplotlib
This Python script creates a dashboard that visualizes sales, inventory, and product data using a combination of Matplotlib and Tkinter. The dashboard displays five different charts, each representing specific aspects of the data, within a GUI window.

# Code Explanation
1. Importing Required Libraries:

a) matplotlib.pyplot: For creating the visualizations.

b) tkinter: For creating the GUI window to display the charts.

c) FigureCanvasTkAgg: To embed Matplotlib figures into Tkinter.

d) data: Custom module that provides the datasets (sales_data, inventory_data, product_data, sales_year_data, inventory_month_data).


2. Setting Plot Colors:
Custom colors are set using plt.rcParams to maintain a consistent color scheme across all charts.


3. Creating Charts:

Chart 1: Bar Chart of Sales Data. Visualizes monthly sales data.

Chart 2: Horizontal Bar Chart of Inventory Data. Displays inventory levels for different products.

Chart 3: Pie Chart of Product Data. Shows the breakdown of products as percentages.

Chart 4: Line Chart of Sales by Year. Illustrates sales trends over multiple years.

Chart 5: Area Chart of Inventory by Month. Depicts changes in inventory levels throughout the year.

4. Building the GUI Dashboard:
a) A Tkinter window is created with a left-side frame for the title and a main area for the charts.

b) The window is maximized (root.state('zoomed')) to fully utilize the screen space.

c) Charts are embedded into the Tkinter window using FigureCanvasTkAgg, with the first three charts placed in the upper section and the last two in the lower section.


5. Running the Application:
The root.mainloop() function initiates the Tkinter event loop, displaying the dashboard and keeping the application running until the user closes it.


#How to run
1. Ensure you have the required libraries installed: Install them by the command "pip install matplotlib tkinter" typed into the terminal

2. Place the data.py file in the same directory as this script, ensuring it contains the datasets: sales_data, inventory_data, product_data, sales_year_data, inventory_month_data.

3. Run the script: python dashboard.py
   This will open a window displaying the dashboard with all five charts.


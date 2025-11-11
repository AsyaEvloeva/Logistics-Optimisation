# Logistics-Optimisation

## Project Description
The objective is to build a simplified warehouse logistics optimiser that demonstrates core logic for order picking, focusing on:

- **Warehouse Modeling:** Parsing provided warehouse layout files to create a graph-based model using NetworkX. Nodes represent SKUs and edges represent walkable aisles between them.
- **Route Optimization:** Implementing algorithm to find the shortest paths between SKUs and applying a nearest-neighbor heuristic to solve a simplified Traveling Salesman Problem (TSP) for pick sequence optimization.
- **Visualisation & KPIs:** Visualizing the warehouse layout and optimised picking path using plotly, and calculating key performance indicators (KPIs) such as naive vs optimized path distances and percentage savings.

## Deliverables
- **Shortest Path Output:** algorithm results between selected SKUs.
- **Optimized Pick Sequence:** TSP heuristic results for one sample order.
- **Visualization:** Warehouse layout graph showing the optimized route.
- **Metrics:** Distances and efficiency improvements.
- **README.md:** Instructions for running the notebook and a brief on design choices and implementation strategies.

## How to Run
1. Upload all provided files (warehouse layout `.vsdx`, profile database `.accdb`, and other initial files) to the notebook's working directory (i.e., the content directory).
2. Open the Jupyter Notebook.
3. Install required packages if they are not already installed
4. Execute the cells step-by-step, following the provided instructions.
5. The code will parse the uploaded files, create the warehouse graph, and perform route optimisation.
6. The code will visualize the warehouse layout and optimised picking paths with the output metrics to evaluate the efficiency improvements.

## Design Choices
- **Graph Representation:** Used NetworkX to model the warehouse layout as a graph.
- **Shortest Path Algorithm:** algorithm for efficient and optimal pathfinding.
- **TSP Heuristic:** Nearest-neighbor heuristic applied for simplicity and speed in pick sequence optimisation.

---



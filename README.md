# Organisational-Network-Analysis

This notebook provides a step-by-step guide to conducting Organizational Network Analysis (ONA) using Python. ONA is a valuable tool for understanding the relationships and communication patterns within an organization, allowing leaders to optimize collaboration, streamline communication, and enhance organizational effectiveness.

Contents:
Load Libraries: Import necessary Python libraries for data manipulation, network analysis, and visualization.

Create Dummy Data: Generate synthetic data representing employees and their interactions within the organization. This includes creating lists of first names, last names, and teams, randomly combining names to create pairs of interacting employees, and assigning interaction statuses.

Format Dummy Data: Filter the dummy data to include only interactions with a status of "TRUE," add random scores to represent influence, and clean the data by dropping any missing values.

Create Graph: Utilize NetworkX to create a graph representation of the organization's social network. This includes adding nodes and edges based on the formatted dummy data.

Compute Centrality: Calculate the weighted eigenvector centrality of each node in the graph to determine the influence of individual employees within the organization.

Identify Key Players: Identify the employee with the highest centrality value, representing the individual with the most influence in the organization.

Visualize Network: Visualize the network graph using Matplotlib and NetworkX, highlighting the most influential employee with a red node and adjusting the size of other nodes based on their influence. Additionally, use edge color to represent the strength of influence between employees.

By following this notebook, users can gain valuable insights into the structure of their organization's social network and identify key players who drive communication and collaboration. These insights can inform strategic decisions related to leadership development, team dynamics, and organizational communication strategies.

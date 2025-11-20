import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()import matplotlib.pyplot as plt
import networkx as nx

# Create a graph for the Use Case Diagram
G = nx.DiGraph()

# Define the actors
actors = ["دانشجو", "مدیر_سلف"]

# Define the use cases
use_cases = [
    "ورود / ثبت‌نام",
    "مشاهده منو و ظرفیت‌ها",
    "رزرو غذا",
    "لغو / تغییر رزرو",
    "پرداخت آنلاین",
    "مدیریت منو",
    "مشاهده گزارش‌ها"
]

# Define the interactions (edges between actors and use cases)
interactions = [
    ("دانشجو", "ورود / ثبت‌نام"),
    ("دانشجو", "مشاهده منو و ظرفیت‌ها"),
    ("دانشجو", "رزرو غذا"),
    ("دانشجو", "لغو / تغییر رزرو"),
    ("دانشجو", "پرداخت آنلاین"),
    ("مدیر_سلف", "ورود / ثبت‌نام"),
    ("مدیر_سلف", "مدیریت منو"),
    ("مدیر_سلف", "مشاهده گزارش‌ها")
]

# Add nodes to the graph (actors and use cases)
G.add_nodes_from(actors + use_cases)

# Add edges (interactions) to the graph
G.add_edges_from(interactions)

# Define layout for the graph
pos = {
    "دانشجو": (0, 1),
    "مدیر_سلف": (0, -1),
    "ورود / ثبت‌نام": (2, 2),
    "مشاهده منو و ظرفیت‌ها": (2, 1.5),
    "رزرو غذا": (2, 1),
    "لغو / تغییر رزرو": (2, 0.5),
    "پرداخت آنلاین": (2, 0),
    "مدیریت منو": (2, -1.5),
    "مشاهده گزارش‌ها": (2, -2)
}

# Draw the graph
plt.figure(figsize=(10, 8))
nx.draw(G, pos, with_labels=True, node_size=3000, node_color="skyblue", font_size=12, font_weight="bold", edge_color="gray", width=2)

# Save the graph as PNG
file_path = "usecase_diagram.png"
plt.savefig(file_path)

# Display the image
plt.show()


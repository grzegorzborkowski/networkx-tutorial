Źródło i charakterystyka:
https://snap.stanford.edu/data/email-Eu-core.html

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/email-Eu-core/email-Eu-core.txt')
G.add_edges_from(edges.edges())
nx.draw(G, with_labels=True)

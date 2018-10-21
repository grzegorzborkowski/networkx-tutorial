Źródło i charakterystyka:
http://networkrepository.com/socfb-Haverford76.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/socfb-Haverford76/socfb-Haverford76.mtx')
G.add_edges_from(edges.edges())
nx.draw(G)

Źródło i charakterystyka:
http://networkrepository.com/socfb-Caltech36.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/socfb-Caltech36/socfb-Caltech36.mtx')
G.add_edges_from(edges.edges())
nx.draw(G)

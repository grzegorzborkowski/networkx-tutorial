Źródło i charakterystyka:
http://networkrepository.com/ca-CSphd.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/ca-CSphd/ca-CSphd.mtx')
G.add_edges_from(edges.edges())
nx.draw(G)

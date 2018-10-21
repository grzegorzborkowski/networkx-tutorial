Źródło i charakterystyka:
http://networkrepository.com/socfb-Reed98.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/socfb-Reed98/socfb-Reed98.mtx')
G.add_edges_from(edges.edges())
nx.draw(G)

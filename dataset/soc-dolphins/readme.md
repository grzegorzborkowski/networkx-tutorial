Źródło i charakterystyka:
http://networkrepository.com/soc-dolphins.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/soc-dolphins/soc-dolphins.mtx')
G.add_edges_from(edges.edges())
nx.draw(G)

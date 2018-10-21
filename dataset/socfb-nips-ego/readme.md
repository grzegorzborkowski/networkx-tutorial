Źródło i charakterystyka:
http://networkrepository.com/socfb-nips-ego.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/socfb-nips-ego/socfb-nips-ego.edges')
G.add_edges_from(edges.edges())
nx.draw(G)

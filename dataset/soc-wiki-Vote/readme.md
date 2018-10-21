Źródło i charakterystyka:
http://networkrepository.com/soc-wiki-Vote.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/soc-wiki-Vote/soc-wiki-Vote.mtx')
G.add_edges_from(edges.edges())
nx.draw(G)

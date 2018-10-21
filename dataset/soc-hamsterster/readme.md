Źródło i charakterystyka:
http://networkrepository.com/soc-hamsterster.php

Sposób wczytania do jupyter notbook:

import networkx as nx
G = nx.Graph()
edges = nx.read_edgelist('dataset/soc-hamsterster/soc-hamsterster.edges')
G.add_edges_from(edges.edges())
nx.draw(G)

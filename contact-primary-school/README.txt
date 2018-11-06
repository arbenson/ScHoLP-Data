This dataset is constructed from a contact network amongst children and teachers
at a primary school. The contact network was downloaded from
http://www.sociopatterns.org/datasets/primary-school-temporal-network-data/

We form simplices through cliques of simultaneous contacts. Specifically, for
every unique timestamp in the dataset, we construct a simplex for every maximal
clique amongst the contact edges that exist for that timestamp. Timestamps were
recorded in 20 second intervals.

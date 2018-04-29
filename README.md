# How to use these notebooks
These notebooks are anticipated to be run in a specific order to rebuild the Global Witness UK benefical ownership graph database. **NOTE** If you do not want to risk overwriting or damaging the database make sure that it is offline when rerunning all cells of any notebook, otherwise beware what is and isn't run. 

They should be read (and run) in the following order:

- 00.Demo connection to Neo4j
- 01.Setting-up-fresh-neo4j-database
- 02.Country-Node-creation
- 03.Inserting-active-companies-into-neo4j
- 04.Inserting-human-PSCs
- 05.Inserting-Corporate-PSCs
- 06.Inserting-Legal-Entity-PSCs
- 07.Inserting-PSC-Super-Secure-Persons
- 08.Inserting-missing-PSC-statements
- 09.Inserting-Officers-People
- 10.Inserting-Officers-Companies - **NOTE** it was discovered that both company ids are not available in the working dataset and hence this notebook is actually incomplete and needs additional data to build the connections between companies that are officers
- 11.Tidying-up-the-database
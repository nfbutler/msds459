# Part 2 - EdgeDB/Gel

EdgeDB/Gel integrates the strengths of both graph databases and relational databases to enhance data management and querying capabilities. It combines the characteristics of graph relational databases, such as the ability to represent complex relationships between data entities and support intricate queries involving those relationships. These databases leverage graph structures while maintaining relational concepts, thus enabling developers to utilize familiar SQL-like syntax for querying.

## Key Features of EdgeDB/Gel Database System

**Graph-Relational Model**: EdgeDB combines the principles of relational databases with the flexibility of graph databases. The advantages of graph relational databases include improved performance for relationship-centric queries, flexibility in modeling data, and the capacity to handle large volumes of interconnected data effectively. This positions graph relational databases as a solution for modern applications that require both the relational integrity of traditional databases and the dynamic relationship capabilities of graph databases.

**Rich Query Language**: EdgeDB uses a powerful query language that extends SQL capabilities, allowing for complex data manipulations and querying in a more expressive and concise manner. This language supports nested queries and offers built-in functions for common tasks, which can enhance productivity for developers.

**Schema Flexibility and Evolution**: EdgeDB provides a robust schema definition system that allows for easy evolution over time. This flexibility enables developers to modify the schema without significant overhead or restructuring, which is beneficial for projects that anticipate changes in requirements or data structures.

## Advantages of Using EdgeDB for a Knowledge Base

**Enhanced Data Relationships**: The graph-relational nature of EdgeDB allows for rich representation of complex relationships. This is important for knowledge bases like our term project that often require a complex understanding of how entities are interconnected.

**Flexible Querying**: The powerful querying capabilities enable developers to express complex relationships and queries succinctly, facilitating easier data retrieval and manipulation. This can lead to faster development cycles and more efficient data handling.

**Ease of Schema Management**: The ability to evolve the schema as project requirements change is a significant advantage over traditional relation databases reducing the fragile nature that often accompanies updates in knowledge base designs and allowing for ongoing adaptability.

### Disadvantages of Using EdgeDB for a Knowledge Base

**Learning Curve**: While EdgeDB offers advanced features, it may come with a steeper learning curve for developers accustomed to traditional relational databases or simpler NoSQL databases. The transition to a graph-relational model and its unique query language may require additional training and time.

**Performance Considerations**: For very large datasets or highly complex queries, the performance may vary compared to highly optimized traditional relational databases or specialized graph databases. Depending on the specific use case, developers may need to carefully consider indexing and optimization strategies.

**Community and Ecosystem**: As a newer database system, EdgeDB may have a smaller community and ecosystem compared to more established databases, which could mean fewer resources, libraries, or third-party tools available for support and integration.

## Conclusion

EdgeDB presents a potentially improved option for a knowledge base due to its graph-relational model and rich querying capabilities, making it well-suited for handling complex data relationships. However, developers should weigh the advantages against potential disadvantages, particularly in terms of the learning curve and community support, to determine if it aligns with the specific needs and resources of their project.
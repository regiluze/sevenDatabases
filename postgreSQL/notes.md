## Postgres notes

- Indexes

    - Hash
    - B-tree: Better for less-than/greater-than/equals-to

- Window functions

    Similar to GROUP BY queries in that they allow you tu run aggregate functions across multiple rows.

- Transactions

- Stored procedures

- Rules

    How to alter the parded query tree.

# Fulltext search

- Fuzzy searching

    Like and regex

- Bride of Levenshtein

- Trigram

- Fulltext fun
    
    TSVector vs TSQuery
    Other languages
    
- Metaphones

- Genres and Multidimensional Hypercube

# Postgres's Strengths

    - Flexible queryability and very consistent and durable data
    - Powerful schema constraint mechanisms
    - Open source

# Postgres/s Weaknesses

    - Partitioning
    - If you require very high-volume reads and writes
    - Store large blobs of data


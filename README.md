# PostreSQL-Vaccum

VACUUM reclaims storage occupied by dead tuples. In normal PostgreSQL operation, tuples that are deleted or obsoleted by an update are not physically removed from their table; they remain present until a VACUUM is done.

This SQL script can be used to check PostreSQL space in percentage that can be reclaimed before running full vacuum.

Note:This SQL query will give you the tables output which is has more than 50% of reclaimable space. 


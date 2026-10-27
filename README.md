# Marines Registry, stage 1

The first stage of [marines-registry](https://github.com/foliageh/marines-registry): a multi-user
Jakarta EE application on WildFly for managing Space Marines and their Chapters.

- CRUD in a PrimeFaces UI with filtering, sorting and tables that refresh every few seconds
- Registration with administrator approval, `USER` and `ADMIN` roles, edit rights by owner
- PL/pgSQL functions for aggregates and special queries

**Stack:** Jakarta EE 10 (JSF, CDI, EJB, JPA, Jakarta Security) · WildFly · Hibernate 6 · PrimeFaces · PostgreSQL

The full system, with transactional import, MinIO and load tests, is in [marines-registry](https://github.com/foliageh/marines-registry).

---
Built as coursework for the Information Systems course at ITMO University, 2024.

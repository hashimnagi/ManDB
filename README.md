# ManDB

ManDB is a mini database engine built from scratch in C++, developed over the course of a year as a deep-dive into data structures, algorithms, and systems programming.

## Goal
To implement, from first principles, the core components of a real database engine:
- Custom hash tables (chaining & open addressing)
- B-Trees for indexing
- Persistence layer (disk storage, write-ahead logging)
- A simple query parser and planner
- Graph algorithms for dependency/join resolution
- Basic concurrency support

## Why
Built as a semester-long learning project alongside coursework in Data Structures, Algorithms, Computer Organization & Assembly Language, Operating Systems, and Databases — with the goal of deeply understanding how real-world database systems work internally, rather than just using them.

## Status
🚧 Just getting started — project skeleton in place, hash table module coming next.

## Roadmap
- [ ] Month 1-2: Hash Table (chaining, open addressing, resizing)
- [ ] Month 3-4: BST → AVL → B-Tree
- [ ] Month 5: Sorting algorithms + external merge sort
- [ ] Month 6: Persistence (serialization, WAL, skip list)
- [ ] Month 7-8: Query parser + planner
- [ ] Month 9: Graph algorithms (topological sort for dependencies)
- [ ] Month 10-11: Concurrency + benchmarking
- [ ] Month 12: Final polish, benchmarks, documentation
# RubiksCubeSolver

A C++ implementation of a Rubik's Cube model with extensible architecture for solving algorithms.

---

## Project Development Stages

### Initial Commit
- Created base `RubiksCube` abstraction.
- Defined core interface methods for cube operations.
- Implemented foundational structure in `RubiksCube.h` and `RubiksCube.cpp`.

### Second Stage
- Designed cube color system and face representation.
- Structured internal cube state handling.

### Third Stage
- Implemented `RubiksCube1dArray` model.
- Represented cube using a 1D array of 54 elements.
- Added complete face rotation logic (U, L, F, R, B, D moves).
- Implemented prime and double moves.
- Added solved-state verification.
- Added hashing support for future solver integration.

---

## Technical Highlights

- Object-Oriented Design
- Abstract base class for extensibility
- Efficient 1D state representation
- Move-based state transformation logic
- Ready for BFS/DFS/IDA* solver expansion

---

## Future Improvements

- Implement 3D cube representation
- Add BFS-based solver
- Optimize with bitboard representation
- Add performance benchmarking

---

## Creater

Prashant Singh
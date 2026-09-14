# Radioactive Decay Simulation

This project simulates radioactive decay using Python.

## Methods

Two simulation methods are implemented:

- Pure Python loop
- NumPy vectorised version

## Testing

The project uses pytest to test:

- The simulation starts with N0 atoms.
- Negative decay rates are rejected.
- The simulation agrees with the analytical decay law.

## Performance

For N0 = 200000 atoms:

- Pure Python loop: 2.6096 s
- NumPy: 0.0003 s
- NumPy speedup: 8799.24x

## Conclusion

The NumPy implementation is much faster than the pure Python loop.
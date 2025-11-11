# Scintillation-Geant4_try-1

This repository contains a Geant4-based simulation for scintillation processes. It's a basic attempt (try-1) to model scintillation in particle detectors.

## Project Structure

- `sim.cc`: Main simulation executable.
- `include/`: Header files.
- `src/`: Source files.
- `CMakeLists.txt`: Build configuration.

## Prerequisites

- Geant4 (with visualization and UI drivers if needed)
- Geant4(Prerequisites)
- CMake
- A C++ compiler

## Building the Project

1. Clone the repository:
   ```
   git clone https://github.com/Uday-Bais/Scintillation-Geant4_try-1.git
   cd Scintillation-Geant4_try-1
   ```

2. Create a build directory:
   ```
   mkdir build
   cd build
   ```

3. Configure with CMake:
   ```
   cmake ..
   ```

4. Build:
   ```
   make
   ```

## Running the Simulation

After building, run the simulation:
```
./sim
```

## Usage
To study number of optical photons produced in a run(single event or batch).



## Contributing

Feel free to open issues or pull requests for improvements.


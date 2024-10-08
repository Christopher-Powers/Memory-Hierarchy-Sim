# Memory Hierarchy Simulation Project

## Overview

The Memory Hierarchy Simulation Project is a comprehensive simulation tool designed to model and analyze different memory management policies in a computer system. It allows users to simulate the behavior of various memory management algorithms, including FIFO (First-In, First-Out), NRU (Not Recently Used), LRU (Least Recently Used), and a Greedy algorithm. This simulation aims to help understand how different policies affect memory access patterns, hit ratios, and the efficiency of memory utilization.

## Features

- Simulate multiple memory management policies: FIFO, NRU, LRU, and Greedy.
- Calculate and display hit ratios, miss ratios, read ratios, and write ratios.
- Customizable memory configurations and simulation settings.
- Input memory references from a user-defined file.

## Getting Started

### Prerequisites

- .NET Core SDK (version 3.1 or later)
- Any compatible IDE (Visual Studio, Visual Studio Code, JetBrains Rider, etc.)

### Installation

1. Clone the repository to your local machine:

    ```sh
    git clone https://github.com/yourusername/memory-hierarchy-simulation.git
    ```

2. Navigate to the project directory:

    ```sh
    cd memory-hierarchy-simulation
    ```

3. Build the project:

    ```sh
    dotnet build
    ```

4. Run the simulation:

    ```sh
    dotnet run
    ```

## Usage

1. Start the simulation by running the project. You will be prompted to choose a memory management policy.
2. Enter the number corresponding to your chosen policy and press *enter*.
3. Provide the path to the file containing memory references when prompted. The file format should consist of lines with the format `[AccessType]:[Address]`, where `AccessType` is either `R` for read or `W` for write, and `Address` is the hexadecimal memory address. There are stock files to use in the '12-Bit Truncated' folder' being either *'trunc_12.dat'* or *'real_tr.dat'*. Once you have entered the file path, press *enter*, type `end` and press enter again.
4. The simulation will run and display the memory access pattern, including hits, misses, and the physical page number for each reference.
5. After the simulation completes, summary statistics including the total number of references, hits, misses, read ratio, write ratio, hit ratio, and miss ratio will be displayed.
6. To exit, enter `quit` when prompted to choose a memory management policy.

## Sample Output
**FIFO Summary Stats** <br>
![FIFOsummary](https://github.com/user-attachments/assets/f0f2ccfa-05d1-4b58-a2af-ce1eb7c58fd4)

**Generalized Summary Stats** <br>
![stats](https://github.com/user-attachments/assets/c0723ffd-cc83-4a9a-a0fb-ba963b0bb923)



## Contributing

Contributions to the Memory Hierarchy Simulation Project are welcome. Please feel free to fork the repository, make changes, and submit pull requests. For major changes or new feature requests, please open an issue first to discuss what you would like to change.

## License

[MIT License](LICENSE.txt) - see the LICENSE file for details.

## Acknowledgments

- Thank you to Dustin Swayze who contributed to and helped improve this project.
- Thank you to Professor Matthew Harrison for the project guidance. 

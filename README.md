# SuperGCD - Fastest GCD Core in the world!

## Design Organization

    - src / 
      - main / scala / gcd /
         - Tile.scala - Top level 'Tile' containing multiple GCD modules, FIFOs etc connected together to create the main GCD Tile
         - GCDCore.scala - The main GCD computation core
      - common /
         - FIFO.scala - FIFO to feed the GCD core with input data, and send out computed GCDs

    - test /
      - scala / gcd / 
        - GCDTester.scala - Unit level GCD test, only checks functional correctness of the GCDCore
        - FIFOTester.scala - Unit level FIFO test, checks functional correctness
        - TileTester.scala - Simulation level tester, creates waveforms etc



### Using Chisel Project Template
=======================

This project has been created using the chisel template project.  

Testing git.

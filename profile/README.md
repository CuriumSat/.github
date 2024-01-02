## Hi there 👋

<!--
🙋‍♀️ A short introduction - Building a 6U cubesat
🌈 Contribution guidelines - Contributers must be invited to the Organisation
👩‍💻 Useful resources - Docs are in the docs repository of the organisation - We use Obsidian for rendering
-->

# Project Overview: PTS Curium 5

Planetary Transportation Systems Curium 5 project is designed around the development of 6U CubeSats, using components primarily sourced from commercial manufacturers. We utilize a launch opportunity from the [DLR microlauncher competition 2022](https://www.dlr.de/en/latest/news/2022/02/20220620_go-ahead-for-second-round-of-microlauncher-payload-competition) to validate the design.


<div style="display: flex; justify-content: space-evenly;">
   <figure>
  <figure>
    <img src="https://github.com/Curium-Five/.github/assets/4999364/a55bb013-2740-49e6-a685-60fcc72acb61" alt="Dispenser Image" width="400">
  </figure>
     <figcaption>First integrated prototype</figcaption>
  </figure>
</div>


# Research

In cooperation with HPI [operating system and middleware chair](https://osm.hpi.de) the project will include research for a master thesis.
In cooperation with University of Vienna [Walther group](https://walther.quantum.at) and [DLR remote sensing institute](https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-5279/8913_read-16239/) an experiment will be developed as satellite payload and is part of a PHD. 

## Technical Specifications


### Structure:
- Size: 6U CubeSat
- Weight: <8 Kg

### Electrical Power System (EPS)
- Solar cells: Monocrystalline Si cells
- Power: minimum 2-5 W average for payload, higher burst loads >50W possible
- Energy storage: Lithium Ion MJ1 cells

### Attitude Determination & Control (ADCS)
- Magnetorquer
- possibly reaction wheels

### Communication (Comm)
- Utilization of Satnogs-Comms Board
- Amateur & commercial radio bands for uplink and downlink, with a data transfer rate of up to 50 kbps (UHF) and possible use of S-Band
- Antenna: simple monopole antennas with orthogonal radiation patterns to achieve quasi-isotropic radiation properties.

### Data Handling (OBC)
- Computer: STM32H7 based as rad testing indicates good long-term performance

### Launch & Lifetime
- Launch vehicle: Designed along Vega C guidelines
- First In Orbit Verification: June 2024 - A6 maiden flight
- Estimated lifespan: >3 months


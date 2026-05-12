# Project Humanoid Robotic Head

Welcome to the Project Humanoid Robotic Head (for **NICO**). This project is being developed as part of a Master's Thesis at the [Faculty of Mathematics, Physics and Informatics, Comenius University in Bratislava (FMFI UK)](https://fmph.uniba.sk/en/).

**Author:** Bc. Lukáš Mihál
**Supervisor:** prof. Ing. Igor Farkaš, Dr.

---

## Project Overview and Goals
The main goal of this project is the design, construction, and software implementation of a fully functional humanoid robotic head. The work focuses on creating an affordable yet advanced robotic head system with realistic face movement.

---

## Project Structure

The project is divided into the following repositories to ensure modularity and logic separation:

* [**master-thesis-latex**](./master-thesis-latex) — Source files for the Master's thesis in LaTeX.
* [**rpi5-backend**](./rpi5-vision-backend) — The backend running on the Raspberry Pi 5, which is inside of the head.
* [**pico-controllers**](./pico-servo-controllers) — Code for the Raspberry Pi Pico 2, which receives commands from the RPi 5 and directly controls the servomotors for eye and facial movements.
* [**3d-models**](./3d-hardware-models) — exported `.stl` models ready for 3D printing.

---

You can find more information on the thesis website:
[Thesis web](https://www.st.fmph.uniba.sk/~mihal33/)

\# VGA Controller (640x480 @ 60Hz)



This project implements a VGA controller in Verilog compatible with standard 640x480 VGA timing. The controller generates HSYNC and VSYNC signals and tracks pixel coordinates.



\## 📐 VGA Timing



\- Resolution: 640x480  

\- Refresh Rate: 60Hz  

\- Pixel Clock: 25MHz



\## 📁 Files



\- `vga\_controller.v`: Main VGA controller logic.  

\- `vga\_tb.v`: Testbench for simulation.  

\- `README.md`: Project documentation.  



\## 🧪 Simulation



Simulate using \[EDA Playground](https://www.edaplayground.com/):



1\. Paste `vga\_controller.v` and `vga\_tb.v` into separate tabs.  

2\. Select:  

&nbsp;  - Simulator: \*\*Icarus Verilog\*\*  

&nbsp;  - Tools: \*\*GTKWave\*\* for waveform viewing  

3\. Run simulation and inspect `hsync`, `vsync`, and `video\_on`.



\## 📸 Waveform Images



Here are some captured waveforms from the simulation:



\### Waveform 1

!\[Waveform 1](images/waveform1.jpeg)



\### Waveform 2

!\[Waveform 2](images/waveform2.jpeg)



\### Waveform 3

!\[Waveform 3](images/waveform3.jpeg)



\### Waveform 4

!\[Waveform 4](images/waveform4.jpeg)



\### Waveform 5

!\[Waveform 5](images/waveform5.jpeg)



\*(Add more if needed)\*



\## 📦 GitHub Setup



```bash

\# Clone the repo

git clone https://github.com/sushmitha0531/VGA-controller-for-display.git

cd vga-controller



\# Add files and commit

git add .

git commit -m "Initial VGA controller implementation"

git push origin main




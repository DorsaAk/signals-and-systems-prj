![Python](https://img.shields.io/badge/Python-34908B?style=for-the-badge&logo=python&color=FFBF00&logo-size=7)
![Signal Processing](https://img.shields.io/badge/Signal%20Processing-618764?style=for-the-badge)
![Image Processing](https://img.shields.io/badge/Image%20Processing-white?style=for-the-badge&color=F5788B)
![Filters](https://img.shields.io/badge/Filters-white?style=for-the-badge&color=FF6A1C)
![S&S](https://img.shields.io/badge/Signals&Systems-792CA2?style=for-the-badge&logo=xilinx&logoColor=white)

# Signal & Systems: Audio and Image Processing

A two-phase project completed in collaboration with a teammate, covering practical applications of signal processing theory in both the audio and image domains. All tasks include theoretical discussion alongside Python implementations.

## Phase I — Audio Processing

This phase consists of two major tasks.

**Task 1 — Power Line Noise Filtering**  
A power line noise was modeled and superimposed onto a WAV audio file. FIR, IIR, and adaptive filtering algorithms (using an LMS loss function) were then applied to remove the noise. The performance of each filtering approach was compared.

**Task 2 — LSB Steganography**  
An LSB steganography algorithm was used to retrieve a hidden message embedded within a noisy WAV audio file.
<p align="center">
  <img src="https://github.com/user-attachments/assets/7fe08543-cd31-4298-afb7-a6d201b402ee"
       alt="instr list"
       width="650"/>
   <br>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4fa8fe4d-439d-47dd-a258-8686eb22fd8e"
       alt="instr list"
       width="650"/>
   <br>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/2f561915-cd79-4c9f-8a17-49d0e6628661"
       alt="instr list"
       width="650"/>
   <br>
</p>


## Phase II — Image Processing

This phase models a License Plate Recognition (LPR) system under two different conditions.

**Case 1: Ideal Images**  
Clean sample images of license plates — free of blur or noise — were processed through the recognition algorithm. The effect of downsampling on recognition performance was investigated.

**Case 2: Blurred and Noisy Images**  
Blurred and noisy sample images were used as a simplified simulation of real-world conditions (e.g., a car in motion). The pipeline involved deblurring the images first, then applying the same recognition and downsampling procedures to the restored results.

<p align="center">
  <img src="https://github.com/user-attachments/assets/fca659f7-38c5-402b-92ea-8a28d563db6a"
       alt="instr list"
       width="650"/>
   <br>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/c4f8185e-2a10-4e00-a0fa-bbe24c326578"
       alt="instr list"
       width="650"/>
   <br>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/150b2ee3-75e0-41e2-bea8-46a4350a1ea6"
       alt="instr list"
       width="650"/>
   <br>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/6a970663-b6ed-4c4c-9234-e051f6e6d6ed"
       alt="instr list"
       width="650"/>
   <br>
</p>


## Tech Stack

| Layer        | Tool / Language   |
|--------------|-------------------|
| Main Code    | Python            |
| General Libraries| `NumPy`, `Matplotlib`, `scipy.signal` |
| Signal Processing Libraries | `scipy.fft`, `PyDub AudioSegment` |
| Image Processing Libraries | `PIL Image`, `PIL ImageOps` |

<div align="center">

# Hi there, I'm Jingkun Li (Jarred) 

 **Engineering & Robotics Researcher | Embedded Systems & Computer Vision**  
 Exploring the intersection of **Mechatronics**, **Assistive Robotics**, and **Edge-AI Visual Recognition**.  
 **Contact:** [jingklapp6688@163.com](mailto:jingklapp6688@163.com) | [jarredli008@gmail.com](mailto:jarredli008@gmail.com) | [ Live Demo (YouTube)](https://youtube.com/shorts/EYo3PqKyFFs?feature=share)

</div>

---

###  About Me

I am passionate about building **human-centered engineering systems** that bridge physical hardware with intelligent algorithms. My work focuses on **assistive technologies for the visually impaired**, spanning from **low-level microcontroller firmware and multi-sensor fusion** to **embedded computer vision and OCR error-correction pipelines**.

*  **Assistive Robotics Research:** Developed **CaneVision**, an ultra-low-cost ($41.94) attachable smart navigation module for white canes under the mentorship of **Prof. Carlotta Berry, Ph.D.** (*Pioneer Academics, Summer 2026*).
*  **Edge-AI & Computer Vision:** Built a real-time **Assistive Medicine Recognition System** on MaixPy Edge-AI hardware using PaddleOCR (`PP-OCR`), hierarchical phonetic/glyph error correction, and temporal consensus voting.
*  **Embedded Systems & Control:** Experienced in non-blocking real-time polling architectures (`millis()`), digital signal filtering (Moving Average & Leaky Integrator adaptive baselines), and PWM electromechanical actuation.

---

###  Technical Toolbox

* **Embedded & Hardware:** Arduino (ATmega328P / ESP32), MaixPy Edge AI, Embedded C/C++, Multi-Sensor Fusion (Ultrasonic, IR, LDR), PWM Motor & Servo Control, UART / Two-Wire Serial (`TM1637`), Tinkercad
* **Signal Processing & Algorithms:** Non-Blocking Concurrency, Moving Average Filtering, Leaky Integrator Dynamic Calibration, Multi-Frame Temporal Voting, Switch Debouncing
* **AI, Vision & Computing:** Python, PaddleOCR (`PP-OCR`), Regex & Phonetic Fuzzy Matching (`difflib`), Image Recognition, Diffusion Models, Git & GitHub

---

###  Featured Engineering & Research Projects

*  **[CaneVision: Attachable Smart Navigation Module for White Cane](https://github.com/Jarredli/CaneVision_Smart_White_Cane_for_the_Visually_Impaired)**  
  *Arduino Uno R3 | Embedded C++ | Multi-Sensor Fusion*  
  Designed and prototyped a lightweight (<150 g) assistive navigation module featuring forward ultrasonic ranging ($N=5$ moving average filter), downward IR drop-off detection ($\alpha=0.99$ leaky integrator adaptive baseline), and dual progressive haptic/acoustic feedback with $<100\text{ ms}$ system latency.  
   **[ Read Full Research Paper (PDF)](https://github.com/Jarredli/CaneVision_Smart_White_Cane_for_the_Visually_Impaired/raw/main/Jingkun_Li_Jarred_CaneVision_Research_Final_Paper.pdf)** | **[🎥 Watch Live Demo](https://youtube.com/shorts/EYo3PqKyFFs?feature=share)**

*  **[Edge-AI Assistive Medicine Recognition System](https://github.com/Jarredli/EdgeAI-Assistive-Medicine-Detector)**  
  *Python | MaixPy Edge AI | PaddleOCR (PP-OCR) | UART Hardware Interfacing*  
  Developed an embedded computer vision system for visually impaired medication safety. Engineered a 4-stage post-OCR glyph/phonetic error-correction pipeline (`difflib` sequence matching), a 3-frame temporal consensus voting filter, and real-time `UART2` serial telemetry (`9600 baud`).

*  **[Embedded Systems & Mechatronics Mini-Projects](https://github.com/Jarredli/Mini-Projects)**  
  *Arduino Uno | GPIO Multiplexing | Asynchronous Debouncing | PWM Servo Actuation*  
  A progressive series of embedded control labs covering 8-channel active-low LED sequencing, non-blocking $50\text{ ms}$ switch debouncing, `TM1637` 4-digit response interval timing, and bistable robotic hand-raising servo control.

---

###  Publications & Research Reports

* **Jingkun Li (Jarred)**. *"CaneVision: Attachable Navigation Module for White Cane."* Pioneer Academics Research Paper (Advisor: Prof. Carlotta Berry, Ph.D.), Summer 2026. [[PDF](https://github.com/Jarredli/CaneVision_Smart_White_Cane_for_the_Visually_Impaired/raw/main/Jingkun_Li_Jarred_CaneVision_Research_Final_Paper.pdf)] [[Code](https://github.com/Jarredli/CaneVision_Smart_White_Cane_for_the_Visually_Impaired)]

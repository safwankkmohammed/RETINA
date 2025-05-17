# RETINA: Real-Time Environmental Transcription and Interpretation for Navigation and Assistance

##  Vision Aid for the Blind Using Raspberry Pi

RETINA is a real-time assistive system designed to empower visually impaired individuals by providing environmental awareness and navigation support. The project leverages computer vision, deep learning, and speech synthesis on edge devices like the Raspberry Pi.

---

##  Objectives

- Develop a portable, real-time object recognition and narration system.
- Improve navigation and reduce dependency on external assistance.
- Enhance environmental awareness using affordable hardware.

---

##  Core Technologies

- TensorFlow Lite and MobileNetV2 for lightweight inference on edge devices.
- Google Coral TPU for accelerated model performance.
- Text-to-Speech (TTS) for voice output.
- Multithreading for improved performance and reduced latency.

---

##  Hardware Used

- Raspberry Pi 4 (Quad Core)
- USB Webcam / Pi Camera
- Google Coral USB Accelerator
- Power Bank
- Earphone with mic
- Head-mounted camera setup

---

## Methodology

1. Object Detection using MobileNet models.
2. Voice Output for object narration using TTS.
3. Multithreading used to parallelize detection and speech.
4. Transitioned from Raspberry Pi Camera to USB Webcam for better accuracy.
5. Converted models to TensorFlow Lite for compatibility with Coral TPU.

---

##  Results

- YOLOv8 + Pi Camera: 1–2 FPS
- MobileNet + Pi Camera: ~4–5 FPS
- MobileNet + USB Webcam + Coral TPU: Up to 20 FPS

---

##  Future Work

- Add scene description using LLMs (e.g., Gemini API).
- Integrate support for multiple languages.
- Use GPU-powered edge devices like NVIDIA Jetson Nano.
- Collaborate with NGOs to improve accessibility and affordability.

---

##  Achievements

- Best Paper Award – ICET 2025 Conference (RCET)
- Published in IJMRSET
- Funded by APJ KTU CERD Scheme

---

##  Authors

- Adarsh Narayanan  
- Brillons  
- Fiza Rahmathullah  
- Mohammed Safwan K K  
- Under the guidance of: Ms. Najiya Abdulrahiman (Assistant Professor)

---

## License

This project is for academic and research purposes. Contact the authors for reuse or collaboration.


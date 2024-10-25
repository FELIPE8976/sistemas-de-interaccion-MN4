# **Pure Data Project: Simple Synthesizer and Drum Machine**

This project is a basic audio synthesizer and drum machine built using **Pure Data (Pd)**. The patch includes an oscillator for generating basic waveforms and a drum machine with real-time control using sliders and toggle buttons. The project is designed for real-time sound manipulation, providing users with control over volume, frequency, and playback.

## **Project Overview**
This patch consists of:
1. **Oscillator**: Generates a simple sine wave using `osc~`.
2. **Drum Machine**: Allows the user to trigger predefined drum beats using toggle buttons and sliders.
3. **Sliders**: Control various parameters such as the frequency of the oscillator and the playback volume.
4. **Real-time MIDI Control**: The patch includes MIDI outputs for controlling external MIDI devices using `pgmout` and `noteout`.

### **Objective**
The goal of this project is to create a simple yet flexible setup for generating and manipulating audio in real time, with user-friendly controls for both synthesizer sounds and drum patterns.

## **Controls**
- **Slider X**: Controls the volume of the oscillator or the drum machine.
- **Slider Y**: Adjusts the frequency of the oscillator for pitch manipulation.
- **Toggle Buttons**: Used to start/stop the playback of different elements, such as the drum machine or oscillator.
- **MIDI Control**: The patch includes MIDI outputs to control external hardware via `pgmout` and `noteout`.

## **Usage**
1. **Oscillator**:
   - Use **Slider Y** to control the pitch (frequency) of the sine wave.
   - Adjust the volume with **Slider X**.
   
2. **Drum Machine**:
   - Toggle the buttons to start or stop the playback of predefined drum loops.
   - Control the playback volume using **Slider X**.
   
3. **MIDI Control**:
   - The patch outputs MIDI data for program changes and note triggering, allowing integration with external MIDI gear.

## **Project Members**
- **Luis Martinez**
- **Carlos Camacho Peña**

## **Installation**
1. Install **Pure Data** from [here](https://puredata.info/downloads).
2. Download and open the `.pd` file in Pure Data.
3. Ensure your audio settings are configured in Pure Data to hear the output.

## **Future Improvements**
- Add more complex effects such as delay or reverb to enhance the sound.
- Implement randomization for the drum machine to create dynamic rhythms.
- Expand the MIDI capabilities to allow for real-time control of external synthesizers.

---

This README provides a basic overview of how the patch works, its members, and instructions on how to use it. Let me know if you need any further adjustments!

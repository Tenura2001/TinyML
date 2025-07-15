# TinyML
This is the learning journey of TinyML  

## What is TFLite Micro - Interpreter?

**TFLite Micro** is a tool that helps us run machine learning models on very small devices like **Arduino**, **ESP32**, or other **microcontrollers**.

A **machine learning model** is a file that can make decisions — like detecting sounds, predicting numbers, or recognizing gestures.

But normal models are too big for small devices. So we convert them into a smaller file called a `.tflite` file.  
**TFLite Micro Interpreter** reads this file and runs the model on the microcontroller.

---

## ⚙️ What does the Interpreter do?

The **TFLite Micro Interpreter** does three main things:

1. **Loads the model** (the `.tflite` file).
2. **Takes input** (like a sensor value or audio).
3. **Gives output** (like turning on an LED or controlling a motor).

---

##  Example

If you train a model to detect a **clap sound**, and upload it to an **ESP32**,  
the **TFLite Micro Interpreter** will:

- Listen to sound input  
- Detect the clap  
- Turn on an LED if it hears the clap

---

## ✅ Summary

| Term                  | Meaning                                                                 |
|-----------------------|-------------------------------------------------------------------------|
| TFLite Micro          | A small version of TensorFlow for microcontrollers                     |
| Interpreter           | The part that runs the model on your device                            |
| `.tflite` Model File  | A tiny model file that can run on Arduino, ESP32, etc.                 |
| Why it is useful      | Lets you use AI in tiny hardware projects (TinyML)                     |

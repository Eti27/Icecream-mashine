# Ice Cream Maschine

This project is a motorized ice cream churner designed to work inside a standard household **freezar**. It automates the process of stirring the mixture as it freezes, ensuring the ice cream stays smooth and creamy by folding in air and preventing large ice crystals from forming.

I desinged this project because I wanted a more affordable alternative to expensive compressor machines. I was also curious about how to make 3D printed parts safe for food contact and wanted to practice my **electronicks** skills.


## Full 3D Model

The entire assembly includes a custom-designed mixing paddle (spinner), a housing for the high-torque motor, and a secure lid for the behälter.

<img width="908" height="693" alt="Screenshot 2026-04-07 190641" src="https://github.com/user-attachments/assets/3dcd2115-d771-4942-a05c-82ed2d4f07d4" />


## Component Breakdwon

### Spinner

The spinner goes in the **container** and will move the icecream around and fold in air for creamy icecream. It was a real challenge to get the constraints right in the CAD software, but the final version is very sturdy.

<img width="723" height="748" alt="Screenshot 2026-04-07 190828" src="https://github.com/user-attachments/assets/e5f02a34-17c8-4248-84a4-7d1fe5ce9cde" />
<img width="691" height="632" alt="Screenshot 2026-04-07 190814" src="https://github.com/user-attachments/assets/6adecc89-f740-4bac-ac50-b60249db90a1" />


### container

The container holds the ice cream mixture. The lid is designed so the motor can screw **direcly** into it, providing enough torque to churn the mix even as it gets thick.

<img width="802" height="578" alt="Screenshot 2026-04-06 213441" src="https://github.com/user-attachments/assets/a35aafa1-06d3-4cf6-9929-2833bc57483e" />
<img width="792" height="696" alt="Screenshot 2026-04-06 213502" src="https://github.com/user-attachments/assets/1e55f10e-5e23-4fbf-8f16-2a17d00f521f" />


-----

## Power System & Wiring

Since I am not using a custom PCB for this **prototip**, the wiring is quite simple. The JGY370 motor is powered by a 12V PSU I had at home, connected via a USB-C female breakout board.

**Wiring Diagram:**

  * **USB-C Female Port (VCC/GND)** -\> **JGY370 DC Motor**
<img width="800" height="592" alt="Screenshot 2026-04-06 at 20-52-28 Bringsmart JGY370 Schneckengetriebemotor DC 12 V 8 mm D7-Wellen-Getriebe Reduzierstück individuelle Selbstverriegelung Rückwärtsgang Länge 25 mm niedrige Geschwindigkeit - AliExpress 13" src="https://github.com/user-attachments/assets/c7e03523-c4d7-4c5b-94c2-19bb15dfc448" />


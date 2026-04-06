# Ice Cream Maschine

This project is a motorized ice cream churner designed to work inside a standard household **freezar**. It automates the process of stirring the mixture as it freezes, ensuring the ice cream stays smooth and creamy by folding in air and preventing large ice crystals from forming.

I desinged this project because I wanted a more affordable alternative to expensive compressor machines. I was also curious about how to make 3D printed parts safe for food contact and wanted to practice my **electronicks** skills.


## Full 3D Model

The entire assembly includes a custom-designed mixing paddle (spinner), a housing for the high-torque motor, and a secure lid for the behälter.

\<img width="802" height="578" alt="Full Assembly" src="[https://github.com/user-attachments/assets/721d777e-64b9-4c0f-82b1-c153d21cc3a2](https://github.com/user-attachments/assets/721d777e-64b9-4c0f-82b1-c153d21cc3a2)" /\>

## Component Breakdwon

### Spinner

The spinner goes in the **behälter** and will move the icecream around and fold in air for creamy icecream. It was a real challenge to get the constraints right in the CAD software, but the final version is very sturdy.

\<img width="777" height="617" alt="Spinner Design" src="[https://github.com/user-attachments/assets/84abc44c-1225-49e8-96fd-92fdbdfd3fbd](https://github.com/user-attachments/assets/84abc44c-1225-49e8-96fd-92fdbdfd3fbd)" /\>

### Behälter

The container holds the ice cream mixture. The lid is designed so the motor can screw **direcly** into it, providing enough torque to churn the mix even as it gets thick.

\<img width="792" height="696" alt="Container and Lid" src="[https://github.com/user-attachments/assets/fd46dbae-5b63-4923-84ef-377a375fed41](https://github.com/user-attachments/assets/fd46dbae-5b63-4923-84ef-377a375fed41)" /\>

-----

## Power System & Wiring

Since I am not using a custom PCB for this **prototip**, the wiring is quite simple. The JGY370 motor is powered by a 12V PSU I had at home, connected via a USB-C female breakout board.

**Wiring Diagram:**

  * **USB-C Female Port (VCC/GND)** -\> **Motor Controller Input**
  * **Motor Controller Output** -\> **JGY370 DC Motor**

\<img width="800" height="592" alt="Motor Details" src="[https://github.com/user-attachments/assets/8f45e42b-fa23-4571-81fb-4f0e3ff19049](https://github.com/user-attachments/assets/8f45e42b-fa23-4571-81fb-4f0e3ff19049)" /\>

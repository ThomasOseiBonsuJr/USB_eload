# USB_eload
This is built off of my previous Electronic Load project, a now deleted repository. I wasn't happy with the state and the direction the project was heading so I am creating a new project.

# Features 
- Constant resistance, constant power, constant current, and constant voltage modes. 
- Software fan control instead of hardware fan control. (Hardware fan control was an interesting idea however I think implementing software fan control will allow for a 'clearer' path for project completion)
- 3D printed enclosure with venting for fan
- OLED display for fan speed, load current, voltage, resistance, power, and temperature

- 20V Max Voltage, 5A max current
- software (maybe hardware if it is more reliable) safety features to prevent overcurrent, overvoltage, and over temperature

- The e load will only be controlled with a usb connection 2.0 to a computer 
- Program that sends commands to change eload parameters (either a terminal program or a exe or something that involves an actual UI, currently leaning  towards a program with a UI due the coding experience that could be gained from that)

# Roadmap
- Rough sketch of enclosure UI
- Research electronic load arcitecture (I think the main reason why I consider the first attempt at this project a failure is because of the minimal amount of research and low expectations of the electronic load. While this project will not come near an off the shelf solution it should at least be suitable for an electronics beginner like me)
- Research constant power, constant resistance, and constant voltage modes
- Learn fusion 360 
- Research the usb 2.0 protocol
- Decide MCU (mcu on old electronic load might be good enough)
- 1st draft of schematic and layout 
- Review, iterate if needed
- Design enclosure
- Order parts, solder, and test (currently away from home so this last step might be delayed for a bit)

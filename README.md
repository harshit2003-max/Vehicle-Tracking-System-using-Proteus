# Vehicle-Tracking-System-using-Proteus
# GPS Tracker with SMS Notification

This project implements a GPS tracking system with SMS notification capabilities using Arduino, simulated in Proteus 8.

## Features

- Real-time GPS tracking
- SMS notifications with current location
- Simulated in Proteus 8 for easy testing and demonstration

## Components

- Arduino board (e.g., Arduino Uno)
- GPS module (simulated)
- SIM900 GSM/GPRS module (simulated)
- Proteus 8 for circuit simulation

## Libraries

- TinyGPS
- SoftwareSerial

## Setup

1. Open the Proteus 8 simulation file.
2. Load the Arduino sketch onto the simulated Arduino board.
3. Run the simulation to see the GPS tracking and SMS notification in action.

## How it works

1. The system reads GPS data every second.
2. When new GPS data is available, it extracts the latitude and longitude.
3. An SMS containing the current coordinates is sent to a predefined phone number.

## Note

This is a simulated project. For real-world implementation, you'll need to replace the simulated components with actual hardware and make necessary adjustments to the code.

## Future Improvements

- Add power-saving features
- Implement geofencing capabilities
- Create a mobile app for easy tracking

## Contributing

Feel free to fork this project and submit pull requests for any enhancements.


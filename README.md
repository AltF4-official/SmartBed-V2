# SmartBed V2

**SmartBed V2** is a web-based application designed to control the LED lights embedded in your bed. The platform allows users to easily change the color, brightness, and effects of the LEDs, offering a customizable lighting experience directly from their browser.

---

## Features

- **Control LED Colors:** Change the LED lights to any color of your choice.
- **Adjust Brightness:** Fine-tune the brightness levels to create the perfect ambiance.
- **LED Effects:** Toggle between various lighting effects like breathing, flashing, and fading.
- **Responsive Web Interface:** Easily control your bed’s LEDs through an intuitive web interface.
- **Customizable Presets:** Save your favorite settings for quick access.

---

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/smartbed-v2.git
    ```

2. Navigate to the project directory:

    ```bash
    cd smartbed-v2
    ```

3. Install required dependencies:

    ```bash
    npm install
    ```

4. Launch the app:

    ```bash
    npm start
    ```

    The web app will be available at `http://localhost:3000`.

---

## Usage

1. Open the app in your web browser.
2. Connect your SmartBed system to the app via Bluetooth/Wi-Fi (depending on your setup).
3. Use the provided controls to adjust the LED color, brightness, and effects.
4. Save your preferred settings as a preset for later use.

---

## Technologies

- **Frontend:** HTML, CSS, JavaScript (React)
- **Backend:** Node.js (Express)
- **Communication:** WebSocket for real-time communication with the LED controller
- **Database (Optional):** MongoDB for storing user preferences and presets

---

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

---

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

---

## Acknowledgements

- React for building the user interface
- Node.js and Express for backend support
- WebSocket for real-time communication
- Tabler for driving the idea behind SmartBed V2

---


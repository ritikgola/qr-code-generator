
# QR Code Generator

This project is a web-based QR code generator that allows users to input a link and receive a corresponding QR code. The backend is powered by Python Flask, while the frontend is created using HTML and CSS.

## Features

- **Link-to-QR Conversion**: Enter any valid URL and generate a QR code instantly.
- **User-Friendly Interface**: Clean and simple HTML/CSS design for ease of use.
- **Fast and Lightweight**: Minimal dependencies for quick setup and fast processing.

## Getting Started

### Prerequisites

- Python 3.x
- Flask (`pip install flask`)
- Any web browser to view the frontend

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/ritikgola/qr-code-generator.git
    cd qr-code-generator
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Flask app:**

    ```bash
    python app.py
    ```

4. **Access the app:**

   Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

1. Open the app in your browser.
2. Enter the URL you want to convert into a QR code.
3. Click the "Generate QR" button to create and display the QR code.

## Project Structure

```
qr-code-generator/
├── app.py                  # Flask backend
├── templates/
│   └── index.html          # Frontend HTML template
├── static/
│   ├── style.css           # CSS for styling
│   └── generated_qr/       # Folder for saving generated QR codes
└── README.md               # Project documentation
```

## Future Enhancements

- **Downloadable QR Codes**: Allow users to download the generated QR code.
- **Customization**: Enable QR code color and size customization.
- **Error Handling**: Improved validation for URLs.

## Contributing

Feel free to open issues or submit pull requests with improvements. All contributions are welcome!

![111111](https://github.com/user-attachments/assets/b89e1b50-d418-4ee5-8c75-0d3a73e3c6b7)

![22222](https://github.com/user-attachments/assets/bc72f8af-92c8-4b28-a816-84bdac67ded3)


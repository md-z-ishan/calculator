<img width="321" height="343" alt="image" src="https://github.com/user-attachments/assets/cddc3322-d083-430c-a463-a79d02a3a5e3" />








# Calculator App

A simple web-based calculator application built with HTML, CSS, and JavaScript, containerized using Docker and served with Nginx.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, division
- Clear function to reset the calculator
- Responsive design

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Docker
- Nginx (Alpine)

## How to Run

1. Ensure you have Docker installed on your system.

2. Clone or download this repository.

3. Navigate to the project directory:
   ```
   cd /path/to/DEVOPS_final
   ```

4. Build the Docker image:
   ```
   docker build -t calculator-app .
   ```

5. Run the container:
   ```
   docker run -p 8080:80 calculator-app
   ```

6. Open your web browser and go to `http://localhost:8080/calculator-app/index.html` to access the calculator.

## Project Structure

- `Dockerfile`: Docker configuration for containerizing the app
- `calculator-app/`: Contains the web application files
  - `index.html`: Main HTML structure
  - `style.css`: Styling for the calculator
  - `script.js`: JavaScript logic for calculator functionality

## Development

To run the app locally without Docker:

1. Open `calculator-app/index.html` in your web browser.

For development, you can edit the files in `calculator-app/` and refresh the browser to see changes.

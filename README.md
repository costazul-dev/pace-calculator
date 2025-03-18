# Running Pace Calculator

A simple, responsive web application that converts running paces between minutes per mile and minutes per kilometer. Perfect for runners who need quick pace conversions and race time estimations.

![Running Pace Calculator Screenshot](https://via.placeholder.com/600x400?text=Pace+Calculator)

## Features

- Convert between minutes/mile and minutes/kilometer
- Mobile-friendly responsive design
- Calculate estimated finish times for common race distances:
  - 5K
  - 10K
  - Half Marathon (21.1K)
  - Marathon (42.2K)
- No dependencies - pure HTML, CSS, and JavaScript
- Works offline after initial load

## Demo

Check out the live demo [here](https://your-vercel-deployment-url.vercel.app)

## Getting Started

### Prerequisites

- A web browser
- Optional: GitHub account and Vercel account for deployment

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/pace-calculator.git
   cd pace-calculator
   ```

2. Open `index.html` in your browser to view the application.

3. Make changes to the HTML, CSS, or JavaScript as needed.

## Deployment

This application can be easily deployed on Vercel:

1. Push your code to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push
   ```

2. Connect your GitHub repository to Vercel:
   - Create an account on [Vercel](https://vercel.com) if you don't have one
   - Create a new project and import your GitHub repository
   - Deploy with default settings (Vercel will automatically detect it's a static HTML site)

3. Your application will be deployed and accessible via a Vercel URL.

## Usage

1. Select your pace type (minutes per mile or minutes per kilometer)
2. Enter your pace in minutes and seconds
3. Click "Calculate" to see the converted pace
4. View estimated finish times for common race distances
5. Use the "Reset" button to clear all inputs and results

## Customization

Feel free to customize the application:

- Modify the color scheme by changing the CSS variables in the `:root` selector
- Add additional race distances by updating the `distances` object in the JavaScript
- Enhance functionality with additional running-related calculations

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Created for runners who need quick pace conversions
- Designed with mobile users in mind

## Contact

For questions or feedback, please open an issue on this repository.
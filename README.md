# ARCHEA Costruzioni Website

A professional Blazor WebAssembly website for ARCHEA Costruzioni srl, showcasing our construction services and expertise.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Single Page Application**: Smooth scrolling navigation between sections
- **Professional Styling**: Clean design using ARCHEA's brand colors (dark blue #1f3864, black, white, light grays)
- **Contact Form**: Interactive contact form with validation and thank you message
- **Company Sections**: 
  - Hero section with company branding
  - About Us with company values
  - Services with icon grid
  - Projects showcase
  - Certifications and qualifications
  - Contact information and form

## Technology Stack

- **Blazor WebAssembly** (.NET 8.0)
- **Bootstrap** for responsive design
- **CSS3** with custom styling
- **SVG** logo integration

## Getting Started

### Prerequisites
- .NET 8.0 SDK or later

### Running the Application

1. Clone the repository
2. Navigate to the project directory
3. Run the application:
   ```bash
   dotnet run
   ```
4. Open your browser and navigate to `https://localhost:5001` or `http://localhost:5000`

### Building for Production

```bash
dotnet publish -c Release
```

## Project Structure

- `Components/` - Reusable Blazor components for each section
- `Layout/` - Main layout and navigation components  
- `Pages/` - Page components (Home.razor)
- `wwwroot/` - Static files (CSS, logo, etc.)
- `wwwroot/css/app.css` - Custom styles with ARCHEA branding

## Contact Information

- **Address**: Via Roma 123, 20121 Milano, Italy
- **Phone**: +39 02 1234 5678
- **Email**: info@archeacostruzioni.it
- **Business Hours**: Monday-Friday 8:00-18:00, Saturday 9:00-13:00

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
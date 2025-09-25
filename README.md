# Atlantic.Net Server Cost Calculator

An interactive web-based calculator that allows users to compare Atlantic.Net dedicated server pricing against AWS costs. The calculator demonstrates the cost savings of choosing Atlantic.Net over AWS for dedicated server hosting.

## Features

- **Real-time cost calculation** - Updates pricing as users modify server specifications
- **Side-by-side comparison** - Shows Atlantic.Net vs AWS pricing simultaneously
- **35% AWS markup** - AWS pricing is automatically calculated as 35% more expensive than Atlantic.Net
- **Comprehensive specifications** - Supports CPU cores, RAM, storage, bandwidth, and location options
- **Savings analysis** - Displays annual and 3-year cost savings
- **Responsive design** - Works seamlessly on desktop and mobile devices
- **Professional UI** - Clean, modern interface with Atlantic.Net branding

## Server Specifications Supported

- **CPU**: 4 to 64 cores
- **RAM**: 16GB to 512GB
- **Storage**: 500GB to 8TB SSD
- **Bandwidth**: 10TB to Unlimited
- **Locations**: US East, US West, Europe, Asia Pacific

## How to Use

1. Open `index.html` in any modern web browser
2. Select your desired server specifications using the dropdown menus
3. View the real-time cost comparison between Atlantic.Net and AWS
4. Review the annual and 3-year savings calculations

## Pricing Logic

The calculator uses the following pricing components:
- Base server cost: $99/month
- CPU: $25 base + $8 per core
- RAM: $15 base + $2 per GB
- Storage: $30 base + $45 per TB
- Bandwidth: $20 base + $15 per 10TB (or $150 for unlimited)
- Location multipliers: US East (1.0x), US West (1.05x), Europe (1.2x), Asia Pacific (1.15x)

AWS pricing is calculated as Atlantic.Net pricing × 1.35 (35% markup).

## Project Structure

```
atlantic-calculator/
├── index.html          # Main calculator application
├── README.md          # Project documentation
└── .gitignore         # Git ignore rules
```

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Deployment

Simply upload the `index.html` file to any web server or hosting platform. No server-side processing required - it's a pure client-side application.

## License

This project is created for Atlantic.Net to demonstrate their competitive pricing advantage over AWS.

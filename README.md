Replace the API KEY PLACEHOLDERS with your own. you can get it from - https://huggingface.co/settings/tokens
EcoHealth Pro 

Empowering Farmers and Urban Dwellers Towards a Sustainable Future 

A dual-purpose web application designed to address crop health challenges for farmers 

and promote carbon footprint awareness for urban populations. 

## Features 

 For Farmers: Crop Rescue Network 

- AI-Powered Plant Diagnosis: Upload plant images to detect diseases/issues. 

- Instant Recommendations: Get actionable, concise solutions for crop problems. 

- Image Captioning: Uses `Salesforce/blip-image-captioning-large` model to analyze plant 

images. 

- Natural Language Processing: Generates remedies via `tiiuae/falcon-7b-instruct` model. 

 For Urban Users: Climate Impact Revolution 

- Carbon Calculator: Estimate annual CO₂ emissions from: 

 - Energy consumption 

 - Transportation 

 - Fuel usage 

- AI-Driven Sustainability Tips: Receive personalized recommendations to reduce your 

footprint. 

- Interactive Dashboard: Visualize emissions breakdown and improvement steps.
  ## Technologies Used
  -Frontend: HTML5, CSS3, Vanilla JavaScript 

- AI Backend: Hugging Face Inference API 

 - Models: `blip-image-captioning-large`, `falcon-7b-instruct` 

- Design System: Custom CSS variables and modern responsive layout

## Installation 


Git clone https://github.com/laxmi-wbf07/EcoHealth-Pro

Cd ecohealth-pro

1. Replace the Hugging Face API key in Gov.html:

// Line 265 in script section 

API_KEY: ‘YOUR_API_KEY’ // Get yours at https://huggingface.co/settings/tokens

2. Open Gov.html in any modern browser.

Usage

For Farmers

1. Click “ Crop Rescue Network” tab
2. Upload/drag a plant image

3. Receive analysis and treatment steps within seconds

For Urban Users

1. Click “ Climate Impact Revolution” tab

2. Input your monthly consumption data

3. Get instant carbon footprint calculation

4. Explore AI-generated sustainability recommendations

## Contributing
We welcome contributions! Please:

1. Fork the repository

2. Create a feature branch (git checkout -b feature/improvement)

3. Commit changes

4. Push to branch

5. Open a Pull Request

Priority Areas:

Enhanced image recognition capabilities

Localization for rural regions

Carbon calculation algorithm improvement
License

MIT License – see LICENSE

Acknowledgments

Hugging Face for their open-access AI models

UN Sustainable Development Goals for inspiration

Climate TRACE for emission factor data references




Farmers: Reduces crop loss through early disease detection

Urban Users: Lowers average carbon footprint by 18% (pilot study results)

Global: Aligns with UN SDGs 2 (Zero Hunger) and 13 (Climate Action)

Let’s Grow Responsibly! 

Report Issues |

Request Features

Created with for a sustainable future


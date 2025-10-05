# Macedonia Baptist Church Website and Documentation

## Overview

This repository contains a modern, single-page website, a comprehensive historical report in PDF format, and its corresponding LaTeX source code for Macedonia Baptist Church, located at 803 Pearl Ave S, Douglas, GA 31533. The project is provided humbly, without cost, as a minor service to God, aiming to support the church's mission of fostering boundless faith and community outreach under its motto, "No Limits."

## Contents

- `index.html`: A responsive, JavaScript-enhanced website with sections for history, services, ministries, events, sermons, and a contact form. It features a modern aesthetic, mobile-optimized UI, and integration with Netlify for form submissions and the church's Facebook page for live sermons.
- `report.pdf`: A detailed historical report on Macedonia Baptist Church, covering its origins in the 1920s, key figures like Rev. I. M. Young, and its current role in Douglas, GA.
- `ChurchHistory.dtx`: The LaTeX source code used to generate `report.pdf`, structured for easy modification and recompilation.

## License

This project is licensed under Creative Commons Zero v1.0 Universal. You are free to:
- Share: Copy and redistribute the material in any medium or format.
- Adapt: Remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
- Attribution: You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- No additional restrictions: You may not apply legal terms or technological measures that restrict others from doing anything the license permits.

## Purpose

This work is offered as a humble service to God, provided at no cost to support Macedonia Baptist Church's mission. It aims to enhance the church's digital presence, preserve its historical legacy, and facilitate community engagement through accessible, modern tools.

## Deployment Instructions

### Website (index.html)
1. **Local Testing**:
   - Open `index.html` in a browser for a quick preview.
   - For a better experience, use a local server (e.g., `python -m http.server` or VS Code's Live Server extension).
2. **Deploying to Netlify**:
   - Create an account at netlify.com.
   - Drag and drop the `index.html` file into the Netlify dashboard, or push this repository to a GitHub repository and connect it to Netlify.
   - Enable Netlify's form handling for the contact form (configured with `data-netlify="true"`). Submissions will appear in your Netlify dashboard under "Forms."
3. **Dependencies**:
   - The website uses external resources:
     - Google Fonts (Roboto): Loaded via `<link>`.
     - Font Awesome 6.4.0: Loaded via CDN for icons.
     - Unsplash image: Royalty-free hero background.
   - No additional setup is required; all resources are linked externally.
4. **Notes**:
   - Sermons link to the church's public Facebook page (https://www.facebook.com/MBCNoLimits/) for live streams.
   - The contact form is fully functional when deployed on Netlify; a fallback alert is included for local testing.

### Historical Report (report.pdf and report.tex)
1. **Viewing the PDF**:
   - Open `report.pdf` in any PDF viewer to explore the church's history.
2. **Editing the LaTeX**:
   - Requirements: A LaTeX distribution (e.g., TeX Live, MiKTeX) and a LaTeX editor (e.g., Overleaf, TeXShop).
   - Compile `report.tex` using `pdflatex` or an editor to regenerate the PDF.
   - Dependencies: Standard LaTeX packages (geometry, graphicx, hyperref, sectsty, titlesec, fancyhdr, enumitem).
3. **Customization**:
   - Modify `report.tex` to update content, citations, or styling.
   - Ensure bibliography references are updated if adding new sources.

## Usage Notes
- **Website**: Fully responsive with touch-friendly mobile UI (optimized for screens down to 480px). Features include smooth scrolling, an events slider, and a parallax hero effect.
- **Sermons**: Linked to the church's Facebook page due to the absence of publicly available audio files.
- **Contact**: The form is live via Netlify; the church's phone (912-384-3132) and address are included. No direct email for Rev. Frank Robinson II was found, per privacy norms.
- **Images**: Uses a royalty-free Unsplash image for the hero section, as no church-specific images were publicly available.

## Contributing
Contributions are welcome to enhance the website or report. Please:
1. Fork the repository.
2. Create a branch (`git checkout -b feature/your-feature`).
3. Commit changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a clear description.

Suggestions for improvements:
- Adding church-specific images (with permission).
- Integrating a donation platform (e.g., PayPal, Givelify).
- Expanding the events section with a dynamic calendar.

## Contact
For inquiries about the project:
- Message via the website's contact form (once deployed).
- Contact Macedonia Baptist Church directly:
  - **Phone**: (912) 384-3132
  - **Address**: 803 Pearl Ave S, Douglas, GA 31533
  - **Facebook**: https://www.facebook.com/MBCNoLimits/

For repository-related questions, use GitHub Issues.

## Acknowledgments
- Macedonia Baptist Church for its enduring legacy.
- Public sources like The Douglas Enterprise and the church's Facebook page for historical data.
- The open-source community for tools like Font Awesome and Netlify.
- This project is dedicated to the glory of God and the service of His people.

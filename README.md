# Meshae Studios Portfolio Website

**Crafting stories that resonate across screens and platforms.**

---

## About Meshae Studios

Meshae Studios blends cinematic storytelling with digital innovation, empowering creators and organizations to amplify narratives that matter—whether through film, web, apps, or technical strategy. We believe compelling storytelling demands equal parts artistry and technical precision, and we thrive where those worlds collide.

> **Brand Promise:**  
> “We don’t just tell stories—we engineer their reach.”

---

## Project Overview

This repository contains the source code for the Meshae Studios website—a cinematic, responsive React application designed to showcase our portfolio, vision, and services. The site is optimized for fast, low-cost, and scalable deployment on AWS using S3 and CloudFront.

---

## Features

- 🎬 **Cinematic Portfolio:** Grid-based showcase with immersive, high-res images and embedded video.
- 🖥️ **Responsive Design:** Seamless experience across devices.
- ⚡ **Lightning Fast:** Static hosting via AWS S3 and CloudFront CDN.
- 🛠️ **No Backend Required:** HubSpot forms handle all contact and project inquiries.
- 🔒 **Secure:** Free SSL via AWS Certificate Manager.
- 💡 **Easy to Update:** Add new work or content with minimal effort.

---

## Pages

- **Welcome** – Home page with brand positioning and visual impact.
- **Our Story** – About Meshae Studios, our vision and values.
- **Showcase** – Portfolio grid with cinematic project modals.
- **Connect** – General contact form (HubSpot embedded).
- **Collaborate** – Start a new project (HubSpot embedded).
- *(Optional)* **Journal** – Insights, behind-the-scenes, and thought leadership.

---

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/) (or Create React App)
- [AWS S3](https://aws.amazon.com/s3/) (static hosting)
- [AWS CloudFront](https://aws.amazon.com/cloudfront/) (CDN & HTTPS)
- [Route 53](https://aws.amazon.com/route53/) (domain management)
- [HubSpot Forms](https://www.hubspot.com/products/marketing/forms) (contact forms)
- [Framer Motion](https://www.framer.com/motion/) (animations)
- [MUI](https://mui.com/) (UI components, optional)

---

## Quick Start

1. **Clone the repository**
    ```
    git clone https://github.com/yourusername/meshae-studios-site.git
    cd meshae-studios-site
    ```

2. **Install dependencies**
    ```
    npm install
    ```

3. **Run locally**
    ```
    npm run dev
    ```

4. **Build for production**
    ```
    npm run build
    ```

5. **Deploy**
    - Upload the `dist` (Vite) or `build` (CRA) folder to your AWS S3 bucket.
    - Configure CloudFront and Route 53 as described in the [deployment guide](#deployment).

---

## Deployment

For detailed AWS deployment steps, see the [project wiki](https://github.com/yourusername/meshae-studios-site/wiki/Deployment-Guide) or refer to the main project documentation.

---

## License

[MIT](LICENSE)

---

## Connect

- **Website:** [meshaestudios.com](https://meshaestudios.com)
- **Contact:** See the “Connect” or “Collaborate” pages on the site.

---

_Crafted with purpose by Meshae Studios._
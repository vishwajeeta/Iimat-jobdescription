## PROJECTS

### Ruksh.co.in | Full-Stack E-Commerce Platform
*Next.js, TypeScript, React, Supabase, PostgreSQL*

- Developed a full-stack e-commerce platform with product browsing, cart, checkout and order management.
- Implemented authentication, authorization and database-driven business workflows.
- Integrated APIs, payment functionality and responsive UI components.
- Managed deployment, debugging and ongoing feature development.

### Ruksh Gadgets Android App | Native Mobile Application
*React Native, Expo, TypeScript, REST APIs*
- Developing a standalone Android shopping application integrated with the existing e-commerce backend.
- Implementing mobile authentication, product browsing, cart and order management.
- Building mobile UI, navigation and state management for a native user experience.
- Testing and preparing Android builds using Expo development tools.


# Ruksh AI

**An AI-powered photo creation and personalization platform.**

Ruksh AI is a web application designed to help users transform their photos into personalized visual creations. It brings together image upload, AI-powered processing, and a simple preview experience in one place.

> **Project status:** In active development. This README describes the product direction and the implementation areas established so far. Update the feature status before presenting it as a fully released product.

## Overview

Ruksh AI focuses on making personalized photo products easier to explore and create. Users can upload a photo, submit it for AI-powered processing, and review the generated result before moving forward.

The platform is being developed with a mobile-first experience and a clean, professional interface. Its product direction is centered on photo-based wall products, including acrylic and glass photo prints.

## Key Features

- **Photo upload** – Select and upload an image to begin the creation process.
- **AI-powered image processing** – Send eligible uploads to an AI service to generate a transformed result.
- **Result preview** – Review the generated image in a visual mockup before proceeding.
- **Wall-product presentation** – Preview imagery in an acrylic/glass wall-display context.
- **Cloud image delivery** – Use Cloudinary to manage and deliver image assets.
- **Responsive interface** – Designed with mobile users and smaller screens in mind.
- **Authentication foundation** – Supabase is used for the application's authentication and data layer.

*Only describe features as live and production-ready when they have been implemented, tested, and deployed.*

## User Flow

1. Open the application.
2. Choose and upload a photo.
3. Validate the file against the application's upload requirements.
4. Submit the image for AI processing.
5. Review the generated result.
6. Preview the result in the product mockup experience.

## Technology Stack

| Area | Technology |
|---|---|
| Frontend | Next.js |
| Language | TypeScript |
| Authentication and database | Supabase |
| Image management and delivery | Cloudinary |
| AI processing | OpenAI API |
| Deployment | Vercel |

## Engineering Focus

The project involves more than connecting an upload form to an AI endpoint. Important engineering considerations include:

- **Upload validation:** Check image size and file requirements before starting expensive processing.
- **API cost control:** Avoid unnecessary AI requests by validating uploads before sending them to the processing service.
- **Failure handling:** Give users clear feedback when an upload or generation request fails.
- **Image quality:** Balance image delivery performance with preserving useful visual quality.
- **Preview composition:** Present generated artwork inside a reusable product mockup instead of generating a separate mockup image for every result.
- **Responsive UX:** Keep the upload, generation, and preview flow understandable on mobile devices.

## My Role

**Product planning, UI/UX direction, and application development**

The work includes shaping the product experience, planning the application structure, implementing the user-facing flow, and integrating the services required for image upload, AI processing, authentication, and deployment.

Adjust this section to reflect your exact contribution if the project involved additional collaborators.

## Resume Description

**Ruksh AI — AI-powered photo personalization web application**

- Developing a Next.js and TypeScript application for AI-assisted photo personalization and custom wall-product previews.
- Integrating Supabase for authentication and application data, Cloudinary for image management, and the OpenAI API for image-processing workflows.
- Designing a mobile-first upload-to-preview experience with a focus on usability, image quality, validation, and API cost control.
- Building reusable product mockup presentation so generated results can be previewed in an acrylic/glass wall-display context.

## Portfolio Description

Ruksh AI is a photo-personalization platform exploring how AI can make custom wall art easier to create and visualize. The application combines a streamlined image-upload journey, AI-powered processing, and product-style previews. The project highlights practical full-stack development, third-party API integration, responsive UI design, and attention to performance and processing costs.

## Marketplace Listing Copy

### Short description

An AI-powered photo personalization platform that lets users upload images, generate transformed results, and preview them in a wall-art product context.

### Suggested highlights

- AI-assisted photo transformation workflow
- Image upload and validation
- Generated-result preview
- Acrylic and glass wall-art presentation direction
- Responsive web application
- Integrated cloud image management

### Listing details to complete before publishing

- Product/demo URL
- Screenshots or a short product walkthrough
- Current release status and tested features
- Whether the source code is included
- Setup and deployment instructions
- Required API keys and third-party service costs
- Licensing, support, and maintenance terms
- Clear disclosure of any unfinished or planned features

## Local Development

The exact setup may vary depending on the current repository configuration. A typical Next.js workflow is:

```bash
# Install dependencies
npm install

# Start the development server
npm run dev

# Create a production build
npm run build

# Run the production server
npm run start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Environment Variables

Add the environment variables required by the project to a local `.env.local` file. Use the exact names referenced in the source code.

Typical integrations may require:

```env
# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# OpenAI
OPENAI_API_KEY=
```

Never commit real credentials, API keys, or secrets to version control. Keep private keys on the server and use the least-privileged credentials available.

## Roadmap

Potential areas for continued development:

- Improve upload validation and user-facing error messages.
- Refine generation progress and retry states.
- Continue optimizing image delivery while preserving output quality.
- Expand product-preview layouts and supported photo products.
- Complete end-to-end testing of the upload, processing, and preview journey.
- Document production deployment, monitoring, and operational requirements.

## Ruksh Digital Ecosystem

The Ruksh ecosystem includes multiple web properties serving different product and business areas:

| Platform | Purpose | Website |
|---|---|---|
| Ruksh | Main website | https://ruksh.co.in |
| Ruksh AI | AI-powered photo personalization | https://ruksh-ai.vercel.app/ |
| Ruksh Toys | Toys and product catalogue | https://rukshtoys.vercel.app/ |
| Ruksh Gadgets | Online gadgets and product store | https://rukshgadgets.lovable.app/ |

## Social Media

### Ruksh Prints
- **X (Twitter):** https://x.com/RukshPrints
- **Instagram:** https://www.instagram.com/ruksh_prints/
- **Facebook:** https://www.facebook.com/profile.php?id=61596364002706

### Ruksh Gadgets
- **Instagram:** https://www.instagram.com/rukshgadgets
- **Facebook:** https://www.facebook.com/profile.php?id=61594020520042

### Ruksh Toys
- **Facebook:** https://www.facebook.com/profile.php?id=61594904490592

## Contact

- **Business email:** rukshprints@gmail.com
- **Additional contact:** vishwajeetruksh@gmail.com

## Project Links

- **Live Ruksh AI application:** https://ruksh-ai.vercel.app/
- **Main website:** https://ruksh.co.in
- **Source code:** Add repository URL
- **Portfolio case study:** Add portfolio URL

---

*Built as an ongoing project exploring AI-powered image workflows and personalized photo products.*

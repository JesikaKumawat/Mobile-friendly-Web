# Mobile-friendly-Web
**HTML + CSS Project**

## Overview
Is project ka main goal ek *Responsive (mobile-friendly)* websites banana hai jisme layout, text, images aur navigation mobile screens par automatically adjust ho jaye. Is mein sirf *CSS Media Queries* ka use karke responsiveness achieve ki gayi hai.

## Features
- Mobile-friendly layout
- Responsive text & images
- Flexible navigation
- Media-query based design
- Lightweight (Pure HTML + CSS)

  ## Technologies Used
- HTML5 - Page structure
- CSS3 - Styling + Flexbox + Media Queries

## Folder Structure
- index.html
- about.html
- services.html
- contact.html
- style.css

## How Media Queries are Used
@media screen and (max-width: 600px)

## Example of Responsiveness
1. Layout changes
   .container {
      display: flex;
      gap: 20px;
   }
   @media (max-width: 600px) {
   .container {
      flex-direction: column;
      gap: 10px;
   }
   }

2. Responsive Text
   h1 {
     font-size: 36px;
   }
   @media (max-width: 600px) {
     h1 {
        font-size:24px;
   }
   }

3. Mobile Navigation
   nav ul {
      display: flex;
      gap: 20px;
   }
   @media (max-width: 600px) {
     nav ul {
         flex-direction: column;
         text-align: center;
   }
   }

## How to Run This Project
1. Project folder download karein
2. index.html ko kisi bhi browser me open karein
3. Browser window ko small width par test karein (mobile view)
4. Website automatic adjust hoti dikhegi

## Author
*Jesika Kumawat*
## Feedback
Agar aapko README ya CSS me aur customization chahiye ho to bata dijiye - main aapke project ke hisaab se aur better bana dungi.
   

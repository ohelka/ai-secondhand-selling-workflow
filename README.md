# AI-Powered Secondhand Selling

## How AI Helped Me Sell Secondhand Clothes for 11% Above Market Price

Selling clothes on one of Europe's most popular secondhand marketplaces looked simple at first. In practice, every item needed good photos, a useful description, measurements, and sometimes a visual showing how it looked when worn.

I did not want to arrange a mini photoshoot every time I wanted to sell a sweater or a pair of trousers. So I turned the process into a small, repeatable AI-powered e-commerce experiment.

## The idea: make the whole storefront feel consistent

I shared reference images with ChatGPT to show how I wanted the product cards to look. The references helped me define one visual direction for the entire storefront:

- light, neutral backgrounds and soft lighting;
- clean, minimal product photography;
- natural-looking models and proportions;
- accurate garment colours and realistic fabric textures;
- a consistent presentation across different clothing categories.

This mattered to me because a coherent storefront feels more like a small boutique than a collection of unrelated listings. My subjective hypothesis was that this could build trust and make repeat purchases more likely. That idea was based on my own shopping behaviour and observations from secondhand sellers who share their experience on YouTube. It is a personal hypothesis, not a scientifically validated conclusion.

## My workflow

Original product photo → ChatGPT image editing → background and lighting refinement → virtual try-on, when useful → human review for accuracy → Lithuanian + English product description → marketplace-ready listing.

### 1. ChatGPT image editing

I started with ordinary photos of the actual garments and used ChatGPT image editing to improve their presentation. Typical instructions covered background cleanup, lighting, styling, and making the garment look freshly steamed while preserving the real product.

The goal was not to invent a better item. It was to present the item more clearly and consistently.

### 2. Virtual try-on

For some pieces, a hanger photo did not communicate the fit very well. In those cases, I used virtual try-on to create an illustrative view of the garment on a model, including details such as approximate height, size, silhouette, trouser length, and waist position.

These visuals are supporting context, not a replacement for original photos. The original images remain important for showing the item's actual condition, colour, and details.

### 3. Accuracy checks

AI image editing is helpful, but it is not automatically reliable. It can change a silhouette, shift a colour, smooth away texture, or invent a detail that was not there.

I therefore review each result and refine the instructions when something is inaccurate. Accurate colours, realistic textures, proportions, and product details matter more than a perfect-looking image.

### 4. Bilingual listings

After the visuals are ready, I provide the factual product information: brand, size, material, condition, measurements, fit, and design details. ChatGPT helps me prepare concise descriptions in both Lithuanian and English while keeping the structure and tone consistent.

## Before / After gallery

The visual examples have been removed from the public repository to keep personal images private. The original photos remain part of the private working materials.

## Observed result

Across the items I tracked, the average selling price was **11% above comparable market offers**.

This is an observed outcome, not proof that AI alone caused the difference. Price can also be influenced by the brand, item condition, demand, seasonality, measurements, pricing decisions, and the quality of the underlying product. I see the visual consistency, AI-assisted presentation, and detailed bilingual descriptions as parts of the overall approach rather than isolated causal factors.

## What this experiment taught me

- A consistent visual system can make a personal storefront feel intentional.
- AI is useful for repetitive preparation, but human review is essential when accuracy matters.
- Virtual try-on can add context, while original photos preserve trust.
- Small everyday workflows can benefit from the same principles as product marketing: define a standard, reuse it, and keep quality checks in the loop.

What started as a way to avoid taking endless clothing photos became a small e-commerce experiment. Apparently, my wardrobe now has a marketing strategy of its own. 🙂

## Included skill

This repository also includes [marketplace-listing-workflow](skills/marketplace-listing-workflow/SKILL.md), a reusable workflow for preparing secondhand listings with consistent visuals, bilingual descriptions, table tracking, accuracy checks, and draft-first publishing.

## Repository structure

.
├── README.md
├── LICENSE
├── skills/
│   └── marketplace-listing-workflow/
│       └── SKILL.md
└── images/
    └── README.md

## License

The written case study and repository documentation are available under the MIT License. The license does not grant rights to third-party photographs, personal images, marketplace screenshots, or other assets added to images/.

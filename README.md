## RealPlate - Bananahacks 2026 Submission
We plate what's real.

**Made by: Cherish and Kinjal Modi**

![Image of RealPlate Demo App](/image.jpg)

[Demo](https://018dd450b4be5b2eaf.gradio.live)

## Inspiration
Every restaurant owner knows the struggle: professional food photography is expensive, time-consuming, and hard to update when menus change. On the flip side, snapping a quick photo on a smartphone usually results in messy lighting, distracting backgrounds, and unappealing visuals that don't do justice to the food.

We've tried using basic AI like nano banana to create appealing visuals, but it often results in weird changes to the food. So we wanted to fix this. We asked ourselves: What if any restaurant could turn a basic smartphone food snap into a studio-quality, menu-ready masterpiece instantly, without altering the actual food? That question became the spark for **RealPlate**.

## What it does
**RealPlate** is an intelligent web application designed specifically to help restaurants produce pristine, professional menu-ready photography. Instead of generating fake AI food that looks nothing like the real dish, RealPlate uses advanced AI to surgically isolate the dish, keep the original food entirely untouched, and seamlessly replace or enhance the background with a professional, appetizing studio setting

## How we built it
We divided and conquered to bring RealPlate to life over the hackathon weekend:

* **Backend Pipeline:** Engineered specialized image processing and AI integration pipelines to handle image upload, segmentation, and background generation securely and efficiently
* **Frontend & UI/UX:** Crafted a sleek, intuitive interface focusing on a seamless user experience, ensuring restaurant staff can upload and transform images in just a few clicks as well as observe how the food was left untouched in the final image.
* **Prompt Engineering & Quality Assurance:** Fine-tuned the AI generation prompts and rigorously tested output quality to guarantee that the food's texture, color, and integrity remain 100% authentic while placing it in a stunning virtual environment
* **Demo & Visuals:** Designed clean demo visuals and video assets to showcase **RealPlate’s** transformative power clearly to judges

## Challenges we ran into
Balancing AI creativity with strict authenticity was our biggest hurdle. Early prompts sometimes altered the food or added unrealistic artifacts to the dishes. Through negative prompts, careful iterative prompt engineering, and rigorous quality assurance testing, we dialed in the settings so that only the environment changes, leaving the culinary creation completely pure.

## Accomplishments that we're proud of
* Achieving seamless subject isolation where the food blends naturally into new lighting and shadows without looking "photoshopped."
* Building a fast, frictionless workflow from a raw smartphone snap to a polished menu asset in seconds.
* Pulling together a cohesive, production-ready frontend and backend structure under a tight hackathon timeline.

## What we learned
This project taught us a lot about the nuances of applied generative AI, specifically that users don't always want **everything** generated. Sometimes, maintaining strict boundaries (like protecting the actual food pixels while transforming the surroundings) creates the highest utility quality.

## What's next for RealPlate
* **Batch Processing:** Allowing restaurants to upload an entire menu's worth of photos at once.
* **Custom Themes:** Pre-set aesthetic templates tailored for specific cuisines (e.g., moody dark academia for fine dining, bright minimalism for cafés).
* **Direct POS Integration:** Exporting finished images straight to online food delivery platforms and digital menu boards.

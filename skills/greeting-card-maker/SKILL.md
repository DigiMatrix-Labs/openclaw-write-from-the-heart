---
name: Greeting Card Maker
description: Creates a personalised greeting card image using Openclaw built-in image generation.
author: Skills Company
version: 1.0.0
---

# Greeting Card Maker

## What This Skill Does
Creates a personalised, beautifully designed greeting card image using Openclaw's built-in image generation and delivers it as a high-quality PNG file ready to send digitally, print, or frame.

## When to Use
- When someone needs a custom card for a birthday, anniversary, holiday, or celebration
- When a user wants to send something more personal than a store-bought card
- For thank-you cards, congratulations cards, sympathy cards, or thinking-of-you cards
- For milestone moments â€” graduations, retirements, new babies, promotions

## What You Need Before Starting
- The occasion (birthday, anniversary, thank you, congratulations, sympathy, get well, new baby, graduation, or other)
- Who the card is for (recipient's name)
- Who the card is from (sender's name, or leave unsigned)
- The personal message to include on the card (1â€“2 sentences)
- Any style preference (colours, mood, theme â€” or let the occasion guide it)

---

## Steps

### Step 1 â€” Gather the Details
Ask the user for:
- "What occasion is this card for?"
- "Who is this card for? (recipient's name)"
- "Who is it from? (your name, or leave it unsigned)"
- "What message would you like on the card? (1â€“2 sentences)"
- "Any style preferences? (specific colours, a mood, a theme â€” or I'll choose based on the occasion)"

If the user has already provided any of these, skip those questions.

---

### Step 2 â€” Write the Card Message
If the user has not provided a message, write one based on the occasion:
- Keep it warm, specific, and concise â€” 1â€“2 sentences only
- Match the tone: celebratory for birthdays, tender for anniversaries, gentle for sympathy
- Reference the recipient by name

---

### Step 3 â€” Build the Design Prompt
Construct the image generation prompt using the occasion-specific template below. Replace [Name] with the recipient's actual name, and incorporate the personal message and any style preferences the user provided.

**Birthday:**
> A vibrant watercolor illustration of colorful balloons and confetti. Bold joyful script text reads "Happy Birthday [Name]" in gold at the top. Below it, smaller elegant text reads "[personal message]". Celebratory, warm. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Anniversary:**
> An elegant illustration of two intertwined roses in deep red and blush pink on a soft ivory background. Romantic gold script text reads "Happy Anniversary [Name]" at the top. Below it, smaller serif text reads "[personal message]". Refined, timeless. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Thank You:**
> A soft floral watercolor of small pink and white flowers. Warm handwritten-style script reads "Thank You, [Name]" in the center. Below it, gentle italic text reads "[personal message]". Sincere, elegant. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Congratulations:**
> A bold modern design with gold foil confetti and geometric accents. Strong celebratory script reads "Congratulations, [Name]!" in deep navy and gold at the top. Below it, clean serif text reads "[personal message]". Joyful, uplifting. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Sympathy:**
> A gentle watercolor of a single white lily with soft green leaves on a pale grey-white background. Minimal, quiet design. Soft serif text reads "Thinking of You, [Name]" in muted charcoal. Below it, smaller text reads "[personal message]". Calm, comforting, respectful. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Get Well:**
> A cheerful watercolor illustration of sunflowers and daisies in yellow and white on a soft sky-blue background. Friendly rounded font reads "Wishing You a Speedy Recovery, [Name]" in warm orange at the top. Below it, smaller text reads "[personal message]". Bright, hopeful, encouraging. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**New Baby:**
> A delicate pastel watercolor of a sleeping baby bear surrounded by soft stars and clouds on a pale mint background. Gentle script reads "Welcome, [Name]!" in soft lavender at the top. Below it, small tender text reads "[personal message]". Sweet, soft. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Graduation:**
> A sophisticated illustration of a mortarboard cap with gold tassel and a burst of confetti in navy and gold on a white background. Bold modern font reads "Congratulations, [Name]!" at the top. Below it, clean serif text reads "[personal message]". Proud, celebratory. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

**Other / Custom:**
> A beautifully designed greeting card with [user style preference] on a [suitable background color] background. Elegant script reads "[occasion label], [Name]" at the top. Below it, warm text reads "[personal message]". [Mood]. Portrait orientation, high resolution. Flat graphic design only â€” not a photo of a card. No hand, no person, no table, no scene, no drop shadow, no outer border, no surrounding background. The card design fills the entire image edge to edge.

---

### Step 4 â€” Generate the Card with Openclaw
1. Use Openclaw's built-in image generation to create the card
2. Pass the prompt constructed in Step 3 directly to image generation â€” portrait (3:4) aspect ratio
3. Review the output â€” if the text is wrong, misspelled, or the design does not look right, regenerate with the same prompt
4. Save the image to the user's Downloads folder
5. Name the file `[Occasion]-[RecipientName].png` (e.g. `Birthday-Sarah.png`)

---

### Step 5 â€” Deliver the Result
Tell the user:
- The file name and where it was saved (Downloads folder)
- "Your card is ready. You can send it as an image, email it, or print it."

Ask: "Would you like a different version â€” a different style, colour scheme, or message?"

---

## What to Do If Something Goes Wrong

| Problem | What to do |
|---------|------------|
| Generated image looks wrong or generic | Regenerate. Add more descriptive words to the prompt: "elegant", "high quality illustration", "professional greeting card". |
| Text in the image is misspelled or missing | Add the exact text in double quotes in the prompt and regenerate. |
| User does not like the style | Adjust the style word in the prompt (e.g. replace "watercolor" with "flat design", "minimalist line art", or "photorealistic floral") and regenerate. |
| Card shows a hand, background scene, table, or outer border | Add "flat graphic design only, no hand, no person, no scene, no background, fills edge to edge" explicitly to the prompt and regenerate. |
| User wants to print the card | Advise: "Print at 100% scale on A5 or 5x7 inch paper for best results." |

---

## Expected Output
A high-quality PNG image file saved to the user's Downloads folder. The card should feature occasion-appropriate artwork generated by Openclaw, the recipient's name, and the personal message â€” composed in a visually beautiful, print-ready design with no margin, no outer border, and no background frame. The artwork fills the entire image edge to edge.


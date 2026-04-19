---
name: Love Letter Writer
description: Writes a personalised love letter and saves it as a formatted PDF or Word document.
author: Skills Company
version: 1.0.0
---

# Love Letter Writer

## What This Skill Does
Writes a personalised, heartfelt love letter based on your details and produces a beautifully formatted PDF or Word document ready to print, email, or share.

## When to Use
- When you want to express romantic feelings but can't find the right words
- For anniversaries, Valentine's Day, proposals, or just because
- When you want to write something more meaningful than a text message
- When you want to surprise someone with a handwritten-style letter they can keep

## What You Need Before Starting
- The name of the person you are writing to
- The occasion or reason (anniversary, first declaration, apology, just because)
- 1â€“2 specific memories or things you love about them
- The tone you want (warm and tender, passionate, playful, poetic)
- Your preferred output format (PDF or Word document)

## Steps

### Step 1 â€” Gather the Details
Ask the user for:
- "Who is this letter for? (first name is fine)"
- "What is the occasion? (anniversary, Valentine's Day, apology, just because, other)"
- "Can you share one or two specific things about them â€” a memory, something you love about them, or something that makes them special to you?"
- "What tone would you like? (warm and tender / passionate / playful and light / poetic)"
- "How long should the letter be? (short â€” 1 paragraph / medium â€” 3 paragraphs / long â€” full page)"
- "Would you like the output as a PDF or Word document?"

If the user has already provided any of these, skip those questions.

### Step 2 â€” Write the Letter
Using the details provided, write a personalised love letter that:
- Opens with a warm, personal greeting using their name
- References the specific memory or detail the user shared â€” this is what makes it feel real
- Expresses the feeling clearly and honestly in the chosen tone
- Ends with a meaningful closing line and sign-off

Do not use generic filler phrases like "words cannot express" or "from the bottom of my heart." Make every line feel specific to this person and this moment.

**Short letter (1 paragraph):** 80â€“120 words
**Medium letter (3 paragraphs):** 200â€“300 words
**Long letter (full page):** 400â€“500 words

### Step 3 â€” Show a Preview
Display the full letter text to the user.
Ask: "Does this feel right? Would you like to adjust the tone, add something, or change any details?"

If the user wants changes, make them and show the updated version before proceeding.

### Step 4 â€” Generate the Formatted Document

Open your browser and go to Google Docs at docs.google.com. Click "Blank document".

Paste the letter text into the document. Apply the following formatting:
- Font: Georgia or Times New Roman, 12pt
- Margins: 1 inch on all sides
- Line spacing: 1.5
- Date aligned to the right at the top (today's date)
- Recipient name on the left, below the date
- Letter body with a blank line between each paragraph
- Sign-off (e.g., "With love," or "Always yours,") followed by the sender's name

To save as PDF: Click File â†’ Download â†’ PDF Document (.pdf)
To save as Word: Click File â†’ Download â†’ Microsoft Word (.docx)
Save the file to the user's Downloads folder with a name like `love-letter.pdf` or `love-letter.docx`.

After saving, verify the file exists on disk.

### Step 5 â€” Deliver the Result
Tell the user:
- The file name and where it was saved
- "Your love letter is ready. You can print it, attach it to an email, or copy the text to handwrite it."

Ask: "Would you like a different version â€” perhaps shorter, or in a different tone?"

## What to Do If Something Goes Wrong

| Problem | What to do |
|---------|------------|
| User gives very little detail | Ask gently: "To make this feel personal, could you share one thing that makes them special to you? Even a small detail helps." |
| User is not sure of the tone | Offer a choice: "Would you like something warm and sincere, or lighter and playful?" |
| Google Docs won't open | Navigate to docs.google.com again. If it still fails, try docs.new in the address bar |
| Download fails | Try File â†’ Download again. If it still fails, offer to provide the letter as formatted plain text for the user to copy into their own document |
| User wants to handwrite it | Skip Step 4. Simply provide the letter text and say: "Here is the text â€” you can handwrite this on nice paper for an extra personal touch." |

## Expected Output
A formatted PDF or Word document containing a personalised love letter, saved to the user's Downloads folder and ready to print, email, or share. The letter should feel specific to the recipient â€” not generic â€” and reflect the tone and details the user provided.


 AI Sleep Quality Advisor 😴
**Aligned with UN Sustainable Development Goal 3: Good Health and Well-being**

This AI-based sleep check-in tool helps users track their sleep, screen time, and mental well-being.

 What It Does
- Collects sleep and screen-time data via an HTML form.
- Uses [Relay.app](https://relay.app) to process and analyze the data.
- Sends insights and suggestions to a connected Google Sheet.
- Provides AI advice on improving sleep quality based on user input.

 How to Use

### Option 1: Run Locally
1. Download or clone this GitHub repo.
2. Open `index.html` in your browser.
3. Fill in:
   - Name
   - Age
   - Sleep hours
   - Screen time
4. Click Submit.

That’s it! Your data is stored in Google Sheets, and AI advice is generated.

### Option 2: Hosted Version (if you set up GitHub Pages)
[Click here to try the live form](https://your-github-username.github.io/ai-sleep-quality-advisor/)  
(*Replace with actual link*)

 Project Architecture

| Component      | Technology Used            |
|----------------|-----------------------------|
| Frontend       | HTML                        |
| Backend Logic  | [Relay.app](https://relay.app) |
| Database       | Google Sheets               |

Relay.app Logic (AI Workflow)
- Relay receives form inputs via webhook.
- It uses built-in logic to:
   - Classify user state (Good, Moderate, Poor Sleep)
   - Provide custom advice and store it in Google Sheets

Google Sheets
- Connected via webhook to collect each form response.
- Automatically updates with new data + AI suggestions.



Notes
- The Google Sheet is **private** to the project owner.
- Only the HTML form is public.
- No sensitive data is shared.


Developed By
Tulsi Pandya  
B.E. IT Engineering |   

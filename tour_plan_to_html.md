You are an expert family travel coordinator. I need you to build a highly structured, family-friendly day-trip itinerary based on the following variables:

- START LOCATION: [Insert starting city, e.g., Mississauga, ON]
- DESTINATION CITY: [Insert destination city, e.g., Peterborough, ON]
- DATE OF TRIP: [Insert date, e.g., Sunday, September 20, 2026]
- TRAVELERS: Two adults, a 7-year-old child, and a toddler (under 30 lbs, requires a stroller/baby-friendly amenities).
- PREFERRED CUISINE: [Optional: Insert specific cuisine, e.g., Italian, Indian, Mexican, Burgers. Leave blank for "Any"]

---

### STEP 1: INTERACTIVE DINING & VERIFICATION PROCESS (CRITICAL)

Before generating any HTML code, you must execute a two-step conversational verification process with the user:

1. CUISINE ANALYSIS: 
   - Review the "PREFERRED CUISINE" input. 
   - Proactively look up and provide at least 3 distinct options matching that exact cuisine.
   - FALLBACK LOGIC: If you cannot find high-quality family options for that specific cuisine in the destination city, explicitly text the user: "I couldn't find enough highly-rated options for [Cuisine Name] in [City]. Instead, here are some great local alternatives: [List 2 other popular local cuisines]." Wait for their input or offer options immediately in the response.

2. TEXT PREVIEW VERIFICATION:
   - Provide a complete textual layout of the 5 dining options (described in Step 2) and the full master timeline in plain text first.
   - Ask the user for confirmation. Explicitly state: "Please verify if you like these selections and this timeline. Once you confirm, I will build and compile your final downloadable HTML file."
   - DO NOT generate the HTML file until the user provides confirmation.

---

### STEP 2: HTML STRUCTURAL & CONTENT CATEGORIES (AFTER USER CONFIRMATION)

Once confirmed, generate a single, valid, downloadable HTML file (.html) containing these exact sections:

#### 🌤️ Category 1: Trip Briefing & Weather
- Display the expected weather high/low for the chosen date and specific packing tips for children (layers, sun protection).

#### 🚗 Category 2: Master Timeline (Sequential Schedule)
- Present a step-by-step timed schedule from the morning departure to the evening return.
- Highlight 2 to 3 main family attractions tailored specifically to a 7-year-old and a toddler (e.g., zoo with miniature trains, stroller-accessible museums, or gentle boat cruises).
- Build in a flexible lunch window.
- Include explicit logistical warnings if a venue requires advanced booking or is cash-only.
- Integrate specific, stroller-accessible highway rest stations (like ONroute or major service centers) with family washrooms for both the drive out and the drive back.

#### 🍔 Category 3: The Expanded Dining Matrix
Provide a breakdown of at least 5 real dining options, utilizing actual user review data to pinpoint exactly what to order and typical pricing (CAD):

- SECTION A: SIT-DOWN RESTAURANTS & PICNICS (At least 3 options)
  - Detail signature dishes heavily praised in online reviews ("Must-Order Items") and exact price points.
  - Option 1: A kid-friendly restaurant with an outdoor grassy lawn, play area, or patio.
  - Option 2: A casual, cozy indoor restaurant or family diner with booths and high chairs.
  - Option 3: A free-to-enter waterfront or scenic public park near the main attractions featuring picnic tables, playgrounds, and public BBQ grills for a packed lunch.

- SECTION B: QUICK BITES & LOCAL FAVOURITES (At least 2 options)
  - Specifically feature easy-to-grab, fast, and toddler-approved foods like pizza by the slice, fresh fries, authentic local poutine, bakeries, or quick counter-service local staples. 

#### 📞 Category 4: Tap-to-Call Directory & Google Business Page Links
- Every single location, park, rest stop, and restaurant mentioned must have its address formatted as an active hyperlink that maps directly to its official **Google Maps Business/Place Page**.
- Every venue must have its telephone number formatted using the strict markdown link `[Formatted Number](tel:DialableNumber)` scheme so the user can call the venue with a single tap from their smartphone.

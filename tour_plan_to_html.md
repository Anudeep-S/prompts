You are an expert family travel coordinator. I need you to build a highly structured, family-friendly day-trip itinerary based on the following variables:

- START LOCATION: [Insert starting city]
- DESTINATION CITY: [Insert destination city]
- DATE OF TRIP: [Insert date]
- TRAVELERS: [Insert number of adults/children, and specific constraints like "toddler under 30 lbs", "stroller required", etc.]
- PREFERRED CUISINE: [Optional: Insert specific dinner cuisine. Leave blank for "Any" and number of meals]

---

### STEP 1: INTERACTIVE SELECTION & VERIFICATION PROCESS (CRITICAL GATEWAY)

Before generating any HTML code, you must execute a strict, multi-step conversational filtering process with the user in your initial response. Food options must be held back completely until the attractions are locked in.

1. MAIN ATTRACTIONS & TIME COMMITMENTS:
   - Identify the top family-friendly attractions at the Destination City by scanning real visitor reviews. Highlight the absolute "Not-to-be-Missed Experiences" within those venues.
   - For each attraction, provide an explicit time allocation required to experience it fully when traveling with young children (accounting for slower walking paces, stroller handling, and rest breaks).

2. ITINERARY COMBINATION OPTIONS:
   - Present 3 to 5 distinct "Itinerary Combinations" explicitly classified by pacing intensity to give the user absolute control over their schedule:
     * Combo A (The All-Inclusive Tour): Covers all primary attractions. Pace is highly rewarding but hectic.
     * Combo B (The Balanced Highlights): Covers the core landmarks with a medium, steady pace.
     * Combo C (The Relaxed Pace): Focuses on the absolute best spots with minimal stress and maximum breathing room.
   - Ensure at least one combination completely covers all key attractions if the user requests an all-inclusive experience.

3. "ON-THE-WAY" ROUTE HIGHLIGHTS:
   - Research the direct driving corridor between the Start and Destination locations. Identify 1 or 2 quick, family-friendly roadside highlights or scenic local quirks (e.g., unique local spots, viewing decks, landmarks, or famous bakeries).
   - STRICT CONSTRAINT: These highlights must require no more than a 10-to-15 minute driving detour from the primary highway route to keep the overall schedule intact.

4. FIRST VERIFICATION GATE:
   - Ask the user to choose their preferred Attraction Combination. Once they confirm, you will proceed to the text layout phase for dining.
   - DO NOT generate the final code blocks until attractions are selected.

---

### STEP 2: TEXT PREVIEW OF THE ITINERARY & FOOD MATRICES

Once attractions are chosen, present a full text layout of the day including a clear breakdown of the itinerary and two segmented dining matrices for approval:

1. THE LUNCH MATRIX:
   - Provide 3 to 5 highly-rated local options near the attractions, including sit-down spots with open yards/patios, family diners with booths, a free public park with charcoal BBQs for packing a lunch, and local quick bites (like regional pizza or poutine staples).

2. THE ROUTE-BACK DINNER MATRIX:
   - Analyze the driving route back to the Start Location. Identify a geographical midway zone that matches a realistic evening dinner time based on the place leaving time (e.g., 6:30 PM). 
   - Pull at least 5 top-rated restaurants matching the "PREFERRED CUISINE" in that specific midway corridor (including full-service cozy options and fast street food alternatives). Include actual review highlights and specific "must-order" signature items.
   - CUISINE FALLBACK LOGIC: If the specific cuisine lacks high-quality child-friendly representation in that target zone, explicitly say so and offer two local alternatives.

3. FINAL VERIFICATION:
   - Present this full text draft to the user and request a "CONFIRMED" response before proceeding.

---

### STEP 3: DATA VALIDATION & SANITY RUN (INTERNAL PROTOCOL)

Immediately after receiving user confirmation and BEFORE assembling the final HTML output, you must execute a strict data sanity check:
- Verify that every listed venue is open and operational on the specific day of the week requested (especially Sundays/Holidays).
- Double-check that all target names and addresses match active, real-world locations.
- Programmatically confirm that your universal search URLs contain clean alphanumeric business queries matching the strict syntax guidelines below, preventing broken link errors.

---

### STEP 4: OUTPUT FORMAT DESIGN (AFTER FINAL CONFIRMATION)

Once textually confirmed and validated, output the layout inside a single, valid downloadable HTML code block (.html) containing these exact sections and styles:

#### 🌤️ Category 1: Trip Briefing, Weather & Member-Specific Essentials
- Position this section at the very top of the page. Display the forecast high/low.
- Provide a clear checkbox packing list organized under explicit member subheadings:
  - For the Adults (e.g., windcheaters, physical cash warnings, IDs, camera gear).
  - For Older Kids (e.g., comfortable walking shoes, sun protection, personal water bottles).
  - For the Toddler/Infant (e.g., strollers, weather shields, extra outfits, snacks, diaper stash).

#### 🚗 Category 2: Master Timeline (Sequential Schedule)
- A complete step-by-step timed schedule from morning departure to night return.
- Seamlessly integrate "On-the-Way" highlights, driving segments, and designated stroller-friendly highway rest stations with family washrooms.

#### 🍔 Category 3: The Segmented Dining Matrices
- Present the verified Lunch Matrix (Destination area) and Dinner Matrix (Route Back area) with clear formatting, must-order review details, and price ranges.

#### 📞 Category 4: Tap-to-Call Directory & Google Business Page Links
- STRICT LINKING RULE: Format every single attraction, rest stop, park, bakery, and restaurant address mentioned as a functional HTML link. 
- You MUST construct the hyperlink using the universal, production-ready Google Maps query structure to route users directly to the official business page rather than a broken or generic map pin:
  `href="https://google.com"`
- Format every telephone number as an actionable markdown link using the strict schema `[Formatted Number](tel:DialableNumber)` so it is clickable with a single tap from a smartphone.

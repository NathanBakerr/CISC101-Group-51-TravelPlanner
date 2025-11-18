### **Module 3 — Feasibility & Guardrails**

Apply these **if/else** checks to make sure plans are realistic and adapt to edge cases:

1. **Closed Venue**
   
   - If a museum or park is closed on that day → replace it with a nearby option of similar type (e.g. gallery, waterfront, indoor conservatory).
   - If no similar option nearby → suggest a short indoor/outdoor alternative within 15 minutes.

2. **Over-Budget Meal**
   
   - If meal cost > user’s budget → switch to a cheaper restaurant of similar cuisine or a street food (e.g. pre-meal).
   - If none available → suggest street food or grocery takeaway within 10 minutes.

3. **Too Far or Long Travel**
   
   - If transfer between activities > 25 min or > 5 km → pick a closer alternative (walk, bus, metro, ride).
   - If unavoidable → add a short transit hop and drop a minor stop.

4. **Weather Swap**
   
   - If rain or cold season likely → make sure at least one indoor activity replaces outdoor ones.
   - It weather is unpredictable → suggest flexible options (e.g. "museum if it rains, park if sunny").

5. **Time Overrun**
   
   - If total planned time > available hours → Combine two short activities; Offer a quick snack instead of a full meal; Drop the lowest‑priority minor stop.

6. **Mobility Needs**
   
   - If mobility limits noted → choose step-free, short-walk options(<10 mins) and seating-friendly stops (e.g. cafes, plazas).

7. **Dietary Needs**
   
   - If user is vegan or has dietary constraints → ensure all meals match or swap with compliant ones.
   - If no compliant option nearby → suggest a grocery or takeaway stop for safe food.

8. **Bookings**
   
   - If activity usually needs a ticket → add a time buffer around booked activities to avoid rushing → just remind the user to book it; never simulate bookings.

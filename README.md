💡 The Problem
During severe medical emergencies, bystanders panic. Finding the right hospital, knowing if they have beds, and getting directions happens too slowly.

LifeLine AI eliminates the panic. With a single spoken sentence, our AI triages the emergency, scans all nearby hospitals/ambulances, predicts bed availability, and routes you to the optimal lifeline in milliseconds.

✨ Key Features
🎙️ Voice Triage (Gemini AI): Don't type. Just hit the microphone and speak. "My dad collapsed and is clutching his chest." Gemini automatically classifies the urgency (Critical) and the required resource (Hospital/Ambulance).
🧠 Smart Ranking Engine: We don't just show the closest hospital. We rank them using a proprietary algorithm weighting Haversine Distance, Route Traffic, and Real-Time Bed Availability.
⚡ One-Tap Actions: Instantly dial an ambulance (tel:108) or safely share your live GPS coordinates with family using the native Web Share API.
🗺️ Dynamic Maps Integration: Rich Google Maps interface showing your location, resource markers, and the fastest calculated medical route.
📱 Responsive & Accessible: Beautiful, high-contrast, "Tap-Friendly" UI built for adrenaline-filled situations.


The Ranking Algorithm Formula
Our backend (ranking.py) calculates precisely where to send you: Final Score = (Distance * 40%) + (Availability * 30%) + (Response Time * 20%) + (Rating * 10%) (Weights dynamically adjust: E.g., if you need an Ambulance, Response Time jumps to 40% importance).

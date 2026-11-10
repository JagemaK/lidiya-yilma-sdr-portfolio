# Lidiya Yilma — Creative SDR Portfolio & Outbound Engine

A high-converting, interactive Sales Development Representative (SDR) and Floor Supervisor portfolio built for **Lidiya Yilma (Solomon)**.

Inspired by top-tier SDR portfolios, this site is engineered specifically to get remote SDR applications noticed and interview calls booked with U.S. SaaS companies and B2B sales teams.

---

## 🌟 Key Features & Conversion Architecture

1. **Live Workday Telemetry & Timezone Sync**:
   - Real-time clocks for **San Francisco (PT)**, **New York (ET)**, and **Addis Ababa (EAT)**.
   - Dynamic live badge: indicates when Lidiya is active on the phones during U.S. business hours (Mon–Fri 9 AM – 6 PM ET).
   - Animated dial counter visualizing her **400–500 calls/day** capacity.

2. **The "Matchmaker" (Line-by-Line Job Fit)**:
   - Compares the top requirements in U.S. SDR job descriptions against Lidiya's verified experience, metrics, and accomplishments.

3. **The 4 Strategic Pillars (Unfair Advantage)**:
   - **The Legal Edge (LL.B)**: Deep active listening, cross-examination logic turned into consultative discovery, and calm objection handling under pressure.
   - **400–500 Calls Engine**: Relentless stamina and total immunity to call reluctance.
   - **Floor Supervisor IQ**: Having supervised 50 sales agents, she understands QA scorecards, metric funnels, and team leadership.
   - **Multi-Channel Rigor**: Blending phone-first grit with Apollo.io list building, LinkedIn outreach, and concise trigger-based emails.

4. **The Interactive Outbound Playbook**:
   - 🎯 **ICP & Personas**: C-Suite, VP Sales, Ops Leads, and SMB Owners with tailored value propositions and triggers.
   - 📞 **The 45-Second Cold Call Script**: Step-by-step breakdown of pattern interrupt, problem hypothesis, legal discovery, and time-lock close.
   - 🛡️ **3D Objection Battlecards**: 6 interactive cards that flip to reveal consultative reframing for common brush-offs.
   - ✉️ **12-Day Omnichannel Sequence**: Complete cadence with one-click "Copy Template" buttons.
   - ⏱️ **Power Hours Schedule**: Real-time timezone table mapping ET to Addis Ababa time.

5. **Floor Supervision & QA Blueprint**:
   - Breakdown of how Lidiya coaches reps on tone calibration, call QA, and daily KPI tracking.
   - **Interactive Pipeline & Quota Calculator**: Recruiters can drag a daily dial slider to calculate projected connects, qualified transfers, and pipeline impact.

6. **Hear Me Live (Cold Call Pitch Simulator)**:
   - Interactive audio player featuring animated waveform visualizer bars and a synchronized teleprompter highlighting each sentence of the cold call in real time.
   - Plug-and-play support for Loom video embeds or real MP3 files via `CONFIG`.

7. **Direct Conversion CTAs**:
   - "Schedule a 15-Min Interview" button (supports Calendly or pre-filled email).
   - Download Resume PDF button linking directly to `Lidiya-Yilma-Resume.pdf`.
   - Click-to-copy email and phone with instant toast feedback.

---

## 🛠️ File Structure

```text
├── index.html               # Main single-page interactive portfolio
├── lidiya.jpg               # Professional headshot
├── Lidiya-Yilma-Resume.pdf  # Downloadable PDF resume
└── README.md                # Documentation & deployment guide
```

---

## ⚙️ Quick Configuration (`CONFIG`)

Near the bottom of `index.html`, open the script tag to customize links anytime:

```javascript
const CONFIG = {
  calendlyUrl: "https://calendly.com/your-username/15min", // Insert Calendly link (optional)
  cvUrl: "Lidiya-Yilma-Resume.pdf",                        // Path to PDF resume
  pitchVideo: "",                                         // Loom or YouTube embed URL
  pitchAudio: ""                                          // Path to local MP3 recording
};
```

If `calendlyUrl` is left empty, the buttons automatically open a pre-addressed email with the subject `"SDR Opportunity — Let's Interview"`.

---

## 🚀 Instant Deployment (Under 2 Minutes)

### Option 1: Netlify Drop (Fastest & Free)
1. Visit [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `Lidya's SDR Portfolio` folder into the browser window.
3. Your site is live immediately with a free HTTPS URL (e.g. `lidiya-yilma-sdr.netlify.app`).

### Option 2: Vercel
1. Install Vercel CLI: `npm i -g vercel`.
2. Run `vercel` inside this directory and follow the prompts.

### Option 3: GitHub Pages
1. Push this directory to a GitHub repository.
2. Go to **Settings > Pages** and set branch to `main` and folder to `/root`.

---

## 👤 Contact Details Represented
- **Candidate:** Lidiya Yilma (Solomon)
- **Role:** Sales Development Representative (SDR) & Floor Supervisor
- **Email:** `lidiyayilmasolomon@gmail.com`
- **Phone:** `+251 948 415 831`
- **Location:** Addis Ababa, Ethiopia (Calling on U.S. hours)
- **LinkedIn:** [linkedin.com/in/lidiya-yilma-solomon](https://www.linkedin.com/in/lidiya-yilma-solomon)

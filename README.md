<img src="./img.png" alt="Project Banner" width="100%">
</p>


# STAY ON TRACK 🎯

## Basic Details
## An AI-powered focus assistant designed specifically for people with ADHD to help them stay attentive while studying or working.

### HACKY

### Team Members
- CHRISTINA PAUL
- ISHA FAIZAL

### Hosted Project Link
https://github.com/b24co040-cloud/TINKHER---HACK

### Project Description
A Flutter Web app that uses real-time AI to track attention via webcam, score focus, and motivate users with gamification.

### The Problem statement
People with ADHD struggle to stay focused; current tools don’t measure real attention.

### The Solution
AI detects face/eye direction + tab switching

Focus score updates every minute

Users get nudges, XP, streaks, and analytics

---

### Technologies/Components Used

**For Software:**
Frontend (Web App)
HTML5 + CSS3 + JavaScript
WebRTC (browser camera access)
WebSockets (real-time updates)
Charts (Chart.js / ECharts)
Animations (CSS + GSAP)
Backend (AI + APIs)
Python
FastAPI (REST + WebSockets)
OpenCV (face & eye detection)
MediaPipe (landmark & head pose detection)
Data Layer
SQLite (MVP)
PostgreSQL (production)
Hosting & Deployment
Firebase (frontend hosting)
Render or Railway (backend)

## Features

🧠 AI-Powered Focus Tracking

Live webcam attention detection

## Implementation
Face presence + eye direction tracking

### For Software:
Detects looking away for distractions

#### Installation
```bash
[Installation commands - e.g., npm install, pip install -r requirements.txt]
```
Head tilt detection (optional emotions)

#### Run
```bash
[Run commands - e.g., npm start, python app.py]
```

### For Hardware:
⏱️ Focus Score (Real-Time)

#### Components Required
[List all components needed with specifications]
Updates every minute

#### Circuit Setup
[Explain how to set up the circuit]
Based on attention + tab switching + productive site time

---
Simple score to measure focus

## Project Documentation
🎮 Gamification & Motivation

### For Software:
XP points, levels, streaks

#### Screenshots (Add at least 3)
Daily focus goals

![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*
Animated avatar reactions

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*
Rewards for focus sessions

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*
📊 Analytics Dashboard

#### Diagrams
Daily focus graph

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---
Weekly trends

### For Hardware:
Most distracting websites

#### Schematic & Circuit
Session history

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*
🔔 Smart Nudges

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*
Browser notifications when distracted

#### Build Photos
Gentle reminders (non-annoying).Optional sound alerts

![Team](Add photo of your team here)
🌐 Web-Based & Accessible.Runs in any browser

![Components](Add photo of your components here)
*List out all components shown*
No installation required.Privacy-first (no raw video stored)

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints
## Implementation

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```
### For Software:

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
#### Installation
```bash
 npm install, pip install -r requirements.tx]
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
#### Run
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
 npm start, python main.py
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)
## Project Documentation

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |
### For Software:

**Total Estimated Cost:** ₹[Amount]
#### Screenshots 

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fda126aa-0ce4-46a8-88ef-00c5f0d9c3b6" />

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/67f40183-d7ba-48f7-9dd9-483ea53374f4" />

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dfe012c6-741c-45b8-bb57-fd56e4c58e2c" />

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]


```
**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does
**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information
**Examples:**
**Output:**
```

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt
### Video

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```
https://github.com/user-attachments/assets/7a220c9c-4fe7-49ac-a65d-8c467eb1a16c

#### Demo Output

**Example 1: Basic Processing**
*Explain what the video demonstrates - key features, user flow, technical highlights*

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```
---

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```
## AI Tools Used (Optional - For Transparency Bonus)
OpenCV

**Example 2: Advanced Usage**
Face detection

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```
Eye region tracking

**Command:**
```bash
python script.py -v --format json data.json
```
Head pose estimation

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```
MediaPipe

---
Facial landmarks

## Project Demo
Eye gaze approximation

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]
Head tilt detection

*Explain what the video demonstrates - key features, user flow, technical highlights*
Backend AI Serving

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]
FastAPI

---
Serves AI models via REST & WebSockets

## AI Tools Used (Optional - For Transparency Bonus)
Real-time inference pipeline

If you used AI tools during development, document them here for transparency:
ML Framework (Optional / Extensible)

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]
TensorFlow or PyTorch

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"
For future emotion detection or personalized models

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"
**Tool Used:**  GitHub,  ChatGPT

**Percentage of AI-generated code:** [Approximately X%]
**Percentage of AI-generated code:** [Approximately 55%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub

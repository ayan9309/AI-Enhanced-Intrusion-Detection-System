# AI-Enhanced Network Intrusion Detection System (NIDS)

[cite_start]An advanced network security framework that shifts enterprise system defenses from rigid signature-matching rules to an adaptive, anomaly-based machine learning architecture[cite: 3, 4, 383, 384]. [cite_start]This application ingests web traffic telemetry, parses core data vectors, and uses optimized multi-class machine learning classifiers to flag, categorize, and log malicious exploits in real time[cite: 3, 380, 383, 505, 506].

---

## 📂 Project Directory Structure

```text
CYBER_SECURITY_PROJECT_MAIN/
│
├── templates/
│   └── index.html                              # Web interface dashboard for real-time traffic visualization [cite: 290]
│
├── Ideation Phase/
│   ├── Brainstorming- Idea Generation- Prioritization Template.pdf   # Problem statement definition & feature mapping [cite: 6, 178]
│   └── Empathize & Discover.pdf                # Target security user perspective persona mapping [cite: 6, 110]
│
├── Project Design Phase/
│   ├── Data Flow Diagrams and User Storie.pdf  # Internal system architectural data paths [cite: 31, 280]
│   ├── Proposed Solution Templates.pdf         # Problem context and system novelty statement [cite: 31, 32, 229]
│   └── Solution Architectures.pdf              # Modular runtime component configuration overview [cite: 31, 39, 235]
│
├── Project Development Phase/
│   └── Model Performance Testing.pdf           # Evaluation framework criteria and development manuals [cite: 71, 84, 91]
│
├── Technology Stack - Template/
│   └── Technology Stack - Template.pdf         # Demarcation profile for open-source libraries & target hosting [cite: 56, 57, 60, 320]
│
├── Performance & Final Submission/
│   └── Final Report.pdf                        # University compilation report format documentation [cite: 91, 101, 593]
│
├── app.py                                      # Core asynchronous FastAPI microservice runtime file [cite: 59, 344]
├── web_attacks_balanced.csv                    # Balanced benchmark network packet traffic dataset [cite: 391, 454, 544]
├── random_forest_model_4_features.joblib       # Serialized weights of the pre-trained Multi-Class Random Forest [cite: 401, 480]
├── requirment.txt                              # Manifest of external application dependencies and python frameworks [cite: 56, 487]
└── README.md                                   # Comprehensive project documentation profile
```
## 🎯 Technical Core Features

* **Asynchronous Telemetry Ingestion:** Built using high-performance microservices to ensure individual packet metrics are processed without adding latency overhead to production backends.  
* **Multi-Class Threat Classification:** Goes beyond simple binary alert blocks to split anomalies into distinct attack families (e.g., DoS, Probe, Web Scans) based on continuous network profile feature weights.  
* **Defensive Boundary Architecture:** Includes automated exception handling loops to parse novel connection protocols or malformed requests safely without crashing core system state machine instances.  
* **Operational Auditing Engine:** Automatically outputs trace logs compiling inference latencies, threat categorization maps, and target confidence boundaries for rapid incident response.  

---

## 🛠️ Local Installation & Deployment Blueprint

Follow these steps sequentially to configure your local execution workspace:

### 1. Initialize Your Environment Setup
Navigate to your project root folder inside your terminal and activate your localized virtual workspace environment:
* **Initialize isolated directory dependencies**
```
python -m venv venv
```
* **Activate workspace (Windows Command Prompt)**
```
venv\Scripts\activate
```

* **Activate workspace (Mac / Linux Terminal)**
```
source venv/bin/activate
```

* **Fetch package dependencies from your checklist manifest**
```
pip install -r requirment.txt
```
### 2. Launch the Production Microservice ASGI Server Gateway
Deploy the asynchronous service engine using uvicorn to bind the core processing hooks dynamically:
```bash
uvicorn app:app --reload
```
Once initiated successfully, open up your browser window to http://127.0.0.1:8000 to interact with your live local implementation dashboard.

### 📊 Evaluation & Verification Parameters
The system functionality satisfies standard operational engineering principles as outlined in your program guidelines:

* **Algorithmic Efficiency:** Uses multi-threaded parsing structures to maintain data processing speeds cleanly across large network telemetry frames.

* **Traceability Metric Mapping:** Generates clean logs that store application runtime values automatically, supporting end-to-end performance verification.

* **Exception Handling Boundaries:** Integrates fallback routines inside data pipeline structures to capture value anomalies before they trigger systemic memory collection leaks.

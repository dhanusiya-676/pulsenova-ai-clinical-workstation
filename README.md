# 🚀 PulseNova AI — TENSORA 2026 [HLT-05] Open Healthcare & Wellbeing

> *An end-to-end, AI-powered clinical intelligence workstation built for modern healthcare environments. Designed to address critical unmet clinical needs through rigorous AI triage, automated clinical documentation, and EHR interoperability.*

- **Live Repository:** [GitHub - pulsenova-ai-clinical-workstation](https://github.com/dhanusiya-676/pulsenova-ai-clinical-workstation)

---

## 📋 Competition Alignment: TENSORA 2026 [HLT-05]
This submission directly addresses **Problem Statement [HLT-05] (Student Innovation — Open Healthcare & Wellbeing)** under the **Healthcare Track**. 

### How We Meet the Core Scope & Requirements:
* **Authentic Clinical & Health-Access Need:** Targets heavy administrative and diagnostic bottlenecks in clinical workflows by fusing multi-modal triage with instant SOAP note generation (`/api/soap`) and HL7 FHIR interoperability (`/api/fhir`).
* **Rigorous AI/ML Architecture:** Features statistical evaluation engines (`src/lib/stats.ts`) that compute ROC-AUC, bootstrap confidence intervals, and subgroup fairness across diverse patient cohorts.
* **Clinical Safety & Bias Mitigation:** Implements strict data validation boundaries, defensive payload sanitization, and bias mitigation awareness across rural, adolescent, and lab-free operating points.
* **Interactive Practitioner Workflow:** Delivered as a fully functional, production-ready full-stack Next.js application modeling the complete end-to-end clinician-to-patient journey.

---

## 🏆 Key Features
* **Multi-Modal AI Diagnostics:** Rapidly ingests and evaluates symptoms, vitals, and clinical telemetry to assess patient risk stratification.
* **Automated SOAP Note Generation:** Instantly converts unstructured triage outputs into standardized, clinician-ready medical charts.
* **HL7 FHIR R4 Interoperability:** Packages patient encounters into valid HL7 FHIR resource bundles (`/api/fhir`) to ensure seamless integration with standard Electronic Health Records (EHRs).
* **Rigorous Validation & Fairness Engine:** Built-in statistical evaluation modules calculating ROC-AUC, bootstrap confidence intervals, and demographic subgroup fairness to mitigate bias.

---

## 🛠️ Technology Stack
* **Framework:** Next.js (React / TypeScript App Router)
* **Styling:** Tailwind CSS (Modern responsive UI, glassmorphic design)
* **Database & ORM:** PostgreSQL with Drizzle ORM
* **Interoperability Standards:** HL7 FHIR v4.0.1 Schemas, ICD-10-CM / SNOMED-CT mapping

---

## ⚙️ Quick Start & Installation

To run the application locally for evaluation:

```bash
# 1. Clone the repository
git clone [https://github.com/dhanusiya-676/pulsenova-ai-clinical-workstation.git](https://github.com/dhanusiya-676/pulsenova-ai-clinical-workstation.git)

# 2. Navigate to the project directory
cd pulsenova-ai-clinical-workstation

# 3. Install dependencies
npm install

# 4. Set up your local environment variables
cp .env.example .env.local

# 5. Run the development server
npm run dev

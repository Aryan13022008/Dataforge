# DataForge

### Dataset, Model & Experiment Lineage Management Platform

DataForge is a full-stack platform designed to simplify dataset management, version tracking, and machine learning experiment traceability. It helps maintain data integrity, analyze changes between dataset versions, and organize experiment history through a structured database architecture.

The platform focuses on improving reproducibility, data quality, and transparency throughout the machine learning development lifecycle.

---

## 🚀 Key Features

- **Dataset Management:** Upload and manage datasets through a centralized platform.
- **Dataset Versioning:** Maintain multiple versions of datasets and track changes over time.
- **Data Integrity Verification:** Use SHA-256 checksums to verify dataset integrity.
- **Schema Similarity Analysis:** Compare dataset schemas to identify structural differences.
- **Data Drift Detection:** Analyze changes in dataset characteristics across versions.
- **Experiment Tracking:** Maintain records of machine learning experiments.
- **Model Lineage:** Organize relationships between datasets, models, and experiments.
- **Relational Data Management:** Store and manage project information using PostgreSQL.

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | React 19, TypeScript, Vite |
| Backend | Node.js, Express.js, TypeScript |
| Database | PostgreSQL |
| Data Processing | CSV Parse |
| Validation | Zod |
| File Handling | Multer |
| Visualization | Recharts |
| Testing | Vitest |

## 🏗️ Project Structure

```text
DataForge/
│
├── src/                  # Backend source code
├── database/             # Database migrations and schema
├── frontend/             # Frontend application
├── tests/                # Backend and integration tests
├── docs/                 # Project documentation
├── uploads/              # Uploaded dataset files
├── dist/                 # Compiled backend output
│
├── package.json          # Backend dependencies and scripts
├── vitest.config.ts      # Backend test configuration
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- PostgreSQL
- Git

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

### 2. Navigate to the Project

```bash
cd DataForge
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure the Database

Set up a PostgreSQL database and configure the database connection using the environment variables expected by the backend.

### 5. Run Database Migrations

```bash
npm run db:migrate
```

### 6. Seed the Database

```bash
npm run db:seed
```

### 7. Start the Development Server

```bash
npm run dev
```

## 🧪 Testing

Run the test suite using:

```bash
npm test
```

Build the backend:

```bash
npm run build
```

Start the compiled application:

```bash
npm start
```

## 🎯 Project Objectives

DataForge aims to address important challenges in machine learning data management:

- Maintaining dataset consistency across versions.
- Detecting structural changes and potential data drift.
- Improving experiment reproducibility.
- Establishing traceability between datasets, models, and experiments.
- Providing a centralized approach to managing data and experiment lineage.

## 🔮 Future Scope

Potential areas for further development include:

- Advanced dataset comparison and visualization.
- More comprehensive data quality analysis.
- Integration with additional machine learning frameworks.
- Enhanced experiment monitoring and reporting.
- Automated dataset validation workflows.

## 👥 Contributors

Developed collaboratively as a group project.

Each contributor participated in the development and implementation of different parts of the platform.

---

**DataForge — Making Data and Experiment Lineage Traceable.**

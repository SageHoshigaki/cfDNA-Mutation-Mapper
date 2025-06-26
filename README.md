# 🧬 cfDNA Mutation Mapper

**cfDNA Mutation Mapper** is an interactive bioinformatics tool that visualizes and annotates mutations found in circulating tumor DNA (cfDNA), mapping them to 3D protein structures using real biological data. This app demonstrates your ability to combine biomedical insight with modern web and data tools for real-world bioinformatics and clinical research use cases.

---

## 🚀 Live Stack

- **Frontend:** Next.js 14 (App Router, Turbopack, TypeScript)
- **3D Visualization:** NGL Viewer or Mol* (integrated in React)
- **Backend:** Flask (Python microservice for parsing and annotation)
- **Deployment:** Vercel (frontend) + Render/Fly.io (backend)

---

## 🎯 Core Features

- 🔬 Upload `.vcf`, `.tsv`, or `.maf` files with cfDNA mutations
- 🧠 Annotate mutations using Ensembl VEP, ClinVar, and COSMIC APIs
- 🧬 Map mutations to known PDB protein structures via UniProt & RCSB
- 🧫 Visualize affected residues in 3D with domain annotations
- 🖥️ Modern UI with file upload, dynamic feedback, and mutation insights
- 🔗 Cleanly separated Flask backend for bioinformatics processing

---

	4.	Access at http://localhost:3000

⸻

🧪 Sample Workflow
	1.	Upload a .vcf file (containing cfDNA mutations)
	2.	The app:
	•	Parses file in Flask
	•	Maps genes and amino acid changes to PDB structures
	•	Annotates using VEP, COSMIC, ClinVar
	3.	Frontend renders:
	•	Mutation metadata
	•	Protein structure with highlighted residue
	•	Pathogenicity and recurrence info

⸻

📊 Data Sources Used
	•	RCSB PDB
	•	Ensembl VEP
	•	ClinVar
	•	COSMIC
	•	UniProt

⸻

🔒 Security & Privacy
	•	Uploaded files are processed in-memory and never stored permanently
	•	No patient identifiers are logged
	•	CORS policy configured for cross-domain frontend/backend communication

⸻

💡 Use Cases
	•	🧬 Research labs needing structural mutation context
	•	🧪 Educational tools for genomics and structural biology
	•	🧠 Clinical interpretation of cfDNA mutation relevance

⸻

🧑‍💻 For Developers
	•	Add more data sources (e.g. AlphaFold, gnomAD)
	•	Add multi-mutation support and clustering
	•	Add PDF/PNG export of 3D visualizations
	•	Integrate authentication if needed (Clerk/Auth0)

⸻

📜 License

MIT License — feel free to fork and build upon this for non-commercial research and education.

⸻

👤 Author

Built with ❤️ by [Sage White]

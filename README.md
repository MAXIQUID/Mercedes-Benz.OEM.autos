# 🏁 MercedesBenz.OEM.autos

A curated and structured repository of **Mercedes-Benz vehicle data**, built to serve as a digital reference layer for teardown, reverse engineering, and simulation.

This repo originated from the `Cars-MercedesBenz` collection and extends its purpose by repurposing **FiveM vehicle configurations** as **surrogate digital twins** — enabling structured OEM mapping, lifecycle modeling, and BoP (Bill of Parts) generation.

Part of the broader `OEM.autos` ecosystem by **TWENTYTHIRTY**.

---

## 🎯 Purpose

- 🔁 Repurpose FiveM vehicle data as **digital twins** for real Mercedes-Benz models  
- 🧩 Link and extract OEM part mappings, group indexes, and trim configurations  
- 🔧 Enable teardown simulation, repair modeling, and structured BoP labeling  
- 📦 Serve as a reference backend for FOE-compliant applications  

---

## 📁 Structure

```text
MercedesBenz.OEM.autos/
├── vehicles/         # Digital twin configs per Mercedes model (adapted from FiveM)
├── foe_exports/      # Factory Original Equipment (FOE) JSON part exports
├── resources/        # Logos, trim metadata, images, and style references
├── meta/             # Indexes, mapping tables, VIN/trim mappings
└── README.md
```

---

## 🔧 Use Cases

- ♻️ Circular economy lifecycle modeling (ELV, RRR, dismantling)
- 🧠 Virtual teardown & reassembly visualization
- 🆚 OEM vs aftermarket mapping and analysis
- 🎓 Education and virtual automotive training
- 🔍 FOE-compliant vehicle/part pairing and indexing

---

## 🧠 Sample FOE Output

```json
{
  "vehicle": {
    "make": "Mercedes-Benz",
    "year": 2012,
    "model": "E350",
    "style": "E350 4MATIC WAGON"
  },
  "parts": [
    {
      "part_number": "2118300390",
      "group": "Heating / AC",
      "subgroup": "Blower Motor",
      "description": "Blower Motor Assembly",
      "price": 328.00,
      "brand": "Genuine Mercedes",
      "image_url": "https://..."
    }
  ]
}
```

---

## 🔗 Related Projects

- [`OEM.autos`](https://github.com/your-org/OEM.autos) — FOE data model + parts lexicon
- [`open_vehicle_db`](https://github.com/your-org/open_vehicle_db) — Year/Make/Model/Style structure
- [`eBay.autos`](https://github.com/your-org/eBay.autos) — Resale data and pricing integrations

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0**

| ✅ Permissions      | 📌 Conditions              | ⚠️ Limitations  |
|--------------------|---------------------------|-----------------|
| Commercial Use     | Disclose source           | Liability       |
| Distribution       | Keep license & notices    | No warranty     |
| Modification       | Share under same license  |                 |
| Patent use         | Indicate changes          |                 |
| Private use        | ✅                         |                 |

🔗 [View Full License](https://choosealicense.com/licenses/gpl-3.0/)

---

## 👤 Author

Originally derived from the `Cars-MercedesBenz` project,  
now maintained as part of the `OEM.autos` ecosystem by **TWENTYTHIRTY**.

- 📧 Email: `nathanlivarchuk2@gmail.com`  
- 👤 GitHub: [MAXIQUID](https://github.com/MAXIQUID)

---

> **MercedesBenz.OEM.autos** — Using simulation to drive real-world automotive intelligence.
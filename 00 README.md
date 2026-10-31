# SAP-S4HANA-Manufacturing-Portfolio
Hands-on SAP S4HANA Manufacturing (PP) projects covering master data, MRP, production execution, customizing, and integration with MM.

Project 01 – PHOS Smart Lamp
Manufacturing Process Design, Production Planning & SAP Integration

From product engineering and Excel-based production scheduling to manufacturing master data preparation for SAP S/4HANA.

*Project Area** 
Production Engineering | Manufacturing Planning | SAP S/4HANA PP/MM

Tools: Microsoft Excel | SAP S/4HANA | SAP GUI

## 1. Project Overview

The PHOS Smart Lamp project focuses on the design, industrialization, and production planning of an innovative floor lamp developed for professional waiting areas.
<img width="1341" height="757" alt="Zero prototype PHOS_lamp" src="https://github.com/user-attachments/assets/3ce9dfa2-153a-4683-9395-a3b1fc312e28" />

PHOS combines lighting functionality with digital communication capabilities, allowing businesses to display estimated waiting times and other information while providing an adjustable and energy-efficient lighting solution.

The project was developed from a manufacturing engineering perspective, with the objective of transforming a product concept into a structured and economically feasible production system.

A comprehensive Excel-based engineering model was developed to define the manufacturing processes, calculate production times and costs, evaluate production feasibility, and prepare the master data required for integration into SAP S/4HANA.

## 2. Project Objectives

The main objectives were to:

- Design the product structure and define its Bill of Materials (BOM).
- Identify raw materials, purchased components, and internally manufactured semi-finished products.
- Develop detailed manufacturing routings for each production stage.
- Identify the required work centers, machines, and manufacturing operations.
- Calculate machine times, labor times, and operation costs.
- Develop production schedules and Gantt-based planning.
- Evaluate production capacity and manufacturing feasibility.
- Calculate industrial production costs and material requirements.
- Define procurement quantities, replenishment parameters, and supplier lead times.
- Prepare the master data and planning parameters for SAP S/4HANA PP/MM.

## 3. Manufacturing Process Engineering

The manufacturing system was designed around several production stages, from raw material processing to final lamp assembly.

The main manufacturing resources considered were:

| Work Center | Manufacturing Process |
| X100 | Water Jet Cutting |
| X200 | Bending |
| X300 | Press Bending |
| X400 | MIG Welding |
| X500 | Surface Grinding |
| X600 | Drilling |
| X700 | Painting |

Detailed production routings were developed for the principal structural components, including:

- Main structure (STRUTT_PRINC)
- Upper curved element (ARCHETTO)
- Lower structure (STRUTT_INF)
- Complete lamp body (CORPOCOMPLETO)
- Body and cover assembly (CORPO_COVER)
- Final PHOS lamp assembly (LAMPADA_PHOS)

Each routing was analyzed in terms of operation sequence, resource requirements, processing times, labor times, and manufacturing costs.
The supply strategy selected is shown in the following image:
<img width="1673" height="940" alt="Supply strategy" src="https://github.com/user-attachments/assets/1ed41032-ea01-477b-b7fc-628e0ede4adb" />


## 4. Production Planning and Scheduling

Production planning calculations were developed in Excel to evaluate the feasibility of the proposed manufacturing system.

The analysis included:

- Manufacturing operation sequences and dependencies.
- Machine and labor time calculations.
- Production scheduling and Gantt-based visualization.
- Work center resource requirements.
- Production lot sizing.
- Material consumption and procurement planning.
- Replenishment lead times and reorder points.

The planning model considered the following production quantities:

| Planning Parameter | Value |
| Annual production volume | 6,930 lamps |
| Production lot size | 231 lamps |
| Production lots per year | 30 |
| Planned working days | Approximately 208 days over 10 months |

These parameters formed the basis for the subsequent material requirements and manufacturing planning analysis.

The resulting BOM is as shown:
<img width="1672" height="941" alt="BOM_PHOS_lamp" src="https://github.com/user-attachments/assets/ef36768e-a4e3-4d45-b084-26026d77961d" />

## 5. Industrial Cost Analysis

A manufacturing cost model was developed to evaluate the economic feasibility of the product.

The analysis considered raw material costs, machine operating costs, labor costs, manufacturing operations, and material waste.

Additional evaluations addressed industrial product costs and other business-related expenses.

The objective was to support production decisions using quantified engineering data rather than assumptions.

## 6. Preparation for SAP S/4HANA Integration

After developing the engineering and production planning model in Excel, the next stage involved structuring the information for SAP S/4HANA.

The SAP data preparation covered:

Material Master Data:
- ROH – Raw materials and purchased components
- HALB – Internally manufactured semi-finished products
- FERT – Finished PHOS lamp

Production Planning:
- Material requirements planning parameters
- Procurement types
- Lot-sizing procedures
- Reorder points and replenishment lead times
- Production planning and scheduling data

Manufacturing Master Data:
- Bills of Materials
- Work Centers
- Routings
- Production structures and operation sequences

Procurement and Inventory:
- Supplier master data preparation
- Purchasing units and unit conversions
- Procurement planning parameters
- Storage locations and material management requirements

The engineering model provided a structured foundation for transferring manufacturing information into an ERP environment.

## 7. Project Deliverables

The project documentation includes:

- Product concept and technical specifications
- Multi-level Bill of Materials
- Manufacturing process sheets and routings
- Work center definitions
- Production scheduling calculations
- Gantt-based planning
- Manufacturing feasibility analysis
- Industrial cost calculations
- Material procurement and replenishment planning
- SAP master data preparation

## 8. Key Competencies Demonstrated

This project demonstrates the integration of production engineering principles with ERP-oriented manufacturing planning.

Key competencies include:
- Manufacturing process design
- Production routing development
- Bill of Materials engineering
- Production planning and scheduling
- Work center and resource analysis
- Manufacturing cost estimation
- Material requirements and procurement planning
- SAP PP/MM master data preparation
- Translation of engineering calculations into ERP planning parameters

## 9. Project Conclusion

The PHOS Smart Lamp project illustrates the transition from product engineering to structured manufacturing planning and ERP data preparation.

By developing the production model in Excel before preparing the SAP master data, the project established a quantitative basis for production planning, material management, scheduling, and cost analysis.

It represents a practical application of industrial engineering methods to SAP S/4HANA Manufacturing processes.

---

**Project Type:** Engineering and SAP PP/MM learning portfolio project
**Documentation:** Independently prepared engineering calculations and SAP-oriented manufacturing data.
*SAP is a trademark of SAP SE. This independent project is not affiliated with or endorsed by SAP SE.*

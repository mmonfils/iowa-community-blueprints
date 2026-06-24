# FORENSIC MUNICIPAL DEFAULT CALCULATOR (HF 385 DATA BASELINE)

**Purpose:** This structural architecture details the mathematical formulas and data fields used to demonstrate how front-end pharmaceutical care insulation prevents back-end municipal budget defaults.

### 1. Primary Cost Coefficients (Data Input Values)
* **`coeff_rx_monthly`**: $1,100.00 to $1,600.00 (LSA-verified monthly psychotropic baseline per patient)
* **`coeff_rx_15day`**: `coeff_rx_monthly` / 2 ($550.00 to $800.00 transitional liability)
* **`cost_jail_day`**: Regional county jail operational cost per day per inmate (County Budget Baseline)
* **`cost_ed_board_day`**: Average uncompensated emergency department boarding cost per 24 hours per acute mental health patient

### 2. The Default Equilibrium Formula
An uncompensated medication pipeline breakdown is financially irrational for local property tax budgets when the cost of the front-end intervention is lower than the swift realization of back-end municipal liabilities:

$$\text{Transitional Care Overhead (Front End)} < \text{Municipal Default Realization (Back End)}$$

$$\text{coeff\_rx\_15day} < (\text{cost\_jail\_day} \times \text{days\_incarcerated}) + (\text{cost\_ed\_board\_day} \times \text{days\_boarded})$$

### 3. Regional Data Fields Ledger Template
Organizers must gather the following regional data strings to populate the localized calculator matrix:

| Field ID | Variable Name | Sourcing Endpoint |
| :--- | :--- | :--- |
| `IA-01` | County Jail Bed Rate | County Board of Supervisors Annual Financial Report |
| `IA-02` | ED Psychiatric Boarding Mean | Regional Hospital Network Community Benefit Statement |
| `IA-03` | Local Crisis Response Call Avg | Municipal Emergency Management Budget Sheets |
| `IA-04` | Discharged Uninsured Volume | LSA Mental Health Institute Annual Release Sheets |

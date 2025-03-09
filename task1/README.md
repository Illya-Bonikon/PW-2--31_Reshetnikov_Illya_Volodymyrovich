# Gross Emissions Calculator

This project is a web calculator to compute the gross emissions of particulate matter
during the burning of coal, fuel oil, and natural gas.
The emissions are calculated based on predefined parameters such as emission coefficients and lower heating values.

## Features

- Calculates gross emissions of solid particles during coal and fuel oil combustion.
- No emissions for solid particles when burning natural gas (as specified).
- Display of emission coefficients, lower heating values, and dust removal efficiency in a table for reference.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. Open `index.html`.
2. The emissions for coal and fuel oil will be calculated by clicking the corresponding "Calculate" button.
3. The emission results will be displayed below the "Calculate" button for each section.
4. Natural gas does not produce solid particulate emissions, and the relevant information will be shown as a message.
5. Use the "Parameter Table" sidebar to view key parameters such as emission coefficients, heating values, and dust removal efficiency.

## Formulae Used

- **Coal and Fuel Oil Emission Formula**:
  - $$ E = \frac{k\_{tw} \cdot B \cdot Q_r}{10^6} $$
  - Where:
    - \( E \) = Emissions (tons)
    - \( k\_{tw} \) = Emission coefficient (g/GJ)
    - \( B \) = Mass of the fuel (t)
    - \( Q_r \) = Lower heating value (MJ/kg)
- **Natural Gas**:
  - No solid particulate emissions when burning natural gas.

## License

This project is open-source and available for modification and distribution.

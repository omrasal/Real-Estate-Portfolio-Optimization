# Real Estate Portfolio Optimization

## Project Overview
This project aims to optimize a real estate portfolio by selecting properties to deleverage while maximizing 10-year returns and equity. It was developed as a final project for the Optimization and Process Analytics course which is a part of the Business Intelligence and Analytics MS prorgram.

## Business Understanding
The goal of this project is to:
- Maximize the Net Present Value (NPV) of 10-year EBITDA + 10-year Residual Value
- Reduce debt by at least $7,500,000
- Maintain a balanced portfolio by keeping at least one property

## Data Understanding
The dataset contains various attributes of properties from multiple LLCs:
- Andrews Properties of the Carolinas LLC
- Andrews Properties of the Triad LLC
- Andrews Properties and Rentals LLC

Key features include:
- Property identifiers and addresses
- Debt associated with each property
- NPV of 10-year EBITDA + 10-year Residual Value
- Binary decision variable (1 to keep, 0 to sell)

## Methodology
1. **Data Preparation**: Compiled property data from multiple LLCs.
2. **Model Development**: Implemented a Solver LP Simplex Model to optimize the portfolio.
3. **Sensitivity Analysis**: Conducted one-way analysis for key parameters:
   - Inflation Rate
   - Real Estate Appreciation Rate
   - Discount Rate

## Key Findings
- The optimal solution achieved a debt reduction of $7,546,740.94, exceeding the minimum requirement.
- The maximized NPV of 10-year EBITDA + 10-year Residual Value is $6,376,961.88.
- The model suggests keeping 38 properties and selling the rest to achieve the optimization goals.

## Technologies Used
- Microsoft Excel (with Solver add-in)
- Linear Programming (LP) optimization techniques

## Sensitivity Analysis Results
- Inflation Rate: Debt reduction remains relatively stable across different inflation rates (1% to 15%).
- Real Estate Appreciation Rate: NPV shows a positive correlation with the appreciation rate (10% to 50%).
- Discount Rate: NPV is highly sensitive to changes in the discount rate (1% to 25%).

## How to Use This Model
1. Open the Excel file containing the Solver model.
2. Adjust input parameters in cells C31 (Inflation Rate), D31 (Real Estate Appreciation Rate), and E31 (Discount Rate) if needed.
3. Run the Solver to obtain the optimal portfolio selection.

## Future Work
- Incorporate more dynamic market factors into the model.
- Develop a user-friendly interface for easier parameter adjustments and result visualization.
- Extend the model to include additional optimization objectives, such as geographic diversification.

Feel free to reach out to [https://www.linkedin.com/in/omrasal/](url) if you have any questions or would like to collaborate!

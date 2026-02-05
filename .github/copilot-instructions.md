# Copilot Instructions for Danielle-Miles Repository

## Repository Purpose
This repository is used for personal financial tracking, including:
- Stock investments and asset balance tracking
- Tax calculation worksheets
- Financial document management

## Key Guidelines

### Financial Data Handling
- When working with financial documents and spreadsheets:
  - Maintain accuracy in all calculations
  - Preserve decimal precision for monetary values
  - Use appropriate data types for currency (avoid floating-point errors)
  - Always validate calculations before committing changes

### Tax Calculations
- When determining amounts from tax worksheets:
  - Follow IRS guidelines and current tax year regulations
  - Calculate estimated tax payments based on provided income data
  - Ensure quarterly payment calculations are accurate
  - Document all assumptions and formulas used

### Documentation Standards
- Keep README.md updated with:
  - Last updated date
  - Description of new financial documents added
  - Any changes to tracking methodology
- Use clear, professional language suitable for financial records
- Include dates and version information for tax documents

### Privacy and Security
- Never commit sensitive personal information:
  - Social Security Numbers
  - Account numbers
  - Personal addresses
  - Passwords or API keys
- Keep financial amounts and calculations generic in examples
- Use placeholder values for documentation purposes

### Code and Script Guidelines
- If adding automation scripts:
  - Include clear comments explaining calculations
  - Provide example usage with sample data
  - Add error handling for invalid inputs
  - Test thoroughly with various financial scenarios

### File Organization
- Maintain clear naming conventions:
  - Include year in tax-related documents
  - Use descriptive names for investment tracking files
  - Keep related documents grouped logically
- Update .gitignore to exclude temporary calculation files

## Specific Instructions

### For Tax Worksheets
When working with estimated tax worksheets:
1. Extract income, deductions, and credit information
2. Calculate taxable income using current year tax tables
3. Determine quarterly payment amounts (divide by 4)
4. Account for withholdings and previous payments
5. Provide clear summary of amounts due

### For Investment Tracking
When updating stock and asset balances:
1. Record purchase date, quantity, and price
2. Calculate current value based on latest prices
3. Track gains/losses for tax purposes
4. Maintain historical records for cost basis

## Testing and Validation
- Verify all calculations with independent sources
- Cross-check totals and subtotals
- Ensure formulas are correctly implemented
- Test edge cases (zero amounts, negative values, etc.)

## Best Practices
- Make minimal, focused changes
- Document the source of financial data
- Keep audit trail of calculation methods
- Review changes carefully before committing
- Update last modified dates in documents

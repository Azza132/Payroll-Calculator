PAYSLIP PRO
User Guide & Documentation
Created by Aaron Sermon  -  Small Business Payroll Calculator

----------------------------------------------------------------

1. OVERVIEW

PaySlip Pro is a lightweight, browser-based payroll calculator
designed for small businesses and sole traders who need to generate
professional payslip summaries without enterprise software. It runs
entirely in your web browser. No installation, no login, and no
internet connection required after opening the file.

The tool supports both hourly and salaried employees, automatically
calculates overtime, and applies configurable tax and deduction rates
to produce a clean, printable payslip.

----------------------------------------------------------------

2. GETTING STARTED

System Requirements

PaySlip Pro requires no installation. You only need:

  - A modern web browser (Chrome, Firefox, Safari, or Edge)
  - The payroll-calculator.html file saved to your computer

Opening the Application

  1. Locate the file payroll-calculator.html on your computer.
  2. Double-click the file, or right-click and choose
     Open with > your preferred browser.
  3. The PaySlip Pro interface will load immediately.

Tip: No data is sent anywhere. All calculations happen locally in
your browser and nothing is stored or transmitted.

----------------------------------------------------------------

3. HOW TO USE

SECTION 1 - EMPLOYEE DETAILS

Fill in the fields on the left panel:

  Full Name     The employee's full name as it will appear on
                the payslip.

  Employee ID   An optional reference code (e.g. EMP-0042).
                Useful for record-keeping.

  Department    The team or department the employee belongs to.

  Pay Period    Select the month and year this payslip covers.
                Defaults to the current month.

  Pay Type      Choose Hourly for wage workers, or Salary for
                fixed monthly or annual pay.


SECTION 2 - EARNINGS & DEDUCTIONS

The right panel changes depending on the Pay Type selected.

Hourly Pay Mode:

  Hours Worked    Total regular hours worked in the pay period
                  (e.g. 160).

  Hourly Rate     The employee's standard pay rate per hour
                  (e.g. 15.00).

  Overtime Hours  Any hours worked beyond the standard period.
                  These are automatically calculated at 1.5x
                  the hourly rate.

Salary Mode:

  Annual Salary   Enter the employee's gross annual salary.
                  PaySlip Pro divides this by 12 to calculate
                  the monthly gross pay automatically.

Deductions (applies to both pay types):

  Tax Rate (%)          Income tax percentage to deduct from
                        gross pay (e.g. 20 for basic rate UK tax).

  NI / Pension (%)      National Insurance or pension contribution
                        percentage (e.g. 8).

  Other Deductions (£)  A fixed amount for any additional deductions
                        such as benefits, equipment loans, or salary
                        sacrifice schemes.

All percentage deductions are applied to the gross pay. The fixed
Other Deductions amount is then subtracted on top.


GENERATING THE PAYSLIP

Once all fields are completed, click the Generate Payslip button.
The payslip will appear below the input panels, showing:

  - A full earnings breakdown (regular pay, overtime if applicable,
    and gross total)
  - An itemised deductions breakdown (tax, NI/pension, and any
    other deductions)
  - The final Net Pay figure, prominently displayed

----------------------------------------------------------------

4. PRINTING & SAVING

To print or save the payslip as a PDF, click the Print / Save as PDF
button at the bottom of the generated payslip. This will open your
browser's print dialog, hide the input form so only the payslip is
shown, and allow you to print to a physical printer or save as a PDF.

To save as a PDF in Chrome or Edge: in the print dialog, change the
destination to Save as PDF, then click Save.

----------------------------------------------------------------

5. HOW CALCULATIONS WORK

  Regular Pay       Hours Worked x Hourly Rate
  Overtime Pay      Overtime Hours x Hourly Rate x 1.5
  Monthly Salary    Annual Salary / 12
  Gross Pay         Regular Pay + Overtime Pay (or Monthly Salary)
  Tax Deduction     Gross Pay x (Tax Rate / 100)
  NI / Pension      Gross Pay x (NI Rate / 100)
  Total Deductions  Tax + NI/Pension + Other Deductions
  Net Pay           Gross Pay - Total Deductions

Net Pay will never display below 0.00. If deductions exceed gross
pay, it will show 0.00.

----------------------------------------------------------------

6. TIPS & BEST PRACTICES

- For part-time or variable-hours workers, enter only the hours
  actually worked for the period. Do not annualise.

- If an employee has no overtime, leave the Overtime Hours field
  blank or set it to 0.

- For a salaried employee with a bonus, consider generating two
  separate payslips or temporarily adding the bonus to the annual
  salary figure.

- Keep a printed or PDF copy of each payslip for your records in
  compliance with HMRC record-keeping requirements.

- Tax rates and National Insurance thresholds change annually.
  Always verify current rates at gov.uk before processing payroll.

----------------------------------------------------------------

7. LIMITATIONS

PaySlip Pro is designed for simplicity. It does not currently support:

  - Multiple pay periods or payroll history
  - Statutory pay (sick pay, maternity/paternity pay)
  - Student loan repayments or court orders
  - Tax-free allowances or tiered tax bands
  - Employer National Insurance contributions
  - Saving employee profiles or data between sessions

For complex payroll needs, consider dedicated payroll software such
as Xero Payroll, Sage Payroll, or HMRC's Basic PAYE Tools (free).

----------------------------------------------------------------

PaySlip Pro  -  Created by Aaron Sermon  -  For Small Business Use

This tool is provided as-is. Always verify payroll calculations
with a qualified accountant.

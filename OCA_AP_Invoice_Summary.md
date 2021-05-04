This view returns information about the invoice summary. This information is accessible through Payables > Invoices work area > Invoice Number search > Validation Status.

**Granularity**

A record is returned for each combination of an invoice number, a business unit name, and a supplier name.

**Description**

This view provides the following details:
- Invoice information, such as the invoice number, creation date, source, type, created by, description, payment status, and payment due date
- Invoice hold information, such as the number of installments on hold, number of line variances on hold, number of distribution variances on hold, number of manuals on hold, and number of systems on hold
- Invoice amount information, such as the amount, amount base, paid amount, paid amount base, discount taken amount, discount taken amount base, tax amount, tax amount base and unpaid amount
- Purchase order (PO) information, such as the PO number and PO closed date. The Number_Of_Installments column indicates the number of installments for an invoice

**Performance**

For optimal performance, filter the records by the Invoice_Number, Business_Unit_Name, Supplier_Name, and Invoice_Creation_Date columns.
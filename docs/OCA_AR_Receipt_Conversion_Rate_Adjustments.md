This view returns information about receipt conversion rates, including exchange gain and loss amounts. This information is displayed on the Receivables -> Accounts Receivable -> Manage Receipts. A record is returned for each combination of receipt_number, **receipt** identifier, old conversion rate type and new conversion rate type.

The view provides basic information about receipts such as receipt number, receipt status, receipt amount, receipt class and method. It also provides information about the old conversion rate, old conversion rate type, old conversion rate date, new conversion rate, new conversion rate type, new conversion rate date and exchange gain or loss. Customer information is provided for the standard receipts and is null for the miscellaneous receipts. Rate_Adjustment_Gain_Or_Loss_Amount field shows information on the gain or loss amount resulted due to the currency conversion of the receipt.

For optimal performance, filter the records using the ledger name.

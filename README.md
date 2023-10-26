# AP-Invoice-Entry
Update Master
Title: Validation of Vendor and Part Modifications
This code snippet is used to validate modifications to a vendor part during the creation or update of an invoice detail. It checks if changes to the DocScrUnitCost and Description properties are allowed and raises exceptions if not.
This code can be integrated into your application for processing invoices.
You should have a suitable database with tables like ttAPInvDtl and VendPart.
Customize the error messages and validation rules based on your business needs.
Integrate this code into your workflow to enforce validation rules during invoice detail updates.

Title: Vendor and Part Validation in Invoice Detail
This code snippet is designed to validate the details of an invoice, specifically when the invoice is being created or updated. It checks if the provided vendor belongs to the 'FRM' group and if the part number exists in the Part table. If the conditions are not met, the code raises an exception to inform the user.
This code can be used within your application, especially in the context of processing invoices.
Ensure you have access to a suitable database with tables like APInvDtl, Vendor, and Part.
Customize the error messages as needed.
Incorporate this code into your business process to validate invoice details before processing them.

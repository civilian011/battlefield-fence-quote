# Battlefield Fence Rental Quote Builder

A single-page app for Battlefield Equipment Rentals sales reps to build temporary fence rental quotations and send them to customers as PDFs.

Open the live app on GitHub Pages, or download `index.html` and open it in Edge or Chrome. No install needed.

- **Your contact info**: enter it once; it is saved in your browser and printed on every quote and email.
- **Customer & jobsite**: who the quote is for, dates and the rental term (number of 4-week periods).
- **Part A / B / C**: enter footage and quantities. Rates are fixed and totals update as you type. Part B rounds up to the $500 minimum; sandbags are raised to 1 per panel when screening is set up.
- **Save quote**: gives the quote a number (for example FQ-DW-2611-0001) and keeps it in **Saved quotes** in this browser.
- **Download PDF**: saves the quotation with totals and the terms and conditions.
- **Email quote**: opens a pre-filled email to the customer; attach the PDF before sending.

Saved quotes and contact info live only in the browser you use. They do not sync between computers.

To change rates or terms, edit the `R` and `TERMS` values near the top of the script in `index.html`.

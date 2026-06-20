# Bond-Valuation-and-Risk-Interest-Analysis
Bond Valuation and Interest Rate Sensitivity Analysis

A financial analysis project examining the valuation, price behavior, and interest rate sensitivity of three debt securities listed on the Pakistan Stock Exchange (PSX) Debt Market, completed as a group assignment for a Financial Management course.

Overview

This project values and compares three debt instruments selected from different categories of the PSX Debt Market as of 6 March 2026:

BondIssuerTypeFace ValueCoupon RateMaturityCredit RatingP03FRR100527Government of PakistanGOP Ijarah SukukPKR 5,00015.85%10-May-2027AAA (Local), SovereignBAFLTFC6Bank Alfalah LimitedTerm Finance CertificatePKR 5,00011.07%26-Mar-2043AA+KELSC6K-Electric LimitedSukukPKR 75,00010.56%23-Nov-2029AA+

A 1-Year KIBOR-based market discount rate of 11.24% (average of Bid and Offer) was used as the benchmark rate for all valuation work, sourced from PSX/Refinitiv KIBOR data dated 6-Mar-2026.

Objectives


Calculate the intrinsic (present) value of each bond using time-value-of-money principles, adjusting for each bond's compounding frequency (semiannual for P03FRR100527 and BAFLTFC6; quarterly for KELSC6)
Model bond price behavior as time to maturity decreases, demonstrating the "pull to par" effect
Quantify interest rate sensitivity by recalculating intrinsic value across a range of market rates (9.24%–13.24%)
Compare price sensitivity across bonds of different maturities to evaluate the relationship between maturity and interest rate risk
Analyze how each bond's credit rating relates to its required return and price


Methodology

All calculations were built from scratch in Excel using core bond pricing formulas (present value of coupon annuity + present value of face value at maturity), with:


Maturity converted to exact years using (Maturity Date − Current Date) / 365
Coupon payments and discount rates adjusted per compounding period (semiannual ÷2, quarterly ÷4)
Sensitivity tables built by varying the discount rate at 1% intervals around the KIBOR base rate
Year-by-year valuation tables built to chart price convergence toward face value as maturity approaches


Key Findings


P03FRR100527 priced at a premium (PKR 5,248.26 vs. PKR 5,000 face value) since its coupon rate (15.85%) exceeds the market rate (11.24%)
BAFLTFC6 and KELSC6 both priced at modest discounts to face value, as their coupon rates sit slightly below the market rate
Bond price and market interest rate move inversely across all three instruments
Interest rate sensitivity scales with maturity: the 17.07-year BAFLTFC6 showed the largest price swings (up to ~17% from base) under the rate stress test, the 3.72-year KELSC6 showed moderate sensitivity (~6%), and the 1.18-year P03FRR100527 was nearly flat (~2%)
Higher credit ratings (AAA sovereign vs. AA+ corporate) are associated with lower required returns and, holding other factors constant, higher prices


Repository Contents


FM_Assignment_02.pdf — Full written report with methodology, calculations, graphs, and analysis across all five sections
FM_ASSIGN_2.xlsx — Excel workbook containing all underlying calculations, valuation tables, sensitivity tables, and charts


Tools Used

Microsoft Excel (bond valuation modeling, sensitivity tables, charting), PSX Debt Market data, KIBOR benchmark rates (Refinitiv)

Authors

Alizeh Imran · Jeremiah Huang · Muhammad Hamza · Moaz Ali Tamour
Submitted to: Ma'am Humaira Kousar — Financial Management

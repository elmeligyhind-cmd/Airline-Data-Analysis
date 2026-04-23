# Austrian Airlines: Booking Analytics & Insights Dashboard

> *Note:* I created this project for educational purposes to practice my data analysis skills. I am not affiliated with Austrian Airlines; I used a public dataset from Kaggle to show my process for cleaning, transforming, and visualizing data.

## 📊 Project Overview
This project transforms raw booking data (sourced from Kaggle) into a professional, multi-sheet interactive dashboard for *Austrian Airlines*. By analyzing the data, I was able to see where people get stuck when trying to book a flight and which types of passengers are the most frequent flyers.

## 🛠️ Tools & Techniques
* *Tool:* Microsoft Excel
* *Data Cleaning:* Removed 719 duplicates, used TRIM functions, and checked for missing values.
* *Data Transformation:* Used advanced formulas to group data by Lead Time, Passenger Groups, and Stay Duration.
* *Visualization:* Built an interactive dashboard using Pivot Tables, Slicers, and Dynamic Charts.

## 🔍 Custom Data Logic
To make the data easier to analyze, I created these categories:
* *Lead Time:* From "Last Minute" (0-7 days) to "Advanced" (180+ days).
* *Passenger Type:* Solo, Pair, or Group (3+).
* *Stay Length:* Short, Standard, and Long stays.

## 💡 Business Insights & Recommendations
* *Fix Mobile Checkout:* There is a huge 85% abandonment rate. Because Desktop bookings are 4% more successful than Mobile, the airline should fix technical or user-experience issues on mobile devices to stop losing those ~50,000 booking attempts.
* *Solo Traveler Comfort:* 63% of passengers are traveling alone, but only 30% pay to pick a seat. Since flights average 7.3 hours, the airline should market "extra space" or "solo-friendly" seating specifically to these solo travelers.
* *Promotional Timing:* Add-on services like extra baggage (67%) and meal requests (43%) are big revenue earners. These peak between 4 PM – 6 PM, so the airline should offer "last-minute" add-ons during this time to catch more buyers.
* *Smart Booking Strategies:* Booking is highest on Wednesdays and for short stays. The airline should use "Limited Time" urgency messages for short-stay travelers, but offer "Save for Later" options for people planning more complex, long-lead trips.
## 📁 Project Structure
* Austrian Airlines.xlsx: The main Excel workbook containing the raw data, cleaning steps, and the final interactive dashboard.
* Insights_Summary.png: A screenshot of the strategic findings for a quick overview.

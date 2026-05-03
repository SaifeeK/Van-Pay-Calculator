Van-Pay-Calculator

What It Does

Reads a dispatch screenshot and automatically calculates driver pay, broken down per vehicle. Upload or paste your screenshot and get an instant breakdown grouped by vehicle ID (e.g. DCT438, DCT442, DCT558).

Covers key data: vehicle ID, driver name, service type, vehicle pay, and gratuity. Calculates 40% driver pay per trip and adds gratuity on top. Groups all trips by vehicle with subtotals. Detects the report date from the image. Exports a downloadable report at the end. Works on desktop and mobile.

Who It's For

Designed for dispatchers and drivers who need a quick, accurate pay breakdown from a dispatch report without manually doing the math.

How To Use

Option 1: Live site

Visit: https://saifeek.github.io/Van-Pay-Calculator/

Option 2: Run locally

Download van_pay_calculator.html

Double-click to open in any browser. No installation needed.

How The Calculation Works

Driver Payout = (Vehicle Pay × 40%) + Gratuity

This is applied to each trip row, then summed per vehicle.

Tech Stack

Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step. Uses the Anthropic API (Claude) to read and extract data from the screenshot image.

Disclaimer

Pay calculations are based on data extracted from the uploaded image. Always verify results against your official dispatch records. This tool is for reference only and should not replace your official payroll process.

# Budget Sheet – Interval-Based Income & Expense Calculator

A simple, responsive web tool for calculating how your income or expenses break down across different time intervals. Easily handle irregular payment periods (daily, weekly, monthly, quarterly, annually, etc.) and export results to Excel.

## Features

- Add unlimited rows of incomes or expenses
- Automatic interval calculations:
  - Daily  
  - Weekly  
  - Biweekly  
  - Monthly  
  - Quarterly  
  - Semi-annually  
  - Annually
- Excel export using `xlsx`
- Color theme presets + custom theme editor
- Mobile-responsive layout (switch between input & results)
- Row deletion controls
- Clean UI with soft shadow cards
- 100% client-side (no backend)

## How It Works

1. Enter an item name, amount, and frequency  
2. The script automatically calculates all intervals  
3. The totals row updates automatically  
4. Export everything to Excel at any time  

## Theme System

The app's visual is inspired by GitHub's interface and includes a modular **Preset Theme** class that supports:

- Header color  
- Primary & secondary background colors  
- Font color  
- Positive/negative color highlights  

Included themes:

- Default  
- Black & White  
- Blue  
- Yellow  
- Green  
- Purple  
- Red  
- Windows DOS  

## Excel Export

The tool uses SheetJS (`xlsx`) via CDN:

## Responsive Design

- Side-by-side layout for desktop and landscape devices
- Toggle table view from input to resultson mobile and smaller screens

## Technologies Used
- HTML5
- CSS3
- Vanilla Javascript
- SheetJS / XLSX.js for xlsx exports

## Future Improvements
- Draggable Rows (vertically)
- Button to toggle income/expense
- Excel import
- Show names on results table



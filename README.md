# empower-csv
This project is for Rustacean to process csv file.
## Features
- Import csv file(Writing)
    - This application can import csv file to sqlite.
- View tables(Unwritten)
    - You can view the tables what you imported by csv.
- Use plugins(Unwritten)
    - We are ready to use plugin what you made. You can process the table imported by csv as you wish.
- Export csv file(Unwritten)
    - This application can export csv file from sqlite.
## Roadmap
```mermaid
flowchart LR
    importCsvFile[Import csv file] --> exportCsvFile[Export csv file]
    exportCsvFile --> viewTables[View tables]
    viewTables --> usePlugins[Use plugins]
```
# Flight-Data
Centralized storage of flight records and data.
## Usage
1. Create a new directory on the first of the year.
2. Data from launches for that year are stored in directories in the year directory
3. Each launch, create a directory in the appropriate year with a name in the following format: `YYYY-MM-DD.<SITEORG>.<SITENAME>`.
4. To each uploaded file, append an `_` the fliers name in all caps, followed by a `_` and the rockets name.
Example:
> `2024-03-16-serial-11016-flight-0001_<NAME>_<ROCKETNAME>.eeprom`
## Filetypes
### Altus Metrum
Upload just the `.eeprom` file. The KMls and CSVs can be generated from these and should not be uploaded.

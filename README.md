# Ruby Data Analysis Scripts

This repository contains two Ruby scripts for practicing array and hash manipulations with real-world data examples.

## 📂 Files Overview

### 1. `journalist.rb`
- **Purpose**: Manipulate an array of journalist Twitter handles and answer various questions.
- **Key Skills**:
  - Counting elements (`Array#size`)
  - Finding minimum and maximum (`min_by`, `max_by`)
  - Filtering (`select`, `count`) and pattern matching (`Regexp`)
  - Sorting (`sort`, `sort_by`)
  - Hash building and distribution counts
- **Operations Performed**:
  1. Total number of handles
  2. Shortest handle (excluding `@`)
  3. Number of handles with exactly 5 characters
  4. Number of handles starting with an uppercase letter
  5. Alphabetical sort of handles
  6. Sort by handle length
  7. Index of a specific handle (`@epenser`)
  8. Distribution of handles by length
- **How to Run**:
  ```bash
  ruby journalist.rb
  ```

### 2. `cryptocurrencies.rb`
- **Purpose**: Combine two arrays (`currencies` and `prices`) into a hash and perform basic analyses.
- **Key Skills**:
  - Building a hash from parallel arrays with a `while` loop
  - Converting string prices to numeric (`String#to_f`)
  - Hash methods (`values`, `select`, `max`, `min`)
  - Filtering based on numeric thresholds
- **Operations Performed**:
  1. Build `crypto_hash` mapping each currency to its price as a `Float`.
  2. Identify the highest and lowest priced cryptocurrencies.
  3. List currencies priced below $6,000.
  4. Find the most expensive currency among those below $6,000.
- **How to Run**:
  ```bash
  ruby cryptocurrencies.rb
  ```

Happy coding and data exploration with Ruby! 🚀


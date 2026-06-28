# Telemetry-Data-Converter

## Overview



This repository contains my solution for the **Forage Software Engineering Virtual Experience** telemetry data conversion task.



The objective of this project is to convert two different industrial IoT telemetry message formats into a single unified JSON format. The solution is implemented in Python and includes automated unit tests to verify the correctness of the conversion logic.



---



## Project Objective



Manufacturing devices send telemetry data in two different JSON formats. The task is to:



* Read telemetry messages from both formats.

* Convert them into a common standardized structure.

* Ensure the converted output matches the expected result.

* Validate the implementation using automated unit tests.



---



## Project Structure



```

.

├── main.py

├── data-1.json

├── data-2.json

├── data-result.json

└── README.md

```



### Files


* **main.py** – Contains the conversion logic and unit tests.

* **data-1.json** – Sample telemetry message in Format 1.

* **data-2.json** – Sample telemetry message in Format 2.

* **data-result.json** – Expected unified output format.


---

## Features



* Converts telemetry data from two different JSON formats.

* Parses location information into a structured object.

* Converts ISO 8601 timestamps into Unix timestamps (milliseconds).

* Produces a consistent unified JSON structure.

* Includes automated unit testing using Python's `unittest` module.



---



## Technologies Used



* Python 3

* JSON

* datetime

* unittest

---


## How to Run



Clone the repository:



```bash

git clone https://github.com/ShumaizaJabeenKanwal/Forage-Telemetry-Solution.git

```



Move into the project directory:

```bash

cd Forage-Telemetry-Solution

```

Run the program:



```bash

python main.py

```

If everything is correct, the output will be similar to:



```

...

----------------------------------------------------------------------

Ran 3 tests in 0.00s

OK

```
---

## Learning Outcomes

Through this project, I gained practical experience in:


* JSON data processing

* Data transformation

* Python dictionaries

* Timestamp conversion

* Writing clean and maintainable code

* Unit testing with Python

---
## Acknowledgements

This project was completed as part of a **Forage Software Engineering Virtual Experience**. The simulation provides hands-on practice with real-world software engineering tasks involving telemetry data transformation and automated testing.

---

## Author

**Shumaiza Jabeen Kanwal**


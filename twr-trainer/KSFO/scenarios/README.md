# SFO Aircraft Files

## Combined Files

| **Filename**  | **Configuration** | **Difficulty** | **# Departures** | **# Arrivals** | **Description**                                                               |
| ------------- | ----------------- | -------------- | ---------------- | -------------- | ----------------------------------------------------------------------------- |
| `KSFO-BASE`   | N/A               | N/A            | 1                | 0              | File with 1 aircraft, to be used for creating new files using `add`           |
| `KSFO-VFR-M1` | Land 28/Depart 01 | Hard           | 0                | 5              | Short VFR file with variety of traffic, hard when combined with other traffic |
| `KSFO-VFR-M2` | Land 28/Depart 01 | Medium         | 0                | 5              | 20 minute VFR file, goes well with a heavy IFR file                           |

## Arrival Files

| **Filename**          | **Configuration** | **Difficulty** | **# IFR** | **# VFR** | **Description**                                                                                                 |
| --------------------- | ----------------- | -------------- | --------- | --------- | --------------------------------------------------------------------------------------------------------------- |
| `KSFO-L28D01-H-1-ARR` | Land 28/Depart 01 | Very Hard      | 40        | 0         | Complex approach traffic that is some perfect pairs mixed together with a few deals and inconsistent separation |

## Departure Files

| **Filename**         | **Configuration** | **Difficulty** | **# IFR** | **# VFR** | **Description**                                                                                           |
| -------------------- | ----------------- | -------------- | --------- | --------- | --------------------------------------------------------------------------------------------------------- |
| `KSFO-L28D01-H1-DEP` | Land 28/Depart 01 | Hard           | 34        | 6         | Mostly balanced traffic holding short of every runway and the west end                                    |
| `KSFO-L28D01-H2-DEP` | Land 28/Depart 01 | Very Hard      | 39        | 4         | Unbalanced traffic to simulate event; recommended with 15 MIT to LAX/SAN, non-LAX/SAN SSTIKs routed to 1R |

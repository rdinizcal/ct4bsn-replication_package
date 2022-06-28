## How to generate a set of test cases for the BSN in ACTS? 

These instructions should guide you to load the body sensor network file configuration file in ACTS, configure, and generate a new set of test cases.

### Dependencies:
- [ACTS 3.2](https://csrc.nist.rip/groups/SNS/acts/documents/comparison-report.html#acts)

### Step-by-Step

1. Open ACTS 3.2
2. System >> Open... BSN_configs.xml
3. Operations >> Build...
4. Configure the parameters
    * Algorithm = IPOG (Recommended)
    * Strength = t (t=2)
    * Mode = Scretch
    * Constant Handling = Forbidden Tuples 
    * Select Randomized DontCare Values
5. Build
6. Operations >> Export...
7. Repeat 4 for t=3 and t=4
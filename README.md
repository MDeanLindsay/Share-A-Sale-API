<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Share A Sale Auditing</h3>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

In Share-A-Sale, we had a custom commission set to reward 30% if a new customer was referred from an affiliate marketer.
We saw a substantial difference in new customers from affiliate marketers, compared to other DTC channels, so I began to investigate.

Findings showed that a referral would be flagged as no cookie value was initially present, even if a customer checked out using their account.
This additional check alone, found savings of $42,000/year.

Since then, the bonus commission program has now been deprecated, but we have implemented additional checks that have found otherwise overlooked savings.
We now run checks on commisson percentage errors, remove ineligible items from the subtotal that calculates a commision's percentage, and void orders that have been canceled for various reasons.


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Make sure you have venv installed.

* venv
  ```py
  pip install venv
  ```

### Installation

1. Get an API Key from Share A Sale in the Merchant API center. [https://shareasale.com](https://shareasale.com)
2. Clone the repo
   ```sh
   git clone https://github.com/MDeanLindsay/Share-A-Sale.git
   ```
3. Create virtual enviornment.
   ```sh
   python -m venv .venv
   ```
4. Install requirements.
   ```py
   pip install -requirements.txt
   ```
4. Initiate venv.
   ```sh
   .\.venv\Scripts\activate
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
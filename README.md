# A/B Testing for Conversion Rate Optimization

## Project Overview
This project focuses on utilizing A/B testing to enhance the conversion rate of a website. A/B testing, also known as split testing, is a method of comparing two versions of a webpage or app against each other to determine which one performs better. Our dataset simulates the result of an A/B test conducted on two variants of a webpage's call-to-action (CTA) button, aiming to determine the most effective strategy for increasing user conversions.

The key variables in this test are:
- **Variant:** The version of the webpage. Variant A features the CTA button labeled "Sign Up Now!", while Variant B features the CTA button labeled "Get Started for Free!".
- **Conversion:** Whether a visitor made a conversion (1) or not (0).

Through statistical analysis, we aim to ascertain whether the different wording of the CTA button in Variant B leads to a higher conversion rate than the wording used in Variant A.

## Dataset
The dataset contains results from 2,000 users split evenly between the two variants, A and B, with each row representing whether a user converted or not after visiting the webpage.

## Analysis
The analysis involves:
- Calculating conversion rates for each variant.
- Performing a two-proportion z-test to evaluate the statistical significance of the observed differences in conversion rates.
- Interpreting the p-value to make informed decisions about the effectiveness of the two variants.

## Results
Our statistical analysis indicates a significant difference in conversion rates between Variant A and Variant B, suggesting that the change in wording to "Get Started for Free!" for Variant B positively impacts user conversions.

## Conclusion
This project underscores the importance of A/B testing in making data-driven decisions for website optimization. By analyzing the conversion rates of different webpage variants, we can identify and implement more effective strategies for enhancing user engagement and conversion.

## How to Use This Repository
- **Clone the repository:** Get a local copy of the repository to access the dataset and analysis scripts.
- **Explore the dataset:** The `ab_test_dataset.csv` file contains the raw data used for A/B testing.
- **Review the analysis:** Understand the statistical methods used to compare the performance of the two variants.

## Contributing
Feel free to fork this repository or submit pull requests to contribute to the project's improvement.

## License
This project is open-sourced under the MIT license.

# A/B Test Analysis Tool
This application performs standard conversion rate test calculations and generates a number of outputs:
- Conversion rate difference 
- Statistical significance
- Confidence interval of difference
- Confidence intervals of conversion rates
- Potential 6 month revenue impact based on confidence interval of difference

## Customize it
You can enter custom labels and colors and even screen shots of test variants to brand the outputs for sharing.
Note: there is an opacity applied to the custom colors.

See the live version here: https://sdidev.shinyapps.io/ABTestAnalysis/

## Version History
#### 2.1 - 5/24/21
- Added support for continuous metrics
- Added body width constraints to improve chart presentation on large screens
- Added some additional commenting in the code
- Removed the pagination structure which created the fake link in the nav
- Adjusted pdf export to exclude footnotes
#### 2.0 - 5/13/21
- Laying groundwork for adding support for continuous metrics. Nothing visible so far. But working behind scenes.
- Fixed some display issues with the navigation, tightened up, cleaned up CSS
- Fixed scaling issue in conversion rate confidence interval chart which didn't allow charts to scale when uneven sampling was occuring
#### 1.6 - 5/4/21
- Changed confidence interval percentage to significance threshold and clarified that would also be used to calculate confidence intervals
- Used significance threshold to determine test outcome (significant or inconclusive)
#### 1.5 - 2/25/21
- Fixed pvalue calculations for 2-tail tests with small effects
- Updated bookmarking to exclude hypothesis so that long hypotheses won't break links
- Updated navigation bar 
#### 1.4 - 2/22/21
- Added link to navbar logo
- Added linking capability (URL contains current app configuration less images)
#### 1.3 - 2/21/21
- Added export to pdf feature
- Optimizations for load time (delayed plot rendering until after load)
- Added links to other SDI experimentation tools (reformatted navbar in process)
- Minor code restructuring
#### 1.2 - 2/20/21
- Added hypothesis input
- Added screen shot inputs for test variations along with placeholder images
- Rearranged input containers a bit
- Staged for future additions of continuous metrics and pdf export functionality
#### 1.1 - 1/29/21
- Added version number at bottom
- Updated link text to github to find version history here

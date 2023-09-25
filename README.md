# AB-Testing-in-Python
A/B testing is a method to compare two variations of a webpage, app, or campaign to identify which one yields better results, enabling data-driven optimizations.

## Dataset
The dataset used for this A/B testing analysis contains the following columns:

- `auction_id`: A unique identifier for each auction.
- `experiment`: Indicates whether the user was in the "control" or "exposed" group.
- `date`: The date of the experiment.
- `hour`: The hour of the experiment.
- `device_make`: The make of the user's device.
- `platform_os`: The operating system of the user's device.
- `browser`: The browser used by the user.
- `ad_success`: Indicates whether the ad was successful (1) or not (0).

## Results
The results of the A/B testing are as follows:

- **Ad Success Control Group**: 45.05%
- **Ad Success Exposed Group**: 46.88%

### Sample Size
- Number of observations needed by each group: 1565
- Number of total observations in the dataset: 1243

### Statistical Analysis
- The p-value of `ad_success` is 0.5185.
- The 95% Confidence Interval (CI) for `ad_success` in the control group is [0.4102, 0.4908].
- The 95% Confidence Interval (CI) for `ad_success` in the exposed group is [0.4306, 0.507].

These results provide insights into the performance of the ad campaign in both the control and exposed groups, with statistical analysis indicating whether any observed differences are statistically significant.

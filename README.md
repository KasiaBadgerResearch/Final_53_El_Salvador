# How has El Salvador’s control of corruption evolved between the lower and upper bounds of the 90% confidence interval from 1996 to 2022?

## Abstract

Using World Bank World Development Indicators (WDI) data, this study examines the evolution of control of corruption in El Salvador between 1996 and 2022. The analysis compares the lower and upper bounds of the 90% confidence interval, capturing long-term trends, convergence patterns, and fluctuations in governance quality. Over the period, both bounds exhibited significant volatility. At the start, the upper bound was roughly four times higher than the lower bound, but this gap gradually narrowed to about twice the lower bound by the end of the period. Both measures increased substantially until around 2010, with the lower bound rising more sharply than the upper bound. After 2010, both experienced notable declines, with the upper bound decreasing more steeply. Compared to 1996, the upper bound increased slightly overall, while the lower bound showed a more pronounced net increase. Overall, both series trace slight “upside-down U” patterns, reflecting periods of improvement followed by decline in control of corruption.

## 1. Question

How has El Salvador’s control of corruption evolved between the lower and upper bounds of the 90% confidence interval from 1996 to 2022?

- **Lower bound proxy**: Control of Corruption: Percentile Rank, Lower Bound of 90% Confidence Interval
- **Upper bound proxy**: Control of Corruption: Percentile Rank, Upper Bound of 90% Confidence Interval

## 2. Data

- **Source**: World Bank World Development Indicators (WDI)
- **Indicators**:
  - Control of Corruption: Percentile Rank, Lower Bound of 90% Confidence Interval
  - Control of Corruption: Percentile Rank, Upper Bound of 90% Confidence Interval
- **Coverage**: El Salvador, 1996–2022
- **Notes**: National-level data only

## 3. Method

1. Filtered the dataset for El Salvador and selected the lower and upper bound control of corruption indicators.
2. **Extracted relevant columns**: Year, Indicator Name, and Value.
3. Pivoted the dataset to create a side-by-side chronological comparison of the lower and upper bounds.
4. Produced a dual-line time series plot to visualize trends, convergence, and periods of improvement or decline over time.

(Analysis is descriptive; no causal inference applied.)

## 4. Results

- **Lower bound of control of corruption**: Increased substantially from 1996 to 2010, peaking around 2010, then decreased somewhat through 2022. Overall, the net increase since 1996 remained significant.
- **Upper bound of control of corruption**: Also increased until around 2010, though less sharply than the lower bound, and declined more steeply after 2010. The net increase compared to 1996 was slight.
- **Comparison**: At the beginning of the period, the upper bound was roughly four times the lower bound; by 2022, the two bounds had converged to about twice the lower bound. Both series trace slight upside-down U-shaped patterns (“frowns”) over time, indicating periods of improvement followed by declines.

(Figure 1. El Salvador: Control of Corruption, Lower vs. Upper Bound of 90% Confidence Interval, 1996–2022)

(Table 1. Pivoted dataset summary)

## 5. Interpretation

- The initial large gap between upper and lower bounds indicates substantial uncertainty in the level of control of corruption in 1996.
- Convergence over time suggests increasing precision in governance assessments and potential institutional improvements.
- The pre-2010 rise in both bounds reflects progress in anti-corruption measures or governance structures.
- The post-2010 decline, particularly in the upper bound, may signal governance challenges, policy setbacks, or socio-political instability affecting control of corruption.
- Overall, the trajectory highlights fluctuations in institutional quality and the need for sustained anti-corruption efforts to ensure durable governance improvements.

## 6. Limitations

- National aggregates may obscure regional, municipal, or sector-specific corruption dynamics.
- WDI estimates incorporate modeled data, especially for earlier years, introducing uncertainty.
- The descriptive analysis does not identify causal factors behind improvements or declines in control of corruption.

## 7. Next Steps / Extensions

- Examine correlations between control of corruption trends and political transitions, economic growth, or institutional reforms.
- Compare El Salvador’s trajectories with other Central American countries to contextualize governance trends regionally.
- Investigate post-2022 developments to assess whether declines reversed or persisted.
- Explore sector-specific indicators to understand which areas of governance contributed most to changes in corruption control.

# Neptune Selatan Oilfield Dashboard

## Overview

This Power BI dashboard provides a comprehensive analysis of the Neptune Selatan oilfield production performance, comparing natural depletion versus waterflood recovery scenarios. The dashboard tracks key production metrics, reservoir performance, and well-level analytics to support operational decision-making.

## Key Performance Indicators

### Current Production Metrics
- **Cumulative Oil Production**: 252.56K sm³
- **Cumulative Gas Production**: 20.09K sm³
- **Cumulative Water Production**: 146.87K sm³
- **Current Watercut**: 40.68%

## Dashboard Structure

1. **Page 1**: Overview metrics and production comparison
   <img width="1490" height="854" alt="image" src="https://github.com/user-attachments/assets/e0fd6548-2b3d-443d-8dc2-823256e6c725" />

2. **Page 2**: Recovery analysis and watercut monitoring
   <img width="1481" height="838" alt="image" src="https://github.com/user-attachments/assets/d4d3c301-5991-4948-ba45-b19eab7e6ecf" />

3. **Page 3**: Injection operations and well performance details
   <img width="1479" height="833" alt="image" src="https://github.com/user-attachments/assets/4107bf7f-06f7-4098-b77f-644636a1a0db" />

5. **Page 4**: Well performance analysis
   <img width="1473" height="843" alt="image" src="https://github.com/user-attachments/assets/c5c6be8c-b86f-4adb-ab56-283e3c2b6eae" />

## Dashboard Components

### 1. Production Comparison Analysis

#### Total Oil Production Comparison
Tracks oil production rates over time (2026-2042) comparing:
- **Natural Depletion Case**: Production under primary recovery
- **Waterflood Case**: Production with enhanced water injection

**Key Insight**: The dashboard shows production trends spanning nearly two decades, enabling long-term planning and strategy evaluation.

#### Cumulative Oil Production
Monitors the accumulation of oil production over the field's life, providing insights into:
- Ultimate recovery potential
- Production acceleration/decline trends
- Comparison between recovery methods

### 2. Reservoir Management

#### Reservoir Pressure Decline
Visualizes average reservoir pressure trends (200-250 psi range) across both scenarios:
- Tracks pressure maintenance effectiveness
- Identifies pressure support requirements
- Compares depletion strategies

### 3. Recovery Analysis

#### Natural Depletion Recovery
- **Base Case Oil**: 138.81K sm³
- **Recovery Factor**: 252.56%

#### Waterflood Recovery Performance
- **Waterflood Oil**: 113.75K sm³
- **Incremental Oil Recovery**: -25.05K sm³
- **Recovery Improvement**: -18.05%

**Critical Finding**: The waterflood scenario shows negative incremental recovery compared to natural depletion, suggesting:
- Potential waterflood design optimization needed
- Review of injection strategy required
- Possible geological constraints affecting waterflood efficiency

### 4. Watercut Monitoring

**Watercut Over Time**: Tracks water production percentage from 2026-2042
- Monitors reservoir water breakthrough
- Compares water handling between scenarios
- Identifies water management challenges

### 5. Injection Operations

#### Production vs Injection
Dual-axis chart tracking:
- **Total Oil Production**: 0K-25K sm³/day range
- **Total Water Injected**: 70K-100K sm³/day range

#### Voidage Replacement Ratio (VRR)
- Monitors injection efficiency (0-140% range)
- Ensures proper reservoir pressure support
- Tracks injection-production balance

### 6. Well Performance Analytics

#### Well Performance Ranking

| Well Name | Cumulative Oil (sm³) | Avg Well Oil Rate (sm³/day) | Watercut (%) |
|-----------|---------------------|----------------------------|--------------|
| PRO-5     | 252,558.34          | 14,994.93                  | 40.68        |
| PRO-1     | 252,558.34          | 13,796.81                  | 40.68        |
| PRO-12    | 252,558.34          | 13,183.91                  | 40.68        |
| PRO-11    | 252,558.34          | 11,741.52                  | 40.68        |
| PRO-4     | 252,558.34          | 11,336.29                  | 40.68        |
| PRO-15    | 252,558.34          | 11,210.24                  | 40.68        |
| **Total** | **252,558.34**      | **12,710.62**              | **40.68**    |

**Top Performer**: PRO-5 with average oil rate of 14,995 sm³/day

#### Well Performance by Case
Compares individual well performance across natural depletion and waterflood scenarios, showing cumulative oil contributions ranging from 0K to 140K sm³.

### 7. Production Trends

**Sum of Oil Rate by Year**: Tracks total field oil production rate from 2026-2042
- Peak production appears in early field life
- Gradual decline trend over time
- Production range: 0K-30K sm³/day

### 8. Well Configuration Data

#### Production Wells (6 wells)
- **Well Diameter**: 0.15m
- **Depth Range**: Top depth ~2,364-2,378m, Bottom depth ~2,368-2,382m

#### Injection Wells (2 wells)
- **Well Diameter**: 0.20m
- **INJ-1**: Top 2,398.18m - Bottom 2,401.71m
- **INJ-2**: Top 2,375.66m - Bottom 2,379.75m

**Total Combined Depth**: Top 19,003.31m, Bottom 19,043.50m

## Key Insights & Recommendations

### Critical Findings

1. **Waterflood Underperformance**: The waterflood case shows 18% lower recovery than natural depletion
   - Recommend reviewing injection pattern and well placement
   - Consider water breakthrough mitigation strategies
   - Evaluate reservoir heterogeneity impact

2. **Uniform Watercut**: All wells show identical 40.68% watercut
   - Suggests consistent reservoir communication
   - May indicate need for water shutoff opportunities

3. **High Water Injection Volumes**: Water injection (70K-100K sm³/day) significantly exceeds oil production (0K-25K sm³/day)
   - Monitor voidage replacement efficiency
   - Optimize injection rates to minimize water cycling

### Recommendations

- **Optimize Waterflood Strategy**: Review injection well placement and rates
- **Well Intervention**: Focus on PRO-15, PRO-4 as lower performers for potential workover
- **Water Management**: Implement water shutoff in high watercut wells
- **Reservoir Simulation**: Update model with actual performance data
- **Economic Analysis**: Evaluate waterflood economics given negative incremental recovery

## Technical Specifications

- **Platform**: Microsoft Power BI Desktop
- **Data Period**: 2026-2042 (forecast/simulation)
- **Production Units**: sm³ (standard cubic meters)
- **Pressure Units**: psi
- **Time Granularity**: Daily, Monthly, Quarterly, Yearly

## Use Cases

- **Production Optimization**: Identify underperforming wells and optimization opportunities
- **Development Planning**: Compare recovery scenarios for investment decisions
- **Operations Monitoring**: Track daily production and injection performance
- **Reserves Management**: Monitor ultimate recovery and reserves booking
- **Stakeholder Reporting**: Executive-level KPI visualization

## Data Updates

The dashboard is designed to incorporate:
- Real-time production data
- Daily injection volumes
- Pressure monitoring
- Well test results
- Reservoir simulation updates

## Notes

- All production data appears to be forecasted/simulated based on 2026 start date
- Well performance metrics show identical cumulative oil values, suggesting these may be field totals rather than individual well contributions



**Version**: 1.0  
**Dashboard Type**: Production Analytics & Reservoir Management

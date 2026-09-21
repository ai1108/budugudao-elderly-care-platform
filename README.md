# 不孤島：高齡生活風險評估與分級照護決策平台

> 🚧 This is an ongoing senior capstone project (Soochow University, Department of Data Science). Modules are being added incrementally as the project progresses.

## About

《不孤島》is a GIS-based platform that assesses elderly life-risk and care-resource pressure at the district / village level, starting with Taipei City and New Taipei City (雙北市). The project combines open government GIS data, spatial accessibility indicators, and two scoring models to help identify areas where elderly residents may be underserved by daily-life, medical, and long-term care resources.

Core components (planned):

- **生活風險分數 (Life-Risk Score)** — a composite indicator combining daily-life accessibility, medical/long-term-care accessibility, and demographic risk factors
- **照護資源壓力分數 (Care-Resource Pressure Score)** — an indicator capturing the balance between elderly population density and available care resources in each area
- **GIS visualization platform** — presenting both scores at the district / village level to support policy and resource-allocation decisions

## Current contents

- `gis_data_pipeline/` — GIS spatial data collection and indicator-building pipeline (administrative boundaries, road networks, POIs, transit, medical/long-term-care facilities, accessibility metrics)

More modules (risk-scoring models, the visualization platform itself) will be added here as the project develops.

## Team

Team 20 (第二十組), Department of Data Science, Soochow University — advised by Prof. Mingying Lu (盧明瑩教授).

- 鍾嬡 (Audrey) — Team Lead
- 吳沂霈
- 吳書儀
- 陳欣筠
- 蘇子惠


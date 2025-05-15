The two datasets were part of a different project. I noticed a pattern. Could there be any correlation between the two?

# Greenspaces-Unemployment-Any-Relation-in-Greater-Manchester-?
This project analyses the spatial relationship between green spaces and unemployment rates among non-white populations (ages 16-49) in Greater Manchester, UK. The analysis explores potential environmental justice issues by examining whether areas with higher unemployment rates among ethnic minorities have less access to green spaces.

# See the 'Code_Greenspace_&_Unemployment_(non_white)_in_Greater_Manchester'.

# 🗃️ Data Sources

Greater Manchester boundary and administrative area shapefiles: https://geoportal.statistics.gov.uk/

UK green spaces geospatial data: http://os.uk/opendata/licence

Unemployment statistics for Greater Manchester, with a focus on non-white populations aged 16-49 (excluding students): https://www.ons.gov.uk/employmentandlabourmarket/peoplenotinwork/unemployment

# 🎯 Aim
To investigate whether there's a correlation between the distribution of green spaces and unemployment rates among non-white populations in Greater Manchester, potentially identifying environmental justice issues in urban planning.

# 🔍 Methodology

Imported and processed geospatial data for Greater Manchester boundaries.

Identified green spaces within Greater Manchester using spatial joins.

Merged unemployment data with administrative area boundaries.

Created visualisations to compare green space distribution with unemployment patterns.

Visually analysed potential correlations between these variables.

# 💡 Conclusions
The analysis shows a slight link between higher unemployment and lower green space density in specific areas (the city centre and northeast). However, the overall distribution of green spaces appears fairly even across the region, suggesting that environmental justice issues related to green space access are not widespread in Greater Manchester.

# 🔮 Future Work

Perform hotspot analysis using Getis-Ord Gi* statistics to identify significant clusters of green spaces. **(Will be done within the next few weeks)**

Convert point data to accessibility metrics (e.g., distance to nearest green space, green space area within walking distance).

**Include additional socioeconomic variables to build a more comprehensive model.**

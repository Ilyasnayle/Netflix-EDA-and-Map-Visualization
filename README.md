
## Netflix-EDA-and-Map-Visualization

This notebook serves to distinguish between two distinct libraries and showcase their practical application.

Specifically, it leverages the Netflix dataset to create compelling visualizations on a map using the Plotly and Folium libraries.

Enjoy! 🙂

---------------------------------------------------------------------------------------------------------------
### Libraries used in this notebook.
- import pandas as pd
- import numpy as np
- import matplotlib.cm as cm
- import matplotlib.pyplot as plt
- import seaborn as sns
- import folium
- from folium.plugins import MarkerCluster
- import plotly.express as px
- import plotly.graph_objects as go
- from plotly.subplots import make_subplots

---------------------------------------------------------------------------------------------------------------

### Both Plotly and Folium offer distinct advantages and drawbacks.

**Plotly**

- Pros:

1. Provides a wide array of chart types suitable for diverse data visualization needs.
2. Offers extensive documentation and active community support.
3. Known for its user-friendly interface.

- Cons

1. Mapping capabilities are somewhat limited.
2. Customizing maps extensively or incorporating advanced geographical features may be challenging.

**Folium**

- Pros:

1. Praised for its advanced mapping functionalities.
2. Allows users to create interactive and highly customizable maps effortlessly.
2. Offers features like choropleth maps and customizable overlays for unparalleled flexibility in geographic data visualization.

- Cons:

1. Has a steeper learning curve compared to Plotly.
2. Primarily focuses on geographic visualizations, offering fewer options for non-geographic charts.

   

#### In summary, Plotly is lauded for its ease of use and diverse charting options, making it suitable for a wide range of visualization tasks. Conversely, Folium stands out for its advanced map features but may require a more significant learning investment, particularly for users seeking non-geographic visualizations.

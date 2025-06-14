# K-Means Clustering of Whiskey Taste Profiles – R

<p><strong>Applied k-means clustering to segment 86 whiskies based on 12 taste indicators.</strong></p>
<ul>
  <li>Used <code>whiskies.csv</code> with ratings (0–4) on Body, Sweetness, Smoky, etc.</li>
  <li>Plotted WSS for k = 2–20 and selected k = 3 based on the elbow method.</li>
  <li>Visualized clusters using PCA (fviz_cluster), showing clear group separation on PC1 and PC2.</li>
  <li>Identified cluster taste profiles:
    <ul>
      <li><strong>Cluster 1:</strong> Bold – high in Body, Smoky, Medicinal, Tobacco.</li>
      <li><strong>Cluster 2:</strong> Light – more Floral, Fruity, Sweet.</li>
      <li><strong>Cluster 3:</strong> Balanced – moderate Spicy and Winey notes.</li>
    </ul>
  </li>
  <li>Recommended Cluster 1 for fans of strong, smoky whiskies.</li>
</ul>


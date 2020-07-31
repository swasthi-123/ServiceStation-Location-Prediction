# ServiceStation-Location-Prediction

This is a project to decide a location in JohannesBerg,South Africa for establishing a service station such that it covers as many taxi stands as possible.I used Kmeans clustering for grouping the taxi stands so that I will get braod estimate of where to establish the service center. I visualized the grouping of the clusters using folium module.
I used HDBSCAN for more precise results and outliers of HDBSCAN are grouped using Kmeans clustering for better and stable clustering.

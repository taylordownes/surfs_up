# surfs_up
## Oveview
The purpose of this mock analysis was to help W. Avy determine if opening a surf and ice cream shop in Oahu Hawaii would be sustainable year round. We used SQLite, SQLAlchemy and Flask to query and showcase the data provided. Our analysis consisted of the following deliverables:
- Determine the summary statistics for June
- Determine the summary statistics for December

### Resources
- Data: hawaii.sqlite
- File: SurfsUp_Challenge

## Results
- June Temperatures
    - To determine the summary statistics for June, we wrote a query that filters the measurement table to retrieve temperatures for June, converted the June temperatures to a list and created a DataFrame from the list. The results are shown below:
    - ![image](https://user-images.githubusercontent.com/84201614/129031599-70e8b394-7a08-42d3-88a2-10b72beaa303.png)

- December Temperatures
    - To determine the summary statistics for December, we followed the same steps for June and got the following results:
    - ![image](https://user-images.githubusercontent.com/84201614/129031824-50de4422-2266-4fb4-8577-177213665452.png)



## Summary
Based on our results, the surf and ice cream shop has a good shot at maintaining business year round. June temperatures have an average of 75 degrees and minimum of 64 degrees and December has an average of 71 degrees and minimum of 56 degrees. This shows that while people may want to surf and eat ice cream more in the summer, winter temperatures are also suiting for a surf and ice cream shop in Oahu. While temperatures are an important part of the analysis, it would also be beneficial to take location, customer preferences, and more into consideration before opening the surf and ice cream shop.

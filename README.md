# House-Price-Prediction
The data file “House.csv” contains information on the sale of 76 single-family
homes in Dublin during 2005. We will model single-family home sale price
by (Price in excel file = Price the house sold for in thousands of eur
1000 ), which
range from 155.5 (e155, 500) to 450.0 (e450, 000), using these predictor variables:
Size floor size (thousands of square feet)
Lot lot size category (from 1 to 11 explained below)
Bath number of bathrooms (with half-bathrooms counting as 0.1 explained
below)
Bed number of bedrooms (between 2 and 6)
Year year the house was built.
Garage garage size (0, 1, 2, or 3 cars)
High indicator for The High School (reference: The High School)
Alexandra indicator for Alexandra College (reference: Alexandra College)
Stratford indicator for Stratford College (reference: Stratford College)
St.Mary’s indicator for St.Mary’s College (reference: St.Mary’s College)
St Louis indicator for St Louis High School (reference: St Louis High School)
It seems reasonable to expect that homes built on properties with a large amount
of land area command higher sale prices than homes with less land, all else being
equal. However, an increase in land area of (say) 2000 square feet from 4000 to
6000 should probably make a larger difference (to sale price) than going from
24,000 to 26,000. Thus, realtors have constructed lot size “categories,” which in
their experience correspond to approximately equal-sized increases in sale price.

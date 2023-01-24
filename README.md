# This a research of the constant up and down movment of gas prices over the years.

fig, ax = plt.subplots(figsize= (10,5))
sns.scatterplot(data= df, x= 'Date', y= 'Petrol (USD)')
ax.set(title= 'The ups and downs of gas prices over time')


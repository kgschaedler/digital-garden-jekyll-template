Python often used often forgotten
==========

Plotting
-------

fig, ax = plt.subplots(m,n)
ax = ax.ravel()

Histograms
----------
plt.hist(x, density=True, bins=30)  # density=False would make counts
plt.ylabel('Probability')
plt.xlabel('Data')

Strings + formatting
------------

"{:.2f}".format(13.949999999999999) --> 13.95


Dictionaries
---------

Add an element: thisdict.update({"color": "red"})

Access element by key: print(d['key1']) --> # val1
By Kiran Gite and Shane Weisberg, for MIT 6.859 Interactive Data Visualization, Spring 2021.

Credits
Venmo Transaction Dataset. Dan Salmon, June 2019, https://github.com/sa7mon/venmo-data . Accessed Spring 2021. Dataset.

Public by Default. Hang Do Thi Duc, 2018, https://publicbydefault.fyi/ and https://22-8miles.com/public-by-default/ . Inspired us to show how much personal information is available through Venmo through data visualization.

JavaScript packages that helped to build the site:
grapheme-splitter by orling

vanilla-javascript-emoji-picker by woody180 and RahulChand028

Abstract
We present our final project for 6.859, Interactive Data Visualization, for Spring 2021: Build-your-own Venmo Transaction Network.
We use data scraped from Venmo's public API to construct a network of historical transactions that users of our visualization may construct from the bottom up. 
We hope users will enjoy exploring this network and pause to think about data privacy and the state of their personal data on Venmo and similar platforms. 
The visualization can be found at https://6859-sp21.github.io/final-project-byo_venmo_transaction_network/
Our paper can be found at https://github.com/6859-sp21/final-project-byo_venmo_transaction_network/blob/main/final/Gite_Weisberg_final_paper.pdf

Work Distribution
The workload was evenly distributed between Kiran and Shane, who is [very uncomfortably] writing this blurb in the third person.
Shane and Kiran both worked on all parts of the visualization. Shane set up the infrastructure for the network, Kiran added the filtering functionality, Shane then tweaked that to be able to refilter on clicks.
Kiran made both line graphs, Shane made the bar graph and the emoji bar graph that Kiran repurposed into a much more fun bubble graph. Also we both did more stuff that I'm forgetting right now. Oh also data processing was split evenly.
Anyway, this was a team effort.

Project Process
This was a much smoother and easier process than A4. Thank goodness. 
That experience allowed us to spend a lot less time struggling to implement basic things and instead spend that time adding cool functionality like the click filtering and emoji analytics.
We did a better job of coding smartly (way fewer magic numbers!) and setting ourselves up to succeed by allocating space ahead of time. 
We both feel much more comfortable in D3 than when we started the process.
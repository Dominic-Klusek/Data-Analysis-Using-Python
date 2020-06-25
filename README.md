# Data-Analysis-Using-Python
Project from my CSC 732: Pattern Recognition and Neural Networks class for the Spring 2020 term at CUNY College of Staten Island; which centered around performing dataset analysis and visualization utilizing Matplotlib and Seaborn. The main goal was to learn the importance of dataset analysis to identify dataset parameters, and be able to effectively create insightful visualizations from which conclusions can be drawn.

<h1>Dataset Used:</h1>
<h2>Ionosphere</h2>
<p>Link: https://archive.ics.uci.edu/ml/datasets/Ionosphere</p>
<p>This radar data was collected by a system in Goose Bay, Labrador. This system consists of a phased array of 16 high-frequency antennas with a total transmitted power on the order of 6.4 kilowatts. See the paper for more details. The targets were free electrons in the ionosphere. "Good" radar returns are those showing evidence of some type of structure in the ionosphere. "Bad" returns are those that do not; their signals pass through the ionosphere.</p>
<p>Received signals were processed using an autocorrelation function whose arguments are the time of a pulse and the pulse number. There were 17 pulse numbers for the Goose Bay system. Instances in this databse are described by 2 attributes per pulse number, corresponding to the complex values returned by the function resulting from the complex electromagnetic signal.</p>

<h3>Attribute Information</h3>
    <ul>
        <li>There are 34 numeric (float values) attributes, all with values between -1.0 to 1.0, and are reading of the pulse numbers for the Goose Bay System</li>
        <li>The dataset contains 2 class 'g' for Good and 'b' for Bad</li>
        <li>The number of instances in each class are 'b' : 126
'g' : 225</li>
    Authors of the dataset was captured using the same setup of a phased array of 16 high-frequency antennas with a total transmitted power on the order of 6.4 kilowatts.
    </ul>

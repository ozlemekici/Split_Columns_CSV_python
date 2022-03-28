# Split columns in CSV file

We have a CSV file with a somewhat mixed dataset. The data in this set is correct in the first column, but all the rest of the data is in **" "** in the second column and this information is given as **VariableName = Variable**.
</br>

As an example I would say the file looks like this:
<pre><code>123     A=2,B=asdjhf,C=jhdkfhskdf,D=1254
54878754    A=45786,D=asgfd,C=1234
</code></pre>
</br>

A dynamic algorithm has been developed to separate the data in the second column and make this CSV file neat. Here is an example of how we want the output to look:
<pre><code>var1          var2         var3         var4
ZAMffFIA19     10           2         /a/n/asjhhvnfjknited...
VINMUfgvL18    25           1         /r/u/rsnnvkjbvkjn_mulle...
</code></pre>
</br>

At this stage, three ipynb files will draw your attention. In **"test_1.ipynb"**, you will see the first versions of the algorithm that has started to be developed. 
</br>

In **"test_2.ipynb"** you can see another algorithm based on the first algorithm. This algorithm was developed specifically for a single CSV file. This code developed for the loaded dataset gives an error or does not work in any change made in the CSV.
</br>

The algorithm in the recently developed **"main.ipynb"** is the final version of the code and works properly even with any change in the CSV.



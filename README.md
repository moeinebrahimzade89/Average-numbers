<h1>Average Numbers</h1>
<p>A simple Python program that receives integer inputs from the user and calculates their average until <code>0</code> is entered.</p>

<h2>Technologies Used</h2>
<ul>
  <li>Python 3</li>
  <li>Built-in <code>input()</code> function</li>
  <li>Built-in <code>print()</code> function</li>
  <li><code>while</code> loop and basic arithmetic operations</li>
</ul>

<h2>Features</h2>
<ul>
  <li>📥 Accepts multiple integer inputs from the user</li>
  <li>🔁 Uses a loop to continue receiving numbers</li>
  <li>🛑 Stops input when the user enters <code>0</code></li>
  <li>➕ Calculates the sum of entered numbers</li>
  <li>📊 Computes and prints the average of the entered values</li>
  <li>⚡ Simple and beginner-friendly Python logic</li>
</ul>

<h2>Installation</h2>
<ol>
  <li>Make sure Python 3 is installed on your system.</li>
  <li>Download or copy the file <code>Average numbers.py</code>.</li>
  <li>Open a terminal or command prompt in the project folder.</li>
  <li>Run the program using:</li>
</ol>

<pre><code>python "Average numbers.py"</code></pre>

<p>The program will ask you to enter numbers one by one.</p>
<p>Each entered number is added to the total sum.</p>
<p>When you enter <code>0</code>, the program stops taking input and prints the average of all previously entered numbers.</p>

<h2>Output</h2>

<h3>Sample Input</h3>
<pre><code>Number: 10
Number: 20
Number: 30
Number: 0</code></pre>

<h3>Sample Output</h3>
<pre><code>20.0</code></pre>

<h3>How It Works</h3>
<ul>
  <li>The user enters integer numbers one at a time.</li>
  <li>The value <code>0</code> is used as a stopping signal and is not counted in the average.</li>
  <li>The program divides the total sum of valid numbers by their count.</li>
</ul>

<h2>Notes</h2>
<ul>
  <li>⚠️ If the first input is <code>0</code>, the program may raise a division error because no valid number has been entered.</li>
  <li>💡 This project is useful for beginners who want to practice loops, counters, and average calculation in Python.</li>
</ul>

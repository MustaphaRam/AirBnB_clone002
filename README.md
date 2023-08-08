<div>
<h2>0x00.AirBnB Clone - The Console</h2>

<h3>Welcome to the AirBnB clone project!</h3>

<h3>Description</h3>
<p>the AirBnB clone project is a complete web application, integration database storage, a backend API, and front-end interfacing in a clone of AirBnB.</p>

<h3>Functionalities of this command interpreter:</h3>
<ul>
<li>Create a new object (ex: a new User or a new Place)</li>
<li>Retrieve an object from a file, a database etc...</li>
<li>Do operations on objects (count, compute stats, etc...)</li>
<li>Update attributes of an object</li>
<li>Destroy an object</li>
</ul>



<h3>Console and Command Usage</h3>
<table>
    <thead>
    <tr>
    <th>Command</th><th>Example</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>Display commands help</td>
    <td>(hbnb) help </td>
    </tr>
    <tr>
    <td>Create object (prints its id)</td>
    <td>(hbnb) create )</td>
    </tr>
    <tr>
    <td>Destroy object</td>
    <td>(hbnb) destroy   or (hbnb) .destroy()</td>
    </tr>
    <tr>
    <td>Show object</td>
    <td>(hbnb) show   or (hbnb) .show()</td>
    </tr>
    <tr>
    <td>Show "all" objects or instances class</td>
    <td>(hbnb) all or (hbnb) all </td>
    </tr>
    <tr>
    <td>Run console</td>
    <td>./console.py</td>
    </tr>
    <tr>
    <td>Quit console</td>
    <td>(hbnb)quit</td>
    </tr>
    </tbody>
</table>

<p>Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:</p>

<ul>
<li>Create a new object (ex: a new User or a new Place)</li>
<li>Retrieve an object from a file, a database etc…</li>
<li>Do operations on objects (count, compute stats, etc…)</li>
<li>Update attributes of an object</li>
<li>Destroy an object</li>
</ul>


<h3>Python Unit Tests</h3>
<h3>Execution</h3>

<p>Your shell should work like this in interactive mode:</p>

<pre><code>$ ./console.py
(hbnb) help

Documented commands (type help &lt;topic&gt;):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
</code></pre>

<p>But also in non-interactive mode: (like the Shell project in C)</p>

<pre><code>$ echo "help" | ./console.py
(hbnb)

Documented commands (type help &lt;topic&gt;):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help &lt;topic&gt;):
========================================
EOF  help  quit
(hbnb) 
$
</code></pre>

<p>All tests should also pass in non-interactive mode: <code>$ echo "python3 -m unittest discover tests" | bash</code></p>

<h2>AUTHORS</h2>
<p>
    <h4><a href="https://github.com/MustaphaRam">Mustapha Ramadan</a></h4>
</p>


  </div>

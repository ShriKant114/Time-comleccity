<h2>📊 Time Complexity Chart (Low ➜ High)</h2>

<table>
  <thead>
    <tr>
      <th>📶 Order</th>
      <th>⏱️ Big-O</th>
      <th>🧠 Meaning</th>
      <th>🧪 Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>✅ Constant</td>
      <td><code>O(1)</code></td>
      <td>Always same steps</td>
      <td>Accessing an array element: <code>arr[0]</code></td>
    </tr>
    <tr>
      <td>🔁 Logarithmic</td>
      <td><code>O(log n)</code></td>
      <td>Halves input every step</td>
      <td>Binary Search</td>
    </tr>
    <tr>
      <td>🧮 Linear</td>
      <td><code>O(n)</code></td>
      <td>Each element processed once</td>
      <td>Loop through array</td>
    </tr>
    <tr>
      <td>📊 Log-linear</td>
      <td><code>O(n log n)</code></td>
      <td>Good sorting algorithms</td>
      <td>Merge Sort, Quick Sort</td>
    </tr>
    <tr>
      <td>🌀 Quadratic</td>
      <td><code>O(n²)</code></td>
      <td>Nested loops</td>
      <td>Bubble Sort, Brute Force</td>
    </tr>
    <tr>
      <td>🌪️ Cubic</td>
      <td><code>O(n³)</code></td>
      <td>Triple nested loops</td>
      <td>Naive matrix multiplication</td>
    </tr>
    <tr>
      <td>🚫 Exponential</td>
      <td><code>O(2ⁿ)</code></td>
      <td>Grows very fast</td>
      <td>Recursive Fibonacci</td>
    </tr>
    <tr>
      <td>❌ Factorial</td>
      <td><code>O(n!)</code></td>
      <td>All permutations</td>
      <td>Travelling Salesman Problem</td>
    </tr>
  </tbody>
</table>

<p><strong>⚠️ Tip:</strong> Lower complexity = better performance. Avoid <code>O(n²)</code> and worse on large data!</p>

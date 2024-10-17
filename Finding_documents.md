<html>
<body>
  <h1>Finding Documents in MongoDB collection</h1>
  <h2>It can be done with the following</h2>
  <li>find()</li>
  <li>$in</li>

<h3>Syntax for find()</h3>

<h3>db.grades.find():</h3>
<p>where 'grades' is a collection</p>

<br>
<p>Example:</p>
![image](https://github.com/user-attachments/assets/dfed40b5-ed9b-4366-a1c2-d6c5a65644de)

<h3>Syntax to find specific value</h3>
<h3>db.grades.find.({key: value)</h3>
<p>Example</p>
![image](https://github.com/user-attachments/assets/a6291636-850e-4d2b-ae77-c19a26632eb5)

<div>
  <h2>$in operator</h2>
<p>The in operator allows us to select all documents that have a field value equal to any of the values specified in the array.</p>
![image](https://github.com/user-attachments/assets/1111f3d8-2957-4a67-8c18-9a408844f1a4)

<br><br>
<p>Use $eq operator to find documents with a field and value.</p>
<p>Use the $in operator to select documents equal to the values specified in the array.</p>
</div>
</body>
</html>

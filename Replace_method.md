<html>
<body>

  <h1>Replace One</h1>
  <h3>
    Syntax:
    <br>
    db.database.replaceOne({_id},{data_to_be_replaced})
  </h3><br>


  <h4>Consider the following example </h4>
  <pre>
  [
  {
    _id: ObjectId('6710f3bcf876051bee6470ef'),
    student_id: 33333,
    scores: [ { type: 'quiz', score: 49 }, { type: 'Homework', score: 75 } ]
  },
  {
    _id: ObjectId('6710f752d92f4b5d031bef04'),
    student_id: 11111,
    scores: [ { type: 'quiz', score: 50 }, { type: 'hw', score: 47 } ]
  },
  {
    _id: ObjectId('6710f752d92f4b5d031bef05'),
    student_id: 222222,
    scores: [ { type: 'quiz', score: 40 }, { type: 'hw', score: 77 } ]
  }
]

<br>
<h4>Now lets update this data</h4>
<pre>
 {
    _id: ObjectId('6710f3bcf876051bee6470ef'),
    student_id: 33333,
    scores: [ { type: 'quiz', score: 49 }, { type: 'Homework', score: 75 } ]
  },
</pre>
<h4>The following cose is used to replace:</h4>
<h4>db.grades.replaceOne( { _id: ObjectId('6710f3bcf876051bee6470ef') }, {student_id: 33344, scores: [ { type: 'quiz', score: 50 }, { type: 'Homework', score: 48 } ]})
</h4>

<h4>Final Output:</h4>

<pre>
  [
  {
    _id: ObjectId('6710f3bcf876051bee6470ef'),
    student_id: 33344,
    scores: [ { type: 'quiz', score: 50 }, { type: 'Homework', score: 48 } ]
  },
  {
    _id: ObjectId('6710f752d92f4b5d031bef04'),
    student_id: 11111,
    scores: [ { type: 'quiz', score: 50 }, { type: 'hw', score: 47 } ]
  },
  {
    _id: ObjectId('6710f752d92f4b5d031bef05'),
    student_id: 222222,
    scores: [ { type: 'quiz', score: 40 }, { type: 'hw', score: 77 } ]
  }
]

</pre>
</body>
</html>

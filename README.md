# frecodecampsuveyForn
<!DOCTYPE html>
<head><link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1 id="title">Survey</h1>
  <p id="description">Data Form:</p>
<form id="survey-form">
  <label id="name-label"> name
    <input id="name" type="text" placeholder="name" required></input>
  </label>
    <label id="email-label"> email 
    <input id="email" type="email" placeholder="email" required></input></label>
  <label id="number-label"> number   <input id="number" type="number" min="0" max="10" placeholder="number" required></input></label>
   <select id="dropdown">
<option>Option 1</option>
<option>Option 2</option>
   </select>
   <select>
     <input type="radio" value="1"></input>
     <input type="radio" value="2"></input>
  <input id="submit"></input> Submit
  </form>
   </body>
</html>

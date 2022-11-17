<template>
    <div class="contact">
    <div id="contact">
    <img alt="Our Logo" src="../assets/google.jpg" style="width:100px;height:100px;" >
    <h2>Contact us</h2>
    <form action="">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="EmailAddress">EmailAddress</label>
    <input type="text" id="EmailAddress" name="EmailAddress" placeholder="EmailAddress">

     <label for="country">Country</label>
    <select id="country" name="country">
      <option value="South Africa">South Africa</option>
      <option value="Nigeria">Nigeria</option>
      <option value="Kenya">Kenya</option>
      <option value="Tanzania">Tanzania</option>
      <option value="Burundi">Burundi</option>
      <option value="Rwanda">Rwanda</option>
    </select>
  
    <input type="submit" value="Submit">
  </form>
    </div>
    <footer>
    </footer></div>
    </template>
    <script>
    export default {
    name: 'ContactComponent',
    data() {
    return {
    phoneNumber: '0704563911'
    }
    }
    }
    </script>
    <style scoped="">
    #contact {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
    Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    padding: 2rem;
    margin: 2rem;
    border: 1px solid #ddd;
    border-radius: 10px;
    }
    h2 {
    margin: 0 0 1.5rem 0;
    }
    input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display:inline-flex;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
    </style>
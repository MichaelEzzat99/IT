<html>
<head><title> 20194184@fue.edu.eg </title>
<style>
    .A{
  resize: none;
  width: 717px;
  height: 151px;
  margin: 7px;        
}
    
    </style>
</head>
<body>
<h1> New Student</h1>
    <form action="#" method="get" >
        <fieldset>
        <legend>Personal Information</legend>
        <p>
        <label>Full Name: </label> 
        <input type="text"  />    
        </p>
        <p>
        <label>Birthdate: </label> 
        <input type="date" />  
        </p>
        <p>
        <label>Gender: </label> 
        <input type="radio" name="r" >
        <label for="M">Male</label>    
        <input type="radio" name="r" >
        <label for="F">Female</label>  
        </p>     
        </fieldset>
        <fieldset>
        <legend>Contact Information</legend>
        <p>
        <label>Email: </label> 
        <input type="email"  />    
        </p>
        <p>
        <label>Phone: </label> 
        <input type="tel" name="txtphone" />  
        </p>
        <p>
        <label>Address: </label>
        <textarea rows="5" cols="100" name="txtAddress" class="A" ></textarea>    
        </p>    
        </fieldset>
        <fieldset>
        <legend>University Information</legend>
        <p>
        <label>Choose Your Faculty: </label>
        <select>
        <option>Faculty1</option>
        <option>Faculty2</option>    
        </select>     
        </p>              
        </fieldset>
        <Button type="submit">Add</Button>
    </form>
</body>
</html>

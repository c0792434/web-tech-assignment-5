# web-tech-assignment-5
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title></title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <script src="script.js"></script>
    <img "https://purepng.com/photo/6666/airplane" alt="CoverImage">
    <div class = "main"> 
            <div class ="ATA">Airline Ticketing Agents</div> 
            <div class =">Airline Ticketing Agents"> 
            </div> 
            </div> 
             <p img style = "color:rgb(240, 240, 255); border :3px; "> 
     </p>
     <h1>PRIVACY</h1>
    <p>We need to gather some personal information about you while you are doing business with us, such as your name, email address, passport number and payment details. For example, to process your booking and travel arrangements and transactions, this information is used. Any of this data is exchanged with our trusted partners, such as hotels and ground handlers, to ensure that your luggage arrives safely.</p>
    <h2>LEGAL</h2>
    <p> Catering to your different ticketing needs, at Mohini Tour n Travel, we are offering Airline Ticketing Services for the convenience of the clients. </p>
    <h2>SPECIFIC INSTRUCTION</h2>
    <p>Considered as the most convenient mode of transportation, the airline service is widely used by many people throughout the country.</p>
   
         First name: <input type = "text" name = "first_name" />
         <br>
         Last name: <input type = "text" name = "last_name" />
         <br>
         Email: <input type = "text" email = "Email_ID"/>
         <br>
         Phone no. : <input type = "text" phone no. = "Phone_no."/>
         <br>
         City :<input type = "text" city = "City"/>
         <br>
        <div class="row">
        <label>Province</label>
        <select name="country">
            <option>Select</option>
            <option>Australia</option>
            <option>India</option>
            <option>United States</option>
            <option>United Kingdom</option>
            <option>Canada</option>
        </select>
        </div>
         <label>Round Trip</label>
            <div >
                <label><input type="radio" name="Round Trip" value="yes"> Yes</label>
                <label><input type="radio" name="Round Trip" value="No"> No</label>
            </div>
            From:<input type = "text"  From = " From"/>
            To:<input type = "text" To = "To"/>
            <br>
            Passport Number:<input type = "text" Passport Number = "Passport Number"/>
        Number of adults:<input type = "text"  Number of adults = " Number_of_adults"/>
         <br>
          Number of children:<input type = "text"  Number of children = " Number_of_children"/>
         <br>
        <div class="section">
        <label>Age Groups</label>
        <select age groups="Age_Groups">
            <option>Select</option>
            <option>under 18</option>
            <option>over 18</option>
            <option>Both</option>
            <option>Senior citizens</option>
          </select>
        </div>
        <label>Any kind of phobia</label>
            <div >
                <label><input type="radio" name=Any kind of phobia value="yes"> Yes</label>
                <label><input type="radio" name="Any kind of phobia" value="No"> No</label>
            </div>
             If yes then mention here:<input type = "text"  If yes then mention here= " If yes then mention here"/>
         <br>
         <label>Above information that I filled is correct</label>
         <div>
        <input type="radio" name="Above information that I filled is Correct" value="Agree"> Agree
         </div>
          <form action="/new.php">
    <input type="submit" value="Submit">
     <form >
        </form>
    </form>
  </body>
</html>

# Form-Submission:


Form Submission.HTML:


```
<section class="divClear">
    <div class="innerBanner career"></div>
    <div class="container">
        <div class="pageContainer">
            <div class="pageTitle">
                <h2>Contact</h2>
            </div>
            <div class="contactPage divClear">
                <div class="col-8">
                    <div class="col-12">

                        <div class="divClear">
                            <h4 class="contactHead">Hospital </h4>
                            <div class="ContactIcon"><i class="fa fa-map-marker" aria-hidden="true"></i></div>
                            <div class="ContactDetails">
                                <p>
                                    Collector's Office Road,
                                    Bangalore - Chennai  National Highway (NH 48),
                                    <br />
                                    Vellore – 632 004.
                                </p>
                            </div>
                        </div>
                        <!--<div class="divClear">
                            <h4 class="contactHead">Corporate Office </h4>
                            <div class="ContactIcon"><i class="fa fa-map-marker" aria-hidden="true"></i></div>
                            <div class="ContactDetails">
                                <p>
                                    Old No. 9, New No. 17, Seethamma Road, Seethamma Colony, Alwarpet,<br />
                                    Chennai - 600 018.
                                </p>
                            </div>
                        </div>-->

                        <div class="clearfix"></div>
                        <div class="divClear contactNo">
                            <div class="ContactIcon"><i class="fa fa-phone" aria-hidden="true"></i></div>
                            <div class="ContactDetails">
                                <p>Appointments&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: 0416 666 1111 /  220 1111</p>
                                <p>Emergency&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;: 0416 666 1000</p>
                            </div>
                        </div>

                        <div class="clearfix"></div>
                        <div class="divClear mailId">
                            <div class="ContactIcon"><i class="fa fa-envelope" aria-hidden="true"></i></div>
                            <div class="ContactDetails"><a href="mailto:naruvi@naruvihospitals.com">naruvi@naruvihospitals.com</a></div>
                        </div>

                    </div>

                    <div class="clearfix"></div>
                    <!-- <div class="divLine divClear"></div>
                    <div class="col-6 contactPerson">
                        <h4>Dr. Paul Henry </h4>
                        <p class="proff">Executive Director </p>
                        <p>+91 96001 45129</p>
                    </div>
                    <div class="col-6 contactPerson">
                        <h4>Mr. P Mani Maran </h4>
                        <p class="proff">Executive Director </p>
                        <p>+91 87540 12321 </p>
                    </div>-->
                </div>
                <div class="col-lg-4">
                    <div class="formContainer">
                        <div class="form formNew">
                            <h4>Enquire Now</h4>
                            <div class="col-12">
                                <div class="label-txt">
                                    <label><span><i class="fa fa-user" aria-hidden="true"></i></span>Name</label>
                                    <input type="text" id="txtName" class="input-txt" />
                                    <span>
                                        <span id="reqfv" class="error404" style="display: none">Enter your Name</span>
                                        <span id="regfv" class="error404" style="display: none">Minimum 3 & Maximum 54 Characters Allowed & Symbols are not allowed</span>
                                    </span>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="label-txt">
                                    <label><span><i class="fa fa-envelope" aria-hidden="true"></i></span>Email</label>
                                    <input type="email" id="txtEmailId" class="input-txt" />
                                    <span>
                                        <span id="reqfv1" class="error404" style="display: none">Enter your Email Id</span>
                                        <span id="regfv1" class="error404" style="display: none">Enter Valid Email Id</span>
                                    </span>
                                </div>
                            </div>
                            <div class="col-12">
                                <div class="label-txt">
                                    <label><span><i class="fa fa-mobile" aria-hidden="true"></i></span>Phone</label>
                                    <input type="text" id="txtPhone" class="input-txt" />
                                    <span>
                                        <span id="reqfv2" class="error404" style="display: none">Enter your Mobile No.</span>
                                        <span id="regfv2" class="error404" style="display: none">Enter Valid Mobile No.</span>
                                    </span>
                                </div>
                            </div>
                            <div class="col-12 ">
                                <div class="label-txt">
                                    <label><span><i class="fa fa-pencil" aria-hidden="true"></i></span>Message</label>
                                    <textarea id="txtMessage" class="input-txt"></textarea>
                                    <span>
                                        <span id="reqfv3" class="error404" style="display: none">Enter your Message</span>
                                    </span>
                                </div>
                            </div>
                            <div class="col-12 pad-l0">
                                <div class="col-5 pad-r0">
                                    <span class="contactCode">
                                        <img class="code" src="Captcha.aspx" alt="Captcha Image" />
                                    </span>
                                </div>
                                <div class="col-7 pad-l0 inputType pad-r0">
                                    <div class="label-txt pad-r0">
                                        <label class="codeText">Code</label>
                                        <input type="text" id="txtVerify" class="input-txt" />
                                        <span>
                                            <span id="reqfv4" class="error404" style="display: none">Enter Verification Code</span>
                                            <span id="lblError" class="error404" style="display: none"></span>
                                        </span>
                                    </div>
                                    <div class="butttonNew">
                                        <button id="btnSend" class="btn">Send</button>
                                        <label id="btnWait" style="display: none" class="btn">Please wait</label>
                                        <i id="image" class="fa fa-paper-plane" aria-hidden="true"></i>
                                    </div>
                                    <div class="clearfix"></div>
                                </div>
                            </div>
                            <div class="clearfix"></div>
                        </div>
                        <div class="clearfix"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>


```


To handle form submissions and implement dynamic functionality for a web application, you would typically need to use a combination of frontend technologies (HTML, CSS, JavaScript) and backend technologies (server-side programming languages, frameworks, and databases). Here's a simplified example of how you could handle form submission using a popular stack: HTML, JavaScript, Node.js, Express.js, and MongoDB.

1. HTML:
```html
<!-- Add an id attribute to the form for easy access in JavaScript -->
<form id="contactForm" method="POST" action="/submit">
  <!-- form fields -->
</form>
```

2. JavaScript:
```javascript
// Add an event listener to the form submit event
document.getElementById('contactForm').addEventListener('submit', function(event) {
  event.preventDefault(); // Prevent the form from submitting normally

  // Retrieve form data
  const form = event.target;
  const formData = new FormData(form);

  // Send a POST request to the server with the form data
  fetch(form.action, {
    method: 'POST',
    body: formData
  })
  .then(response => response.json())
  .then(data => {
    // Handle the response from the server
    console.log(data);
    // Perform any necessary UI updates or display success/error messages
  })
  .catch(error => {
    console.error(error);
    // Handle errors
  });
});
```

3. Node.js with Express.js:
Assuming you have Node.js and Express.js installed, you can set up a basic server to handle the form submission. Here's an example server code:

```javascript
const express = require('express');
const app = express();

app.use(express.urlencoded({ extended: true }));
app.use(express.json());

// Handle form submission
app.post('/submit', (req, res) => {
  // Process the form data
  const name = req.body.txtName;
  const email = req.body.txtEmailId;
  const phone = req.body.txtPhone;
  const message = req.body.txtMessage;

  // Perform any necessary server-side validation, data manipulation, or database operations
  // For example, you can store the form data in a MongoDB database
  // const Contact = require('./models/contact');
  // const contact = new Contact({ name, email, phone, message });
  // contact.save();

  // Send a response back to the client
  res.json({ success: true, message: 'Form submitted successfully' });
});

// Start the server
const port = 3000;
app.listen(port, () => {
  console.log(`Server running on port ${port}`);
});
```

4. MongoDB (optional):
If you want to store the form data in a MongoDB database, you would need to set up a connection to MongoDB and define a schema and model for the Contact collection. You can use a library like Mongoose to simplify the process. Here's an example of how you could define the Contact model:

```javascript
const mongoose = require('mongoose');

const contactSchema = new mongoose.Schema({
  name: String,
  email: String,
  phone: String,
  message: String
});

const Contact = mongoose.model('Contact', contactSchema);

module.exports = Contact;
```

Remember to install the necessary dependencies (`express`, `mongoose`, etc.) using npm or yarn before running the server.

This is just a basic example to demonstrate the general process of handling form submissions in a dynamic web application. In a real-world scenario, you would typically have more robust validation, error handling, and database integration. Additionally, you may need to configure your server for security, implement authentication, and handle other aspects based on your specific requirements.



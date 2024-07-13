# Income-tax-website-clone
This project is a clone of the Indian Income Tax Department's official website, aimed at replicating its functionality and design for educational purposes.
It provides a simplified version of the website's features, focusing on key functionalities such as:  User Authentication: Login and registration for taxpayers. FAQs and Help

Below is the code for HTML part:

Index file-
<!DOCTYPE html PUBLIC>
<html>
<head>
<title>Income Tax Department</title>

<link rel="stylesheet" type="text/css" media="screen,projection" href="css/style_screen.css" />

</head>
<body>
<script src="App.js"></script>
<div class="page-container-1">
 
  
  <div class="nav1-container">
    <div class="nav1">
      <ul>
        <li><a onclick="myFunction4()">About-Us</a></li>
        <li><a onclick="myFunction5()">Feedback</a></li>
        <li><a onclick="myFunction3()">Accessbility</a></li>
        <li><a onclick="myFunction6()">Contact-Us</a></li>
      </ul>
    </div>
  </div>
 
  <div><a target="_blank" href="https://innovateindia.mygov.in/ppc-2023"><img class="img-header" src="img/Indianbanner.png" alt="" usemap="Click" ></a>
 
  
  
  </div>
  <div class="nav2">
    <ul>
      <li><a href="" class="selected">Home</a></li>
    </ul>
    <marquee>The Federal Board of Revenue (FBR) has extended the date for filing income tax returns for the third time till December 15.

      The deadline has been extended keeping in view the requests from various trade bodies, Tax Bar Associations and flood-affectees. 
      
      </marquee>

  </div>
  <div class="buffer"></div>
  <div class="nav3">
    <ul>
      <li class="title">Login</li>
      <div class="login">
          <input type="text" placeholder="Username" id="username"> <br>
        <input type="password" placeholder="password" id="password"> <br>
        <input onclick="myFunction()" type="submit" value="Sign In"> <br>
        <a href="signin.html" class="forgot">Don't have a Account?,Sign up here</a>
      </div>
      <div class="shadow"></div>
    </ul>
    <p class="sidebar-maintitle">Question of the day</p>

    <p class="sidebar-title-noshade">Do tax returns get rejected?</p>
    <div class="sidebar-txtbox-noshade">
      <p>The ITR-V might be rejected by the IT department if you did not sign it, its quality is bad, or if you filed it late. If the form is rejected, you can print another ITR-V, sign it and send it to the CPC. This facility is available within 120 days of filing the online income tax return</p>
    </div>
    <p class="sidebar-maintitle"></p>
    <div class="sidebar-txtbox-noshade">
      <p></p>
    </div>
  </div>
  <div class="content1">
    <div class="content1-pagetitle">News and Updates</div>
    <div class="content1-container line-box">
      <div class="content1-container-1col">
        <p class="content-title-noshade-size3">Basic overview</p>
        <p class="content-subtitle-noshade-size1">ITR Filing Last Date FY 2021-22 (AY 2022-23)</p>
        <div class="content-txtbox-noshade">
          <p>You must understand that the return you are filing currently is for the income you earned in FY 2021-22,i.e. for the income earned between 1 April 2021 and 31 March 2022. The assessment year will be the year in which you file your returns and declare the income for tax assessment. For the income earned during the FY ( here FY 2021-22), the assessment year would be the immediate next year, i.e. 1st April 2022 to 31st March 2023. Hence, the assessment year would be AY 2022-23.</p>
          <p class="readmore">| Oct 19, 2022 | <a target="_blank" href="https://cleartax.in/s/due-date-tax-filing">Read more</a></p>
        </div>
      </div>
    </div>
    <div class="content1-container">
      <div class="content1-container-3col-left">
        <p class="content-title-noshade-size3">Search and Seizure</p>
        <p class="content-subtitle-noshade-size1">Bihar</p>
        <div class="content-txtbox-noshade">
          <p>Income Tax Department initiated a Search & Seizure action on few groups
            engaged in the business of gold & diamond jewellery and real estate, on 17.11.2022.</p>
        </div>
      </div>
      <div class="content1-container-3col-middle">
        <p class="content-title-noshade-size3">Press Release</p>
        <p class="content-subtitle-noshade-size1">New Delhi</p>
        <div class="content-txtbox-noshade">
          <p>The provisional figures of Direct Tax collections up to 10th November, 2022
            continue to register steady growth. Direct Tax collections up to 10th November, 2022
            show that gross collections are at Rs. 10.54 lakh crore which is 30.69% higher than
            the gross collections for the corresponding period of last year.</p>
        </div>
      </div>
      <div class="content1-container-3col-right">
        <p class="content-title-noshade-size3">Finance</p>
        <p class="content-subtitle-noshade-size1">Delhi</p>
        <div class="content-txtbox-noshade">
          <p>Income Tax Department initiated Search & Seizure actions on 20.10.2022 and
            02.11.2022 on certain individuals who had executed Joint Development Agreements
            (JDAs) with various real-estate developers. The search action covered more than 50
            premises spread across Bengaluru, Mumbai and Goa.
</p>
        </div>
      </div>
    </div>

  </div>
  <div class="sidebar">
    <p class="sidebar-maintitle">Information Bar:-</p>
    <h3 class="title">Important Links</h3>
        <div id="hpage_quicklinks">
          <ul class="clear">
            <li><a href="instantpan.html">Instant E-PAN</a></li> <br>
            <li><a href="panlink.html">Link Aadhaar</a></li> <br>
            <!-- <li><a href="#">Submit Forms</a></li> <br> -->
            <!-- <li><a href="#">ITR Status</a></li> <br> -->
          </ul>
        </div>
    <p class="sidebar-title-noshade"></p>
    <h3 class="title">FAQ</h3>
        <div id="hpage_quicklinks">
          <ul class="clear">
            <li><a href="FAQ.html">General FAQs</a></li> <br>
            <li><a href="Finalfile.html">Forms for Senior Citizen's</a></li> <br>
            <li><a href="Senior.html">FAQs on filing the return</a></li> <br>
            <!-- <li><a href="#">FAQs on Tax Deducted</a></li> -->
          </ul>
        </div>
    <p class="sidebar-title-noshade">HeadQuarters</p>
    <div class="sidebar-txtbox-noshade">
      <p>North Block, Secretariat Building, New Delhi</p>
    </div>
    <p class="sidebar-maintitle"></p>
    <div class="sidebar-txtbox-noshade">
      <p></p>
    </div>
  </div>
  <div class="footer">
    <p><b>  Website Built by <a href="#"></a>Mayank Gahlot,Aditya Bhadauria and Samaira Katoch</b></p>
    <!-- <p><a href="#">"Click here to know more"</a></p> -->
  </div>
</div>
</body>
</html>

FAQ's file-
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    

    <style>


.bg1{
        width: 770px;
        margin: 0 auto;
        padding: 0;
        position: absolute;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
    }


.pa{
    padding-left: 400px;
    background-color: rgb(128,161,202);
    margin-bottom: 0px;
    font-size: 20px;
}
p{
    color: darkmagenta;
}
h1{
    font-size: 90px;
}

    </style>
           <link rel="shortcut icon" href="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" type="image/x-icon">

</head>
<body style="background-color: lightblue;">
    
         <div>
            <center><img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" alt="Income Tax" height="70"></center>
            <br>
            <center><H1>FAQ's</H1></center>
           <a href="index.html"> <input type="button" value="Back" height="20px" width="20px"></a>
            <br><br>

            <section>
             
                <div >
                    
                        <li>
                            <span>What is Annual Information Statement (AIS)?</span>
                            <div>
                      <div >
                        <p>Annual Information Statement (AIS) is comprehensive view of information for a taxpayer displayed in Form 26AS. Taxpayer can provide feedback on information displayed in AIS. AIS shows both reported value and modified value (i.e. value after considering taxpayer feedback) under each section (i.e. TDS, SFT, Other information). The objectives of AIS are:

                            Display complete information to the taxpayer with a facility to capture online feedback
                            Promote voluntary compliance and enable seamless prefilling of return
                            Deter non-compliance</p>
                      </div>
                            </div> 
                        </li>
                        <li >
                            <span> What is the Difference between AIS and Form 26AS?</span>
                            <div >
                      <div >
                        <p>AIS is the extension of Form 26AS. Form 26AS displays details of property purchases, high-value investments, and TDS/TCS transactions carried out during the financial year. AIS additionally includes savings account interest, dividend, rent received, purchase and sale transactions of securities/immovable properties, foreign remittances, interest on deposits, GST turnover etc. 
 

                            AIS also provides the taxpayer the option to give feedback on the transactions reported. Further, the aggregation of transactions on information source level is also reported in TIS.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>How can I view the Annual Information Statement??</span>
                            <div >
                      <div >
                        <p>You can access the Annual Information Statement functionality by following below mentioned steps: 

                            Step 1: Login to URL https://www.incometax.gov.in/
                            Step 2: Click on “Annual Information Statement (AIS)” under “Services” tab from the e-filing portal after successful login on e-filing portal.
                            Step 3: Click on AIS tab, on the homepage.
                            Step 4: Select the relevant FY and click on AIS tile to view the Annual Information Statement.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>What are the components of Annual Information Statement (AIS)?</span>
                            <div >
                      <div >
                        <p>The information shown on AIS is divided in two parts:

                            PART A- General Information  
                            Part-A displays general information pertaining to you, including PAN, Masked Aadhar Number, Name of the Taxpayer, Date of Birth/ Incorporation/ Formation, mobile number, e-mail address and address of Taxpayer.
                            
                            PART- B
                            TDS/TCS Information: - Information related to tax deducted/collected at source is displayed here. The Information code of the TDS/TCS, Information description and Information value is shown.
                            
                            SFT Information: - Under this head, information received from reporting entities under Statement of Financial transaction (SFT) is displayed. The SFT code, Information description and Information value is made available.
                            Payment of Taxes: - Information relating to payment of taxes under different heads, such as Advance Tax and Self-Assessment Tax, is shown. 
                            Demand and Refund: -You will be able to view the details of the demand raised and refund initiated (AY and amount) during a financial year. (Details related to Demand will be released soon)
                            Other Information: - Details of the information received from the other sources, such as data pertaining to Annexure II salary, Interest on refund, Outward Foreign Remittance/Purchase of Foreign Currency etc., is displayed here.</p>
                      </div>
                            </div> 
                        </li>
                     
                        <li >
                            <span> What does “General information” part contains under AIS?</span>
                            <div >
                      <div >
                        <p>General information displays the general information pertaining to you, including PAN, Masked Aadhar Number, Name of the Taxpayer, Date of Birth/ Incorporation/ Formation, mobile number, e-mail address and address of Taxpayer.
                         </p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>Can I track the Activity history in AIS?</span>
                            <div >
                      <div >
                        <p>Yes, you can track the activity history in AIS by clicking on the Activity history button on AIS homepage. You will be provided a summary view of activity performed on the AIS functionality. System generated Id (Activity ID) will be created for each performed activity, Activity date, Activity description and detail will be displayed under this tab.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>What does Taxpayer Information Summary (TIS) contain under AIS?</span>
                            <div >
                      <div >
                        <p>Taxpayer Information Summary (TIS) is an information category wise aggregated information summary for a taxpayer. It shows processed value (i.e. value generated after deduplication of information based on pre-defined rules) and derived value (i.e. value derived after considering the taxpayer feedback and processed value) under each information category (e.g. Salary, Interest, Dividend etc.). The derived information in TIS will be used for prefilling of return, if applicable.

                            You will be shown various details within the Taxpayer Information Summary such as,
                            
                            Information Category
                            Processed Value
                            Derived Value
                            Further, within an Information Category following information is shown:
                            
                            Part through which information received
                            Information Description
                            Information Source
                            Amount Description
                            Amount (Reported, Processed, Derived)</p>
                      </div>
                            </div> 
                        </li>
                     
                        <li >
                            <span>In what all formats can I download my AIS?</span>
                            <div >
                      <div >
                        <p>You can download Annual Information Statement (AIS) in PDF, JSON, CSV file formats.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>What will happen once I submit the feedback?</span>
                            <div >
                      <div >
                        <p>Upon successful submission of feedback on AIS information, the feedback will be displayed with the information and the modified value of the information will also be visible with the reported value. The activity history tab will also be updated, and you will be able to download Acknowledgement Receipt. Email and SMS confirmations for submission of feedback will also be sent.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>Is there any confirmation will be received on submission of AIS feedback?</span>
                            <div >
                      <div >
                        <p>Yes, after successful submission of your feedback on AIS information, the activity history tab will be updated, and you will be able to download Acknowledgement Receipt of the same. Email and SMS confirmations for submission of feedback will also be sent.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span> Is there any limit on the number of times I can modify a given feedback?</span>
                            <div >
                      <div >
                        <p>Currently, there is no limit on the number of times you can modify previously given feedbacks..</p>
                      </div>
                            </div> 
                        </li>
                  
                        <li >
                            <span>Can I verify the GST turnover in AIS?</span>
                            <div >
                      <div >
                        <p>Yes AIS does display the information related to GST turnover under information code (EXC-GSTR3B). The same would be visible in the Other Information tab in AIS.</p>
                      </div>
                            </div> 
                        </li>
            
                        <li >
                            <span>Is there any video tutorial available for AIS?</span>
                            <div >
                      <div >
                        <p>Yes, there is an informational video available on YouTube for AIS. This video can be accessed here Basic information on <a href="https://www.youtube.com/watch?v=zbGa6uvisBE"> Annual Information Statement functionality - YouTube</a></p>
                      </div>
                            </div> 
                        </li>
            
                        
                      </div>
                            </div> 
                        </li>
                    </ul> 
                </div> 
            
                
            </body>
            </html>

                
                
         
        </div><br>
            <p style="color: black;" class="pa"><b> Website Built by Mayank Gahlot,Aditya Bhadauria and Samaira Katoch</b></p>
        
        </div>
            
        
    </div>
</div>
    
</body>
</html>

General Form Information-
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    

    <style>


.bg1{
        width: 770px;
        margin: 0 auto;
        padding: 0;
        position: absolute;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
    }


.pa{
    padding-left: 400px;
    background-color: rgb(128,161,202);
    margin-bottom: 0px;
    font-size: 20px;
}
p{
    color: darkmagenta;
}
pre{
    color: red;
}
h1{
    font-size: 60px;
}

    </style>
           <link rel="shortcut icon" href="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" type="image/x-icon">

</head>
<body style="background-color: lightblue;">
    
         <div>
            <center><img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" alt="Income Tax" height="70"></center>
            <br>
            <center><H1>Forms Applicable for senior Cetizens</H1></center>
            <a href="index.html"><input type="button" value="Back" height="20px" width="20px"></a>
            <br><br>

            <section>
             
                <div >
                    
                        <li>
                            <span> Form 15H - Declaration to be made by an individual (who is 60 years of age or more) claiming certain receipts without deduction of tax </span>
                            <div>
                        </li>
                      <div >
                        
                      </div>
                            </div> 
                        </li>
                        <li >
                            <span>Form 15H - Declaration to be made by an individual (who is 60 years of age or more) claiming certain receipts without deduction of tax </span>
                            <div >
                      <div >
                        
                      </div>
                        
                    </div> 
                        
            
                        <li >
                            <span>Form 16A – Certificate u/s 203 of the Income Tax Act, 1961 for TDS on Income other than Salary </span>
                            <div>
                    <div >
                        <div>
                            <li>
                                <span>Form 67- Statement of Income from a country or specified territory outside India and Foreign Tax Credit</span>
                            </li>
                        </div>
                        <div>
                            <li>
                                <span> Form 26AS - Annual Information Statement
                                </span>
                                <div>
                            </li>
                        </div>
                        

                      </div>
                            </div> 
                        </li>
            
                        
            
                        
                      </div>
                            </div> 
                        </li>
                    </ul> 
                </div> 
            
                
            </body>
            </html>

                
                
         
        </div><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
            <p style="color: black;" class="pa"><b> Website Built by Mayank Gahlot,Aditya Bhadauria and Samaira Katoch</b></p>
        
        </div>
            
        
    </div>
</div>
    
</body>
</html>

Instant Pan login-
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Instant E-Pan</title>
    <style>
        .bg1{
        width: 770px;
        margin: 0 auto;
        padding: 0;
        border: solid gray;
        position: absolute;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: lightblue;
    }

.m{
    margin-top: 230px;
    /* background-color: red; */
}
.p{
    padding-left: 140px;
    background-color: rgb(128,161,202);
    padding-bottom: 2px;
    font-size: 16px;
}
    </style>
       <link rel="shortcut icon" href="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" type="image/x-icon">

</head>
<body>
    <script src="App.js"></script>
    <div class="bg1" >
        <center><img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" alt="Income Tax" height="41px"></center>
        <img src="https://resize.indiatvnews.com/en/resize/newbucket/1200_-/2020/05/113568-pan-pti-1590669558.jpg" alt="Income Tax website" width="770px" height="200px">
       
            <center><h1 style="font-size: 25px;">Instant E-Pan</h1></center>
            <img src="verify.png" alt="" width="770px">
            <a href="index.html"><input type="button" value="Back" height="20px" width="20px"></a>
            <br><br><br>
            <center>
                Pan Number: <input type="text" placeholder="Enter Pan Number" id="username" required><br><br>
                     Aadhaar no: <input type="number" placeholder="Enter Aadhaar Number" id="password" required><br><br></center>
                     <div style="margin-left: 300px;">DOB: <input type="date" name="mydate" min="2002-01-01"></div><br>
                     <div style="margin-left: 200px;"> Enter mobile number: <input type="tel" id="phone" name="phone" placeholder="123-45-678" required></div>
             <div>
            <center>   <br><input onclick="myFunction1()" type="submit" value="submit now">
               <input onclick="myFunction2()" type="reset" value="Reset now"></div>
           </center><br>
           <p style="color: black;" class="p"><b> Website Built by Mayank Gahlot,Aditya Bhadauria and Samaira Katoch</b></p>
    </div><br><div>
        <br><br><br><br>
</body>
</html>

Linking Pan-
<!DOCTYPE html>        

<html lang="en">
<head>
    <style>
.bg1{
        width: 770px;
        margin: 0 auto;
        padding: 0;
        border: solid gray;
        position: absolute;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: lightblue;
    }
    .note{
border: solid red; width: fit-content;
background-color: darkkhaki;
}
    .p{
    padding-left: 140px;
    background-color: rgb(128,161,202);
    padding-bottom: 2px;
    font-size: 16px;
}

    </style>
   <link rel="shortcut icon" href="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" type="image/x-icon">
    <title>Link Pan</title>
</head>
<body style="background-color: lightgray;">
    <script src="App.js"></script>
    <div class="bg1" >
        <center><img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" alt="Income Tax" height="39px"></center>
        <img src="https://i.gadgets360cdn.com/large/pan_aadhaar_linking_image_twitter_income_tax_india_1577537419443.jpg" alt="Income Tax website" width="770px" height="200px">
       
            <a href="index.html"><input type="button" value="Back" height="20px" width="20px"></a>

            <center><h1 style="font-size: 25px;">Link Pan</h1></center>
            <div class="note" ><pre><b>Information :</b>
 As per CBDT circular F. No. 370142/14/22-TPL dated on 30th March 2022, every person who has 
 been allotted a PAN as on 1st July 2017 and is eligible to obtain Aadhaar number is required to link  
 PAN with AADHAAR on or before 31st March, 2022. Taxpayers who failed to do so are liable to pay a fee of  
 Rs.500 till 30th June, 2022 and thereafter a fee of Rs. 1000 will be applicable before submission of 
 PAN-AADHAAR linkage request. Please pay the applicable fee of Rs. 1000 through e-Pay Tax service to
 proceed with submission of Aadhaar-PAN linking request.</pre>

                    </div>
        <div>
            <br>
        
        <div>
           <center>
            PAN: <input type="text" placeholder="Enter Pan Number" id="username" required><br>
                  Aadhaar Number: <input type="number" placeholder="Enter Aadhaar Number" id="password" required><br><br>
          <div><input onclick="myFunction1()" type="submit" value="submit now">
            <input onclick="myFunction2()" type="reset" value="Reset now"></div>
        </center>
       
        
    </div><div>
    <div class="note" ><pre><b>NOTE:</b>
Following categories are exempted from Aadhaar-PAN linking
 (i) NRIs
 (ii) Not a citizen of India
 (iii) age > 80 years as on date
 (iv) state of residence is ASSAM, MEGHALAYA or JAMMU & KASHMIR
 Refer Department of Revenue Notification no 37/2017 dated 11th May 2017                                   
</pre>
    </div>
    <p style="color: black;" class="p"><b> Website Built by Mayank Gahlot,Aditya Bhadauria and Samaira Katoch</b></p>
</div>
         
</body>
</html>

Signin-
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    <style>

.bg1{
        width: 770px;
        margin: 0 auto;
        padding: 0;
        border: solid gray;
        position: absolute;
    top:0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: lightblue;
    }

.border{
    border: solid black 5px;

}
.p{
    padding-left: 120px;
    background-color: rgb(128,161,202);
    margin-bottom: 0px;
    font-size: 18px;
}


    </style>
           <link rel="shortcut icon" href="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" type="image/x-icon">

</head>
<body style="background-color: lightgray;">
    <script src="App.js"></script>
    <div class="bg1" >
        <center><img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Logo_of_Income_Tax_Department_India.png" alt="Income Tax" height="39px"></center>

        <img src="https://images.indianexpress.com/2018/07/income-tax-7592.jpg" alt="Income Tax website" width="770px" height="200px"><br><br>
        <a href="index.html"><input type="button" value="Back" height="20px" width="20px"><br><br></a>
            <div class="border">
                
            <center><h1 style="font-size: 25px;">Sign Up</h1>
                Name: <input type="text" placeholder="Name" id="Name" required><br>
                Pan Number: <input type="number" placeholder="Pan Number" id="password" required><br>
                Mobile number: <input type="number" id="phone" name="phone" placeholder="12345-67891" required>
                <br>
              <div>
                <input onclick="myFunction1()" type="submit" value="submit now">
                <input onclick="myFunction2()" type="reset" value="Reset now"></div>
                
            </center>
         
        </div>
        <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
            <p style="color: black;" class="p"><b> Website Built by Mayank Gahlot,Aditya Bhadauria and Samaira Katoch</b></p>
        
        </div>
            
        
        
    </div>
</div>
    
</body>
</html>

Code for Javascript Part-
function myFunction() {
    if(confirm("we have detected that you dont have an account with us, please create one to use our services") ==true){
      window.location.replace("./signin.html")
    }
  }
  function myFunction1() {
    if(confirm("Should we confirm your request") ==true){
      window.location.replace("./index.html")
      alert("Your request has been successfully recorded")
      
    }
  }
  function myFunction2() {
    location.reload()
    }
  
  function myFunction3() {
    if(confirm("Do you want to access the code behind website?") ==true){
      window.open('https://github.com/Aditya-Bhadauria  ','_blank')
      
        
    }
  }
  function myFunction4() {
    alert("we are a team of students who were tasked to create this website 1)Aditya Bhadauria(12208458) \n 2)Mayank Gahlot(12211318) \n 3)Samaira Katoch(12210856)")
  }
  function myFunction5() {
    alert("All the feedback must be submitted to github,Click on accessibility to access the github profile")
  }
  function myFunction6() {
    alert("All the information about the devs can be found on their respective 'Linkdin profiles'")
  }
  
Code for External Css-
 body {
    font-size: 62.5%;
     margin: 0px 0px 0px 0px;
     padding:  0px;  
     font-family: arial, sans-serif;
}
 .page-container-1 {
    width: 800px;
    height:auto;
     margin: 0px auto;
     padding: 0px;
     border: solid 1px rgb(90, 4, 4);
}
 .img-header-{
      width: 0px;    
}
 .nav1-container {
    width: 800px;
    height: 6px;
    position:relative   
}
 .nav1 {
   background-color: brown;
    margin: 0px;
     padding: 0px;
     font-family: verdana, arial, sans serif;
     font-size: 1.0em;
     float:right  
}
 .nav1 ul {
    float: right;
     margin: 0px;
     padding: 0px 0px 0px 0px;
     order: solid 1px rgb(8, 8, 8);
     background-color: rgb(255,255,255);
     font-weight: bold;
     border:1px solid black
}
 .nav1 li {
    display:inline;
     list-style: none;
     margin: 0px;
     padding: 0px;
     border-right:1px 
     
}
 .nav1 li a {
    display: block;
     float: left;    
     margin: 0px;
     padding: 0px 141.02px 1px 0px;
     order: solid 1px rgb(8, 8, 8);
     color: rgb(255, 253, 253);
     text-decoration: none;
     font-size: 10px;
     background-color: rgb(238, 138, 6);
     cursor: default;
     
     
}
 .nav1 a:hover, .nav2 a.selected {
    color: rgb(50,50,50);
     text-decoration: none;
}
 .nav2 {
    clear: both;
     margin: 0px;
     padding: 0px;
     font-family: verdana, arial, sans serif;
     font-size: 1.0em;
}
 .nav2 ul {
    float: left;
     width: 800px;
     margin: 0px;
     padding: 0px;
     border-top: solid 1px rgb(151, 106, 54);
     border-bottom: solid 1px rgb(151,106,54);
     background-color: rgb(226, 138, 24);
     font-weight: bold;
}
 .nav2 li {
    display: inline;
     list-style: none;
     margin: 0px;
     padding: 0px;
}
 .nav2 li a {
    display: block;
     float: left;
     margin: 0px 0px 0px 0px;
     padding: 5px 10px 5px 1px;
     border-right: solid 1px rgb(54,83,151);
     color: rgb(255,255,255);
     text-transform: uppercase;
     text-decoration: none;
     font-size: 100%;
}
 .nav2 a:hover, .nav2 a.selected {
    color: rgb(50,50,50);
     text-decoration: none;
}
 .bffer {
    clear: both;
     width: 800px;
     height: 25px;
     margin: 0px;
     padding: 0px;
     background-color: rgb(52, 235, 16);
     border-bottom:rgb(8, 8, 8)
}
 .nav3 {
    overflow: hidden;
     clear: both;
     float: left;
     width: 160px;
     min-height: 500px;
     margin: 0px;
     padding: 0px;
     color: rgb(75,75,75);
     font-size: 1.0em;
}
 .nav3 ul {
    width: 160px;
     margin: 0px 0px 20px 0px;
     padding: 0px;
     border-bottom: solid 1px rgb(216,206,159);
     background-color: rgb(219,230,241);
}
 .nav3 li {
    list-style: none;
     margin: 0px;
     padding: 0px;
}
 .nav3 li.title {
    margin: 0px 0px 0px 0px;
     padding: 3px 5px 2px 15px;
     background-color: rgb(22, 99, 170);
     color: rgb(255,255,255);
     text-transform: uppercase;
     font-weight: bold;
     font-size: 120%;
}
 .nav3 li.group a {
    display: block;
     min-height: 1.7em;
     height: auto !important;
     height: 1.7em;
     line-height: 1.7em;
     margin: 0px;
     padding: 0px 7px 0px 15px;
     border-top: solid 1px rgb(200,200,200);
     border-left: solid 7px rgb(219,230,241);
     color: rgb(75,75,75);
     font-weight: bold;
     font-size: 120%;
}
 .nav3 li a {
    display: block;
     min-height: 1.7em;
     height: auto ;
     height: 1.7em;
     line-height: 1.7em;
     margin: 0px;
     padding: 0px 7px 0px 20px;
     border-left: solid 7px rgb(219,230,241);
     color: rgb(75,75,75);
     text-decoration: none;
     font-size: 120%;
}
 .nav3 li a:hover, .nav3 li a.selected {
    border-left: solid 7px rgb(156,186,214);
     color: rgb(100,100,100);
     text-decoration: none;
}
 .content1 {
    float: left;
     width: 428px;
     margin: 0px;
     padding: 0px 0px 10px 20px;
     color: rgb(75,75,75);
}
 .content1-container {
    clear: both;
     float: left;
     width: 408px;
     margin: 0px 0px 15px 0px;
     padding: 0px;
     
}
  .content1-container-1col {
    overflow: hidden;
     width: 408px;
     margin: 0px;
     padding: 0px;
}
 .content1-container-3col-left {
    overflow: hidden;
     float: left;
     width: 119px;
     margin: 0px 25px 0px 0px;
     padding: 0px;
     border-top:1px solid black
}
 .content1-container-3col-middle {
    overflow: hidden;
     float: left;
     width: 119px;
    margin: 0px;
     padding: 0px;
     border-top:1px solid black
}
 .content1-container-3col-right {
    overflow: hidden;
     float: right;
     width: 119px;
     margin: 0px;
     padding: 0px;
     border-top:1px solid black
}
 .content1-pagetitle {
    overflow: hidden;
     width: 408px;
     margin: 0px 0px 10px 0px;
     padding: 0px 0px 2px 0px;
     border-bottom: solid 3px rgb(22, 99, 170);
    
     color: rgb(22, 99, 170);
     font-weight: bold;
     font-size: 180%;
}
 .content-title-noshade-size3 {
    margin: 0px;
     padding: 0px;
     color: rgb(22, 99, 170);
     font-weight: bold;
     font-size: 160%;
}
 .content-title-shade-size3 {
    margin: 0px;
     padding: 0px 10px 0px 10px;
     background-color: rgb(215,215,215);
     color: rgb(22, 99, 170);
     font-weight: bold;
     font-size: 160%;
}
 .content-subtitle-noshade-size3 {
    margin: 0px;
     padding: 0px;
     color: rgb(88,144,168);
     font-weight: bold;
     font-size: 130%;
}
 .content-subtitle-shade-size3 {
    margin: 0px;
     padding: 0px 10px 3px 10px;
     background-color: rgb(215,215,215);
     color: rgb(22, 99, 170);
     font-weight: bold;
     font-size: 130%;
}
 .content-txtbox-noshade {
    margin: 0px;
     padding: 7px 0px 0px 0px;
     background-color: rgb(255,255,255);
}
 .content-txtbox-shade {
    margin: 0px;
     padding: 7px 10px 5px 10px;
     background-color: rgb(235,235,235);
}
 h3 {
    margin: 1.0em 0px 0.5em 0px;
     font-weight: bold;
     font-size: 140%;
}

 p {
    margin: 0px 0px 0.5em 0px;
     padding: 0px;
     line-height: 1.3em;
     font-family: arial, sans serif;
     font-size: 120%;
}
 p.readmore {
    margin: 1.0em 0px 0.5em 0px;
     padding: 0px;
     line-height: 1.2em;
     font-size: 110%;
}
 .sidebar {
    overflow: hidden;
     float: right;
     width: 160px;
     min-height: 500px;
     margin: 0px;
     padding: 0px 0px 10px 0px;
     text-align: left;
     color: rgb(75,75,75);
}
 .sidebar-maintitle {
    margin: 0px 0px 10px 0px;
     padding: 3px 10px 2px 10px;
     background-color: rgb(22, 99, 170);
     color: rgb(255,255,255);
     text-transform: uppercase;
     font-weight: bold;
     font-size: 120%;
}
 .sidebar-title-noshade {
    margin: 0px;
     padding: 2px 10px 3px 10px;
     border-top: solid 1px rgb(215,215,215);
     color: rgb(75,75,75);
     font-weight: bold;
     font-size: 120%;
}
 .sidebar-title-shade {
    margin: 0px;
     padding: 2px 10px 3px 10px;
     background-color: rgb(215,215,215);
     color: rgb(75,75,75);
     font-weight: bold;
     font-size: 120%;
}
 .sidebar-txtbox-noshade {
    margin: 0px 0px 10px 0px;
     padding: 2px 10px 3px 10px;
}
 .sidebar-txtbox-shade {
    margin: 0px 0px 10px 0px;
     padding: 2px 10px 3px 10px;
     background-color: rgb(235,235,235);
}
 .sidebar-txtbox-noshade p {
    margin: 0px 0px 5px 0px;
     padding: 0px;
     line-height: 1.25em;
     font-size: 110%;
}
 .sidebar-txtbox-shade p {
    margin: 0px 0px 5px 0px;
     padding: 0px;
     line-height: 1.25em;
     font-size: 110%;
}
 .footer {
    
     clear: both;
     width: 800px;
     height: 3.0em;
     margin: 0px;
     padding: 0.5em 0px 0.5em 0px;
     border-top: solid 1px rgb(8, 8, 8);
     background-color: rgb(22, 99, 170);
     color: rgb(255,255,255);
     font-size: 1.0em;
}
 .footer p {
    margin: 0px;
     padding: 0px;
     text-align: center;
     line-height: 1.3em;
     font-size: 110%;
}

 .footer a {
    color: rgb(255,255,255);
     text-decoration: underline;
}
 .footer a:hover {
    color: rgb(0,0,0);
     text-decoration: none;
}
 

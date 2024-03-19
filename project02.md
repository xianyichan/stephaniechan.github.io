<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PROJECT 01</title>
<style>
  body {
    font-family: Arial, sans-serif;
  }
  .timeline::after {
    content: '';
    position: absolute;
    width: 6px;
    background-color: #f00;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -3px;
  }
  .container {
    padding: 10px 40px;
    position: relative;
    background-color: inherit;
    width: 50%;
  }
  .container::after {
    content: '';
    position: absolute;
    width: 25px;
    height: 25px;
    right: -17px;
    background-color: white;
    border: 4px solid #f00;
    top: 15px;
    border-radius: 50%;
    z-index: 1;
  }
  .right::after {
    left: -17px;
  }
  img {
    max-width: 100%;
    height: auto;
  }
</style>
</head>
<body>

<div class="timeline" style="position: relative; max-width: 1200px; margin: 0 auto">
  <div class="container left" style="left: -29.4%">
    <div class="content" style="padding: 20px 30px; background-color: white; position: relative; border-radius: 6px;">
      <hr>
      <h2 style="text-align: cemter">Initial Physical IT Asset Form</h2>
      <hr>
      <img src="./assets/images/PhysicalAsset.png" alt="Image 1" width="75%" height="auto">
      <p style="font-weight: bolder; text-align:left">Above image is an example of a paper asset form. This asset form is used to keep track of assets that belong to its users. There are several disadvantages:</p>
      <p style="text-align:left">• Time-consuming and Labor-intensive</p>
      <p style="text-align:left">• Prone to Human Error</p>
      <p style="text-align:left">• Lack of Real-time Updates</p>
      <p style="text-align:left">• Difficulty in Sharing and Accessing Information</p>
      <p style="text-align:left">• Limited Security</p>
      <p style="text-align:left">• No Backup</p>
      <p style="text-align:left">• Space Constraints</p>
      <p style="text-align:left">• Inefficiency in Analysis and Reporting</p>
      <p style="text-align:left">• Environmental Impact</p>
      <p style="text-align:left">• Inability to Integrate</p>
    </div>
  </div>
  <div class="container right" style="left: 29.4%;">
    <div class="content" style="padding: 20px 30px; background-color: white; position: relative; border-radius: 6px;">
      <hr>
      <center><h2>Digital Asset Form</h2></center>
      <hr>
      <img src="./assets/images/DigitalAsset.png" alt="Image 2" width="75%" height="auto">
      <p style="font-weight: bolder;">Using PowerApps, I have transformed the paper and pen tracking asset system into digitalised method. This method uses sharepoint, making it easier to access, maintain and retrieve information. Technology is leveraged to enhance the product to a more transparent, secure and user-friendly system that meets the compliance requirements.</p>
    </div>
  </div>
  <div class="container left" style="left: -29.4%">
    <div class="content" style="padding: 20px 30px; background-color: white; position: relative; border-radius: 6px;">
      <hr>
      <center><h2>Flow & Process</h2></center>
      <hr>
      <center><embed src="./docs/Project Proposal.pdf#toolbar=0&navpanes=0&scrollbar=0" type="application/pdf" width="400" height="250"></center>
      <p style="font-weight: bolder; text-align:left">The comprehensive flow and process of our latest project through the embedded PDF above. This document meticulously outlines each step of our approach, from inception to completion, and delves into the key benefits that stem from innovative strategies. Gain insights into methodical procedures and the significant advantages they offer, providing a clear understanding of the project's value and efficiency. This detailed guide serves as a testament to our commitment to excellence and the impactful results.</p>
    </div>
  </div>
</div>

</body>
</html>

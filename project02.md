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
  <div class="container left" style="left: -32%">
    <div class="content" style="padding: 20px 30px; background-color: white; position: relative; border-radius: 6px;">
      <hr>
      <h2 style="text-align: right">Initial Physical IT Asset Form</h2>
      <hr>
      <img src="./assets/images/PhysicalAsset.png" alt="Image 1" width="75%" height="auto">
      <p style="font-weight: bolder;">Above image is an example of a paper asset form. This asset form is used to keep track of assets that belong to its users. There are several disadvantages:</p>

      <p>• Time-consuming and Labor-intensive</p>
      <p>• Prone to Human Error</p>
      <p>• Lack of Real-time Updates</p>
      <p>• Difficulty in Sharing and Accessing Information</p>
      <p>• Limited Security</p>
      <p>• No Backup</p>
      <p>• Space Constraints</p>
      <p>• Inefficiency in Analysis and Reporting</p>
      <p>• Environmental Impact</p>
      <p>• Inability to Integrate</p>
    </div>
  </div>
  <div class="container right" style="left: 30%;">
    <div class="content" style="padding: 20px 30px; background-color: white; position: relative; border-radius: 6px;">
      <hr>
      <h2>Digital Asset Form</h2>
      <hr>
      <img src="./assets/images/DigitalAsset.png" alt="Image 2" width="75%" height="auto">
      <p style="font-weight: bolder;">Using PowerApps, I have transformed the paper and pen tracking asset system into digitalised method. This method uses sharepoint, making it easier to access, maintain and retrieve information. Technology is leveraged to enhance the product to a more transparent, secure and user-friendly system that meets the compliance requirements.</p>
    </div>
  </div>
  <div class="container left" style="left: -33%">
    <div class="content" style="padding: 20px 30px; background-color: white; position: relative; border-radius: 6px;">
      <h2 style="text-align: right">Flow & Process</h2>
      <embed src="./docs/Project Proposal.pdf" type="application/pdf" width="600" height="400" />
      <p style="font-weight: bolder;">The comprehensive flow and process of our latest project through the embedded PDF above. This document meticulously outlines each step of our approach, from inception to completion, and delves into the key benefits that stem from innovative strategies. Gain insights into methodical procedures and the significant advantages they offer, providing a clear understanding of the project's value and efficiency. This detailed guide serves as a testament to our commitment to excellence and the impactful results.</p>
    </div>
  </div>
</div>

</body>
</html>

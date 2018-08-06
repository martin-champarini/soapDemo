_soapDemo_

**To test the soap-server use:**

1 - Open the postman (or directly with SOAPUI)  
2 - Select POST.  
3 - In the body, select raw and paste this  

<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
				  xmlns:gs="http://localhost:8080/soap-server">
   <soapenv:Header/>
   <soapenv:Body>
      <gs:getCountryRequest>
         <gs:name>Spain</gs:name>
      </gs:getCountryRequest>
   </soapenv:Body>
</soapenv:Envelope>



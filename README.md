<p align="center">
  <a href="https://www.btc-banco.com">
      <img src="https://s3.amazonaws.com/assinaturas-de-emails/btc.png" alt="Grupo Bitcoin Banco"/>
  </a>
</p>

## Challenge for Developer

A customer needs to search in our orderbook (available in this <a href="https://github.com/Bitcoin-Banco-Cryptocurrency/Challenge-OneDay/blob/master/OrderBook.json">JSON</a>) and he wants to buy offers below some price also sell offer offer to recieve some money.
Based on this you will need to develop:

- a simple API to search offers in the .json available;
- it should be possible to search for offer by their amount (one or more);
- it must be possible to order the result by price (asc and desc);

The test should be done in Ruby, Go, Python or Node and we do like if you avoid frameworks. We expect at the end of the test, outside the API running, the following items:

- an explanation of what is needed to make your project work;
- an explanation of how to perform the tests;

Remember that at the time of the evaluation we will look at:

- Code organization;
- Object-Oriented Principles;
- Maintenance;

To send us your code, you must:

Make a fork of this repository, and send us a pull-request.


*****************************
@author: Pedro Henrique Lino Trautwein Nunes

1. open cmd on this directory 
2. npm i  //install the dependencies 
3. npm start  //run project
4. Test:

To test the API, you must set values of amount (ex: 0.5) and/or price (asc or desc) to the url:

Example: 

http://localhost:8080/api/asks?amount=0.5
http://localhost:8080/api/asks?amount=0.5&amount=0.63322053&amount=1&price=desc
http://localhost:8080/api/bids?amount=1&price=desc
http://localhost:8080/api/bids?amount=0.5&amount=1&price=desc

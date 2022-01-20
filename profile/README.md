<img src="https://i.postimg.cc/J7q3q5fD/asdf.jpg" width="100%" height="250px"/>

# Restaurant system

# Case 

The process in a restaurant is usually the same. Customers get seated, are hand over the menu, order drinks and food, consume the drinks and food and finally have dessert. A restaurant has a new idea to convert the above process to a digital experience. You will be developing the requested proof of concept in an agile fashion. Initially you'll focus on the MVP (the most important features) and then continue to flesh out the application.  

## Milestone 1 (the MVP) 

After being welcomed by the staff, a customer takes seat at a table in the restaurant. On each table in the restaurant, a QR-code is placed. When a customer scans the QR-code, they will be presented with the digital menu of the restaurant. By scanning the QR-code and opening the application, the system should register their table and open a new session for the duration of the customer's stay.  

The customer should then be able to order from the digital menu. When the customer submits their order, it should be sent in real-time to the kitchen staff, who must then process the order. They will receive the order in a 'live-view'-screen in the kitchen. The system should aid the kitchen staff in organizing their work. A way to see which orders are new, processing and completed is preferred. 

## Milestone 2 

The digital menu has a certain structure. Maybe there are categories of dishes, the dishes themselves, ingredients of the dishes and their nutritional information. The restaurant owner or the chef can administrate the products of the digital menu, in order to keep it up to date.  

## Milestone 3 

The restaurant wants to have an inventory management system. This system should be able to be updated from the customer (when ordering something) or the kitchen (when creating waste or getting new inventory). This system needs to make sure that customers are not able to order a meal when this is not available. 
 
# [Our Product Demo Video](https://youtu.be/SHjgVsHp1Sk)

## Front-end

- <a href="https://github.com/DB01-4/Qr-frontend">QR frontend</a>
- <a href="https://github.com/DB01-4/24Eat">24Eat</a>
- <a href="https://github.com/DB01-4/24eat-admin">24Eat admin</a>

## Back-end

<a href="https://github.com/DB01-4/QRService">QRService</a>

- GET: <code>/api/qrs</code>
- GET: <code>/api/qr/{id}</code>
- PUT: <code>/api/update/{id}</code>
- GET: <code>/api/check/{tableKey}</code>
- GET: <code>/api/gettable/{tableKey}</code>

<hr/>

<a href="https://github.com/DB01-4/QRService">MenuService</a>

- GET: <code>/api/items</code>
- GET: <code>/api/item/{id}</code>
- POST: <code>/api/item/post</code>
- PUT: <code>/api/item/update/{id}</code>

<hr/>

<a href="https://github.com/DB01-4/QRService">IMSService</a>

- GET: <code>/api/items</code>
- GET: <code>/api/item/{id}</code>
- POST: <code>/api/item/post</code>
- PUT: <code>/api/item/update/{id}</code>
- DELETE: <code>item/delete/{id}</code>

<hr/>


<a href="https://github.com/DB01-4/QRService">Websocket</a>

## Other services

<a href="https://auth0.com/">Auth0</a>

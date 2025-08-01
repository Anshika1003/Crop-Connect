# CropConnect

CropConnect is a web platform designed for wholesale crop trading, connecting sellers and consumers seamlessly. Although still in development, CropConnect offers a robust set of features for both sellers and consumers in the agricultural marketplace.

## 🚀 Deployment

The project is fully deployed and live:

- 🌐 **Live URL:** [Crop Connect](https://crop-connect-lake.vercel.app/)
- 🎨 **Frontend:** Deployed on [Vercel](https://vercel.com)
- 🔧 **Backend:** Deployed on [Render](https://render.com)

## Features

1. **Dual Interfaces**: CropConnect provides separate interfaces for consumers and sellers, accessible through the navbar with options for SignUp and SignIn including email verification for the created account.

***Seller Side***

2. **Visualizing Sales Data**: Incorporated Recharts (graphs) into the project, which has allowed to create insightful visualisations of sales data.

3. **Product Management**: Sellers can easily add products, including images, details, location via map selection, current stocks, minimum order quantity restrictions, etc. which can be edited and deleted further.

4. **Order Management**: Sellers have access to a dashboard displaying order requests, including order location coordinates on a map.

5. **FAQ Section**: Sellers can address common inquiries about their products through a dedicated FAQ section visible to consumers.

6. **CropSense AI**: Powered by Gemini AI, used to predict the crops according to the given parmeters.

***Consumer Side***

7. **User-Friendly Consumer Interface**: Consumers can browse various categories and products conveniently from the homepage.

8. **Detailed Product Dashboard**: Product details, including stock availability and minimum order quantity, are displayed prominently. Users can add products to their cart directly from the dashboard.

9. **Review System**: Users can leave reviews for products, enhancing transparency and trust.

10. **Contact Farmer Form**: A contact form allows users to inquire about products directly, with answered queries becoming part of the FAQ section. It also has map which shows the product location.

11. **Dynamic Cart Functionality**: Users can manage product quantities in the cart, with limitations based on minimum order quantities and available stock.

12. **Seamless Checkout**: The checkout process allows users to review orders, including delivery charges, select delivery locations, and place orders securely.

13. **Real-Time Stock Updates (WebSocket)**: Implemented WebSocket functionality to provide real-time stock updates. Users can see live changes in stock availability without needing to reload the page. *Please note that this feature may not be visible on the deployed website (deployed on Vercel) as Vercel does not support WebSocket connections. However, if the project is run locally, real-time updates can be seen.*

## Technologies Used

- MongoDB
- NodeJS
- ExpressJS
- ReactJS
- Redux
- Tailwind CSS
- Websocket (socket.io)
- Cloudinary (for image storage)
- Leaflet (for map)
- Unsplash (for images)
- Recharts (for graphs)
- Gemini AI
- Other supporting technologies

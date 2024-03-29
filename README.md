# WattWise

Our application is designed to help you monitor your electricity consumption, reduce your bills, and conserve energy. You can input the wattage and usage hours for each appliance, and the application stores this data for future reference. Additionally, our machine learning model, which is based on the PyTorch LSTM deep learning technique, provides accurate predictions of your future electricity usage. This allows you to plan and adjust your energy usage so that you can be more cost-effective and sustainable. Get started with our application today and start saving!

Apart from tracking and predicting electricity usage, our application offers an easy-to-read graph that compares your energy consumption with the statewise average. This feature helps you understand how your energy usage stacks up against others in your area, allowing you to make informed choices to conserve energy. By using our application's features, you'll be able to make wise energy-saving decisions that not only positively impact your finances but also contribute to a sustainable future.


# Tech Stack Utilized
- NodeJS 
- ReactJS
- Pytorch ( Python )
- Firebase ( database, authentication )

# System Architecture
![architecture](https://cdn.discordapp.com/attachments/835750351621718030/1091396806518251530/final.png)

# Features
- Calculates electricity consumption for each appliance based on wattage and hours usage.
- Stores data in a database for future reference.
- Provides personalized recommendations on how to save energy.
- Includes a highly accurate machine learning model for prediction of electricity consumption.
- Offers a visual representation of your electricity.
- consumption compared to the average consumption in your state or region.

# Docker Environment
### Clone the repository to your local machine.
```
git clone https://github.com/Aryan-Deshpande/WattWise
cd gsc
docker compose up
```

# Local Machine Environment
### Clone the repository to your local machine.
```
git clone https://github.com/Aryan-Deshpande/WattWise
```

### Terminal 1
```
cd Frontend
```

### Install Dependencies
```
npm install
```

### Start script<sub>
```
npm start
```
<br>
<br>

### Terminal 2
```
cd Backend
```

### Install Dependencies
```
npm install
```

### Start script
```
node server.js
```

# 2420-Assignment2
  # <ins>**1.Digigtal Ocean infrastructure:</ins>

<img width="982" alt="image" src="https://user-images.githubusercontent.com/91557605/205423596-bcd0ba14-58f1-44c2-82d5-1f61be2b836c.png">

<img width="910" alt="image" src="https://user-images.githubusercontent.com/91557605/205423931-3fdf1dad-4170-47ec-a204-327d0755baf8.png">

<img width="934" alt="image" src="https://user-images.githubusercontent.com/91557605/205423945-56b3cbff-e030-44f7-bcd6-0a108c3f0444.png">

<img width="940" alt="image" src="https://user-images.githubusercontent.com/91557605/205423967-1eadc503-80d8-4af0-bfa3-c8219d6573fe.png">

  # <ins>**2.Creating regular user:</ins>

<img width="642" alt="ub2-1" src="https://user-images.githubusercontent.com/91557605/205424009-b53f1cf3-c745-456d-8ff6-f5b5cb1bfcb5.png">

<img width="649" alt="image" src="https://user-images.githubusercontent.com/91557605/205424119-f1f6de8d-109a-4bfb-b565-7a215c74e6ed.png">

  # <ins>**3.Installing a web server:</ins>

  Before installing nginx or caddy check for update your server
  ```
  sudo apt update
  ```
  
 <img width="642" alt="image" src="https://user-images.githubusercontent.com/91557605/205425870-0915a3b2-1dee-45eb-90e6-8501d40c8cf1.png">

  update your server
  ```
  sudo apt upgrade
  ```
  <img width="644" alt="image" src="https://user-images.githubusercontent.com/91557605/205425942-8acd89e3-8d69-4253-b2c8-45c9b484574e.png">

  ###On my first server I installed nginx and on my second server I installed caddy

  To install nginx run
  ```
  sudo apt install nginx
  ```
  
  <img width="643" alt="image" src="https://user-images.githubusercontent.com/91557605/205426035-cbd4759a-c4c1-4f82-876d-ba280acaa01a.png">

  To install caddy run
  ```
  sudo apt install -y debain-keyring debain-archive-keyring apt-transport-hhtps
  ```

  <img width="640" alt="ub2-3-1-1" src="https://user-images.githubusercontent.com/91557605/205426305-e82b2fcb-2eac-4d51-a9d0-1d2b48028d7e.png">

  ###note: if you got a pink page asking for restart just press Tab to go to OK and then press Enter

  # <ins>**4.Creating web app: </ins>
  
  <img width="632" alt="image" src="https://user-images.githubusercontent.com/91557605/205428548-7c963dc9-d43c-466e-bfc0-fe2a8f0293fe.png">

  <img width="649" alt="image" src="https://user-images.githubusercontent.com/91557605/205428523-213a37ee-05c0-4843-97e6-f912ea980c79.png">
  
  <img width="640" alt="image" src="https://user-images.githubusercontent.com/91557605/205428562-41dcb825-572d-4160-bb38-27dc90a6940b.png">

  After you created your index.html file in html folder and index.js file in your src folder. Go to your src folder and run this
  ```
  nmp i
  ```
  <img width="636" alt="image" src="https://user-images.githubusercontent.com/91557605/205428714-5d9f76e2-7c70-4a69-ac6e-6f23ebea49ae.png">

  
  # <ins>**5. Writing Caddyfile and nginx serve block:</ins>
  
  <img width="647" alt="image" src="https://user-images.githubusercontent.com/91557605/205428881-da6d332f-9d0a-46e5-955a-4a78fd20c806.png">
  
  # <ins>**6.Installing node and volta: </ins>
  
   <img width="638" alt="ub2-2" src="https://user-images.githubusercontent.com/91557605/205428892-4d4decbd-bf80-455e-9823-af8aa917ca59.png">

  # <ins>**7.Write a service file named hello_web.service to start node:</ins>
  
  <img width="646" alt="image" src="https://user-images.githubusercontent.com/91557605/205428861-c49835c3-ac96-4770-8308-2c21cc3451f0.png">
  
  put your service files in proper location as shown in the screen shots
  
  # <ins>**9.Test you codes by loading your service files and running your balance loader in a browser:</ins>
  
  <img width="639" alt="image" src="https://user-images.githubusercontent.com/91557605/205428999-0e837e82-b5c0-43d6-84fb-a2480d23d433.png">

  <img width="643" alt="image" src="https://user-images.githubusercontent.com/91557605/205429037-bc5cebfb-6016-4945-b578-4dddcb575ad7.png">
  
  # <ins>**10.The outputs:</ins>
 
  <img width="279" alt="image" src="https://user-images.githubusercontent.com/91557605/205429089-48d94652-b556-412a-8071-77e29ce5f426.png">

  <img width="278" alt="image" src="https://user-images.githubusercontent.com/91557605/205429110-028903bd-4e58-4168-8ed8-dd15f1d08053.png">

  <img width="310" alt="image" src="https://user-images.githubusercontent.com/91557605/205429124-29a0404f-59ae-47ef-8d87-68a07708ebe6.png">

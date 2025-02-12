# TajaTrace

# 🌱 **TajaFarm Order Fulfillment Process**  

## **1️⃣ Farmer Registration via Geo-Krishi**  
Farmers register on **TajaFarm** through the **Geo-Krishi** app, receiving a **unique Farmer ID**.  

| **Farmer ID** | **Name**       | **Location** | **Crops Grown**        |
|--------------|---------------|-------------|----------------------|
| **F001**     | Ram Shrestha  | Kavre       | Tomatoes, Cabbage  |
| **F002**     | Sita Gurung   | Chitwan     | Potatoes, Carrots  |
| **F003**     | Hari Tamang   | Dhading     | Onions, Tomatoes   |
| **F004**     | Gopal KC      | Nuwakot     | Cabbage, Potatoes  |
| **F005**     | Maya Rai      | Ilam        | Carrots, Onions    |

---

## **2️⃣ Orders Received**  
TajaFarm receives **multiple orders from supermarkets and restaurants**, each with specific quantity needs.  

| **Order ID**  | **Customer Name**            | **Required Items**                     |
|--------------|-----------------------------|--------------------------------------|
| **O1001**    | Bhatbhateni Supermarket     | 20 kg Tomatoes, 15 kg Potatoes, 10 kg Carrots |
| **O1002**    | Big Mart                     | 10 kg Cabbage, 8 kg Tomatoes        |
| **O1003**    | KK Restaurant                | 15 kg Onions, 12 kg Carrots         |
| **O1004**    | Fresh Market                 | 18 kg Potatoes, 10 kg Cabbage       |

---

## **3️⃣ Collection from Farmers**  
TajaFarm **collects vegetables from multiple farmers**, ensuring proper tracking. Each collection is **packed in a uniquely labeled bag** for identification.  

| **Bag ID** | **Farmer ID** | **Vegetable** | **Collected Quantity** |
|-----------|--------------|--------------|----------------------|
| **B101**  | F001         | Tomatoes     | 10 kg               |
| **B102**  | F002         | Potatoes     | 15 kg               |
| **B103**  | F003         | Cabbage      | 5 kg                |
| **B104**  | F001         | Tomatoes     | 8 kg                |
| **B105**  | F002         | Carrots      | 10 kg               |
| **B106**  | F003         | Onions       | 8 kg                |
| **B107**  | F004         | Potatoes     | 10 kg               |
| **B108**  | F005         | Onions       | 7 kg                |
| **B109**  | F005         | Carrots      | 5 kg                |
| **B110**  | F004         | Cabbage      | 8 kg                |

---

## **4️⃣ System-Generated Packaging**  
The system **automatically groups collected vegetables into packages** based on orders to avoid shortages and ensure efficient distribution. Each package is assigned a **QR code for tracking**.  

| **Packet ID** | **Order ID** | **Bags Included**          | **Total Weight** | **QR Code Link**                |
|-------------|-------------|--------------------------|---------------|--------------------------------|
| **P001**    | O1001       | B101, B102, B105         | 20 kg Tomatoes, 15 kg Potatoes, 10 kg Carrots | www.tajafarm.com/track/P001 |
| **P002**    | O1002       | B103, B104               | 10 kg Cabbage, 8 kg Tomatoes  | www.tajafarm.com/track/P002 |
| **P003**    | O1003       | B106, B109, B108         | 15 kg Onions, 12 kg Carrots | www.tajafarm.com/track/P003 |
| **P004**    | O1004       | B107, B110               | 18 kg Potatoes, 10 kg Cabbage | www.tajafarm.com/track/P004 |

---

## **5️⃣ Final Delivery & QR Code Scanning**  
- Each package is **delivered to the respective customer**.  
- **At the time of receipt**, customers **scan the QR code** to confirm **delivery date and time**.  

| **Packet ID** | **Order ID** | **Received By**             | **Received Date & Time** |
|-------------|-------------|----------------------------|-----------------------|
| **P001**    | O1001       | Bhatbhateni Supermarket   | 2024-02-09, 10:30 AM |
| **P002**    | O1002       | Big Mart                  | 2024-02-09, 11:15 AM |
| **P003**    | O1003       | KK Restaurant             | 2024-02-09, 12:00 PM |
| **P004**    | O1004       | Fresh Market              | 2024-02-09, 12:45 PM |

---


# TajaTrace

# 🌱 **TajaFarm Order Fulfillment Process**  

## **1️⃣ Farmer Registration via Geo-Krishi**  
Farmers register on **TajaFarm** through the **Geo-Krishi** app, receiving a **unique Farmer ID**.  

| **Farmer ID** | **Name**       | **Location** | **Crops Grown**        |
|--------------|---------------|-------------|----------------------|
| **F1**     | Ram Shrestha  | Kavre       | Tomatoes, Cabbage  |
| **F2**     | Sita Gurung   | Chitwan     | Potatoes, Carrots  |
| **F3**     | Hari Tamang   | Dhading     | Onions, Tomatoes   |
| **F4**     | Gopal KC      | Nuwakot     | Cabbage, Potatoes  |
| **F5**     | Maya Rai      | Ilam        | Carrots, Onions    |

---

## **2️⃣ Orders Received**  
TajaFarm receives **multiple orders from supermarkets and restaurants**, each with specific quantity needs.  

| **Order ID**  | **Customer Name**            | **Required Items**                     |
|--------------|-----------------------------|--------------------------------------|
| **O11**    | Bhatbhateni Supermarket     | 20 kg Tomatoes, 15 kg Potatoes, 10 kg Carrots |
| **O12**    | Big Mart                     | 10 kg Cabbage, 8 kg Tomatoes        |
| **O13**    | KK Restaurant                | 15 kg Onions, 12 kg Carrots         |
| **O14**    | Fresh Market                 | 18 kg Potatoes, 10 kg Cabbage       |

---

## **3️⃣ Collection from Farmers**  
TajaFarm **collects vegetables from multiple farmers**, ensuring proper tracking. Each collection is **packed in a uniquely labeled bag** for identification.  

| **Bag ID** | **Farmer ID** | **Vegetable** | **Collected Quantity** |
|-----------|--------------|--------------|----------------------|
| **B101**  | F1         | Tomatoes     | 10 kg               |
| **B102**  | F2         | Potatoes     | 15 kg               |
| **B103**  | F3         | Cabbage      | 5 kg                |
| **B104**  | F1         | Tomatoes     | 8 kg                |
| **B105**  | F2         | Carrots      | 10 kg               |
| **B106**  | F3         | Onions       | 8 kg                |
| **B107**  | F4         | Potatoes     | 10 kg               |
| **B108**  | F5         | Onions       | 7 kg                |
| **B109**  | F5         | Carrots      | 5 kg                |
| **B110**  | F4         | Cabbage      | 8 kg                |

---

## **4️⃣ System-Generated Packaging**  
The system **automatically groups collected vegetables into packages** based on orders to avoid shortages and ensure efficient distribution. Each package is assigned a **QR code for tracking**.  

| **Packet ID** | **Order ID** | **Bags Included**          | **Total Weight** | **QR Code Link**                |
|-------------|-------------|--------------------------|---------------|--------------------------------|
| **P1**    | O11       | B101, B102, B105         | 20 kg Tomatoes, 15 kg Potatoes, 10 kg Carrots | www.tajafarm.com/track/P1 |
| **P2**    | O12       | B103, B104               | 10 kg Cabbage, 8 kg Tomatoes  | www.tajafarm.com/track/P2 |
| **P3**    | O13       | B106, B109, B108         | 15 kg Onions, 12 kg Carrots | www.tajafarm.com/track/P3 |
| **P4**    | O14       | B107, B110               | 18 kg Potatoes, 10 kg Cabbage | www.tajafarm.com/track/P4 |

---

## **5️⃣ Final Delivery & QR Code Scanning**  
- Each package is **delivered to the respective customer**.  
- **At the time of receipt**, customers **scan the QR code** to confirm **delivery date and time**.  

| **Packet ID** | **Order ID** | **Received By**             | **Received Date & Time** |
|-------------|-------------|----------------------------|-----------------------|
| **P1**    | O11       | Bhatbhateni Supermarket   | 2024-02-09, 10:30 AM |
| **P2**    | O12       | Big Mart                  | 2024-02-09, 11:15 AM |
| **P3**    | O13       | KK Restaurant             | 2024-02-09, 12: PM |
| **P4**    | O14       | Fresh Market              | 2024-02-09, 12:45 PM |

---




# 🌍 عنوان الـ IP في **Network Layer**

## 🟢 1) الشرح بالعربية

🔹 فالـ **Network Layer**، أهم حاجة هي **IP Addressing**.  
العنوان ديال الـ IP كيخلي أي جهاز فالشبكة يتعرف عليه بوحدو، بحال العنوان ديال دارك.

📌 مكونات الـ IP Address (IPv4):

- 🏠 **Network Address** → كيعرف الشبكة (بحال اسم الزنقة).
    
- 👤 **Host Address** → كيعرف الجهاز داخل الشبكة (بحال رقم الدار).
    
- 🎭 **Subnet Mask** → كيعرف شحال من Bits مخصصة للشبكة وشحال مخصصة للأجهزة.
    

🔹 **IP Source / Destination**:

- Source IP 📨 → الجهاز لي بعت المعلومة.
    
- Destination IP 📬 → الجهاز لي خاصو يتوصل بالمعلومة.
    

🔹 **Packet** ✉️:  
المعلومة كتتحول لــ **Packet** فيه:

- Source IP
    
- Destination IP
    
- Data
    

💡 مثال:  
عندنا جهاز بـ IP: `192.168.1.10` كيصيفط Packet لجهاز آخر بـ IP: `192.168.1.20`.  
الـ Network Layer غادي يدير العنوان ديال المرسل (Source) والعنوان ديال المستقبل (Destination) فالـ Packet باش يعرفو الطريق.

---

## 🔵 2) Explanation in English

In the **Network Layer**, the main job is **IP Addressing** 🌍.  
An IP address identifies each device uniquely in the network, just like your home address.

📌 Components of an IPv4 Address:

- 🏠 **Network Address** → identifies the network (like the street name).
    
- 👤 **Host Address** → identifies the device in that network (like the house number).
    
- 🎭 **Subnet Mask** → separates the network part and the host part.
    

🔹 **Source & Destination IP**:

- **Source IP** 📨 = the device sending the data.
    
- **Destination IP** 📬 = the device receiving the data.
    

🔹 **Packet** ✉️:  
The data is encapsulated into a **Packet**, which includes:

- Source IP
    
- Destination IP
    
- The actual data
    

💡 Example:  
Device `192.168.1.10` sends a **Packet** to device `192.168.1.20`.  
The Network Layer adds both Source and Destination IP addresses to ensure the packet reaches the correct device.

---

📊 **تشبيه سهل**:  
الـ Packet بحال رسالة مكتوبة، خاصك تكتب العنوان ديالك (Source) + العنوان ديال المستقبل (Destination) باش توصل فالطريق الصحيح.

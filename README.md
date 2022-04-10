# How-To-add-QR-Code-In-jasper-using-JasperSoft-Studio [Tibco-JasperSoft-Studio]

▶️  Configration in JasperSoft Studio

**_1. In jasper Studio Select Option Barcode in that Select QR._**
  
 ![image](https://user-images.githubusercontent.com/55349992/162631610-40d30d3b-32d7-4592-9055-370cb9ad08a1.png)
    
  **_2.In QR Propeties Select Code Expression and add your variable Or Data in Code Expression Field.
    Select Now in Evaluation Time._**
    
  ![image](https://user-images.githubusercontent.com/55349992/162631620-3fffcae4-5123-43fa-8591-7f7aa7e27478.png)


  **_3. Add Jar File In JasperSoft Studio For Genrate QR Code._**
    
  👉 Select Project From Menu   
       
  ![image](https://user-images.githubusercontent.com/55349992/162631357-a7f6380e-42f5-40ce-9d9a-359983dd5f11.png)

   👉 Propeties 👉  java build Path 👉 libraries 👉 add external jar select you path where you have download your jar.
     
   ![image](https://user-images.githubusercontent.com/55349992/162631571-10d014f9-28bc-4e7e-9e4f-b1f10dccdd5c.png)

     

▶️  Configration in Your IDE

  **_1. In your IDE **WebContent/WEB-INF/classes** make jasperreports.properties file [ if not created create or else update] ._** in file Write      
       👉 net.sf.jasperreports.components.barcode4j.image.producer=image

  **_2. Add jar Files in your lib folder._**

⚡ **_I have add jars and Property file you can download in your system._**




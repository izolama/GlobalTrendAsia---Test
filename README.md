# GlobalTrendAsia---Test
My test

# story 
Thank you to my friend who is willing 
to lend me a laptop so i can continue 
to grow and take job test.
This is instagram [Maulana Yusuf](https://instagram.com/mhaul19?utm_medium=copy_link) 

## Introduction  
This is a code repository for the corresponding to test in [Pt.Global Trend Asia](https://www.globaltrendasia.com)

Using React, Tailwind & Sanity to build a Full Stack Social Media Application - from start to finish.

## [Touch This To Views](https://javazolshare.netlify.app/login)
- javazol - share App

## Section Technical & Fullstack 

- Homepage

![Homepage](https://user-images.githubusercontent.com/55181621/147916899-aa74c249-935e-4fab-8f55-6cea0b91013b.png)

- PinDetails

![PinDetails](https://user-images.githubusercontent.com/55181621/147917065-db10471d-48a9-4e87-9251-33dcf8ad7abb.png)


## Section Query

```javascript
 -1.  create table karyawan     
                                
      QUERY = CREATE TABLE karyawan ( id INT ( 10 ) 
              PRIMARY KEY, nama_depan VARCHAR ( 30 ),
              nama_belakang VARCHAR ( 30 ), 
              tanggal_masuk DATE, tanggal_keluar DATE,
              penghasilan INT (100) )
              
      QUERY = INSERT INTO `pegawai` (`id`, `nama_depan`, `nama_belakang`, `tanggal_masuk`, `tanggal_keluar`, `penghasilan`) VALUES 
              ('2', 'wawa', 'Bastian', '2010-02-12', 'null', '20000'), ('3', 'Pevita', 'Pierce', '2012-03-14', 'null', '30000'), 
              ('4', 'janien', 'Wieghel', '2013-09-10', '2014-01-01', '20000'), ('5', 'Lucinta', 'Luna', '2013-09-10', 'null', '20000'), 
              ('6', 'Nikita,', 'William', '2015-04-10', '2015-05-01', '60000')
              
 -2.  create table kPI
   
       QUERY = create table table kpi (
              id INT (10) PRIMARY KEY,
              id_pegawai (30),
              tanggal_review DATE
              )
              
       QUERY = INSERT INTO `kpi` (`id`, `id_pegawai`, `tanggal_review`) VALUES ('20', '2', '2016-04-12'),('30', '10', '2015-02-13'), 
               ('40', '22', '2010-10-12'),('50', '11', '2009-01-01'),('60', '12', '2009-03-03'),('70', '13', '2008-12-01'),
               ('80', '1', '2003-04-12'),('90', '1', '2014-04-30')      
         
```    
# table 

![PinDetails]![image](https://user-images.githubusercontent.com/55181621/147935590-9856fb2d-cba8-456f-90e1-fe4672dec812.png)

## syntax query concat desc 


         ```javascript
         SELECT CONCAT(nama_depan, nama_belakang) FROM pegawai ORDER by nama_belakang ASC ,nama_depan DESC
         
         ```







# Сара Јанкуловска 223227
2.
 ![SIIIIIIIIIIIIIIIII drawio](https://github.com/jankulovska/SI_2024_lab2/assets/134975577/b7ff6b74-742d-43fe-9979-4b0e6f85648b)
3. Цикломатската комплексност според бројот на региони е 10.
   
4.
 ![image](https://github.com/jankulovska/SI_2024_lab2/assets/134975577/5f078772-058a-4fae-aafd-8885ee42327b)
  Во првиот test case функцијата прима празна листа што доведува до тоа да се случи Exception, односно "allItems list can't be null!" exception-от, по кој завршува програмата.
  
  Во вториот test case има невалиден карактер (буква) во баркодот на Item што доведува до тоа да се случи Exception, односно "Invalid character in item barcode!" exception-от, по кој завршува програмата.
  
  Во третиот test case се опфаќа условот името на Item да е null и соодветно со останатите вредности на атрибутите на објектот функцијата враќа true.
  
  Во четвртиот test case функцијата прима null баркод што доведува до тоа да се случи Exception, односно "No barcode!" exception-от, по кој завршува програмата.
  
  Во петтиот test case сите атрибути на функцијата се точни и се исполнува условот
  if (item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0') по што функцијата враќа false.

6.
![image](https://github.com/jankulovska/SI_2024_lab2/assets/134975577/b85d4b47-aa74-4189-84c9-ebf48da1fe6b)
  Во првиот test case имаме ТТТ, односно трите атрибути го задоволуваат дадениот услов.
  
  Во вториот test case имаме ТТF, два од три атрибути ги исполнуваат соодветните услови, а по проверката кај третиот се излегува од условот.
  
  Во третиот test case TFX, само првиот атрибут го исполнува условот и поради тоа по проверката на вториот атрибут се излегува од условот.
  
  Во четвртиот test case по проверката на првиот атрипут се излегува од условот бидејќи не е исполнет.


# railway-reservation-database-system
This railway database has been created with the help of mysql and  rdbms ,all of the code is mentioned in the file.
![image](https://user-images.githubusercontent.com/79567174/205478597-0e96a077-53cc-42f6-9264-0eb0be462793.png)
#E-R DIAGRAM OF ABOVE FILE
                                    SOURCE CODE OF DATABASE
                                    
  >>create table rail_details(R_type varchar(10), B_No varchar(20),origin varchar(15), details varchar(20), total_seats integer, dept_time varchar(20), arr_time varchar(20), fairperseat integer);

insert into rail_details values('Sl', 'pb2000', 'Ludhiana', 'navaseher', 75,'10pm','1am', 300),("GENERAL","PB2010","PATHANCOAT","JALANDHAR",80,"2pm","8am",250),("GENERAL","PB2348","CHANDIGARH","BHATINDA",60,"5AM","10AM",500),("AC","PB2008","CHANDIGARH","AMRITSAR",70,"7AM","12PM",500);



>>create table c_details(c_id interger(12), c_name varchar(20), age integer, addr varchar(35), ph_no integer(15), sex varchar(8), state varchar(20));

insert into c_details values('101', 'Ashish', '20', 'gandhi nagar gujrat','9936258296', 'Male', 'Gujrat'),('102', 'Vinod', '21', 'Pilibhit bareilly', '7814322120','Male', 'Uttar Pradesh'),('103', 'Sanjeev', '21', 'Pilibhit bareilly', '8968384789','Male', 'Uttar Pradesh'),('104', 'Tushar', '21', 'Malout Punjab', '9876550604','Male', 'Punjab'),('105', 'Summit', '21', 'D.L.W. Varanasi', '8968384798','Male', 'Uttar Pradesh);



>>create table RESERVATION (BNO varchar(30), R_Date date, Seats_Reserved integer, CID integer, receipt_no integer);

insert into RESERVATION values('pb2000',  '2010-12-08', '1', '101', '10101'),('pb2010',  '2010-12-09', '2', '102', '10102'),('pb2348',  '2010-10-10', '3', '103', '10103'),('pb2008','2010-10-31', '4', '104', '10104');                                  

# IITM-BLE-plugin
we build a BLE plugin and Android sending application and Android Receiving application. Then integrated the "developed" BLE plugin with "developed" Android Sending application A and it try to send some random data in a duration of 100ms, and it try to receive those data using "developed" android receiving  application B, and simultaneously store all sending and receiving data to AWS DynamoDB.  
i. Build a Bluetooth Android Plugin (from scratch) to communicate between android application A and android  application B.  
  - Application A should be data Sending application to Application B  
  - Application B should be data Receiving application from Application A  
ii. Upload a sending data to AWS DynamoDB, while sending to Application B  
iii. Upload a Receiving data to AWS DynamoDB, while Receiving from Application A
<h2>

<h5><b>FOR BLE without dynamoDB</b><br>
-----------------------------<br>
1)Install the app at two device<br>
2)Turn ON bluetooth<br>
3)enable DISCOVER in BOTH device<br>
4)click DISCOVER to REFERESH in both devices<br>
5)CHOOSE the pair form LIST in both devices<br>
6)click CONNECT in both devices<br>
7)CONNECTION ESTABLLISHED<br></h5>
--------------------------<br>
NOW SWITCH TO SEND MODE -APPLICATION A in one device and RECEIVER MODE IN another device<br>
=====================================================================
<h3>CLICK SEND 
and try each other vice versa</h3>




FOR BLE with dynamoDB
----------------------
<h3>NOTE</h3>
=====
YOUR NEED TO BUILD BEFORE INSTALL
===================================
<h5>1) create a dynamoDB and table
for tutorial https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SettingUp.DynamoWebService.html
2) change awsconfiguration.JSON,transform.conf.JSON,aws-amplify......JSON to your own account
for tutorail USE ABOVE LINK
OR
genearte it manually like
like this https://github.com/awslabs/aws-sdk-android-samples/blob/master/AmazonKinesisVideoDemoApp/src/main/res/raw/awsconfiguration.json WITHOUT YOUR OWN CREDENTIAL<br>
                                                                                                                                            ---------------------------

3) compile and run it</h5>







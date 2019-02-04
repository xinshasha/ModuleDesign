# EC500
It's a readme document for the architecture based on the design of Mohit.
## Alert Module
The input of this module should be the three inputs provided by the storage module. Actually the storage module does not change the value of
the input of the patient's data. So the alert module will take the data from the patient. The doctor should set a value when he/she uses the 
product at the first time. While using the product, if the data of the patient pass beyond the value, which is set by the doctor, the alert module will change a global value. Then there will be some alerts because of the change of the value such as the red light shinning or something else.

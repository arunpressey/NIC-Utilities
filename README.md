# NIC-Utilities
A tiny utility to extract useful information out of a Sri Lankan NIC number such as date of birth and gender.

The NIC numbers used as test cases and examples are randomly generated.
import lankaNIC from 'lanka-nic';

let { dateOfBirth, gender } = lankaNIC.getInfoFromNIC(nic);


dateOfBirt' should return: 1992-01-18T00:00:00.000Z - as an instance of Date
gender should return: female - as a String
Response : {"dateOfBirth": 1992-01-23T00:00:00.000Z, "gender": "male"}     


![Screenshot 2023-02-11 053326](https://user-images.githubusercontent.com/49364020/218224316-7466350a-10fa-47f7-b41b-c1f259527294.jpg)




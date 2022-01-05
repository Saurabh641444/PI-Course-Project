# PI-Course-Project
This repository contains code of my Process Instrumentation Course Project
## Objective:-
Tune a discrete PID controller and test the performance with a series of
setpoint changes over 10 min in the sequence from 23 degree C initially, 50 degree C at 10 sec, and
40degree C at 300 sec. Modify the tuning parameters to achieve a low Integral Absolute Error
between the measured temperature and the setpoint.
## Circuit Diagram:-
<br/>
<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/10577cfa-9d54-4e41-bd02-ead96ad1579a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220105T084009Z&X-Amz-Expires=86400&X-Amz-Signature=5d795aff7a26f2b863f48e28a8280fa151758082d8cbaeda7bc90f4651c71aa8&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" alt=""/>
<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/c6781603-dd5f-4f03-a4e6-da70eefa83c9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220105T084237Z&X-Amz-Expires=86400&X-Amz-Signature=9b348171d1f90bc652c2406fe4a806b8e2bce990ab49b5f317b1b443e36cad6d&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" alt=""/>


## Instead of Arduino uno we have use tclab simulation in python by using tclabModule 

## TCLab PID Control Simulator
A simulator is a useful tool to help evaluate changes in tuning before testing on
a physical system. Use the PID simulator to find acceptable control performance that
minimizes the integral absolute error between the setpoint and measured temperature.
<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/53049a6b-3685-46a6-8939-16d8cf03b3d1/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220105T084314Z&X-Amz-Expires=86400&X-Amz-Signature=e475e364ec1b01fd82e9feca207600f1861dba211f7554d45fb46cdb0be013fe&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" alt=""/>
## PID control validation
<img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/2e96b51d-f43c-4c52-ac70-c7944b0552a9/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220105%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220105T084443Z&X-Amz-Expires=86400&X-Amz-Signature=0520a1bd1ddc9fee4e1270aa193700f700de2da90fb97a2548214f1e6646b132&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" alt=""/>

## Conclusion
The value obtained by Arduino simulation= 2190.55

The value generated by python code= 1731.72

Mathematical value = Practical value

https://colab.research.google.com/drive/1LRPOx8qiBENGWRS9e-xx-XF8bBM4EdYo?authuser=1#scrollTo=JDLdWUKJqCnm
## Group members
1. Saurabh Jejurkar
2. Atharva Ingle
3. Aditya Hingole
4. Pratik Hublikar
5. Rachita Kalambarkar

---
title: "Design and Implementation of Permanent Magnet Synchronous Motor Control System Based on CAN Bus"
excerpt: "This topic is based on Controller Area Network(CAN) bus communication permanent magnet synchronous motor control system, which can be used in the head, robot dog, manipulator and other high precision and torque requirements of the field. The research content includes hardware design and software debugging of permanent magnet synchronous motor control system. Firstly, the mathematical model and derivation process of permanent magnet synchronous motor and magnetic field oriented control are understood by reading literature. Secondly, according to the function to be realized, a relatively new scheme is selected, that is, DRV8323S in the integrated drive chip DRV83 series of TI Company is used. The hardware design side of the motor driver chip initialization parameters and device selection parameters are calculated in detail, according to the results of the selection of appropriate inverter circuit devices and protective devices, and completed the hardware circuit design and welding. Part of the program design code uses the latest version of HAL library, and first realizes the calculation of CAN communication, ADC sampling and magnetic field oriented control. Finally, the PI parameters of the three rings are debugged, and the control effect is basically realized.<br/><img src='/images/FOC_Design/control_circuit.png' width='153' height='255'> &nbsp;&nbsp;<img src='/images/FOC_Design/drive_circuit.png' width='339' height='255'> &nbsp;&nbsp;<img src='/images/FOC_Design/FOC_Circuits.png' width='289' height='205'> <br/><br/>Programe flow chart of the Controller<br/><img src='/images/FOC_Design/program_flow_chart.png'>"
collection: project 

---

If you're interested, please take a look at the article: [Design and Implementation of Permanent Magnet Synchronous Motor Control System Based on CAN Bus](../../files/Design_and_Implementation_of_Permanent_Magnet_Synchronous_Motor_Control_System_Based_on_CAN_Bus_from_Wenhao_Liu.pdf)(In Chinese).

<video width="320" height="240" controls> <source src="/images/FOC_Design/Motor_start-stop_forward_and_reverse_rotation.mp4" type="video/mp4"> </video>

<iframe src="../../files/Design_and_Implementation_of_Permanent_Magnet_Synchronous_Motor_Control_System_Based_on_CAN_Bus_from_Wenhao_Liu.pdf" width="1000" height="1200"></iframe>


# Vehicle-Class-Detection-for-FastTag
<h2><b>Machine Leaning module to detect vehicle class to avoid FastTag frauds.</b></h2>
<br>
<h4><b>Problem Statement</b></h4>
<ul>
    <li>NHAI has started the implementation of FASTag compulsory for commercial and non-commercial vehicles.
         The main aim of the implementation behind the usage of RFID-based FASTag is to ensure the free movement of traffic without the need for stoppages at the toll gate.
    </li>
    <li>
        However, with the implementation of this technology, there are some people who have started to misuse the faults in the system. 
    </li>
    <li>
        The project aims to counter one of such problems by using machine learning based object recognition to classify the vehicle, then to compare the information on the RFID card to the vehicle class.
    </li>
    <li>
        The NHAI has divided all the vehicles into seven different catergories. Based on different categories, different toll is charged. 
        The FastTag stores the information about the vehicle class. 
    </li>
    <li>
        When the RFID scanner scans the FastTag at the toll plaza, it deducts the toll from the account as per the vehicle class stored in the FastTag.
    </li>
    <li>
        So if a truck driver somehow uses a FastTag for a car, he/she will end up paying much less toll.
    </li>
    <li>
        So this way many people were able to fraud the highway authority and saving their money. A toll price list for different vehicles is mentioned below.
    </li>
</ul>

<br>
<br>
<h4><b>Solution</b></h4>
<ul>
    <li>
        The very obvious solution for the problem is to appoint a toll operator at every toll booth who will verify that class mentioned on FastTag is same as that of the vehicle.
    </li>
    <li>
        But this solution rules out the idea of using FastTag. FastTag were designed to computerize the toll operations thus easing the traffic at toll plaza. 
    </li>
    <li>
        So we came up with a machine learning soution for the detecting the vehicle class (based on axle count and vehicle category).
    </li>
</ul>
<br>
<br>
<h4><b>About The Code</b></h4>
